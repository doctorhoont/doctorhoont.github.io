# doctorhoont.github.io

닥터훈트(내과 전문의 · 신장내과 의사)의 진료실 기록 사이트. 주소: https://doctorhoont.github.io

## 새 글 올리는 법

`_posts` 폴더에 `YYYY-MM-DD-영문-주소.md` 파일을 만들고 맨 위에 아래 머리말을 넣는다.

```yaml
---
title: "글 제목"
date: 2026-10-19 21:19:40 +0900   # 쓰레드에 처음 올린 시각
kind: info                        # info = 진료실 정보, diary = 병원 일기
threads_url: https://www.threads.com/@doctor_hoont/post/...
summary: "한 줄 요약 (정보 글만, 선택)"
faq:                              # 정보 글만, 선택
  - q: "질문"
    a: "답"
---
```

- 본문은 빈 줄로 문단을 나누고, 문단 안에서 줄을 바꾸면 그대로 줄바꿈된다.
- 날짜와 쓰레드 원문 링크는 글 맨 아래에 자동으로 붙는다.

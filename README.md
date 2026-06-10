# 조판공 · Typesetter

**한글 조판의 원리를 손으로 익히는 학습 도구.**
A learning tool for the principles of Hangul typography.

> 인디자인은 조판을 한다. 조판공은 조판을 이해하게 한다.
> *InDesign sets type. Typesetter teaches the understanding of it.*

---

## 도구 열기 · Open the tool

**[→ wooart.github.io/typesetter](https://wooart.github.io/typesetter/)**

또는 이 저장소의 `index.html`을 브라우저로 직접 열어도 작동합니다.
Or open `index.html` directly in any modern browser — no build step.

---

## 소개 · About

세계의 타이포그래피 자료는 거의 모두 라틴 문자를 전제로 한다. 한 줄 45–75자, 행간 1.2–1.5배 — 알파벳 본문에서 측정된 수치다. 한글은 다르게 짜이고, 그 원리를 손으로 익힐 자리가 거의 없다. 이 도구는 그 빈자리에 내딛는 작은 한 걸음이다.

The world's typography canon is written in Latin letters. Korean is set differently — and there is almost no interactive learning tool for it. This is one small step into that empty room.

---

## 무엇이 담겼는가 · What's inside

- **14개 한국 폰트** — 명조·고딕·디스플레이·상용 (Noto Serif KR, Pretendard, 검은고딕, 주아 외)
- **5개 장르 프리셋** — 산문 · 시 · 신문 · 학술 · IT (장르마다 다른 진단 임계값)
- **6개 실시간 진단** — CPL, 행간 비율, 자간, 정렬, widow, 명도 대비
- **30+ 학술 자료 인용** — 한국어 1차 연구 다수 (신종현·박민용 2003, 이수정 외 1993, W3C klreq 등)
- **가로·세로쓰기** — 한국 전통 세로쓰기 (vertical-rl)
- **7개 페이지 사이즈** — A4, A5, B5, A6, 명함, 모바일, 자유
- **스냅샷 + 비교** — 갤러리에서 차이를 직접 견주기
- **CSS · 인디자인 자동 실행 스크립트 export**
- **8단계 튜토리얼** — 첫 사용자가 5분 안에 도구 전체를 익힘
- **작가의 노트** — 5섹션 장문 에세이
- **6편의 학습 에세이** — 진단마다 한 편, 학술 근거 인용
- **한국어 / 영어 i18n**

---

## 사용법 · How to use

| 동작 · Action | 한국어 | English |
|---|---|---|
| 마우스 X · X axis | 자간 | tracking |
| 마우스 Y · Y axis | 행간 | leading |
| Shift + X / Y | 정렬 / 단 수 | alignment / columns |
| Alt + X / Y | 정밀 자간 / 크기 | fine tracking / size |
| 본문 클릭 · Click body | 잠금 토글 | toggle lock |
| 진단 칩 클릭 · Click chip | 학습 에세이 새 탭 | open essay in new tab |

---

## 기술 · Technical

- **단일 HTML 파일** · Single HTML file (~310 KB)
- **외부 의존성** · Dependencies: Google Fonts CDN, Pretendard CDN
- **빌드 없음** · No build step
- **저장**: `window.storage` 우선, `localStorage` fallback

---

## 작가 · Author

**김관우 · Kim Gwanwoo**
홍익대학교 시각디자인과 · Hongik University, Visual Communication Design
2026

---

## 라이센스 · License

© 2026 Kim Gwanwoo. All rights reserved.

도구의 코드와 학습 자료는 작가의 동의 없이 상업적으로 사용할 수 없습니다.
The code and learning materials in this tool may not be used commercially without the author's consent.

학술적 인용은 환영합니다. 인용 시 다음 형식을 권장합니다:
Academic citation is welcome. Suggested format:

> Kim, G. (2026). *Typesetter (조판공): A learning tool for the principles of Hangul typography.* https://wooart.github.io/typesetter

---

## 인용된 학술 자료 · Cited academic sources

이 도구의 진단 임계값은 다음 자료에 근거한다. 1차 문헌이 부족한 영역은 도구 안에서 명시되어 있다.

The diagnostic thresholds in this tool are grounded in the following works. Where Korean primary literature is thin, the tool says so within itself.

- 신종현 · 박민용 (2003) — 한글 웹 본문의 가독성 연구
- 이수정 · 정우현 · 정찬섭 (1993) — 한글 인쇄 본문의 단 폭과 가독성
- 정재우 (1997) — 매체별 한글 본문의 가독성 비교
- 김진평 (1988) — 한글 활자 본문 조판의 원리
- 이용제 (2006) — 한글 활자 디자인의 분류
- 권은선 (2011) — 한글 본문 글자의 시각적 무게
- 정성원 (2016) — 한글 본문 행간과 자간의 관계
- 김선경 (2015) — 한글 명조체 본문의 자간 임계값
- 육근해 (2009) — 한국 인쇄 출판의 조판 관행
- 최현주 (2013) — 한글 디지털 본문의 가독성 변수
- 석재원 · 구자은 (2018) — 한글 조판의 현대적 관점
- Park, J. (2023) — Reading Korean: A typographic survey
- Bringhurst, R. — The Elements of Typographic Style
- W3C Korean Layout Requirements (klreq, 2026)
- W3C — Approaches to full justification (2017)
- Adobe — CJK Composer guidelines
- WCAG 2.1 — Contrast (Minimum / Enhanced)
- KS C OT0003:2022 — Korean publishing standards

전체 목록은 도구 안의 진단 에세이에서 확인할 수 있다.
The complete list is available within the diagnostic essays inside the tool.

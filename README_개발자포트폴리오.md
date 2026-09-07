# 🚀 이솔지 — QA에서 개발자로

> QA 4년 6개월 경력을 가진 이솔지가 **개발자로 전환 중**임을 보여주는 포트폴리오 랜딩페이지입니다.
> "버그를 찾던 눈이 이제 코드를 씁니다"를 한 문장으로, QA 감각과 개발 역량을 한 페이지에 함께 보여줍니다.

🔗 **랜딩페이지** → [Claude 아티팩트로 게시됨](https://claude.ai/code/artifact/81dc6f2e-0d6d-4492-be9e-07f9dfa54b94) *(아직 별도 GitHub 저장소/도메인은 없습니다)*
🌐 **기존 QA 포트폴리오** → [leesolgi.github.io/qa-portfolio-solji](https://leesolgi.github.io/qa-portfolio-solji/)
🐙 **GitHub** → [github.com/leesolgi](https://github.com/leesolgi)

---

## 📌 About This Page

| 항목 | 내용 |
|------|------|
| 목적 | QA 경력 4년 6개월 + 바이브코딩/자동화 프로젝트를 묶어, "개발자로 전환 중"이라는 메시지를 보여주는 랜딩페이지 |
| 대상 | 개발 직무 지원 시 QA 경력을 강점으로 함께 어필하고 싶을 때 |
| 형태 | 단일 HTML 페이지 (Hero → About → Projects → Skills → Career → Contact) |
| 배포 상태 | Claude 아티팩트로 게시 (비공개 → 공유 시 링크로 열람 가능), GitHub Pages 배포는 아직 안 함 |
| 테마 | 다크/라이트 토글 지원 (기본값 다크) |

---

## 🧩 페이지 구성

| 섹션 | 내용 |
|------|------|
| Hero | "QA 4년 6개월이 개발을 만났을 때" 헤드라인, 핵심 지표 4개(경력·자동화TC·검증디바이스·결함재현율), 실제 pytest 실행 로그를 흉내낸 터미널 UI |
| About | QA 경력이 개발에 어떻게 이어지는지 서술 + QA→자동화→개발전환 3단계 타임라인 |
| Projects | 직접 만든 프로젝트 4개를 카드로 소개 (아래 표 참고) |
| Skills | QA 역량 4개 + 개발 역량 4개를 막대그래프로 병렬 비교 + 기술 태그 클라우드 |
| Career | 엔씨엘(NCL) 재직 중 담당 업무 3건을 시간순 타임라인으로 정리 |
| Contact | 이메일(클립보드 복사 버튼 포함)·GitHub·QA 포트폴리오·이력서 PDF 링크 |

---

## 🔬 소개된 프로젝트

| 프로젝트 | 스택 | 상태 | 링크 |
|------|------|------|------|
| MockOTT 자동화 테스트 | Python · Selenium · pytest · GitHub Actions | 완료 (TC 18개 전체 통과) | [github.com/leesolgi/ott_automation](https://github.com/leesolgi/ott_automation) |
| 전자 계산기 | JavaScript · HTML/CSS (바이브코딩) | 완료 | [github.com/leesolgi/calculator](https://github.com/leesolgi/calculator) |
| QA 포트폴리오 사이트 | HTML/CSS/JS · GitHub Pages | 배포 완료 | [leesolgi.github.io/qa-portfolio-solji](https://leesolgi.github.io/qa-portfolio-solji/) |
| 조합 테스트 케이스 생성기 | Python · Selenium · Pairwise | 진행중 (2026-09-08~09-12 제작) | [빌드로그(진행 상황)](https://claude.ai/code/artifact/5471e17c-9679-4564-9c67-fa748ed6897c) |

---

## 🛠 이 페이지를 만든 기술

| 구분 | 내용 |
|------|------|
| 마크업/스타일 | 단일 HTML, CSS 변수 기반 다크/라이트 테마, `color-mix()`로 hover·그라데이션 색상 계산 |
| 폰트 | Space Grotesk(제목) · Noto Sans KR(본문) · JetBrains Mono(코드/숫자) |
| 인터랙션 | `IntersectionObserver`로 스크롤 시 섹션 등장 애니메이션 + Skills 막대그래프 애니메이션, 이메일 클립보드 복사 |
| 데이터 | 별도 백엔드 없이 정적 콘텐츠, 테마 선택만 `localStorage`에 저장 |

---

## 📞 Contact

- ✉ Email: sughjd9@gmail.com
- 🐙 GitHub: [github.com/leesolgi](https://github.com/leesolgi)
- 🌐 QA 포트폴리오: [leesolgi.github.io/qa-portfolio-solji](https://leesolgi.github.io/qa-portfolio-solji/)
- 📄 이력서 PDF: [다운로드](https://leesolgi.github.io/qa-portfolio-solji/resume.pdf)

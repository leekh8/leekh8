<div align="center">

# 이규해 · leekh8

**보안 엔지니어** — 웹 취약점 분석으로 시작해, 지금은 *보안 점검을 자동화하는 도구*를 만든다.

[![Blog](https://img.shields.io/badge/기술_블로그-leekh8.github.io-222222?style=flat&logo=githubpages&logoColor=white)](https://leekh8.github.io/)
[![Gmail](https://img.shields.io/badge/amysun125@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:amysun125@gmail.com)

</div>

---

## 🔨 만든 것들

무엇을 만들었는지보다 **어떤 문제를 풀었는지**를 적었다.

### 보안

| 프로젝트 | 푼 문제 | 스택 |
|---|---|---|
| **[TestWeave](https://github.com/leekh8/TestWeave)** | 단발성 스캐너는 *"지금 상태"* 만 알려준다. **"지난번보다 나빠졌다"(회귀)** 를 잡는 스캐너 — 보안 헤더·TLS·쿠키를 baseline과 비교해 `REGRESSION/FIXED/NEW` 판정. SSRF 가드 내장, 매일 GitHub Actions 자동 스캔 | Spring Boot · Java 17 |
| **[Site-Mapper](https://github.com/leekh8/Site-Mapper)** | 사이트 구조를 크롤링해 sitemap 생성. 사용자 입력 URL을 다루므로 **SSRF 가드**로 내부망 접근 차단 | Node · Puppeteer |
| **[vmpulse](https://github.com/leekh8/vmpulse)** | vCenter 인벤토리를 CSV로 뽑아 자산 현황을 추적 | Python |

### 웹 · 풀스택

| 프로젝트 | 푼 문제 | 스택 |
|---|---|---|
| **[MD-GGU](https://github.com/leekh8/MD-GGU)** | 마크다운 문서를 작성·관리하고 규칙 기반으로 요약·이모지·참고링크를 자동 추출 | React(Vite) · Spring Boot · Flask · PostgreSQL |
| **[TimeTrack](https://github.com/leekh8/TimeTrack)** | 뽀모도로 타이머 + 할 일 관리. 백그라운드 탭에서 타이머가 느려지는 문제를 **벽시계(Date.now) 재계산**으로 해결 | React · Express |
| **[GitGGu](https://github.com/leekh8/GitGGu)** | GitHub 프로필 README를 쓰는 마크다운 에디터 — 커서 인식 서식·자동 저장·다운로드 | React(Vite) |
| **[SEO-Booster](https://github.com/leekh8/SEO-Booster)** | 글 쓰는 중에 SEO 점수를 실시간으로 매겨 개선점을 알려주는 에디터 | React(Vite) |

### 앱 · 게임

| 프로젝트 | 푼 문제 | 스택 |
|---|---|---|
| **[uno_flutter](https://github.com/leekh8/uno_flutter)** | UNO 오프라인 싱글플레이 — 규칙 엔진을 UI와 분리한 순수 함수로 두고 단위 테스트로 검증 | Flutter · Dart |
| **[uno-deathmatch](https://github.com/leekh8/uno-deathmatch)** | UNO No Mercy 룰 실시간 멀티플레이 (WebSocket) | Node · React |
| **[SwiftType](https://github.com/leekh8/SwiftType)** | 타자 연습 — 정확도·CPM·WPM 계산 로직을 분리해 테스트 | JavaFX · Java 17 |

---

## 📝 기술 블로그

**[leekh8.github.io](https://leekh8.github.io/)** — 실무에서 만난 버그를 원인까지 파고들어 기록한다. (주 1회 발행)

- **React 버그 해부** 시리즈 — [stale closure](https://leekh8.github.io/react-stale-closure-timer/) · [useCallback deps](https://leekh8.github.io/react-useCallback-deps/) · [백그라운드 탭 타이머 드리프트](https://leekh8.github.io/react-background-timer-drift/) · [react-beautiful-dnd와 StrictMode](https://leekh8.github.io/react-beautiful-dnd-strictmode/)
- **보안 자동화** — [보안 권고문 RSS 수집기](https://leekh8.github.io/security-advisory-rss-watcher/) · [Nuclei 스캔 비결정성 추적](https://leekh8.github.io/nuclei-ssh-maxstartups/)
- **웹 보안 기초** — OWASP Top 10 · API Security · LLM Top 10 · JWT/OAuth/세션

---

## 📑 논문

| 제목 | 발행처 | 연도 |
|---|---|---|
| [OWASP ZAP을 이용한 다계층 프로그래밍 언어 Links의 웹 취약점 분석](https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE11035877) | 한국정보과학회 | 2021.12 |
| [다계층 프로그래밍언어 Links의 웹 취약점 분석](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11224401) | 한국정보과학회 | 2022.12 |
| [다계층 프로그래밍 언어 Links의 웹 취약점 분석](http://www.riss.kr/search/detail/DetailView.do?p_mat_type=be54d9b8bc7cdb09&control_no=b2153b3cea019db5ffe0bdc3ef48d419) | 학위 논문 | 2023.02 |

---

## 🛠️ 주로 쓰는 것

**언어** Java · Python · JavaScript/TypeScript · Dart
**백엔드** Spring Boot · Node/Express · Flask · PostgreSQL · MongoDB
**프론트** React · Vite · Tailwind
**보안·자동화** OWASP ZAP · Nuclei · Playwright · GitHub Actions
**기타** Flutter · TensorFlow · Linux · Docker

<div align="center">

[![Solved.ac](http://mazassumnida.wtf/api/v2/generate_badge?boj=leekh)](https://solved.ac/leekh/)

![stats](https://github-readme-stats.vercel.app/api?username=leekh8&show_icons=true&layout=compact&theme=graywhite&hide_border=true)

</div>

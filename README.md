<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,100:8957E5&height=180&section=header&text=leekh8&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Security%20Engineer&descAlignY=58&descSize=18" width="100%"/>

**웹 취약점 분석 → 보안 점검 자동화 도구 개발**

<a href="https://leekh8.github.io/">
  <img src="https://img.shields.io/badge/Tech_Blog-222222?style=for-the-badge&logo=githubpages&logoColor=white"/>
</a>
<a href="mailto:kyuhailee@gmail.com">
  <img src="https://img.shields.io/badge/kyuhailee@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://solved.ac/leekh/">
  <img src="https://img.shields.io/badge/solved.ac-0076C0?style=for-the-badge&logo=leetcode&logoColor=white"/>
</a>

</div>

<br/>

## 🔐 Security

<table>
<tr>
<td width="33%" valign="top">

### [TestWeave](https://github.com/leekh8/TestWeave)
**웹 보안 회귀 스캐너**

- baseline 대비 `REGRESSION` / `FIXED` / `NEW` 판정
- 보안 헤더 · TLS 버전 · 쿠키 플래그 점검
- 값의 *강도*까지 검증 (존재 여부 X)
- SSRF 가드 내장 · 일일 자동 스캔

`Spring Boot` `Java 17` `GitHub Actions`

</td>
<td width="33%" valign="top">

### [Site-Mapper](https://github.com/leekh8/Site-Mapper)
**사이트맵 생성기**

- 크롤링 기반 사이트 구조 추출
- 사용자 입력 URL → SSRF 가드로 내부망 차단
- 스트리밍 다운로드

`Node` `Puppeteer`

</td>
<td width="33%" valign="top">

### [vmpulse](https://github.com/leekh8/vmpulse)
**vCenter 인벤토리 수집기**

- 가상 자산 현황 CSV 추출
- 자산 추적 자동화

`Python`

</td>
</tr>
</table>

## 🌐 Web · Full-stack

<table>
<tr>
<td width="33%" valign="top">

### [MD-GGU](https://github.com/leekh8/MD-GGU)
**마크다운 문서 관리 플랫폼**

- 규칙 기반 요약 · 이모지 · 참고링크 자동 추출
- JWT 인증 (Access + Refresh)
- KaTeX 수식 · 다크모드 · i18n

`React` `Spring Boot` `Flask` `PostgreSQL`

</td>
<td width="33%" valign="top">

### [TimeTrack](https://github.com/leekh8/TimeTrack)
**뽀모도로 타이머 + TODO**

- 백그라운드 탭 타이머 드리프트 해결 (벽시계 재계산)
- 드래그 정렬 · 다국어 · 다크모드

`React` `Express`

</td>
<td width="33%" valign="top">

### [GitGGu](https://github.com/leekh8/GitGGu) · [SEO-Booster](https://github.com/leekh8/SEO-Booster)
**에디터 2종**

- GitGGu — 프로필 README 마크다운 에디터
- SEO-Booster — 작성 중 실시간 SEO 점수

`React` `Vite`

</td>
</tr>
</table>

## 📱 App · Game

<table>
<tr>
<td width="33%" valign="top">

### [uno_flutter](https://github.com/leekh8/uno_flutter)
**UNO 오프라인 싱글플레이**

- 규칙 엔진 = UI와 분리된 순수 함수
- AI 3인 · 드로우 중첩 · 덱 재활용
- 단위 테스트 14

`Flutter` `Dart`

</td>
<td width="33%" valign="top">

### [uno-deathmatch](https://github.com/leekh8/uno-deathmatch)
**UNO No Mercy 실시간 멀티**

- WebSocket 기반 방 생성 · 대전
- 룰 엔진 단위 테스트

`Node` `React` `WebSocket`

</td>
<td width="33%" valign="top">

### [SwiftType](https://github.com/leekh8/SwiftType)
**타자 연습**

- 정확도 · CPM · WPM 계산 로직 분리
- JUnit 테스트

`JavaFX` `Java 17`

</td>
</tr>
</table>

<br/>

## 📝 Tech Blog · [leekh8.github.io](https://leekh8.github.io/)

> 실무에서 만난 버그 → 원인까지 추적 · 기록 (주 1회)

| 시리즈 | 글 |
|---|---|
| **React 버그 해부** | [stale closure](https://leekh8.github.io/react-stale-closure-timer/) · [useCallback deps](https://leekh8.github.io/react-useCallback-deps/) · [백그라운드 탭 타이머 드리프트](https://leekh8.github.io/react-background-timer-drift/) · [react-beautiful-dnd + StrictMode](https://leekh8.github.io/react-beautiful-dnd-strictmode/) |
| **보안 자동화** | [보안 권고문 RSS 수집기](https://leekh8.github.io/security-advisory-rss-watcher/) · [Nuclei 스캔 비결정성 추적](https://leekh8.github.io/nuclei-ssh-maxstartups/) |
| **웹 보안 기초** | OWASP Top 10 · API Security · LLM Top 10 · JWT/OAuth/세션 |

<br/>

## 📑 Papers

| 제목 | 발행처 | 연도 |
|---|---|---|
| [OWASP ZAP을 이용한 다계층 프로그래밍 언어 Links의 웹 취약점 분석](https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE11035877) | 한국정보과학회 | 2021.12 |
| [다계층 프로그래밍언어 Links의 웹 취약점 분석](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11224401) | 한국정보과학회 | 2022.12 |
| [다계층 프로그래밍 언어 Links의 웹 취약점 분석](http://www.riss.kr/search/detail/DetailView.do?p_mat_type=be54d9b8bc7cdb09&control_no=b2153b3cea019db5ffe0bdc3ef48d419) | 학위 논문 | 2023.02 |

<br/>

## 🛠️ Stack

<div align="center">

**Languages**

![Java](https://img.shields.io/badge/Java-F44336?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)

**Backend & Frontend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

**Security & Automation**

![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-000000?style=flat-square&logo=owasp&logoColor=white)
![Nuclei](https://img.shields.io/badge/Nuclei-1F2937?style=flat-square&logo=projectdiscovery&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

<br/>

<img src="https://github-readme-stats.vercel.app/api?username=leekh8&show_icons=true&hide_border=true&theme=graywhite&hide_title=true&card_width=450" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8957E5,100:1F6FEB&height=120&section=footer" width="100%"/>

</div>

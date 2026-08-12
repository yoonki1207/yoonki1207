<div align="center">
  
# Hey, I'm Yoonki Hong, Backend Developer 👋

**About me**
</div>

# 자기소개

특정 기술에 얽매이지 않는 개발자가 되기 위해 **백준에서 1,044개의 문제**를 풀며 자료구조와 알고리즘의 기본기를 다졌습니다. **코드 레벨에서 문제의 원인을 빠르게 좁히는 강점**을 바탕으로, **크래프톤 정글 12기 과정**에서 알고리즘 풀이에 어려움을 겪는 동료들을 도와주며 신뢰를 얻었습니다. 이후 **팀 프로젝트 리더 역할**을 수행하며, 일의 우선순위와 일정을 관리하고 결과물 완성을 책임졌습니다. 대규모 트래픽을 처리하고 복잡한 문제를 해결하여 신뢰할 수 있는 서비스를 개발하는 **백엔드 개발자**로 성장하고자 합니다.

---

# 주요 프로젝트

## [Krafton Jungle] LLM 워크플로우 자동화 플랫폼 — Nodease

n8n 스타일의 노드 기반 워크플로우에 LLMOps와 기업용 RBAC를 결합한 AI 워크플로우 자동화 서비스입니다.

<aside>

**기간/인원**: 2026.06.19 - 2026.07.25 · 5주 · 5명<br/>
**역할**: 팀장(일정 관리, 발표·데모 준비), RBAC 및 RAG 권한 경계 일부 설계·구현<br/>
**스킬**: Python3.11, FastAPI, PostgreSQL, NextJS, Docker compose, AWS<br/>
**GitHub**: [github.com/yoonki1207/nodease](https://github.com/yoonki1207/nodease)

</aside>

- 대규모 Markdown 문서 개발 방법론에서 TDD 도입으로 **문서 5시간 작성 -> 병합 주기 3시간**으로 단축.
- LLM model routing **비용 57% 절감, 응답 시간 20%** 단축.
- 사용자 **권한 기반 RAG** 검색 제한 구현.
- 이벤트 유실 문제에서 사용자 행동과 감사로그를 같은 트랜잭션으로 처리하는 **dual write문제를 outbox 패턴**으로 해결.
- 프롬프트만으로 워크플로우를 구성하는 **Agent Builder** 구현.

<br/>

## [Krafton Jungle] KAIST Pintos

KAIST Pintos는 x86-64 아키텍처 기반 교육용 운영체제를 구현하는 실습 과제입니다. 커널 스레드의 스케쥴링과 가상 메모리를 구현했습니다.

<aside>

**기간**: 2026.04.24 - 2026.05.21 · 4주<br/>
**역할**: 우선순위 선점 스케줄링, Semaphore·Condition Variable 우선순위 처리<br/>
**기술**: C<br/>
**GitHub**: [github.com/Jungle-12-303/week09-team-05-pintos-threads](https://github.com/Jungle-12-303/week09-team-05-pintos-threads)

</aside>

- **초기 메모리 적재 비용**을 줄이기 위해 page fault를 통해 필요한 페이지만 적재하는 **demand paging(lazy loading)** 구현.
- Priority donation 역전 방지 구현 중 쓰레드 대기열의 선택 복잡도를 **O(n log n)에서 O(n)으로 개선.**
- swap 메모리를 위해 물리 메모리 **frame eviction을 second-cahnce/clock** 방식으로 구현.

<br/>

## [강남대학교] 모여라 지금(MOJI)

사용자가 즉석 모임을 만들고 참여할 수 있는 웹 애플리케이션입니다.

<aside>

**기간/인원**: 2023.07.01 - 2024.02.20 · 7개월 · 6명<br/>
**역할**: 백엔드 — 번개 모임 API, 실시간 채팅<br/>
**기술**: Java 17, Spring Boot 3.1, STOMP/WebSocket, MongoDB<br/>
**GitHub**: [github.com/AUNAE-WEB-Dev](https://github.com/AUNAE-WEB-Dev)

</aside>

- STOMP와 MongoDB를 사용하여 **채팅방 재접속 시 이전 대화 내역 조회** 구현.
- 채팅 이력 조회를 **무한 스크롤** 커서 기반 채팅 이력 조회 기능 구현.
- 채팅방 생성 및 사용자 참여·퇴장 **이벤트 발생 시 해당 채팅방에 시스템 알림 메시지**가 전송되도록 구현.

<br/>

## [벤처스타트업아카데미 해커톤] 대학생 심부름 애플리케이션 — Took

“우리 학교 뿐 아니라 주변 환경에 도움이 되는 비즈니스 서비스를 만드시오”라는 주제에서 학생 간 심부름 요청과 수행을 연결해주는 중개 서비스를 개발했습니다.

<aside>

**기간/인원**: 2024.08.19 - 2024.08.20 · 1박 2일 · 4명<br/>
**역할**: 백엔드 — 로그인·회원가입, 정산, 심부름 요청·수행<br/>
**기술**: Flutter, Dart, Python, FastAPI<br/>
**GitHub**: [github.com/SURFERTON/backend](https://github.com/SURFERTON/backend)

</aside>

- 중간에 기획이 변경될 수 있는 상황을 고려하여, **짧은 시간** 안에 API를 재구성하기 위해 **FastAPI**를 선택하여 개발.
- 요청자와 수행자의 책임을 구분할 수 있도록 **요청·수행·완료·정산의 상태** 흐름과 단계별 완료 조건을 설계.
- **일방적인 완료 처리와 중복·누락 정산을 방지**하고, 진행 이력으로 분쟁 상황을 확인할 수 있게 설계.

<br/>

---

# 활동

## [인턴] 아이나비시스템즈 — LiDAR 뷰어

- **기간**: 2024.07.01 - 2024.07.26 · 4주
- **기술**: C++, MFC
- 자율주행 자동차의 **LiDAR 센서가 생성한 LAS 파일**의 이진 구조를 조사하고, `#pragma pack`을 적용한 구조체로 데이터를 읽어 **2D 시각화 프로그램** 제작.
- **최소 요구사항**인 2D 시각화를 완성한 뒤 **사용자의 편의를 고려**해 Camera 구조체, 행렬 변환과 삼각함수를 적용해 3D 뷰어로 확장 구현.
- 마우스와 키보드 입력으로 **시점 이동·회전·확대·축소 기능을 구현**하고, 렌더링할 포인트 수를 조절해 상호작용 시 발생하는 지연 감소.

<br/>

## [외주] 크몽 개인 외주

- **기간**: 2023.12 - 2024.03 · 3개월
- Python **이미지 일괄 편집 프로그램** 제작.
- 광고 기획 및 제작 전문 기업 [rmsid.net](https://rmsid.net) **웹 페이지 퍼블리싱.**
- 요구사항에 따라 Java와 Spring Boot로 기존 서비스에 Apple·Facebook·Google·Naver·Kakao **소셜 로그인 연동.**

<br/>

---

# 교육

## [부트캠프] Krafton Jungle SW/AI Lab 12기 [2026.03.03 ~ 2026.07.30]

- KRAFTON에서 진행한 컴퓨터공학 기본기를 갖추는 AI-Native 인재 양성 프로그램 진행.
    - mini-Redis, React 프레임워크, 디스크기반 MiniDB 구현.
    - x86-64기반 **운영체제** Pintos 구현.
    - Self-Attention기반 **GPT-3** 모델 구현.
    - 최종 프로젝트 **Nodease** 진행.

<br/>

## [부트캠프] SSAFY 13기 [2025.01 ~ 2025.03]

- SSAFY(삼성청년SW · AI아카데미). 취업 준비생 대상 소프트웨어 및 AI 인재 양성 프로그램 진행.
    - **삼성 역량테스트 B형** 취득.

<br/>

---

# 학력

## [학력] 강남대학교 [2019.03 ~ 2025.02]

- **강남대학교 학사 졸업** · 학점 **4.23** / 4.5
    - **[주전공] 소프트웨어전공** / [복수전공] 데이터사이언스

<br/>

---

# 수상

- 2024 벤처스타트업 아카데미 해커톤 장려상

<br/>

# 자격증

- 삼성 SW 역량테스트 B형
- SQLD
- 정보처리기사

<br/>

# Contact

- Mail: yoonki1207@gmail.com

---

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=yoonki1207)](https://solved.ac/yoonki1207/)

[![Anurag's GitHub stats](https://github-stats-extended.vercel.app/api?username=yoonki1207)](https://github.com/stats-organization/github-stats-extended)


<!-- [![GitHub Stats](https://github-stats-extended.vercel.app/api/top-langs?username=yoonki1207&langs_count=4)](https://github-stats-extended.vercel.app/api/top-langs?username=anuraghazra&langs_count=4) -->


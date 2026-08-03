<div align="center">
  
# Hey, I'm Yoonki Hong 👋

**About me**
</div>

특정 기술에 얽매이지 않는 개발자가 되기 위해 **백준에서 1,044개의 문제**를 풀며 자료구조와 알고리즘의 기본기를 다졌습
니다. 

**코드 레벨에서 문제의 원인을 빠르게 좁히는 강점**을 바탕으로, **크래프톤 정글 12기** 과정에서 알고리즘 풀이에 어려
움을 겪는 동료들을 도와주며 신뢰를 얻었습니다. 

이후 **팀 프로젝트 리더 역할**을 수행하며, 일의 우선순위와 일정을 관리
하고 결과물 완성을 책임졌습니다. 

대규모 트래픽을 처리하고 복잡한 문제를 해결하여 신뢰할 수 있는 서비스를 개발하는
**백엔드 개발자**로 성장하고자 합니다.

# Featured Projects

## [KRAFTON Jungle] Nodease — LLM 워크플로우 자동화 플랫폼

**LLMOps + workflow 자동화 플랫폼입니다.**

- 5 weeks / 5명 / 2026.06.19 ~ 2026.07.25
- https://github.com/yoonki1207/nodease

`Python 3.11` `FastAPI` `PostgreSQL` `Next.js` `Docker Compose` `AWS`

### 역할
5인 팀의 리더로 일정과 발표·데모를 관리하고, RBAC와 RAG 권한 경계 일부를 설계·구현했습니다.

### 주 기능
- 노드 기반 워크플로우 구성
- 프롬프트기반 워크플로우 생성·수정·삭제
- 권한 기반 RAG 검색 시스템
- AI API 비용 Cost optimizer

## [KRAFTON Jungle] Pintos-KAIST thread

**x86-64 architecture 기반 교육용 OS 실습 과제 프로젝트입니다.**

- 2 weeks / 3명 / 2026.0 4.2 4 ~ 2026.05.07
- https://github.com/Jungle-12-303/week09-team-05-pintos-threads

`C` `Thread` `Scheduling` `Synchronization`

### 역할
교육용 운영체제 Pintos에서 우선순위 스케줄링과 동기화 로직을 구현했습니다.

### Trouble shooting
- 대기 중인 스레드의 변경된 우선순위가 선택 결과에 반영되지 않는 문제를 발견했습니다.
- 대기열을 미리 정렬하는 대신 스레드를 깨우는 시점에 최고 우선순위 대상을 탐색하도록 재설계했습니다.
- Semaphore와 Condition Variable의 우선순위 일관성을 확보했습니다.
- 대기 스레드 선택 복잡도를 **O(n log n)에서 O(n)**으로 개선했습니다.

## [Kangnam University] Moji — 즉석 모임 및 실시간 채팅 서비스

**모임·식사·활동을 같이할 사람을 모집하는 웹앱 서비스입니다.**

- 8 months / 7명 / 2023.07 ~ 2024.02
- https://github.com/AUNAE-WEB-Dev

`Java 17` `Spring Boot 3.1` `STOMP` `WebSocket` `MongoDB`

### 역할
번개 모임 API와 실시간 채팅 기능을 담당했습니다.

### Trouble shooting
- 채팅 메시지를 MongoDB에 저장한 뒤 방별 STOMP 토픽에 전달해 실시간 전송과 이전 메시지 조회를 함께 지원했습니다.
- MongoDB의 `findAndModify`로 메시지 순번을 원자적으로 발급했습니다.
- `idx < cursor` 조건으로 필요한 메시지만 조회해 시간순으로 반환하는 커서 기반 채팅 이력을 구현했습니다.
- 모임 ID를 기준으로 채팅방 생성·참여·퇴장과 사용자별 참여 방 조회를 연결했습니다.

## [벤처스타트업아카데미·해커톤] Took — 대학생 심부름 애플리케이션

**대학생 전용 심부름 어플리케이션 서비스입니다.**

- https://github.com/SURFERTON/backend

`Python` `FastAPI` `Flutter`

### 역할
1박 2일 해커톤에서 로그인·회원가입, 정산, 심부름 요청·수행 API를 담당했습니다.

- **2024 벤처스타트업 아카데미 해커톤 장려상** 수상.

# Experience

## [아이나비시스템즈] 인턴 — LiDAR 뷰어

- 2024.07.01 ~ 2024.07.26

`C++` `MFC`

- LAS binary data에서 `#pragma pack`을 적용한 구조체로 데이터를 읽어 2D 시각화 프로그램을 구현.
- Camera 구조체, 행렬 Library를 제작해 3D 뷰어로 확장.
- 시점 이동·회전·확대·축소 기능 구현.

## 크몽 개인 외주 활동

- 2023.12 ~ 2024.03

`Python` `Spring Boot` `HTML/CSS`

- Python 이미지 일괄 편집 프로그램
- [rmsid.net](https://rmsid.net/) 퍼블리싱
- Spring Boot 서비스에 Apple·Facebook·Google·Naver·Kakao 소셜 로그인을 연동

# Education

- **Krafton Jungle SW/AI Lab 12기** · 2026.03 ~ 2026.07
- **SSAFY 13기** · 2025.01 ~ 2025.03
- **강남대학교 학사 졸업** · 학점 4.23 / 4.5

# Credentials

- 2024 벤처스타트업 아카데미 해커톤 장려상
- 삼성 SW 역량테스트 B형
- 정보처리기사
- SQLD

# Contact

- Mail: yoonki1207@gmail.com

---

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=yoonki1207)](https://solved.ac/yoonki1207/)

[![Anurag's GitHub stats](https://github-stats-extended.vercel.app/api?username=yoonki1207)](https://github.com/stats-organization/github-stats-extended)


<!-- [![GitHub Stats](https://github-stats-extended.vercel.app/api/top-langs?username=yoonki1207&langs_count=4)](https://github-stats-extended.vercel.app/api/top-langs?username=anuraghazra&langs_count=4) -->


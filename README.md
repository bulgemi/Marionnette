Marionnette
===========
Introduction
------------
> SSH가 지원되는 원격 서버에 인증된 사용자가 등록한 Job(Pack[명령어 묶음, Shell Script]수행, 파일전송)을 사용자가 지정한 타겟으로 원격수행

Idea
----
* 심플한 아키텍처
* 사용자 편의성 중심의 인터페이스
* 강력한 보안
* 손쉬운 확장
* 수평적인 구조
* 쉬운 사용법
* 자연스러운 업무 흐름 지원
* 5W1H 기반의 Job 정의

관련 라이브러리
------------
* Python 3.7
* Flask 1.0
* Fabric 2.4
* Bootstrap
* Handsontable
* Dashing
* Ace
* Maria DB
* Celery
* Redis

Features
--------
* SSH 프로토콜 지원(agentless)
* Network 연결 테스트 지원
* 모든 데이터 암호화
* 사용자 관리, 인증
* Job 생성/저장/공유/실행
* Pack 생성/저장/수행 테스트/공유
* Target 생성/저장/연결 테스트/공유
* 파일 송수신(SFTP)
* 병렬 처리/제어
* 스케줄링
* 금지 명령어 검사, 특수문자 제거
* 대시보드
* 결과 출력 md(Mark Down) 포맷 지원

Elements
--------
### Type
* 정의
* 처리 흐름

### Job
* 정의
* 처리 흐름

### Target
* 정의
* 처리 흐름

### Pack
* 정의
* 처리 흐름

# Chzzk Survival Quiz Backend

치지직 채팅 API를 활용한 실시간 시청자 참여형 생존 퀴즈 게임 프로젝트입니다.

## 목표

- 채팅 입력 `O / X / 1 / 2 / 3` 기반 실시간 투표 처리
- Redis 기반 현재 게임 상태 관리
- WebSocket(STOMP) 기반 관리자 화면 및 방송 오버레이 실시간 반영
- 텍스트 기반 결과 내보내기 지원

## 기술 스택

- Java 21
- Spring Boot
- Spring Web
- Spring Data Redis
- Spring WebSocket

## 디렉토리 구조

```text
src/main/java/com/chzzk/quiz
├── api
│   ├── admin
│   └── ws
├── application
│   ├── game
│   ├── participant
│   └── vote
├── domain
│   ├── common
│   ├── game
│   ├── participant
│   └── vote
└── infra
    ├── chzzk
    ├── redis
    └── ws
```

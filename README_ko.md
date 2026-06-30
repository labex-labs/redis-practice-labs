# Redis 실습 랩

## 언어

🇨🇳 [简体中文](README_zh.md) 🇯🇵 [日本語](README_ja.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

<div align="center">
<img width="128px" src="https://file.labex.io/upload/u/1991/R6Np6c0ZgOWm.png">
</div>

초보자를 위해 설계된 포괄적인 학습 경로를 통해 Redis 를 배우세요. 이 Redis 강좌는 오픈 소스 인메모리 데이터 구조 저장소를 마스터하기 위한 체계적인 로드맵을 제공합니다. 기본적인 데이터 구조부터 고급 캐싱 전략 및 성능 최적화에 이르기까지 학습을 진행하세요. 전용 Redis 플레이그라운드에서 실습 위주의 비디오 없는 튜토리얼과 대화형 연습을 통해 데이터 캐싱 및 실시간 데이터 처리 분야에서 실용적이고 실제적인 경험을 얻으세요.

LabEx 의 17개 이하 Redis 실습 랩을 살펴보세요. 각 랩은 대화형 환경에서 열려 직접 해 보며 연습할 수 있습니다.

|   인덱스 | 이름                                                                                                        | 스킬          | 난이도   | 연습                                                                                           |
|-------|-----------------------------------------------------------------------------------------------------------|-------------|-------|----------------------------------------------------------------------------------------------|
|    01 | [Redis 리스트 연산](https://labex.io/ko/labs/redis-redis-list-operations-552098)                               | 목록          | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-list-operations-552098)                         |
|    02 | [Redis 트랜잭션](https://labex.io/ko/labs/redis-redis-transactions-552106)                                    | 트랜잭션        | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-transactions-552106)                            |
|    03 | [Redis Sorted Set 연산](https://labex.io/ko/labs/redis-redis-sorted-set-operations-552105)                  | 정렬된 세트      | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-sorted-set-operations-552105)                   |
|    04 | [Redis Set 연산](https://labex.io/ko/labs/redis-redis-set-operations-552104)                                | 세트          | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-set-operations-552104)                          |
|    05 | [Redis 보안 설정](https://labex.io/ko/labs/redis-redis-security-settings-552103)                              | 접근 보안       | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-security-settings-552103)                       |
|    06 | [Redis Pub/Sub 메시징](https://labex.io/ko/labs/redis-redis-pub-sub-messaging-552102)                        | 게시/구독       | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-pub-sub-messaging-552102)                       |
|    07 | [Redis 지속성 관리](https://labex.io/ko/labs/redis-redis-persistence-management-552101)                        | RDB 지속성     | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-persistence-management-552101)                  |
|    08 | [Redis 성능 모니터링](https://labex.io/ko/labs/redis-redis-performance-monitoring-552100)                       | 런타임 모니터링    | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-performance-monitoring-552100)                  |
|    09 | [Redis Lua 스크립팅](https://labex.io/ko/labs/redis-redis-lua-scripting-552099)                               | Lua 스크립팅    | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-lua-scripting-552099)                           |
|    10 | [Redis 설치 및 초기 설정](https://labex.io/ko/labs/redis-installation-and-initial-setup-of-redis-552075)         | CLI 연결      | 초급    | [실습 시작](https://labex.io/ko/labs/redis-installation-and-initial-setup-of-redis-552075)       |
|    11 | [Redis HyperLogLog 연산](https://labex.io/ko/labs/redis-redis-hyperloglog-operations-552097)                | HyperLogLog | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-hyperloglog-operations-552097)                  |
|    12 | [Redis 해시 연산](https://labex.io/ko/labs/redis-redis-hash-operations-552096)                                | 해시          | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-hash-operations-552096)                         |
|    13 | [Redis 고급 키 관리](https://labex.io/ko/labs/redis-redis-advanced-key-management-552094)                      | 키 조회        | 초급    | [실습 시작](https://labex.io/ko/labs/redis-redis-advanced-key-management-552094)                 |
|    14 | [Redis 지속성 및 간단한 설정](https://labex.io/ko/labs/redis-persistence-and-simple-configuration-in-redis-552079) | 구성          | 초급    | [실습 시작](https://labex.io/ko/labs/redis-persistence-and-simple-configuration-in-redis-552079) |
|    15 | [Redis 데이터 구조 입문](https://labex.io/ko/labs/redis-introduction-to-redis-data-structures-552078)            | 문자열         | 초급    | [실습 시작](https://labex.io/ko/labs/redis-introduction-to-redis-data-structures-552078)         |
|    16 | [Redis의 기본 키-값(Key-Value) 작업](https://labex.io/ko/labs/redis-basic-key-value-operations-in-redis-552077)  | 문자열         | 초급    | [실습 시작](https://labex.io/ko/labs/redis-basic-key-value-operations-in-redis-552077)           |
|    17 | [Redis 기본 데이터 관리](https://labex.io/ko/labs/redis-basic-data-management-in-redis-552076)                   | 키 조회        | 초급    | [실습 시작](https://labex.io/ko/labs/redis-basic-data-management-in-redis-552076)                |

[모든 랩 보기](https://labex.io/ko/learn/redis).

## 더 보기

- 🔗 [LabEx 에서 Redis 더 알아보기](https://labex.io/ko/learn/redis)
- 🔗 [더 많은 프로그래밍 프로젝트 탐색](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [프로그래밍 코스 탐색](https://github.com/labex-labs/awesome-programming-courses)


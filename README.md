# 🏠 HomeSweetHome
> **'오늘의 집'** 핵심 요구사항 분석 및 대규모 트래픽에서의 안정적 성능 확보를 목표로 한 이커머스 플랫폼 프로젝트입니다.

<img width="750" height="400" alt="image" src="https://github.com/user-attachments/assets/57f5dfbf-a606-4bf6-b4f6-c4938a7e3598" />

---

## 📑 목차
1. [Team JAKODH](#-team-jakodh)
2. [프로젝트 소개](#-프로젝트-소개)
3. [기술 스택](#기술-스택)
4. [담당 기능](#-담당-기능)
5. [설계 문서](#-설계-문서)
6. [실시간 채팅 고도화 작업 및 성능 개선](#-실시간-채팅-고도화-작업-및-성능-개선)
    - [성능 개선 핵심 요약](#-성능-개선-핵심-요약)
    - [DB 병목 해결 과정 (Challenge)](#-challenge-db-병목-해결을-위한-아키텍처-개선-및-시행착오-기록)
7. [반성 및 고도화 과제](#-반성-및-고도화-과제)

---

## 👥 Team JAKODH

<table align="center">
  <tr>
     <td align="center">
      <img src="https://avatars.githubusercontent.com/ohhalim" width="100" height="100" style="object-fit:cover;"/>
      <br/>오하림<br/>
      <a href="https://github.com/ohhalim">@ohhalim</a>
    </td>
     <td align="center">
      <img src="https://avatars.githubusercontent.com/chaeho5" width="100" height="100" style="object-fit:cover;"/>
      <br/>안채호<br/>
      <a href="https://github.com/chaeho5">@chaeho5</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/dogyungkim" width="100" height="100" style="object-fit:cover;"/>
      <br/>김도경<br/>
      <a href="https://github.com/dogyungkim">@dogyungkim</a>
    </td>
     <td align="center">
      <img src="https://avatars.githubusercontent.com/Jooahyeon" width="100" height="100" style="object-fit:cover;"/>
      <br/>주아현<br/>
      <a href="https://github.com/Jooahyeon">@Jooahyeon</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/normaldeve" width="100" height="100" style="object-fit:cover;"/>
      <br/>김준우<br/>
      <a href="https://github.com/normaldeve">@normaldeve</a>
    </td>
     <td align="center">
      <img src="https://avatars.githubusercontent.com/ssooyya" width="100" height="100" style="object-fit:cover;"/>
      <br/>권희수<br/>
      <a href="https://github.com/ssooyya">@ssooyya</a>
    </td>
  </tr>
</table>

---

## 📍 프로젝트 소개

- **해당 프로젝트는** `'오늘의 집'` 핵심 요구사항을 분석하여, 대규모 트래픽에서 안정적인 성능 확보를 목표로 하였습니다.
- **이를 위해 체계적인 3단계 과정을 통해 성능 최적화 및 테스트 진행했습니다.**
  
  1. **기획 및 설계를 통한 빠른 MVP 구현**
     - 요구사항 분석 및 구체화, 핵심 API 설계 및 프론트 프로토타이핑
  2. **테스트 체계화를 통한 서비스 안정성 강화**
     - 테스트 코드 설계 및 구현, 테스트 커버리지 측정 및 분석 (커버리지 80% 달성)
     - <img width="840" height="139" alt="image" src="https://github.com/user-attachments/assets/86359f9e-baae-4b3f-be85-89160af4c4e3" />
  3. **프로덕션 레벨을 향한 성능 최적화 및 E2E 테스트**
     - 성능 부하 테스트, 성능 병목 지점 분석 및 최적화, 전문 기술 문서화

### 📍 프로젝트 링크
| Frontend | Backend |
| :--- | :--- |
| [FE Github](https://github.com/PRF-JAKODH/HomeSweetHome-front) | [BE Github](https://github.com/PRF-JAKODH/HomeSweetHome-backend) |

---

## 기술 스택
<img width="700" height="350" alt="image" src="https://github.com/user-attachments/assets/fa89b43e-d17e-4614-ae33-c17db0bda066" />

---

## ⚙️ 담당 기능
<img width="700" height="350" alt="image" src="https://github.com/user-attachments/assets/a5f4086d-b776-474e-b70e-63734db71c1f" />

---

## 📄 설계 문서

<details>
<summary><b>📼 시연 영상 (펼쳐보기)</b></summary>
<br>
<div align="center">
  <a href="https://youtu.be/tDZQVn2-uPs?si=hE2dqdOiXLe87Cf">🎬 HomeSweetHome 기능 별 시연 영상 보러가기</a>
</div>
</details>

<details>
<summary><b>🚧 시스템 아키텍쳐 (펼쳐보기)</b></summary>
<img width="978" height="582" alt="image" src="https://github.com/user-attachments/assets/8dbba002-28ad-4461-be66-2e56a626f891" />
</details>

<details>
<summary><b>📋 요구사항 명세서 (펼쳐보기)</b></summary>
<img width="1053" height="638" alt="image" src="https://github.com/user-attachments/assets/e4d5ce02-bd90-4db9-a9f1-2faa2c7fc4ff" />
<img width="1052" height="499" alt="image" src="https://github.com/user-attachments/assets/2f6d5f13-900d-4a26-9bb1-d76dc88bef64" />
</details>

<details>
<summary><b>📘 ERD (펼쳐보기)</b></summary>
<img width="100%" alt="오늘의집-ERD" src="https://github.com/user-attachments/assets/6a42c739-687f-4fb9-9924-4afe488fdc38" />
</details>

---

## 📈 실시간 채팅 고도화 작업 및 성능 개선
> 실시간 채팅 서비스의 안정성 확보를 위해 진행한 **부하 테스트 기반의 성능 최적화 및 아키텍처 고도화** 과정입니다.


### ⚡ 성능 개선 핵심 요약
* **목록 조회 최적화**: 기존 Page 방식에서 **Slice 기반 페이징 전략**으로 변경하여 대량 데이터 조회 시 발생하는 부하를 줄이고 성능 개선
* **연결 안정성 확보**: `ulimit`, `somaxconn` 등 커널 파라미터 최적화를 통해 **WebSocket 동시 연결 성공률 27% → 100% 개선** (10,000 CCU 기준)

---

### 🚀 [Challenge] DB 병목 해결을 위한 아키텍처 개선 및 시행착오 기록

<details>
<summary><b>📘 DB 병목 현상 해결 과정 상세 기록 (펼쳐보기)</b></summary>

#### 1. 원인 분석: RDB 업데이트 지연 및 Lock 경합 확인
* **병목 지점 발견**: 메시지 전송 시마다 RDB의 `chat_room` 테이블 메타데이터(`last_message` 등)를 즉시 업데이트하는 로직이 고부하 환경에서 전체 시스템의 속도를 저하시키는 핵심 원인임을 확인
* **동시성 이슈 인지**: 10,000 CCU 환경에서 대량의 메시지 전송 시, 동일한 채팅방(Row)에 대해 반복적인 수정 작업이 발생하며 **Row-level Lock 충돌 및 Deadlock 에러 확인**

#### 2. 대안 제시: Redis 기반 Write-back 비동기 전략 설계
* **Redis Hash 활용**: 디스크 I/O 기반인 RDB의 한계를 극복하기 위해, 메타데이터를 메모리 상에서 초고속 처리할 수 있는 **Redis Hash** 구조 도입 설계
* **Write-back 전략 설계**: 실시간 데이터는 Redis에 우선 기록하여 응답 속도를 확보하고, 일정 주기마다 DB에 반영하는 비동기 전략을 통해 DB 커넥션 부하를 최소화하고자 함

#### 3. 실행 내용 및 한계 분석 (Prometheus & Grafana 활용)
* **구현상의 오류**: 설계 당시 비동기 처리를 목표로 했으나, 실제 구현 과정에서 **Redis 분산 락(SETNX)을 활용한 직렬화 구조**로 연동되면서 의도치 않은 동기 방식 구조로 인한 병목이 발생
* **연쇄 장애 발생 (Cascading Failure)**: 
    - **병목의 전이**: **Prometheus 및 Grafana** 모니터링 결과, DB Lock 경합은 해소되었으나 Redis 응답을 기다리는 WebSocket 메시지 처리 스레드가 차례로 블로킹(Block)되는 현상 발견
    - **스레드 풀 고갈**: 800여 개의 락 요청이 Redis 싱글 스레드 큐에 적체되면서 서버의 워커 스레드가 모두 소진되었고, 결국 서버가 사실상 멈추는 상태 발생 (scenarios: 800 max VUs, 7m30s max duration)

#### 4. 인사이트 및 결론
* **설계와 구현의 정교함 체감**: 동일한 캐시 도입이라도 **동기(Lock)냐 비동기(Event)냐**에 따라 시스템 가용성에 극명한 차이가 발생함을 실제 부하테스트를 통해 이해함
* **비동기 구조의 필연성 이해**: 고부하 채팅 시스템에서는 메시지 발송과 메타데이터 갱신 로직이 분리되어야 실시간 처리에 유용함을 깨달았으며, 이를 위해 메시지 큐(Message Queue)를 활용한 완전한 비동기 아키텍처의 필요성 경험함
* **트러블슈팅 역량 확보**: 장애 발생 시 단순히 로그에 의존하지 않고, Prometheus 지표와 스레드 상태를 종합적으로 분석하여 근본 원인(Root Cause)을 찾아내는 경험을 통해 문제 분석에 대한 시각을 키울 수 있었음

</details>

---

## 📝 [반성 및 고도화 과제]

- **문제점**: DB 락 회피를 위해 도입한 Redis 분산 락(SETNX)이 오히려 WS 스레드 블로킹을 유발하여 서버 전체의 Thread Pool 고갈 및 장애를 초래함을 확인
- **배운 내용**: 분산 시스템에서 동기식 락 구조가 전체 시스템 가용성에 끼치는 치명적인 영향을 경험하며 고부하 환경에서는 비동기 메시징 기반의 아키텍처가 필수적임을 깨달음
- **향후 계획**: Redis Pub/Sub 또는 Message Queue를 도입하여 메시지 발송과 메타데이터 갱신 로직을 완전히 비동기로 분리하는 고도화를 진행할 예정

---

### 🔗 Reference
- [HomeSweetHome Wiki](https://github.com/PRF-JAKODH/HomeSweetHome-backend/wiki)

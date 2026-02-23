## 🎟 STAGE – 대규모 트래픽을 고려한 공연 티켓 예매 플랫폼
<img width="643" height="358" alt="Image" src="https://github.com/user-attachments/assets/65433a0d-22ac-49ad-9bae-81483a8031da" />

## 📌 프로젝트 개요
> 이번에는 티켓팅에 성공하겠지?
> 
> 서버 다운되지 않겠지?

STAGE는 트래픽이 폭증을 안정적으로 처리하는 티켓팅 사이트입니다.
STAGE는 오토스케일링을 통해 순간적으로 트래픽이 폭증하는 상황에 서버가 마비 다운되는 것을 방지합니다.


## 🏗 아키텍처 구조
![Image](https://github.com/user-attachments/assets/7c448db2-3b50-4a92-b924-6efb702c88b4)

## ⚙ 기술 스택

### Backend
* Java 21
* Spring Boot
* Spring Security (JWT, OAuth2)
* JPA (Hibernate)
* Redis
* MySQL

### Infra
* Docker
* Kubernetes (K3s)
* GitHub Actions (CI/CD)
* GHCR
* Prometheus (Monitoring)

## 📊 성능 테스트

* JMeter 기반 부하 테스트
  * (서버 2개 기준)
    * Throughput : 160.4/s
    * 접속 인원 : 880명
* ~~동시 사용자 1,000~5,000명 시나리오 검증~~

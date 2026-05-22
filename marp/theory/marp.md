---
marp: true
theme: kakao
size: kakao-landscape
paginate: true
html: false
---

# PREVIEW OF LAB

![width:700px](https://objectstorage.kr-central-2.kakaocloud.com/v1/b6a9201d6cca4af591ff15a779724de1/doc2edu-sync/essential_basic_course/theory/diagram-01.png)

---

**SECTION.01**

# 클라우드 사용 전 환경 VS 클라우드 사용 후 환경

| 항목 | 클라우드 사용 전 (On Premises) | 클라우드 사용 후 |
| --- | --- | --- |
| 유연성 | 리소스 확장 및 축소가 제한적 | 자원을 빠르게 확장 및 축소 가능, 동적 리소스 조절 가능 |
| 빠른 배포 | 배포에 더 많은 시간 및 리소스 소요 | 새 서버/애플리케이션 빠르게 배포, 리드 타임 크게 단축 |
| 비용 절감 | 고정비용, 초기 투자 비용, 유지보수 비용 | Pay-as-you-go, 대량의 초기 투자 없음, 인프라 비용 절감 |
| 규정 준수 | 별도의 규정 준수 메커니즘이 필요 | 국내외 표준/규정 준수 서비스 제공, 규정 준수에 유용 |
| 보안 | 지속적인 업데이트 및 투자가 필요 | 최신 보안 조치/업데이트 지속 서비스, 독립적 네트워크 환경 제공 |

---

**SECTION.01**

# 서비스 모델 : IaaS, PaaS, SaaS

서비스 모델이란 클라우드 컴퓨팅에서  
제공되는 서비스의 종류나 수준을 나타내는 개념

## Infrastructure as a Service (IaaS)

∙ IaaS는 컴퓨팅 리소스(Server, Storage, Network 등)를 인터넷을 통해 제공하는 서비스 모델  
∙ 사용자는 인프라를 관리하지 않고도 컴퓨팅 리소스를 필요에 따라 구매하고 사용할 수 있음  
∙ “공간 대여”로 비유할 수 있음  
∙ 예) 가상 머신 서비스 (AWS EC2, Google Compute Engine, Azure Virtual Machines)

## Platform as a Service (PaaS)

∙ PaaS는 애플리케이션 개발, 배포, 및 운영을 지원하는 플랫폼을 인터넷을 통해 제공하는 서비스 모델  
∙ 개발자는 개발에 필요한 자원들을 신경 쓰지 않고 애플리케이션 개발에만 집중할 수 있음  
∙ “부엌 대여”로 비유할 수 있음  
∙ 예) Heroku (웹 애플리케이션 배치 모델로 사용되는 여러 프로그래밍 언어를 지원하는 클라우드 플랫폼)

## Software as a Service (SaaS)

∙ SaaS는 사용자가 인터넷을 통해 액세스할 수 있는 완전히 기능이 구현된 애플리케이션 서비스를 제공하는 모델  
∙ 소프트웨어를 설치하거나 유지 보수할 필요가 없음  
∙ “음식 체인점”으로 비유할 수 있음  
∙ 예) Gmail, MS365, Dropbox

---

**SECTION.01**

# 서비스 모델 : IaaS, PaaS, SaaS

![height:447px](https://objectstorage.kr-central-2.kakaocloud.com/v1/b6a9201d6cca4af591ff15a779724de1/doc2edu-sync/essential_basic_course/theory/service-model-diagram.png)

---

**SECTION.02**

# 카카오클라우드 연혁

카카오 10년간의 클라우드 네이티브 기술이 집약된 카카오클라우드

| 2021년 | 2022년 | 2023년 | 2024년 | 2025년 |
| --- | --- | --- | --- | --- |
| 카카오 i 클라우드 공식 첫 릴리즈 | 대외 고객 대상 퍼블릭 서비스 제공 | ‘카카오클라우드’로 서비스명 변경 | CPU크레딧 기반의 버스터블 기능 출시 | 국내 첫 지역혁신중심 대학지원체계(RISE) 플랫폼 구축 |
|  | 현재 공동체, 공공기관, 스타트업 등 약 60여 개 고객사에 클라우드 서비스 제공 | 고성능 컴퓨팅 서비스 BCS) 서비스 공개 | 카카오클라우드 교육센터 오픈 | AI/금융/모빌리티 도메인 대상 고성능 클라우드 집중 |
|  |  | VPC간 빠르고 성능 저하 없는 연결, TGW) 서비스 제공 | 전 세계 슈퍼컴퓨터 TOP 500중 41위 기록 |  |

BCS: Beyond Compute Service  
TGW: Transit Gateway

---

**SECTION.02**

# 카카오클라우드 배포 모델

|  | Public Cloud | Hybrid Cloud | Private Cloud |
| --- | --- | --- | --- |
| 위치 | Kakao IDC Public Zone | Kakao IDC 내 Kakao Cloud Extension | 고객사 IDC / 전산실 |
| 특징 | Container / 빅데이터 / AI 등 최신 PaaS 및 SaaS 서비스 제공 | 전문인력이 운영하는 프라이빗 존에 특정 고객을 위한 ITO, 클라우드 전용 공간 제공 | 고객이 원하는 환경에 설치형으로 제공 / IaaS / PaaS 서비스 제공(SaaS 서비스 불가) |
| 가격정책 | 월 사용료 (On-Demand) / Reserve Instance (1년/3년) | 사용료 (On-Demand) / 약정(Reserve) 계약 | H/W 구매 및 유지보수 비용 / S/W 구매 및 유지보수 비용 |
| 투자비 | - | - | 서버 등 인프라 장비 구매비 + 설치비 |
| 특장점 | 비용 절감, 유지 관리 불필요 / 전문인력을 통한 운영 서비스 제공 / 지속적인 서비스 개선과 관리 가능 / Kakao 데이터 및 컨텐츠 연동 용이 | 높은 수준의 제어와 개인 정보 보호 관리 / 전문인력을 통한 운영 서비스 제공 / 지속적인 서비스 개선과 관리 기능 / Kakao 데이터 및 컨텐츠 연동 용이 | 플랫폼 안정성이 높음 / 신속한 컨텐츠 응답처리 가능 / 거버넌스 적용 용이 |
| 고려사항 | 고성능 서비스 경우, 비용 절감 효과 미흡 / 전용회선 사용시 부가 비용 발생 | Public 대비 유연한 확대/축소 제한됨 / 전용회선 사용 시 부가 비용 발생 | 추가 투자비 발생 / 전문인력 필요(신속한 이슈 처리 곤란) |

---

**SECTION.02**

# 카카오클라우드의 다양한 서비스

![height:344px](https://objectstorage.kr-central-2.kakaocloud.com/v1/b6a9201d6cca4af591ff15a779724de1/doc2edu-sync/essential_basic_course/theory/cloud-services-overview.png)

---

**SECTION.02**

# 카카오클라우드의 차별성

![diagram](https://objectstorage.kr-central-2.kakaocloud.com/v1/b6a9201d6cca4af591ff15a779724de1/doc2edu-sync/essential_basic_course/theory/cloud-differentiators.png)

---

**SECTION.03**

# IAM

주요 구성 요소 및 개념 (조직, 프로젝트, 리소스)

## 카카오클라우드 IAM은 역할 기반 접근 제어 (Role Based Access Control, RBAC) 방식을 사용

### RBAC

미리 정의된 역할을 기반으로 사용자, 조직, 프로젝트의 권한을 제어

### 조직

프로젝트, 사용자 등을 하나의 조직으로 구성할 수 있는 추상화된 공간

### 프로젝트

서비스 레벨의 리소스를 소유하는 상위 단위  
• 반드시 특정 조직에 소속되어야 함  
• 자원 할당량은 프로젝트 단위로 설정됨  
• 사용자는 자원에 접근하기 위해 프로젝트 레벨 역할을 획득해야 함

### 리소스

단위프로젝트에 생성할 수 있는 인스턴스, 스토리지, 네트워크  
등의 컴퓨팅 자원이나 카카오클라우드에서 제공하는 서비스

---

**SECTION.03**

# IAM

![width:50%](https://objectstorage.kr-central-2.kakaocloud.com/v1/b6a9201d6cca4af591ff15a779724de1/doc2edu-sync/essential_basic_course/theory/iam-structure.png)

---

<!-- _class: security-group -->

**SECTION.05**

# Networking - VPC

## Security Group

### Bastion

#### 인바운드 정책

| 프로토콜 | 패킷 출발지 | 포트 번호 | 정책 설명 |
| --- | --- | --- | --- |
| TCP | 관리자 IP | 22 | 관리자 IP의 SSH 프로토콜 허용 |

#### 아웃바운드 정책

| 프로토콜 | 패킷 목적지 | 포트 번호 | 정책 설명 |
| --- | --- | --- | --- |
| ALL | 0.0.0.0/0 | ALL | 모든 패킷을 허용 |

### Web server

#### 인바운드 정책

| 프로토콜 | 패킷 출발지 | 포트 번호 | 정책 설명 |
| --- | --- | --- | --- |
| TCP | 0.0.0.0/0 | 80 | 모든 http 패킷 허용 |
| TCP | 0.0.0.0/0 | 443 | 모든 https 패킷 허용 |
| TCP | Bastion Private IP | 22 | SSH |

#### 아웃바운드 정책

| 프로토콜 | 패킷 목적지 | 포트 번호 | 정책 설명 |
| --- | --- | --- | --- |
| ALL | 0.0.0.0/0 | ALL | 모든 패킷을 허용 |

---

**SECTION.06**

# MySQL

## 백업

• 데이터베이스의 정보와 구조를 보존하고 나중에 복원할 수 있는 과정  
• 중요한 데이터를 안전하게 보호하고 비즈니스 운영을 지원하는 데 필수적인 요소  
• 시스템 장애, 인간 실수, 악성 코드 공격 등으로 인한 데이터 손실을 방지  
• 시스템 장애나 데이터 손실 상황에서 데이터를 빠르게 복구하는 데 도움  
• 백업 데이터는 데이터 분석, 테스트, 개발 등 다양한 목적으로 활용

![diagram](https://objectstorage.kr-central-2.kakaocloud.com/v1/b6a9201d6cca4af591ff15a779724de1/doc2edu-sync/essential_basic_course/theory/mysql-backup-lifecycle.png)

---

**SECTION.06**

# MySQL

## 백업 생명주기

백업은 Pending 상태로 시작하며, Processing 상태를 거쳐 Succeeded 상태가 되면 완료됨

• PENDING : 백업 초기 상태  
• PROCESSING : 현재 백업이 수행되는 중  
• SUCCEEDED : 백업이 성공적으로 종료된 상태  
• ERROR : 백업이 비정상적으로 종료된 상태 및 Backend 로직상의, DB, 외부 API 요청의 실패 시 업데이트 되는 상태  
• IN-USE-CHECKING : 성공한 백업을 삭제할 때 해당 백업을 이용한 복구가 진행중인지 확인하는 상태  
• DELETION-PENDING : 복구에 사용중인 백업이 삭제 대기중인 상태 (복구 완료 후 삭제 진행)  
• BACKUP-DELETING : 백업을 삭제하는 중  
• DELETED : 백업이 완전히 삭제된 상태

---

**SECTION.07**

# Networking - Load Balancer

## Round Robin

간단하고 예측 가능 : 라운드 로빈은 각 서버에 순차적으로 트래픽을 분산시키므로 알고리즘이 어떻게 동작하는지 예측하기 쉬움  
동등한 분배 : 서버 간에 균등한 트래픽 분배를 목표로 하므로, 초기 설정에서는 모든 서버에 동등한 부하가 생김  
쉬운 구성 : 라운드 로빈은 상대적으로 구현 및 설정이 쉬워서 소규모 환경에서 빠르게 설정하고 시작할 수 있음

![diagram](https://objectstorage.kr-central-2.kakaocloud.com/v1/b6a9201d6cca4af591ff15a779724de1/doc2edu-sync/essential_basic_course/theory/load-balancer-round-robin.png)

---

**SECTION.07**

# Networking - Load Balancer

## Least Connections

동적 부하 분배 : 현재 서버의 연결 수를 기반으로 트래픽을 분산시키기 때문에, 서버 간의 실시간 부하 차이를 고려하여 트래픽을 분산시킬 수 있음  
효율적인 자원 사용 : 특정 서버가 과부하 상태인 경우, 새로운 연결 요청은 부하가 덜한 서버로 전달됨. 이를 통해 전체 시스템의 자원 사용률을 극대화할 수 있음  
비동기 처리에 효과적 : 서버 간의 처리 시간이 크게 다를 경우, 가장 덜 바쁜 서버를 선택하여 전체 성능을 최적화할 수 있음

## Source IP

동일한 IP 헤더를 사용하는 클라이언트는 반드시 동일한 대상에게 트래픽을 전송

![diagram](https://objectstorage.kr-central-2.kakaocloud.com/v1/b6a9201d6cca4af591ff15a779724de1/doc2edu-sync/essential_basic_course/theory/load-balancer-least-connections.png)

---

**SECTION.08**

# Lab7 : Multi-AZ 구성 및 DNS 실습

## (실습 교재 76 page, Github Link)

## Lab

VPC안에 기존에 생성한 AZ1에 있는 웹서버와 AZ2에 새롭게  
 VM을 생성하여 DNS에 연결  
연결한 도메인을 통해 DNS 서비스가 작동하는지 확인하는 실습을 진행

## 목차

1. VPC 안 다른 AZ에 VM생성하기
2. DNS 서비스 설정
3. DNS 서비스 동작 확인

![height:215px](https://objectstorage.kr-central-2.kakaocloud.com/v1/b6a9201d6cca4af591ff15a779724de1/doc2edu-sync/essential_basic_course/theory/multi-az-dns-lab.png)

---

**SECTION.11**

# Management - Monitoring/Alert Center/Cloud Trail/Billing

## Monitoring

Monitoring이란?  
  
**모니터링하여 이벤트 발생 시 알림 기능으로 빠른 이슈 확인과 대처를 지원하는 개념**

• 대시보드에서 웹 환경의 주요 리소스에 대한 실시간 모니터링이 가능  
• 메트릭 및 로그 정책을 설정하여 체계적인 모니터링 시스템을 구성할 수 있음  
• 사용자의 자원을 유연하고 효율적으로 관리할 수 있으며, 관리에 필요한 리소스를 최소화할 수 있음

## 모니터링 서비스 시스템 아키텍처

미리 등록된 정책에 따라 장애가 발생할 시, 알림을 통해 모니터링 이력을 조회하며 장애를 빠르게 확인

![diagram](https://objectstorage.kr-central-2.kakaocloud.com/v1/b6a9201d6cca4af591ff15a779724de1/doc2edu-sync/essential_basic_course/theory/monitoring-architecture.png)

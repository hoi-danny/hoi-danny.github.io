---
marp: true
theme: default
paginate: true
style: |
  section {
    font-family: 'Noto Sans KR', 'Malgun Gothic', sans-serif;
    background-color: #ffffff;
    color: #222222;
    display: block !important;
    padding: 40px 50px !important;
  }
  section > *:first-child {
    margin-top: 0 !important;
  }
  section.title-slide {
    background-color: #FEE500;
    color: #222222;
    display: flex !important;
    flex-direction: column;
    justify-content: center !important;
  }
  section.section-header {
    background-color: #F5F5F5;
  }
  h1 {
    color: #222222;
    font-size: 1.6em;
    border-bottom: 3px solid #FEE500;
    padding-bottom: 8px;
    margin-top: 0;
    margin-bottom: 0.5em;
  }
  h2 {
    color: #333333;
    font-size: 1.2em;
  }
  h3 {
    color: #555555;
    font-size: 1.0em;
  }
  table {
    font-size: 0.55em;
    width: 100%;
    border-collapse: collapse;
  }
  th {
    background-color: #333333;
    color: #ffffff;
    padding: 4px 6px;
    text-align: center;
  }
  td {
    padding: 3px 6px;
    border: 1px solid #ddd;
    text-align: center;
  }
  ul, ol {
    font-size: 0.85em;
  }
  section.dense-table table {
    font-size: 0.45em;
  }
  section.dense-table td, section.dense-table th {
    padding: 2px 4px;
  }
---

<!-- _class: title-slide -->

# 카카오클라우드의 다양한 서비스

**SECTION.02**

카카오클라우드는 공공부터 기업까지 다양한 산업 도메인 특성을 고려한 전용 서비스 존(Zone) 구성, 맞춤형 솔루션 및 서비스 통합 제공을 통해 고객 비즈니스 성장을 위한 클라우드 환경을 제공합니다.

---

## 다양한 형태의 클라우드 제공

| 클라우드 유형 | 설명 |
|:---:|:---|
| **민간 클라우드** | 퍼블릭, 프라이빗 및 기업의 클라우드를 멀티, 하이브리드 등 원하는 방식으로 다양한 클라우드 서비스 제공 |
| **공공 클라우드** | 안정적인 공공서비스 및 편리한 대민 서비스 구축을 위해 보안 요건을 충족하는 클라우드 서비스 제공 |
| **금융 클라우드** | 금융기관과 핀테크 기업에 요구되는 엄격한 규제 속에서 신뢰 높은 서비스를 위한 클라우드 서비스 제공 |
| **의료 클라우드** | 스마트 헬스케어 서비스 구현을 위해 의료 보안 인증 기반의 안전한 의료 전용 클라우드 서비스 제공 |
| **교육 클라우드** | 실시간 영상 트래픽이 높은 스마트 교육 온라인 환경 제공을 위한 에듀테크 클라우드 서비스 제공 |
| **GPU 클라우드** | 인공지능 연구 개발부터 사업화까지 기업/기관의 고성능 연산 처리에 최적화된 클라우드 서비스 제공 |

---

# 카카오클라우드의 다양한 서비스

**SECTION.02**

---

## 서비스 목록 (1/3)

### Computing · Storage · Security

| 카테고리 | 서비스 | 설명 |
|:---:|:---:|:---|
| **Computing** | Virtual Machine | 물리적인 하드웨어 시스템을 바탕으로 재구성한 클라우드 컴퓨팅 환경 |
| | Bare Metal Server | 고성능의 물리 서버를 독립적으로 구성하여 뛰어난 성능과 안정성 제공 |
| | GPU | 대규모 병렬 연산을 위한 가속화된 인스턴스를 제공 |
| **Storage** | Block Storage | 데이터를 고정된 크기의 블록으로 나누어 저장하고 활용하는 스토리지 |
| | Object Storage | 확장성과 안정성을 갖춘 객체 기반 스토리지로 대용량 데이터처리에 최적화 |
| | File Storage | 공유 파일 시스템 프로토콜을 통해 다수의 서버가 공동으로 사용하는 스토리지 |
| **Security** | DDos Defender | DDos 공격을 탐지 완화 방어 대응하는 안정적인 보안 서비스 |
| | IDS | 외부침입에 대한 24×365 모니터링으로 치명적 위협 탐지와 대비 가능 |
| | Managed Security | 이벤트 모니터링, 취약점 정보 및 정기적 보안 리포트 제공 등 보안 관제 서비스 |

---

## 서비스 목록 (2/3)

### Container · Developer Tool · Data Store · Hybrid

| 카테고리 | 서비스 | 설명 |
|:---:|:---:|:---|
| **Container Pack** | Kubernetes Engine | VPC 기반의 관리형 쿠버네티스 서비스 |
| | Container Registry | 컨테이너 이미지를 클라우드에 안전하게 보관하고 활용할 수 있는 비공개 저장소 |
| **Developer Tool** | DevOps Pipeline | 서비스를 지속적으로 관리/개발/배포하는 과정을 파이프라인으로 관리 |
| | OSS Library | 미리 구성된 인프라 자동화 템플릿을 이용한 손쉬운 클라우드 프로비저닝 서비스 |
| **Data Store** | MySQL | 복잡한 설치 과정 없이 사용할 수 있는 관리형 데이터베이스 서비스 |
| | Redis | Key-Value 구조의 비정형 데이터를 메모리에 저장하여 사용하는 NoSQL DB |
| **Hybrid Cloud** | Hybrid Data Center | 멀티/하이브리드 클라우드 환경 구성을 위한 코로케이션, IT 호스팅, 관제 등의 서비스 |

---

## 서비스 목록 (3/3)

### Networking · Analytics · AI Service

| 카테고리 | 서비스 | 설명 |
|:---:|:---:|:---|
| **Networking** | VPC | 논리적으로 격리된 가상의 네트워크 공간을 제공 |
| | Load Balancing | 서버 과부하와 장애를 대비하기 위한 부하 분산 처리 서비스 |
| | CDN | 대용량의 웹 콘텐츠를 빠르고 안전하게 전송하는 네트워크 서비스 |
| | DNS | 서비스에 빠르고 안전하게 접근하기 위한 도메인관리 서비스 |
| | Transit Gateway | 다수의 VPC와 온프레미스 네트워크를 쉽고 자유롭게 연결하는 고가용성 서비스 |
| **Analytics** | Hadoop Eco | 대규모의 데이터를 활용한 데이터 분석 에코시스템 |
| | Data Catalog | 메타데이터들을 쉽게 검색하고 조회할 수 있는 데이터 관리 서비스 |
| | Pub/Sub | 대용량 이벤트와 데이터 분석을 위한 비설치형 메시지 큐서비스 |
| **AI Service** | OCR / Translation / STT / NLP / TTS / Vision / Conversation / Kubeflow |

---

# 카카오클라우드의 차별성

**SECTION.02**

## KakaoCloud만의 기술 경쟁력

KakaoCloud만의 기술 경쟁력을 기반으로 다양한 형태의 클라우드로 고객별 니즈를 충족하고자 합니다.

| Beyond the Cloud | Connect Everything | Ready for Business |
|:---:|:---:|:---:|
| **고성능 및 저비용** | **확장성 및 안정성** | **검증된 보안성** |

---

# IAM — 역할

**SECTION.03**

## 역할 : 권한의 모음

### 역할의 유형

- **조직 레벨 역할**
  조직 소유자, 조직 관리자, 조직 리더, 빌링 관리자, 빌링 매니저, 빌링 뷰어, 트레일 뷰어, Alert Center 관리자로 구성

- **프로젝트 레벨 역할**
  프로젝트 관리자, 프로젝트 멤버, 프로젝트 리더, Kubeflow 관리자로 구성

> 사용자에게 특정 역할을 부여하면, 해당 역할이 가진 권한이 사용자에게 자동으로 부여됨

---

<!-- _class: dense-table -->

# IAM — 조직 레벨 역할 (1/2)

**SECTION.03**

### 권한 매트릭스

| 권한 | 조직 소유자 | 조직 관리자 | 조직 리더 | 빌링 관리자 | 빌링 매니저 | 빌링 뷰어 | 트레일 뷰어 | Alert Center 관리자 |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 조직 생성/삭제 신청 | ✔ | | | | | | | |
| 조직 정보 수정 | ✔ | ✔ | | | | | | |
| 사용자 등록/삭제 | ✔ | ✔ | | | | | | |
| IAM 역할 추가/삭제 | ✔ | ✔ | | | | | | |
| 조직/프로젝트 정보 조회 및 IAM 역할 조회 | ✔ | ✔ | ✔ | | | | | |
| 그룹 관리 | ✔ | ✔ | | | | | | |
| 헬프데스크 일반 문의 답변 관리 | ✔ | ✔ | | | | | | |
| IdP 연동 및 로그인 정보 설정 | ✔ | ✔ | | | | | | |
| 보안 설정 | ✔ | ✔ | | | | | | |
| 빌링 역할 추가/삭제 | | | | ✔ | | | | |
| 결제수단 관리 | | | | ✔ | | | | |
| 크레딧 관리 | | | | ✔ | | | | |
| 청구서 조회 | | | | ✔ | ✔ | | | |
| 전체 프로젝트 예상요금 조회 | | | | ✔ | ✔ | | | |
| 특정 프로젝트 예상요금 조회 | | | | ✔ | ✔ | ✔ | | |
| 조직/프로젝트 이벤트 조회 | | | | | | | ✔ | |
| 조직 이벤트 알람 등록 및 발송 내역 조회 | | | | | | | | ✔ |

---

<!-- _class: dense-table -->

# IAM — 조직 레벨 역할 (2/2)

**SECTION.03**

### 역할 설명

| 역할 | 설명 |
|:---|:---|
| **조직 소유자** | 조직 생성을 신청한 사용자가 자동으로 획득하는 역할. 조직 생성 시 조직 관리자, 빌링 관리자 역할을 함께 획득. 조직 소유자 역할은 삭제가 불가능 |
| **조직 관리자** | 조직과 프로젝트를 관리하는 역할. 사용자 등록/삭제 가능, 그룹 생성/삭제, 프로젝트 생성 가능. 헬프데스크 일반 문의글의 답변 상태 및 질문 유형 변경 가능. 조직 리더 역할의 모든 권한 포함 |
| **조직 리더** | 조직 및 프로젝트의 사용자 조회와 IAM 역할 조회 가능. 프로젝트의 리소스 관리는 불가 |
| **빌링 관리자** | Billing 서비스에서 결제 수단, 크레딧 등록 및 관리. 빌링 매니저 역할의 모든 권한 포함 |
| **빌링 매니저** | Billing 서비스에서 조직 내 모든 프로젝트의 리소스 사용량 및 예상요금 조회. 빌링 뷰어 역할의 모든 권한 포함 |
| **빌링 뷰어** | Billing 서비스에서 조직 내 모든 프로젝트의 리소스 사용량 및 예상요금 조회 |
| **트레일 뷰어** | Cloud Trail 서비스 한정 역할. 조직 이벤트 및 프로젝트 이벤트 조회 가능 |
| **Alert Center 관리자** | Alert Center 서비스 한정 역할. 조직 이벤트의 알람 등록 및 발송 내역 조회 가능 |

---

# IAM — 프로젝트 레벨 역할 및 관리 권한

**SECTION.03**

| 권한 | 조직 소유자 | 조직 관리자 | 프로젝트 관리자 | 프로젝트 멤버 | 프로젝트 리더 |
|:---|:---:|:---:|:---:|:---:|:---:|
| 프로젝트 생성/삭제 | ✔ | ✔ | | | |
| 프로젝트 정보 수정 | ✔ | ✔ | ✔ | | |
| 프로젝트 레벨 역할 관리 | ✔ | ✔ | ✔ | | |
| 프로젝트 내 전체 리소스 CRUD | | | ✔ | | |
| 프로젝트 내 소유한 리소스 CRUD | | | ✔ | ✔ | |
| 프로젝트 내 리소스 조회 | | | ✔ | ✔ | ✔ |

### 역할 설명

- **프로젝트 관리자** — 소속 프로젝트 내 리소스 접근 및 관리 권한. 리소스 CRUD 가능, 사용자의 프로젝트 레벨 역할 추가/삭제/변경 가능. 프로젝트 멤버의 모든 권한 포함
- **프로젝트 멤버** — 소속 프로젝트 내 리소스 접근 및 관리 권한. 프로젝트 리소스 CRUD 가능
- **프로젝트 리더** — 프로젝트 내 권한이 있는 리소스 조회

---

# IAM — 자원과 리전 & AZ 간의 관계

**SECTION.03**

### 리소스 구분

- **글로벌 리소스(Global Resource)** — 전 세계 어디에서나 사용할 수 있음
- **리전 리소스(Region Resource)** — 특정 리전 내에서 사용
- **가용 영역 리소스(AZ Resource)** — 특정 데이터 센터 또는 가용 영역 내에서만 사용할 수 있음

| 서비스 | 유형 | | 서비스 | 유형 |
|:---:|:---:|:---:|:---:|:---:|
| IAM | Global | | Key Pair | Global & Region |
| VM | AZ | | DNS | Global |
| VPC | Region | | Volume | AZ |
| Subnet | AZ | | File Storage | AZ |
| Route Table | Global & Region | | Object Storage | Region |
| Security Group | Region | | | |
| Public IP | Region | | | |

---

# MySQL — Failover

**SECTION.06**

## Failover란?

데이터베이스 서버에 문제가 발생할 때, 다른 서버로 자동으로 전환하는 것

- MySQL은 **고가용성(HA, High Availability)** 기능을 지원
- 백업 인스턴스 가용성 타입을 고가용성으로 선택한 경우 다수의 Standby 인스턴스를 생성할 수 있으며, 장애 시 Failover 가능

### 리전별 지원 현황

- **kr-central-1** : 수동 Failover만 지원
- **kr-central-2** : Auto-Failover, 수동 Failover 둘다 지원

### Failover 생명주기

- **SWITCHING** : Failover를 진행하는 상태, MySQL 서비스를 사용할 수 없음
- **PRIMARY-AVAILABLE** : Standby 인스턴스를 구성하는 상태

> `Active` → `Fail` → `Passive` → `Active` (Standby가 승격)

---

<!-- _class: dense-table -->

# MySQL — 비용 (1/2)

**SECTION.06**

### 범용 (Standard) — MySQL 인스턴스 이용 요금

| 인스턴스 타입명 | vCPU | Memory (GB) | 시간 요금 | 월 요금 (30일 기준) |
|:---:|:---:|:---:|:---:|:---:|
| m2a.large | 2 | 8 | 227원 | 163,440원 |
| m2a.xlarge | 4 | 16 | 455원 | 327,600원 |
| m2a.2xlarge | 8 | 32 | 909원 | 654,480원 |
| m2a.4xlarge | 16 | 64 | 1,818원 | 1,308,960원 |
| m2a.8xlarge | 32 | 128 | 3,636원 | 2,617,920원 |
| m2a.12xlarge | 48 | 192 | 5,455원 | 3,927,600원 |
| m2a.16xlarge | 64 | 256 | 7,273원 | 5,236,560원 |
| m2a.24xlarge | 96 | 384 | 10,909원 | 7,854,480원 |

※ MySQL 볼륨 이용 요금: 시간당 0.16원 (VAT 별도) · 이용 요금은 변경될 수 있습니다.

---

<!-- _class: dense-table -->

# MySQL — 비용 (2/2)

**SECTION.06**

### 메모리 최적화 — MySQL 인스턴스 이용 요금

| 인스턴스 타입명 | vCPU | Memory (GB) | 시간 요금 | 월 요금 (30일 기준) |
|:---:|:---:|:---:|:---:|:---:|
| r2a.large | 2 | 16 | 278원 | 200,160원 |
| r2a.xlarge | 4 | 32 | 555원 | 399,600원 |
| r2a.2xlarge | 8 | 64 | 1,111원 | 799,920원 |
| r2a.4xlarge | 16 | 128 | 2,221원 | 1,599,120원 |
| r2a.8xlarge | 32 | 256 | 4,442원 | 3,198,240원 |
| r2a.12xlarge | 48 | 364 | 6,663원 | 4,797,360원 |
| r2a.16xlarge | 64 | 512 | 8,884원 | 6,396,480원 |
| r2a.24xlarge | 96 | 768 | 13,327원 | 9,595,440원 |

※ MySQL 볼륨 이용 요금: 시간당 0.16원 (VAT 별도) · 이용 요금은 변경될 수 있습니다.

---

# Lab5 : Private 서브넷 구성 및 MySQL을 통한 DB 구축 실습 (1/2)

**SECTION.06** · (실습 교재 46 page, Github Link)

MySQL 인스턴스를 생성한 후 기존에 구성한 Web Server VM과 연동하는 실습입니다.

### 목차

1. MySQL 인스턴스 생성
2. Bastion에 MySQL 인스턴스 그룹 연결 및 DB 설정
3. Web서버와 MySQL 인스턴스 연결 확인

---

# Lab5 : Private 서브넷 구성 및 MySQL을 통한 DB 구축 실습 (2/2)

**SECTION.06** · (실습 교재 46 page, Github Link)

### 네트워크 구성도

```
Internet Gateway
└── vpc_1 (172.30.0.0/16)
    └── Availability Zone (kr-central-2-a)
        ├── Public_subnet_1 (172.30.0.0/20)
        │   ├── web_server_1 (VM)
        │   └── bastion (VM)
        └── Private_subnet_1 (172.30.16.0/20)
            └── MySQL
```

---

# File Storage (1/2)

**SECTION.10** · Beyond Storage Services

## File Storage란?

**NFS(Network File System)** 프로토콜을 사용하여 공동의 데이터를 저장할 저장소를 간편하게 생성할 수 있는 서비스

- 주로 "파일" 형태의 데이터를 저장하고 관리하는 스토리지 유형으로 **공유 파일 시스템 및 협업용**으로 사용
- 저장한 데이터를 다수의 서버로 구성된 서비스 및 애플리케이션과 공유하기 때문에 여러 사용자가 파일을 읽고 쓸 수 있음
- File Storage 서비스는 데이터를 저장, 관리 및 Migration이 필요한 대부분의 IT 서비스에서 활용 가능

```
Availability Zone
├── VM1 ──┐
├── VM2 ──┼── File Storage
└── VM3 ──┘
```

---

# File Storage (2/2)

**SECTION.10** · Beyond Storage Services

## 인스턴스 타입 및 볼륨

- 인스턴스 생성 시 타입 선택이 가능하며, 각 타입 별 할당 가능한 최소/최대 용량이 상이
- 인스턴스 타입 별로 File Storage의 성능이 결정됨
- 현재(2024.01.30) File Storage 서비스는 **Basic 인스턴스 타입만 지원**

### 주요 개념

- **인스턴스** — CPU와 시스템 메모리를 포함한 가상 하드웨어 리소스
- **볼륨** — 실제 데이터가 저장될 공간

### 볼륨 할당

- 용량 단위: **TB 단위**
- 단일 인스턴스 타입(Basic): **1.0~10TB** 할당 가능 (0.5TB 단위로 설정)

---

# Lab9 : File Storage 실습

**SECTION.10** · (실습 교재 102 page, Github Link)

새로운 File Storage 인스턴스를 생성하고, File Storage를 사용 중인 VM 인스턴스와 연결해보고, 연결이 되었는지 확인합니다. 연결된 File Storage를 마운트 해제 후 확인해봅니다.

### 목차

1. File Storage 인스턴스 생성하기
2. VM에서 마운트하기
3. NFS 마운트 해제하기


# Wheelsafe - Backend

# 휠체어 이용자를 위한 길찾기 서비스

## TEAM 👨‍👨‍👧

|<img src="https://avatars.githubusercontent.com/u/78792358?v=4" width="100" height="100"/>|<img src="https://avatars.githubusercontent.com/u/77609030?v=4" width="100" height="100"/>|<img src="https://avatars.githubusercontent.com/u/86547109?v=4" width="100" height="100"/>|<img src="https://avatars.githubusercontent.com/u/26043178?v=4" width="100" height="100"/>|
|:-:|:-:|:-:|:-:|
|[@박현우](https://github.com/smartcow99)|[@김지민](https://github.com/wlasl0121)|[@김동해](https://github.com/e-astsea)|[@손승우](https://github.com/sons369)


---

## 프로젝트 개요 📝
휠체어 이용자를 위한 안전한 길을 찾아주는 웹 및 모바일 서비스를 개발. 공공데이터와 T-Map API를 활용하여 휠체어 이용자의 접근성을 고려한 최적 경로를 제공. **소프트웨어 공모전 은상**을 수상하고, 이후 경로 선정 로직을 40% 성능 개선하여 **새싹 공모전 대상**을 수상.

---

## 아키텍처 🏚

<div align="center">
  <img src="https://github.com/user-attachments/assets/10cb6f41-271f-43c4-9d92-922f0732c460" alt="System Architecture" width="45%" style="margin-right: 10px;"/>
  <img src="https://github.com/user-attachments/assets/ca9f8d01-8f95-4071-b42c-dbe47411783f" alt="Data Flow" width="45%"/>
</div>

---

## 시스템 환경 및 사용 기술 💻

| **항목**            | **상세 정보**                                                                                 |
|---------------------|-----------------------------------------------------------------------------------------------|
| **클라우드 플랫폼** | <img src="https://img.shields.io/badge/AWS EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white"/> <br> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat-square&logo=amazons3&logoColor=white"/>  |
| **데이터베이스**     | <img src="https://img.shields.io/badge/Mysql-4479A1?style=flat-square&logo=mysql&logoColor=white"/>  |
| **백엔드**          | <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/> <br> <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/> |
| **API**             | <img src="https://img.shields.io/badge/T_Map API-FF4500?style=flat-square"/> <br> <img src="https://img.shields.io/badge/Public Data-006400?style=flat-square"/> |
| **버전 관리**        | <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>  |
| **프로젝트 관리**    | <img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white"/>  |

---

## 주요 기능 🚀

1. **휠체어 이용자 맞춤 경로 제공**: 
   공공 데이터와 T-Map API를 이용하여 휠체어 이용자에게 적합한 안전한 경로를 제공.

2. **실시간 업데이트**: 
   외부 API로부터 실시간 데이터를 처리하여 최신 경로 정보를 제공.

3. **최적화된 성능**: 
   초기 출시 이후 경로 최적화 알고리즘을 수정하여 성능을 **40%** 개선, 경로 제공 속도와 정확도를 높임.

---

## 수상 내역 🏆

- **소프트웨어 공모전 은상**
- **새싹 공모전 대상** (성능 최적화 이후)

---

## 개발 과정 🔧

### 1. **백엔드 개발**:
   - **Node.js Express**를 사용해 경로 데이터를 처리하는 RESTful API 개발.
   - **T-Map API**를 통합하여 실시간으로 접근 가능한 경로를 계산.
   - **MySQL**을 사용해 사용자 데이터와 경로 기록을 관리.

### 2. **API 통합**:
   - **공공 데이터**와 **T-Map API**를 결합하여 휠체어 접근성을 고려한 실시간 경로 데이터를 제공.

### 3. **성능 최적화**:
   - 경로 선택 로직을 수정하여 성능을 **40%** 개선, 시스템의 응답 시간을 단축하여 경로 추천의 정확성을 높임.

---

## 문제 해결 🔥

| **문제**                           | **해결 방법**                                                                                              |
|-------------------------------------|-----------------------------------------------------------------------------------------------------------|
| **경로 계산 속도 저하**            | 경로 선택 알고리즘을 최적화하여 불필요한 계산을 줄이고 성능을 40% 개선.                                       |
| **API 통합 지연**                   | API 호출 흐름을 조정하여 외부 서비스로부터 더 빠르게 응답받도록 수정.                                        |
| **데이터베이스 병목 현상**          | 자주 조회되는 데이터에 대해 데이터베이스 인덱스를 추가하여 쿼리 성능을 향상.                                  |

---

## 결론 🎯

이 프로젝트는 휠체어 이용자를 위한 실용적인 길찾기 서비스를 제공하며, **공공 데이터**, **T-Map API**를 통해 실시간으로 경로를 업데이트하고 안전한 길을 추천합니다. 성능 최적화 후 여러 공모전에서 인정받아 수상하였으며, 이를 통해 사용자가 신뢰할 수 있는 경로 정보를 제공합니다.

---


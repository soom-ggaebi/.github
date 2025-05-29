# 🔍 숨숨파인더

#### 📌 프로젝트 소개
숨숨파인더는 경찰청 습득물 공공데이터를 활용한 유실물 통합 관리 서비스입니다.

#### 🗓️ 수행 기간
2025.03.03 ~ 2025.04.11

-----

# 👩‍💻 개발 환경
### Frontend
<img src="https://img.shields.io/badge/flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"> <img src="https://img.shields.io/badge/dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"> <br/>
### Backend
<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white"> <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/spring boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/spring Seucyrity-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white">
<img src="https://img.shields.io/badge/firebase-DD2C00?style=for-the-badge&logo=firebase&logoColor=white"> <br/>


### Database
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/redis-FF4438?style=for-the-badge&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=white">

### AI
<img src="https://img.shields.io/badge/Hugging face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=white"> 

### Data Processing
<img src="https://img.shields.io/badge/Apache Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"> <img src="https://img.shields.io/badge/apache hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=white">
<img src="https://img.shields.io/badge/apache spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white">
<img src="https://img.shields.io/badge/elastic search-005571?style=for-the-badge&logo=elasticsearch&logoColor=white">

### Infra / Devops
<img src="https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"> <img src="https://img.shields.io/badge/amazon s3-569A31?style=for-the-badge&logo=amazons3&logoColor=white">
<img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Gitlab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white">

### Tools
<img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"> <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
<img src="https://img.shields.io/badge/mattermost-0058CC?style=for-the-badge&logo=mattermost&logoColor=white">
  <br/>

-----

# 📋 기능 요약

- **지도 기반 습득물 확인**: 경찰청 및 숨숨파인더 등록 습득물을 지도 위 클러스터링으로 시각화
- **필터링 검색**: 상태, 보관 장소, 일자, 카테고리, 색상 기반 습득물 검색
- **AI 기반 자동 입력**: 습득물/분실물 이미지 등록 시 AI 이미지 분석을 통해 정보 자동 입력
- **AI 습득물 매칭**: 분실물 등록 시 유사한 습득물 자동 추천
- **1:1 채팅 및 경로 크로스체킹**: 사용자 경로 데이터 기반 신뢰성 검증
- **소지품 알림**: 사용자 이동 시 소지품 분실 방지 알림

-----

# 🔧 설계

### 시스템 아키텍처
![image](https://github.com/soom-ggaebi/.github/blob/b6e5f403ddc5703ec0a8417fa5253b99056476ce/images/architecture.png)

<br/>

### ERD
![erd](https://github.com/soom-ggaebi/.github/blob/b6e5f403ddc5703ec0a8417fa5253b99056476ce/images/erd.png)

-----

# 🎯 주요 화면 및 기능

#### 메인화면

| 메인화면 |
| :---: |
| <img src="https://github.com/soom-ggaebi/.github/blob/a9b860c046a78dbf367033e1bdb86a8a6aaaae96/images/main.png" width="300" /> |

#### 습득물 검색 및 상세조회

| 지도 클러스터링 | 필터링 검색 |
| :---: | :---: |
| <img src="https://github.com/soom-ggaebi/.github/blob/a9b860c046a78dbf367033e1bdb86a8a6aaaae96/images/found_map.png" width="300" /> | <img src="https://github.com/soom-ggaebi/.github/blob/a9b860c046a78dbf367033e1bdb86a8a6aaaae96/images/found_filter.png" width="300" /> |

| 상세 조회(숨숨파인더) | 상세 조회(경찰청) |
| :---: | :---: |
| <img src="https://github.com/soom-ggaebi/.github/blob/a9b860c046a78dbf367033e1bdb86a8a6aaaae96/images/found_detail_ssfinder.png" width="300" /> | <img src="https://github.com/soom-ggaebi/.github/blob/a9b860c046a78dbf367033e1bdb86a8a6aaaae96/images/found_detail_lost112.png" width="300" /> |

#### AI 이미지 분석 및 습득물 매칭

| AI 이미지 분석 | 자동 정보 입력 | AI 습득물 매칭 |
| :---: | :---: | :---: |
| <img src="https://github.com/soom-ggaebi/.github/blob/a9b860c046a78dbf367033e1bdb86a8a6aaaae96/images/lost_image_processing.png" width="300" /> | <img src="https://github.com/soom-ggaebi/.github/blob/a9b860c046a78dbf367033e1bdb86a8a6aaaae96/images/lost_add_image.png" width="300" /> | <img src="https://github.com/soom-ggaebi/.github/blob/bdd70fba6af690b9cbd1ac672f0bf35732d9bd84/images/found_recommend.png" width="300" />  |

#### 채팅 및 알림

| 채팅 | 소지품 알림 |
| :---: | :---: |
| <img src="https://github.com/soom-ggaebi/.github/blob/3e5268a236ba6dbb979fd223cfbcd54de0ccf550/images/chat.png" width="300" /> | <img src="https://github.com/soom-ggaebi/.github/blob/3e5268a236ba6dbb979fd223cfbcd54de0ccf550/images/notification.png" width="300" /> |

-----

# 🥳 팀원
| 송가연(팀장) | 김자연 | 박수미 | 손서현 | 오연수 | 이영재 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| FE<br/>UI/UX | BE<br/>DevOps | FE | BE<br/>AI | BE | BE<br/>DATA |
<br/>

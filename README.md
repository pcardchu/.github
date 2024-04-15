# 피카추 ⚡

<div align="center">
  <br />
  <img src="images/앱로고.png" width="60%"/>
  <br />
</div>

## 목차

- [서비스 개요](#서비스-개요)
- [팀원소개](#팀원소개)
- [기술스택](#기술스택)
- [시스템 아키텍처](#시스템-아키텍처)
- [기능소개](#기능소개)
- [프로젝트 산출물](#프로젝트-산출물)
- [컨벤션](#컨벤션)

## 서비스 개요

```
빅데이터 기반 소비 패턴 분석 및 카드 추천 서비스
피카추 ⚡⚡ (Personal 카드 추천)

📌 2024.02.19 ~ 2024.04.05 (7주)
```

## 팀원소개

<div align="middle">
<table>
    <tr>
        <td height="140px" align="center"> <a href="https://github.com/LeeChangon">
            <img src="https://avatars.githubusercontent.com/LeeChangon" width="140px" /> <br><br> 👑 이창곤 <br>(Front-End) </a> <br></td>
        <td height="140px" align="center"> <a href="https://github.com/lhgeer7485">
            <img src="https://avatars.githubusercontent.com/lhgeer7485" width="140px" /> <br><br> 🥈 이해건 <br>(Front-End) </a> <br></td>
        <td height="140px" align="center"> <a href="https://github.com/seolyeonpark">
            <img src="https://avatars.githubusercontent.com/seolyeonpark" width="140px" /> <br><br> 🍻 박설연 <br>(Front-End) </a> <br></td>
        <td height="140px" align="center"> <a href="https://github.com/yi219">
            <img src="https://avatars.githubusercontent.com/yi219" width="140px" /> <br><br> 🐹 금예인 <br>(Back-End) </a> <br></td>
        <td height="140px" align="center"> <a href="https://github.com/Int-TRUE">
            <img src="https://avatars.githubusercontent.com/Int-TRUE" width="140px" /> <br><br> 🍔 정수진 <br>(Back-End) </a> <br></td>
        <td height="140px" align="center"> <a href="https://github.com/TutiTuti">
            <img src="https://avatars.githubusercontent.com/TutiTuti" width="140px" /> <br><br> 🥩 최용수 <br>(Back-End) </a> <br></td>
    </tr>
</table>
</div>

## 기술스택

### 프론트엔드

<div align="middle">

<img src="https://img.shields.io/badge/flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white">
<img src="https://img.shields.io/badge/dart-0175C2?style=for-the-badge&logo=dart&logoColor=white">

**Language |** Dart 3.3.0

**Framework |** Flutter 3.19.0

**IDE |** Android Studio Hedgehog

**Library |** local_auth: ^2.2.0, provider: ^6.1.2, dio: ^5.4.1
, change_app_package_name: ^1.1.0, kakao_flutter_sdk: ^1.9.0, flutter_secure_storage: ^9.0.0, shared_preferences: ^2.2.2, flutter_dotenv: ^5.1.0, encrypt: ^5.0.3, crypto: ^3.0.3, flutter_native_splash: ^2.4.0, confetti: ^0.7.0, credit_card_scanner: ^1.0.5, webview_flutter: ^4.7.0, intl: ^0.19.0, pie_chart: ^5.4.0, table_calendar: ^3.1.1, rive: ^0.13.1, secure_application: ^4.0.0, flutter_launcher_icons: ^0.13.1, flutter_card_swiper: ^7.0.0,

<br>
<br>

</div>

### 백엔드

<div align="middle">

<img src="https://img.shields.io/badge/java-3a75b0?style=for-the-badge&logo=java&logoColor=black"> <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
<img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens">
<img src="https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white">
<img src="https://img.shields.io/badge/spring boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/spring mvc-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
<img src="https://img.shields.io/badge/JPA Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white">
<img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">

**Language |** Java 17.0.9

**Framework |** Spring Boot 3.2.3

**Data(RDBMS) |** Spring Data JPA

**Build Tool |** Gradle 8.4.0

**ETC |** Chrome: 122.0.6261.112, Chrome Driver: 122.0.6261.111 (크롤링)

</div>

<br>
<br>

### 분산

<div align="middle">

<img src="https://img.shields.io/badge/apache hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=white"> 
<img src="https://img.shields.io/badge/apache spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"> 
<img src="https://img.shields.io/badge/apache cassandra-1287B1?style=for-the-badge&logo=apachecassandra&logoColor=white"> 
<img src="https://img.shields.io/badge/JASYPT-000000?style=for-the-badge">
<img src="https://img.shields.io/badge/apache zookeeper-47802F?style=for-the-badge&logoColor=white"> 
<img src="https://img.shields.io/badge/zeppelin-4E5EE4?style=for-the-badge&logo=zeppelin&logoColor=white"> 
<img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">

**Language |** Python 3.8

**Framework |** Apache Hadoop 3.2.4, Apache Spark 3.2.4, Apache Zookeeper 3.8.4, Zeppelin 0.10.1

**DB |** HDFS, Apache Cassandra 4.1.4

</div>

<br>
<br>

### 인프라

<div align="middle">

<img src="https://img.shields.io/badge/gitlab-F05032?style=for-the-badge&logo=gitlab&logoColor=white">
<img src="https://img.shields.io/badge/AWS EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">
<img src="https://img.shields.io/badge/maria DB-4479A1?style=for-the-badge&logo=mariadb&logoColor=white">
<img src="https://img.shields.io/badge/jenkins-111111?style=for-the-badge&logo=jenkins&logoColor=white">
<img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/mattermost-0058CC?style=for-the-badge&logo=mattermost&logoColor=white">
<img src="https://img.shields.io/badge/nginx-00953B?style=for-the-badge&logo=nginx&logoColor=white">

**DB |** MariaDB 10.11, MongoDB

**Server |** GitLab, Jenkins, Docker

</div>
<br>
<br>

## 시스템 아키텍처

<div align="middle">
  <br />
  <img src="images/시스템아키텍처.png" width="80%"/>
  <br />
</div>

## 기능소개

✨ 회원가입
<br>
<img src = "images/2차로그인.gif" width="200">

<br>
<br>
✨ 로그인
<br>
<img src = "images/페이스아이디.gif" width="200">

- 카카오 소셜 로그인 (1차)
- 지문과 페이스 아이디를 통한 생체 로그인 (2차)

<br>
<br>

✨ 홈화면 - 혜택 별 카드 리스트
<br>
<img src = "images/홈-카드리스트.gif" width="200">

- 연령 별 소비 데이터를 통한 분석 결과 제공
- 개인 데이터를 이용하여 같은 집단과 비교 결과 제공
- 혜택 별로 살펴보는 인기 카드 리스트

<br>
<br>
✨ 내 카드 화면
<br>
<img src = "images/카드등록.gif" width="200">

<img src = "images/등록완료.gif" width="200">

- ocr을 통한 카드 등록
<br>
<img src = "images/내카드정보.gif" width="200">

- 등록된 카드 이미지와 상세 정보
- 하루동안의 소비와 카드 혜택을 잘 이용하고 있는지 계산
<br>
<br>
✨ 소비패턴 화면
<br>
<img src = "images/소비패턴.gif" width="200">

- 등록한 카드를 바탕으로 소비 패턴 분석
- 한달 소비 내역 및 카테고리 분석
- 이전 달과 비교한 소비 결과

<br>
<br>
✨ 추천 카드 화면
<br>
<img src = "images/카드추천.gif" width="200">

- 분석한 소비패턴을 기반으로 카드 추천
- 가장 많이 사용한 혜택 내역 위주의 추천

<br>
<br>

## 프로젝트 산출물

- API 명세서

> https://www.notion.so/yi219/API-5df77923d2d04ae5ae141e36410670be?pvs=4

- ERD

<div align="middle">
  <br />
  <img src="images/erd.png" width="70%"/>
  <br />
</div>

<br>
<br>

- 와이어프레임

> https://www.figma.com/file/7OJJjBJYvG7yZHZMA2RcJ4/D110-%EC%A7%B1%EB%93%A4%EC%9D%98%EB%94%94%EC%9E%90%EC%9D%B8?type=design&node-id=143%3A533&mode=design&t=jmWbTaIamnQybbWO-1

<br>
<br>

- 분산 파이프라인
<div align="middle">
  <br />
  <img src="images/분산처리구조.png" width="50%"/>
  <br />
</div>

- 포팅매뉴얼

> [포팅매뉴얼](./exec/distributed_file_system_setting.md)

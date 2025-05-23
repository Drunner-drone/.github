# Drunner - 스마트 러닝 서비스

![main](images/main_sample.png)

<br />

# 목차

1. [프로젝트 개요](#프로젝트-개요)
2. [프로젝트 기간](#프로젝트-기간)
3. [팀원 소개](#팀원-소개)
4. [프로젝트 설계 및 구성](#프로젝트-설계-및-구성)  
   4-1. [서비스 아키텍처](#아키텍처)  
   4-2. [데이터베이스 설계](#데이터베이스-erd)
5. [사용 기술](#사용-기술)
6. [주요 기능](#주요-기능)

<br />

# 프로젝트 개요

### 🏃‍♀️ 혼자 뛰는 러닝, 아쉬운 점이 있지 않으셨나요?

> 러닝을 하며 **페이스 조절이 어렵고**, **자세 교정이나 피드백을 받기 힘들다**는 점은 많은 러너들의 공통된 고민입니다. 저희는 이러한 문제를 해결하기 위해, **드론을 활용한 스마트 러닝 서비스 `Drunner`** 를 개발했습니다.
>
> 📡 **실시간 자세 분석**, 🕒 **페이스 메이커 기능**, 📱 **운동 기록 관리**까지
> 이제 러닝은 혼자가 아닌, 하늘에서 함께합니다.

<br />

# 프로젝트 기간

### 2025.04.14 ~ 2025.05.22

<br />

# 팀원 소개

<table align="center">
  <tr>
    <td align="center" width="17%;">
      <img src="images/drone1.png" alt=""/>
      <br/><sub><b>이건우</b><br/>
      <span>팀장</span><br/>
      <span>BE/AI</span>
      </sub>
    </td>
    <td align="center" width="17%;">
      <img src="images/drone2.png" alt=""/>
      <br/><sub><b>김본</b><br>
      <span>팀원</span><br/>
      <span>DRONE</span>
      </sub>
    </td>
    <td align="center" width="17%;">
      <img src="images/drone3.png" alt=""/>
      <br/><sub><b>유영신</b><br>
      <span>팀원</span><br/>
      <span>DRONE</span>
      </sub>
    </td>
    <td align="center" width="17%;">
      <img src="images/drone4.png" alt=""/>
      <br/><sub><b>한슬기</b><br>
      <span>팀원</span><br/>
      <span>BE/INFRA</span>
      </sub>
    </td>
    <td align="center" width="17%;">
      <img src="images/drone5.png" alt=""/>
      <br/><sub><b>박해구</b><br>
      <span>팀원</span><br/>
      <span>AOS</span>
      </sub>
    </td>
  </tr>
</table>

<br>

# 프로젝트 설계 및 구성

## 아키텍처

![architecture](images/architecture.png)

## 데이터베이스 ERD

![erd](images/erd.png)

<br />

# 사용 기술

### 운영체제

- **로컬 개발 환경:**

  ![windows11](https://img.shields.io/badge/Windows%2011-%230079d6.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)

- **서버 운영 환경:**

  ![amazonec2](https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
  ![linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

### IDE & Editor

![IntelliJIDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)

---

### 버전 & 이슈 관리 및 협업 도구

![git](https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white)
![gitlab](https://img.shields.io/badge/Gitlab-FC6D26?style=for-the-badge&logo=Gitlab&logoColor=white)
![notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white)

---

### 배포 환경 및 빌드 도구

![amazonec2](https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white)
![docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white)
![docker-compose](https://img.shields.io/badge/DockerCompose-blue?style=for-the-badge&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white)

- AWS EC2 (Ubuntu `22.04`)
- Nginx `1.27.4`
- Docker `28.1.1`
- Docker Compose `2.35.1`
- Jenkins (CI/CD) `2.504.1`
- Gradle `8.11.1`

---

### Drone

- **드론 모델**

  **DJI Mini 3**

  ![drone](images/drone.png)

---

### AI

- **언어**

  ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

- **서버**

  ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

- **모델**

  ![Yolo](https://img.shields.io/badge/-YOLO-111F68?style=for-the-badge&logo=YOLO&logoColor=white)

- **프레임워크 / 추론 알고리즘**

  ![MedaiPipe](https://img.shields.io/badge/-Mediapipe-007ACC?style=for-the-badge&logo=google&logoColor=white&size=40x40)
  ![Pose Estimation](https://img.shields.io/badge/-Pose%20Estimation-2E8B57?style=for-the-badge&logo=python&logoColor=white&size=40x40)

---

### BackEnd

![java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![springboot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![jpa](https://img.shields.io/badge/Spring_data_jpa-F37C20?style=for-the-badge&logo=SpringSecurity&logoColor=white)
![querydsl](https://img.shields.io/badge/Query%20DSL-000000?style=for-the-badge&logo=apachekafka&logoColor=white)
![config](https://img.shields.io/badge/Spring%20Cloud%20Config-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-FF9800?style=for-the-badge)

- JAVA (OpenJDK `17.0.14`)
- SpringBoot `3.2.5`
- QueryDSL `5.1.0`
- Spring Cloud Config `4.2.2`

---

### FrontEnd(Mobile & WearOS)

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Hilt](https://img.shields.io/badge/Hilt%20DI-34A853?style=for-the-badge&logo=google&logoColor=white)
![Retrofit](https://img.shields.io/badge/Retrofit-007AFF?style=for-the-badge&logo=retrofit&logoColor=white)

- Kotlin `2.0.20`
- Jetpack Compose `2.0.20`
- Hilt `2.56.1`
- Retrofit `2.9.0`

---

### DB & Storage

![mysql](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![minio](https://img.shields.io/badge/minio-C72E49.svg?style=for-the-badge&logo=minio&logoColor=white)

- MySQL `8.0.41`
- Minio `RELEASE.2025-04-22T22-12-26Z`

<br />

# 주요 기술

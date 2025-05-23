# Drunner - 하늘에서 시작되는 나의 러닝 다이어리

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
6. [주요 기술](#주요-기술)
7. [주요 기능](#주요-기능)

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
![WebSocket](https://img.shields.io/badge/WebSocket-FF9800?style=for-the-badge&logo=openjdk)

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

---

### Drone

- **드론 모델**

  **DJI Mini 3**

  ![drone](images/drone.png)

<br />

# 주요 기술

### 1. 영상 정보 전송 & 피드백 알림 전송

- 드론 서버로부터 실시간 영상을 받기 위해 **`UDP Websocket`** 연결
- 워치로부터의 운동 데이터 수신 및 피드백 알림 전송을 위해 **`TCP Websocket`** 연결

### 2. 사용자 인식

- YOLO 11 모델을 사용하여 사용자를 인식
- **손의 포인트가 코보다 높게 2초간 유지**되면 해당 사용자 추종을 시작

  ![recognize](images/gif/recognize.gif)

### 3. 드론 위치 제어

객체 인식 후, 첫 **Bounding Box의 면적(`targetArea`)** 을 저장하고, 이후 프레임에 대한 **Bounding Box의 면적(`area`)** 을 계산하여 드론의 위치를 제어

- **전진 및 후진**

  area의 크기가 감소한다면 전진, 증가한다면 후진으로 판단하여 드론의 위치 제어

- **좌/우진 및 좌/우향**

  인식된 객체의 Bounding Box의 중심이 화면 중앙에서 얼마나 벗어났는지 정규화한 offset의 x축 값을 이용하여 좌/우 이동과 좌/우 방향 각도를 조절

### 4. 관절 좌표 추정 및 피드백

- **`MediaPipe의 Pose Estimation`** 을 활용하여 상체 기울기, 팔 기울기, 무릎 각도 등 다양한 부위의 각도를 측정
- 측정 각도가 정상 범위를 벗어나면 피드백 전송

### 5. Round Robin

- 동시에 여러가지의 피드백이 들어왔을 때, 섞이지 않고 순차적으로 피드백을 보내기 위해 사용
- 빠른 응답을 위해 영상 분석부터 피드백 전달까지의 과정을 **백그라운드**로 수행

  ![Round Robin](images/rr.png)

### 6. 영상 Upscaling

- 빠른 영상 통신을 위해 저해상도(320x240)로 전달
- 전달 시 **`FSRCNN 기반 4배 업스케일링`**으로 화질을 개선하여 전달

  ![Upscaling](images/upscaling.png)

### 7. 피드백 영상 저장

- 유연한 확장성과 비용 효율성을 확보하기 위해 MinIO를 활용해 자체 영상 저장 스토리지를 구축
- 러닝 중 촬영된 피드백 영상은 **`MinIO`**에 업로드되며, 추후 사용자 피드백 기록과 함께 조회

<br />

# 주요 기능

### 1. 러닝 시작

- **갤럭시 워치를 통해 트래킹(일반) 모드와 페이스 모드를 선택하여 러닝 시작**
- **러닝을 시작하면 드론이 떠올라 러닝을 준비**

  ![watch start](images/static/watch_start.png)

### 1. 러닝 트래킹

- **드론이 러닝 중인 사용자를 따라 이동하며 자세를 분석합니다.**

  ![drone_tracking](images/gif/drone_tracking.gif)

### 2. 실시간 자세 피드백 알림

- **갤럭시 워치를 통해 심박수, 페이스 등 러닝 시 측정되는 신체 정보와 잘못된 러닝 자세에 대한 피드백을 제공**
- **페이스 모드에서는 페이스를 조절하여 진행 가능**

  ![watch](images/gif/watch.gif)

### 3. 운동 기록

- **러닝 종료 시, 기록 확인 및 저장**

  ![summary](images/static/summary.png)

- **날짜 별 러닝 기록과 러닝 경로, 페이스 구간 등 다양한 정보 확인**

  ![history](images/gif/mobile.gif)

- **러닝 자세 분석 히스토리**

  ![feedback](images/gif/history.gif)

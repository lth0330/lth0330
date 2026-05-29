![header](https://capsule-render.vercel.app/api?type=waving&color=0:1E3A8A,100:2563EB&height=180&section=header&text=Lee%20Tae%20Hyung&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=Backend%20Developer&descSize=18&descAlignY=55)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=lth0330&label=Profile%20Views&color=2563eb&style=flat-square" alt="profile views" />
</p>

# 이태형 | Backend Developer

데이터 흐름을 이해하고, 문제를 구조적으로 분석하며 개선하는 백엔드 개발자를 지향합니다.

Java와 Spring Boot 기반 REST API 개발을 중심으로, React 웹 프론트엔드, Flutter 앱, Python 기반 객체 인식 모듈이 연동되는 졸업작품 프로젝트를 구현하고 있습니다.

<p>
  <a href="mailto:xm3003@naver.com">
    <img src="https://img.shields.io/badge/Email-xm3003%40naver.com-03C75A?style=flat-square&logo=naver&logoColor=white" alt="email" />
  </a>
  <a href="https://github.com/lth0330">
    <img src="https://img.shields.io/badge/GitHub-lth0330-181717?style=flat-square&logo=github&logoColor=white" alt="github" />
  </a>
</p>

## About Me

- 성결대학교 정보통신공학과 졸업예정
- 관심 분야: 백엔드 개발, REST API 설계, 데이터베이스 설계, 서비스 연동 구조
- 주 사용 기술: Java, Spring Boot, JPA, MySQL, React, Python
- Git/GitHub 기반 협업, Jira 이슈 관리, Pull Request 코드 리뷰 경험
- AWS EC2, RDS, S3 기반 배포 및 데이터베이스 연동 경험

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Java%2017-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" alt="Spring Security" />
  <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white" alt="JPA" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
</p>

### Backend

- Java 17
- Spring Boot
- Spring Web MVC
- Spring Security
- Spring Data JPA
- JWT Authentication
- Lombok

### Frontend

- React
- Vite
- React Router
- Axios
- HTML / CSS / JavaScript

### App

- Flutter
- Dart
- Firebase Cloud Messaging
- flutter_secure_storage
- sqflite

### Database & Infra

- MySQL
- AWS RDS
- AWS EC2
- AWS S3
- Git / GitHub
- Jira

### Python & AI

- Python
- FastAPI
- OpenCV
- Ultralytics YOLO
- EasyOCR
- NumPy

## Graduation Project

### 아파트 주차 관리 시스템

웹 관리자, 아파트 관리자, 입주민 앱 사용자, Python 객체 인식 모듈이 함께 동작하는 아파트 주차 관리 시스템입니다.

이 프로젝트는 주차장과 주차구역을 관리하고, 입주민 차량과 방문차량 정보를 등록하며, 카메라 기반 객체 인식 결과를 백엔드로 전달해 주차 상태를 갱신하는 구조로 설계했습니다.

### Main Features

- JWT 기반 로그인 및 권한 분리
- 웹 관리자 로그인
- 아파트 관리자 회원가입 승인/거절
- 입주민 가입 요청 승인/거절
- 주민 정보 관리
- 입주민 차량 및 방문차량 관리
- 주차장/주차구역 등록, 수정, 삭제
- 주차구역 상태 및 배치 관리
- 입주민 앱 로그인, 회원가입, 차량 등록
- 주차 대기 신청
- 입주민 문의 및 관리자 답변
- FCM 기반 앱 푸시 알림
- Python 객체 인식 모듈의 주차 이벤트 전달

### Project Architecture

```text
React Admin Web
        |
        | REST API
        v
Spring Boot Backend ---- MySQL / AWS RDS
        ^
        | REST API
        |
Flutter Resident App
        ^
        |
FastAPI Relay Server
        ^
        |
Python YOLO / OCR Parking Detection Module
```

### My Role

- Spring Boot 기반 웹/앱 공통 백엔드 기능 구현
- 관리자 및 입주민 권한 흐름 설계
- JWT 기반 인증/인가 구조 적용
- 주민, 차량, 주차장, 주차구역 관리 API 구현
- React 관리자 웹 화면과 백엔드 API 연동
- Flutter 입주민 앱과 Spring Boot API 연동 구조 정리
- Python 객체 인식 모듈과 백엔드 사이의 이벤트 연동 구조 설계
- DB 테이블 구조 정리 및 API 명세 관리

### Project Tech Stack

- Backend: Java 17, Spring Boot, Spring Security, Spring Data JPA, JWT
- Frontend: React, Vite, Axios, React Router
- App: Flutter, Dart, Firebase Messaging
- AI/Python: Python, FastAPI, OpenCV, YOLO, EasyOCR
- Database: MySQL, AWS RDS
- Collaboration: Git, GitHub, Jira

## Project Experience

### GreenZone

탄소 데이터 기반 인증 플랫폼 프로젝트에서 백엔드 및 프론트엔드 개발을 담당했습니다.

- 전문가 답사 보고서 기능 구현
- ESG 보고서 생성 기능 구현
- 이메일 자동 전송 기능 구현
- 지도 기반 데이터 시각화 기능 구현
- 나무 데이터 관리 CRUD API 구현
- Java Stream `groupingBy`를 활용해 ESG 보고서 데이터 집계 로직 개선

성과:

- 반복 필터링 구조를 그룹화 기반 집계 구조로 개선
- 데이터 처리 시간 약 40~70% 단축
- 코드 가독성과 유지보수성 개선

## Strengths

- 요구사항을 기능 단위로 나누고 데이터 흐름을 먼저 정리하는 방식으로 개발합니다.
- 문제가 발생하면 로그와 재현 과정을 통해 원인을 단계적으로 추적합니다.
- API 명세, 역할 분담, Git 브랜치 전략을 활용해 협업 기준을 맞추는 경험이 있습니다.
- 기능 구현뿐 아니라 유지보수성과 설명 가능한 구조를 중요하게 생각합니다.

## Awards & Activities

- 성결스터디즈 교내 프로젝트 장려상
  - 센서 기반 시스템 설계 및 하드웨어-소프트웨어 연동 개발
  - 팀 리더로 일정 관리와 역할 분담 수행
- 전자회로설계 경진대회 우수상
  - OPAMP 기반 필터 회로 설계
  - PSpice 시뮬레이션 및 측정 데이터 분석

## Focus Areas

- Spring Boot 기반 REST API 설계
- JPA 기반 데이터 모델링
- React 기반 관리자 페이지 구현
- AWS 기반 서비스 배포
- Python AI 모듈과 백엔드 API 연동

## GitHub Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=lth0330&show_icons=true&theme=default&hide_border=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lth0330&layout=compact&theme=default&hide_border=true" alt="Top languages" />
</p>

## Contact

<p>
  <a href="mailto:xm3003@naver.com">
    <img src="https://img.shields.io/badge/Email-xm3003%40naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white" alt="email" />
  </a>
  <a href="https://github.com/lth0330">
    <img src="https://img.shields.io/badge/GitHub-lth0330-181717?style=for-the-badge&logo=github&logoColor=white" alt="github" />
  </a>
</p>

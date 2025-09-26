# 🏋️ Capstone Project - Dongguk University

**운동 어플리케이션 (Fitmotion)**

👉 현재 프로젝트는 [fitmotion-refactor/fitmotion-backend](https://github.com/fitmotion-refactor/fitmotion-backend) 로 리팩토링 진행 중입니다.

---

## 🤝 팀원

* 홍지수
* 조윤수
* 김태영
* 안수연

---

## 👨‍💻 개발 포지션

| 개발내용                                | 상세 역할            | 담당 팀원 |
| ----------------------------------- | ---------------- | ----- |
| **JavaScript, Node.js, MySQL**      | 백엔드, 데이터베이스      | 조윤수   |
| **MySQL, MediaPipe**                | 모션 인식, 데이터베이스    | 김태영   |
| **Figma, MediaPipe**                | 모션 인식, UI/UX 디자인 | 홍지수   |
| **Figma, React Native, JavaScript** | 프론트엔드, 디자인       | 안수연   |

---

## 🎯 프로젝트 목적

* 모션 인식을 활용하여 올바른 자세로 운동을 돕고, 동기부여 기능을 제공하는 웹앱
* **기술 스택:** JavaScript / Node.js / React Native / MySQL / MediaPipe

---

## 📚 주요 기능

### 1. 회원 인증

* JWT 기반 회원가입 및 로그인
* 트레이너 전용 기능 제공

### 2. 게시글 관리

* **Create:** 운동 기록 게시글 및 댓글 작성
* **Read:** 전체 게시글 보기, 내 프로필 게시글 조회, 가입자 목록 확인, 날짜별 운동 기록 검색
* **Update:** 게시글, 댓글, 프로필 수정
* **Delete:** 게시글, 댓글 삭제

### 3. 운동 기록 관리

* 날짜별 운동 기록 관리
* 좋아요 추가 및 취소

### 4. 실시간 대화

* WebSocket 기반 비동기 대화 시스템

  * 게시글 작성자와 실시간 DM
  * 메시지 답장 및 삭제 기능

### 5. 운동 동작 분석

* MediaPipe 활용 동작 분석

  * 운동 동작 인식 및 초기 위치 설정
  * 동작 평가 및 피드백 제공

---

## ⚙️ 실행 방법

### 백엔드 실행

* **폴더명:** `capstone_final_back`
* **명령어:** `npm run dev`
* **포트:** `3000`

### 프론트엔드 실행

* **폴더명:** `capstone_final_front`
* **명령어:** `npx expo start`
* **웹 실행:** [http://localhost:8081](http://localhost:8081)
* **앱 실행:** `exp://192.168.35.45:8081`

---

## 🌐 웹/앱 서비스 제공

### 웹

* 별도 권한 설정 없이 사진 및 모션 인식 사용 가능
* 접속 주소: [http://localhost:8081](http://localhost:8081)

### 앱

* 사진 및 모션 인식 사용 시 권한 설정 필요
* 준비 사항:

  * Expo Go 앱 설치
  * QR 코드 연동 필수

---

## 🤸 모션 인식 서비스

* 접속 주소: [https://jisuuuuu.github.io/mediapipe_js/](https://jisuuuuu.github.io/mediapipe_js/)
* 로그인 후 **자세 측정** 버튼 클릭 시, 웹앱에서 모션 인식 서비스 사용 가능

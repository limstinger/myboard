# 📊 Flask 게시판 & FMS 통합 대시보드

Flask 기반 게시판 서비스에 **농장 물류(FMS) 데이터를 시각화한 관리자 대시보드**를 결합한 웹 애플리케이션
게시글 CRUD 기능과 함께, **PostgreSQL에 저장된 FMS 집계 데이터**를 KPI 카드와 차트 형태로 확인할 수 있음

---

## 🔍 주요 기능

### 1️⃣ 게시판 기능
- 게시글 목록 조회
- 게시글 작성 / 수정 / 삭제
- 조회수 증가
- 좋아요(Like) 기능
- Flask + Jinja2 템플릿 기반 UI

---

### 2️⃣ FMS 통합 대시보드
게시판과 별도로 **운영/관리자 관점의 데이터 시각화 페이지**를 제공합니다.

#### 📌 KPI 카드
- 전체 입고 건수
- 합격(P) 건수
- 불합격(F) 건수

#### 📈 시각화 차트
- **합격 / 불합격 비율** (도넛 차트)
- **고객사 TOP4 입고 건수** (바 차트)
- **도착일별 입고 건수 추이** (라인 차트)

> 최근 입고 물량 추이 및 주요 고객사 물량 분포를 한눈에 확인할 수 있음
<img width="1312" height="897" alt="image" src="https://github.com/user-attachments/assets/1e111a36-d5cb-4881-ba83-ed43acb39567" />

---

## 🛠 기술 스택

- **Backend**: Python, Flask
- **Database**: PostgreSQL (View 기반 집계)
- **Frontend**: HTML, CSS, Jinja2
- **Visualization**: Chart.js
- **Environment**: Git, GitHub, Azure PostgreSQL, dotenv

---

## 🌐 페이지 구성
- `/` : 게시판 메인 페이지
- `/fms_result` : FMS 통합 대시보드 페이지

> 아래에 FMS 대시보드 화면 캡처를 그대로 붙여넣어도 됩니다.

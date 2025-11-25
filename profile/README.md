# 🧪 FilterFacts
AI 기반 건강기능식품·화장품 광고 문구 사실 검증 서비스

FilterFacts는 SNS, 쇼핑몰, 커뮤니티에서 유통되는 광고 문구가  
**허위/과장인지 식약처(MFDS) 공공데이터 기반으로 AI가 자동 검증**해주는 모바일 서비스입니다.

---

## 📌 프로젝트 개요

### 📅 개발 기간
2025.06 ~ 2025.09

### 🎯 목표
- 건강기능식품/화장품 광고 문구의 진위 여부 자동 검증
- 식약처 공식 데이터 기반의 신뢰성 높은 결과 제공
- Hybrid Search + RAG 기반 Fact-check AI 구축

### 👥 타겟 사용자
- 건강정보 관련 광고·리뷰를 믿어도 되는지 확인하고 싶은 사용자  
- 정확한 식약처 근거 기반 정보를 얻고 싶은 사람들  

---

## 📌 프로젝트 소개

### 🔍 배경
- SNS·쇼핑몰을 중심으로 **허위 건강광고가 급증**
- 소비자는 의학/식품학 지식 없이 검증이 어려움
- 기존 앱은 **단순 정보 조회**, AI 기반 검증 기능 없음

### ❗ 문제점
- 광고 문구와 실제 기능성 비교 불가  
- 식약처 데이터 기반 Fact-check 서비스 부족  
- 단순 성분 조회 위주 서비스가 대부분  

### 🧠 FilterFacts 솔루션
- MFDS 오픈데이터 직접 수집·정제  
- pgvector + pg_trgm 기반 Hybrid Search  
- Ollama + Qwen2.5 기반 LLM Fact-check 모델  
- 모바일에서 문구만 입력하면 근거와 함께 결과 표시  

---

## 📁 기능 명세서
(링크 또는 문서 연결 예정)

주요 기능:
- 회원가입 / 로그인 / 로그아웃 / 이메일 인증
- 광고 문구 AI 검증 및 근거 제공
- 검증 기록 저장
- 대화 기반 검색 UI

---

## 📚 API 명세서
(추후 Swagger / Postman Collection 연동)

---

## 🗄 DB 구조 (ERD)
- 주요 테이블:
  - `users`
  - `refresh_token`
  - `conversation`
  - `chat_message`
  - `rag_documents_food`
  - `rag_documents_cosmetic`
  - MFDS 관련 데이터 테이블

*(ERD 이미지 추가 가능)*

---

## 🏛 서비스 아키텍처
Android App
↓
Spring Boot Backend ────── PostgreSQL / Redis
↓
AI Server (FastAPI + Ollama)
↓
MFDS Vector DB (pgvector + pg_trgm)


---

# 🛠 기술 스택

## 📱 **Android (Frontend)**
- Java
- Retrofit / OkHttp / Gson
- Hilt (DI)
- EncryptedSharedPreferences
- MVVM (ViewModel, LiveData)
- Material Design Components

---

## 🧩 **Backend (Spring Boot)**
- Java 21  
- Spring Boot 3.5.4  
- Spring Security + JWT  
- Spring Data JPA  
- Spring Web / WebFlux  
- Redis (Refresh Token)  
- PostgreSQL  
- Spring Mail (SMTP)

---

## 🤖 **AI Server (FastAPI + Hybrid Search)**
- FastAPI  
- PostgreSQL  
- Ollama  
- Embedding: `nomic-embed-text`  
- LLM: `qwen2.5-1.5b-instruct-q4_K_M`  
- Hybrid Search (pgvector + trigram)  
- Evidence Ranking System  
- Structured Logging + PII Redaction  

---

## 🏗 **Infrastructure / DevOps**
- Naver Cloud Platform (NCP)
- NKS (Kubernetes Service)
- NCR (Container Registry)
- GitHub Actions CI/CD  
- Docker / Docker Compose  
- Kubernetes Deployment YAML  

---

# ⚙ 설치 및 실행

## 🟦 Backend 실행
```bash
./gradlew clean build
java -jar build/libs/app.jar

🟩 Android

Android Studio에서 실행

baseUrl 을 Backend 주소로 설정

👥 팀원 소개

Android Developer

Backend Developer

AI Developer

DevOps / Infra Engineer

📄 문서 자료

발표자료 PDF

ERD

아키텍처 Diagram

MFDS 데이터 정리 문서

🎯 프로젝트 핵심 요약

FilterFacts는
“건강 광고 문구가 사실인지 AI가 과학적 근거로 검증해주는 서비스”
입니다.

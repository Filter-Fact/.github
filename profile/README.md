<div align="center">

# Filter&Facts  
### 과대광고 · 허위광고를 AI로 검증하는 소비자 보호 서비스

</div>

---


## 1. 프로젝트 개요

### 프로젝트명  
**Filter&Facts — AI 기반 과대·허위 광고 검증 서비스**

### 프로젝트 기간  
2025년 6월 ~ 2025년 9월

### 프로젝트 목표
- AI 기반으로 허위·과대 광고 여부 자동 판단  
- MFDS 기준 및 제품 성분 기반의 객관적 근거 제공  
- 소비자가 쉽게 활용할 수 있는 모바일 검증 도구 개발  
- 정보 비대칭 및 소비자 피해 예방  

### 주요 타겟 사용자
- 건강기능식품·화장품 성분을 구매 전 확인하고 싶은 사용자  
- 광고 문구의 사실 여부를 검증하고 싶은 일반 사용자  
- SNS/AI 생성 광고의 신뢰성을 의심하는 사용자  
- 전문 지식 부족 또는 고령층 등 정보 접근이 어려운 사용자  

---

## 2. 프로젝트 소개

### 프로젝트 배경

#### 문제 상황
- 허위·과대 건강 제품 광고 증가  
- SNS·인플루언서 중심의 검증되지 않은 광고 확산  
- AI 기반 가짜 의사 영상·조작된 인터뷰 등 신종 광고 기법 증가  
- 건강기능식품 관련 오해 및 소비자 금전적 피해 증가  

#### 기존 서비스의 한계
- 광고 문구에 대한 AI 검증 기능 부재  
- 성분/효능 정보를 연계해 해석해주는 서비스 부족  
- 과대광고 판단 기준을 사용자가 직접 찾아 비교해야 함  
- 단순 정보 제공 앱은 존재하지만 “판단 + 근거 제공” 기능은 부족  

### 목표 정리
Filter&Facts는 다음 방향으로 개발되었습니다.
- AI 기반 허위·과장 가능성 자동 판단  
- MFDS 고시·개별인정 원료 기반 근거 중심 분석  
- 제품 성분과 기능성 정보의 자동 매핑  
- 사용자에게 신뢰성 있는 결과와 해석 제공  
- 모바일에서도 간편하고 빠른 검증 흐름 제공  

---

## 3. 기능 명세서
문서 링크 추가 예정  
<img src="profile/assets/기능흐름도.png" width="600">

---

## 4. API 명세서
문서 링크 추가 예정  
(예: Notion 또는 Swagger UI)

---

## 5. DB 명세서
ERD 이미지 파일 추가 예정  
예: `docs/erd.png`

---

## 6. 서비스 아키텍처
아키텍처 다이어그램 추가 예정  
예: `docs/architecture.png`

---

## 7. 팀원 소개

| 이름 | 담당 |
|------|------|
| **이성원** | Android 앱 개발, UI/UX, Retrofit 통신 |
| **김현수** | Backend API(회원, 채팅), AI 서버, RAG 파이프라인, MFDS 데이터 처리 |
| **조현우** | Backend API(공공 데이터), Kubernetes(NKS), Docker, GitHub Actions |

---

## 8. 기술 스택

| 영역                       | 기술                                                                        |
| ------------------------ | ------------------------------------------------------------------------- |
| Frontend             | Java, Retrofit, OkHttp, Hilt, Security Crypto, MVVM(ViewModel & LiveData) |
| Backend              | Java 21, Spring Boot 3.5, JPA, Security, JWT, Redis, PostgreSQL           |
| AI Server            | FastAPI, Python, Ollama, qwen2.5 모델, Hybrid Search, PostgreSQL            |
| Database             | PostgreSQL, Redis                                                         |
| Infra / DevOps       | Docker, Kubernetes(NKS), NCR, GitHub Actions CI/CD                        |

---

## 9. 문서 자료
profile/assets/F_F 제품 소개서.pdf

---

<div align="center">

### ⭐ Filter&Facts는  
### “과대·허위 광고 없는 건강한 정보 환경”을 목표로 합니다.

</div>

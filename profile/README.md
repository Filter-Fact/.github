<div align="center">

# 🧪 Filter&Facts  
### 과대광고 · 허위광고를 AI로 검증하는 소비자 보호 서비스

</div>

---

# 1. 프로젝트 개요

Filter&Facts는 건강기능식품·화장품 광고 문구를 AI가 분석하여  
**과대·허위 광고 여부를 자동으로 검증하는 AI 기반 서비스**입니다.

광고 문구를 입력하면  
- 실제 식약처 MFDS 기능성 자료  
- 개별인정형 원료 정보  
- 제품 성분·효능 정보  
- RAG 기반 문헌 검색  

을 기반으로 **"판단 + 근거"를 제공하여 소비자가 올바른 판단을 할 수 있도록 돕습니다.**

---

# 2. 프로젝트 소개

광고 시장이 급속도로 성장함에 따라  
허위·과장 광고로 인한 소비자 피해도 증가하고 있습니다.  
Filter&Facts는 다음을 해결합니다:

- 객관적 정보 없이 주장만 가득한 광고  
- 소비자 스스로 검증하기 어려운 전문 용어  
- 제품 성분과 고시 기능의 연관성 확인의 어려움

AI 기반의 RAG(검색증강생성) 기술과  
정규화된 식약처 데이터베이스를 활용하여  
**신뢰 가능한 근거 기반 AI 판단 시스템**을 제공합니다.

---

# 3. 프로젝트 목표

- 🔍 **광고 문구의 과대·허위 가능성 자동 검출**
- 📚 **식약처 고시·제품 성분 기반의 근거 제공**
- 🤖 **LLM이 AI 전문가처럼 판단을 요약해주는 서비스**
- 📱 **누구나 쉽게 모바일 앱에서 검증할 수 있도록 구현**
- 🧩 **AI·백엔드·안드로이드·인프라 통합 서비스 구축**

---

# 4. 주요 기능

### ✔ AI 허위·과대광고 자동 검증
- LLM + RAG 기반 판단
- MFDS 기능성·제품 성분 매칭
- "요약·판단·근거" 출력 템플릿 제공

### ✔ 광고 문구 입력 / 결과 제공
- 광고 한 줄 입력하면 AI가 자동 분석
- 관련 원료-기능성 근거 및 제품 근거 반환

### ✔ 대화형 Q&A 챗봇
- 사용자의 대화를 저장하고 다시 불러오기 가능
- 질문별로 AI 분석 결과 제공

### ✔ 회원가입·로그인·토큰 인증
- JWT Access/Refresh Token 기반 인증

### ✔ 전체 서비스 자동 배포
- GitHub Actions → Naver Cloud NKS → Docker → K8s 자동 배포

---

# 5. 팀원 소개

| 이름 | 역할 | 담당 업무 |
|------|------|-----------|
| **이성원** | 👨‍💻 Android 개발자 | Android 앱 개발, UI/UX, Retrofit 통신 |
| **김현수** | 🧑‍💻 백엔드 & RAG 모델 개발 | Spring Boot API, RAG 모델, 데이터 파이프라인 |
| **조현우** | 👨‍💼 백엔드 & CI/CD·인프라 구축 | Backend, Kubernetes, Docker, GitHub Actions, NCP 인프라 |

---

# 6. 기술 스택

| 영역                       | 기술                                                                        |
| ------------------------ | ------------------------------------------------------------------------- |
| **Frontend(Android)**    | Java, Retrofit, OkHttp, Hilt, Security Crypto, MVVM(ViewModel & LiveData) |
| **Backend(Spring Boot)** | Java 21, Spring Boot 3.5, JPA, Security, JWT, Redis, PostgreSQL           |
| **AI Server**            | FastAPI, Python, Ollama, qwen2.5 모델, Hybrid Search, PostgreSQL            |
| **Database**             | PostgreSQL, Redis                                                         |
| **Infra / DevOps**       | Docker, Kubernetes(NKS), NCR, GitHub Actions CI/CD                        |
| **Logging/Monitoring**   | Structured Logging, Debug toggles, PII Redaction                          |


---

# 7. 문서 자료

### 📌 ERD 문서
- (이미지/링크 첨부)

### 📌 기능 명세서
- (Notion/Google Docs 링크)

### 📌 API 명세서
- (Notion/Swagger/Google Docs 링크)

### 📌 시스템 아키텍처
- (아키텍처 다이어그램 이미지/링크)

---

<div align="center">

### ⭐ Filter&Facts는  
### “과대·허위 광고 없는 건강한 정보 환경”을 목표로 합니다.

</div>

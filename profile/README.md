<div align="center">

# Filter&Facts  
### 과대광고 · 허위광고를 AI로 검증하는 소비자 보호 서비스

</div>

---

1. 프로젝트 개요
📌 프로젝트 명

Filter&Facts — AI 기반 과대·허위 광고 검증 서비스

📅 프로젝트 기간

2025년 6월 ~ 2025년 9월

🎯 프로젝트 목표

AI 기반으로 허위·과대 광고 여부를 자동 판단

식약처 기준 및 제품 성분 데이터 기반의 객관적 근거 제공

소비자가 쉽게 활용할 수 있는 모바일 검증 도구 제공

광고 시장의 정보 불균형 해소 및 소비자 피해 예방

🎯 주요 타겟 사용자

건강기능식품, 화장품 구매 전에 성분을 확인하고 싶은 소비자

광고 정보를 검증하고 싶은 일반 사용자

SNS 광고·AI 생성 광고에 회의감을 가진 사용자

고령층·전문 지식 부족으로 인해 피해를 보기 쉬운 사용자

2. 프로젝트 소개
🧩 프로젝트 배경
▸ 문제 상황
허위·과대 건강 제품 마케팅 증가

SNS·인플루언서 기반 검증되지 않은 광고 확산

AI 생성 가짜 의사 영상·가짜 전문가 인터뷰 등 조작된 광고 증가

건강기능식품 오해 야기 → 소비자 금전적 피해 지속 증가


▸ 기존 서비스의 문제점

광고 문구에 대한 AI 기반 검증 기능 부재

성분·효능 정보를 직접 연결해주는 서비스 부족

과대광고 판단 기준을 사용자가 직접 찾아서 비교해야 함

단순 정보 제공 앱은 많지만 정확한 “판단 + 근거”까지 제공하는 앱이 없음


🎯 프로젝트 목표

Filter&Facts는 아래 목표를 기반으로 제작됨:

AI 기반 허위·과장 가능성 판단 자동화

MFDS 고시·개별인정 원료 기반 근거 중심 분석

제품 성분과 기능성 정보를 자동 매핑

신뢰성 있는 결과 제공으로 소비자 피해 예방

모바일 환경에서도 간편한 검증 흐름 제공

3. 기능 명세서

📄 기능 명세서 링크:
(노션 / 구글 문서 링크 첨부 예정)

4. API 명세서

📄 API 명세서 링크:
(Notion / Swagger 링크 첨부 예정)

5. DB 명세서

📸 ERD 이미지 첨부:
(GitHub 업로드 후 경로 연결 예정)
예:
docs/erd.png

6. 서비스 아키텍처

📸 아키텍처 다이어그램 첨부:
(GitHub 업로드 후 경로 연결 예정)
예:
docs/architecture.png

7. 팀원 소개
이름    역할    담당
이성원    Android 개발자    Android 앱 개발, UI/UX, Retrofit 통신
김현수    백엔드 & RAG 모델 개발자    Spring Boot 서버, AI 서버, RAG pipeline, MFDS 데이터 처리
조현우    백엔드 & 인프라/CI/CD 구축    Backend API, Kubernetes(NKS), Docker, GitHub Actions

8. 기술 스택
🟦 프론트엔드(Android)

Kotlin

MVVM Architecture

Retrofit / OkHttp

Coroutine / Flow

Android Jetpack

🟩 백엔드

Java 21

Spring Boot 3

Spring Security / JWT

JPA / Hibernate

🟨 데이터베이스

PostgreSQL

Redis

pgvector

MFDS 데이터 정규화 파이프라인

🟥 인프라 / DevOps

Naver Cloud Platform (VPC, NKS, NCR)

Kubernetes

Docker

GitHub Actions CI/CD

Prometheus / Grafana(Optional)

9. 문서 자료

발표자료 첨부:
(업로드 후 링크 추가 예정)

---

<div align="center">

### ⭐ Filter&Facts는  
### “과대·허위 광고 없는 건강한 정보 환경”을 목표로 합니다.

</div>

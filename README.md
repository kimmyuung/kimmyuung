<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,100:7928ca&height=300&section=header&text=Kim-Myung-Ho&fontSize=80&fontAlignY=35&animation=fadeIn" alt="header" />
</p>

<p align="center">
  <b>Kim Myung Ho</b><br>
  <br>
  <b>Full Stack Engineer interested in MSA & AI</b><br>
  웹과 모바일, AI를 아우르는 융합형 서비스를 만드는 데 관심이 있습니다.
</p>

<br>

### 🛠 Tech Stack

**Backend & Infrastructure**
<p align="left">
  <img src="https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Boot_3.5-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Cloud-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white">
  <img src="https://img.shields.io/badge/Github_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
</p>

**Frontend & Mobile**
<p align="left">
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
</p>

**Database**
<p align="left">
  <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white">
  <img src="https://img.shields.io/badge/Redis_7-DC382D?style=for-the-badge&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
</p>


<br>

### 🚀 Featured Projects

#### 🧩 1. Aenigma (Project Aenigma)
> **MSA 구조 기반의 실시간 멀티플랫폼(Web/App) 게임/채팅 서비스**
> *최신 기술 스택(Java 21, React 19)을 적용하고, 도메인 주도 설계(DDD)와 멀티 모듈 아키텍처를 통해 확장성을 극대화한 프로젝트입니다.*

- **Tech Stack:**
  - **Backend:** Java 21, Spring Boot 3.5, Spring Cloud, WebSocket, JPA, Redis, MariaDB
  - **Frontend:** React 19, TypeScript, Vite 7, Zustand
  - **Mobile:** React Native, Expo 54
  - **Infra:** Docker, Nginx
- **Key Features:**
  - **Multi-Module Architecture:** API, Socket, AI, Domain, Common 등으로 모듈을 분리하여 MSA 전환 용이성 확보
  - **Real-time Interaction:** WebSocket을 활용한 실시간 게임 로직 및 채팅 구현
  - **Cross-Platform:** React(Web)와 React Native(App) 클라이언트를 동시에 구축하여 유연한 서비스 제공
  - **Performance:** Java 21 Virtual Threads 및 Redis 캐싱을 통한 성능 최적화

#### 🤖 2. ITDG (Intelligent Test Data Generator)
> **AI/ML 기반 지능형 테스트 데이터 생성 서비스**
> *개발 환경에서 부족한 테스트 데이터를 AI 모델(CTGAN)을 활용해 생성하고 관리하는 플랫폼입니다.*

- **Tech Stack:** Java 21, Spring Boot 4.0, Python (CTGAN), Spring Cloud
- **Key Features:**
  - **AI Integration:** SDV/CTGAN 알고리즘을 활용해 원본 데이터의 통계적 특성을 유지한 가상 데이터 생성 gpt-4-0-mini 모델 사용
  - **Microservices:** 대용량 데이터 처리의 유연한 확장을 위한 MSA 아키텍처 적용

### 3. 🔐 DayLog (AI & 보안 특화 오프라인-First 일기장)
> **"네트워크가 끊겨도, DB가 유출되어도 안전한 일기장"**
> React Native와 Django로 구축한 엔터프라이즈급 아키텍처의 스마트 일기장 플랫폼입니다. 단순 CRUD를 넘어 **오프라인 동기화**, **데이터 암호화**, **자체 모니터링 인프라**까지 직접 설계하고 구현했습니다.

| 항목 | 상세 내용 |
| --- | --- |
| **핵심 기술** | **Offline-first Sync**, **AES-256 DB Encryption**, **AI Analysis (Gemini)**, **Biometric Auth** |
| **Frontend** | React Native (Expo), TypeScript, React Query, Zustand |
| **Backend** | Django REST Framework, Celery, Redis, PostgreSQL |
| **Infra & DevOps** | Docker Compose, GitHub Actions (CI/CD), Nginx, EC2 |
| **Monitoring** | **Prometheus + Grafana** (서버 리소스 및 API 성능 시각화), Sentry |

#### 🚀 Technical Highlights (기술적 도전 및 해결)
- **📡 완벽한 오프라인 지원 (Offline-First):** 네트워크가 불안정한 환경에서도 끊김 없는 사용자 경험을 위해 `OfflineQueue` 시스템을 직접 구현하여, 연결 복구 시 자동으로 서버와 데이터를 동기화합니다.
- **🛡️ 강력한 데이터 보안:** 민감한 일기 데이터 보호를 위해 애플리케이션 레벨에서 **AES-256 암호화**를 적용하고, 모바일 생체 인증(지문/FaceID)을 통합했습니다.
- **🤖 비동기 AI 파이프라인:** Celery와 Redis 메시지 큐를 도입하여 AI 감정 분석 및 이미지 생성 작업을 비동기로 처리, 사용자 응답 지연(Latency)을 최소화했습니다.
- **📊 자체 모니터링 구축:** SaaS에 의존하지 않고 Prometheus와 Grafana를 Docker로 직접 구성하여 서버 상태와 비즈니스 지표를 실시간으로 대시보드에서 관제합니다.
- **🖥️ 관리자 대시보드:** Vite + React 기반의 별도 어드민 웹을 구축하여 사용자 관리 및 콘텐츠 모니터링 시스템을 갖췄습니다.

📂 **Repository:** [capstone-diary](https://github.com/kimmyuung/capstone-diary)

<br>

### 📈 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats-sigma-five.vercel.app/api?username=kimmyuung&show_icons=true&theme=tokyonight&hide_border=true&title_color=7928ca&icon_color=7928ca&text_color=9effff&bg_color=1a1b27" alt="stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kimmyuung&layout=compact&theme=tokyonight&hide_border=true&title_color=7928ca&text_color=9effff&bg_color=1a1b27" alt="languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kimmyuung&theme=tokyonight&area=true&hide_border=true&color=7928ca" width="100%" alt="activity-graph" />
</p>

<br>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=kimmyuung&color=7928ca&style=flat-square&label=VISITORS" alt="visitors" />
</p>

<img width="512" height="512" alt="Image" src="https://github.com/user-attachments/assets/35654db2-4439-44ce-be0f-9a0d74c024d5" />

<img width="1510" height="1080" alt="Image" src="https://github.com/user-attachments/assets/9b476d68-4f3f-4ce4-8fd3-1426290aed7c" />

# PaperC0re

**PaperC0re**는 arXiv의 최신 논문을 자동으로 수집, 분석하여 사용자에게 인사이트를 제공하는 **자동화된 논문 분석 및 뉴스레터 서비스**입니다.

최신 기술 트렌드를 파악하고 싶은 개발자와 연구자를 위해, AI 에이전트가 매일 쏟아지는 논문들을 분석하여 핵심 내용만 간추려 전달합니다.

---

## 📂 Project Structure

<img width="2784" height="1536" alt="Image" src="https://github.com/user-attachments/assets/b0f5ea3d-d69e-4f9b-9993-83c5b1aa544e" />

PaperC0re 조직은 크게 3가지의 핵심 저장소로 구성되어 있습니다.

### 1. [Frontend](https://github.com/PaperC0re/Frontend)
<p align="left">
  <img src="https://img.shields.io/badge/Next.js%2016-000000?style=flat-square&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS%204-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Radix%20UI-161618?style=flat-square&logo=radix-ui&logoColor=white" />
</p>

사용자에게 논문 추천 및 구독 관리 기능을 제공하는 웹 애플리케이션입니다.
- **주요 기능**: 논문 피드 탐색, 카테고리별 필터링, 뉴스레터 구독 설정
- **Tech Stack**: Next.js 16 (App Router), Framer Motion, Lucide React

### 2. [Backend](https://github.com/PaperC0re/Backend)
<p align="left">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot%204.0-6DB33F?style=flat-square&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
</p>

구독자 데이터 관리 및 논문 메타데이터를 저장하고 서빙하는 API 서버입니다.
- **주요 기능**: 구독 및 사용자 관리 API, 논문 데이터 조회 및 저장, 이메일 발송 로그 관리
- **Tech Stack**: Kotlin 2.2.21, Spring Data MongoDB, Gradle

### 3. [AgentWorkflows](https://github.com/PaperC0re/AgentWorkflows)
<p align="left">
  <img src="https://img.shields.io/badge/n8n-FF6584?style=flat-square&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini%20Pro-8E75B2?style=flat-square&logo=google-gemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" />
</p>

논문 수집부터 분석, 뉴스레터 발송까지의 전 과정을 자동화하는 에이전트 워크플로우 저장소입니다.
- **주요 기능**:
  - **Collector**: arXiv API 연동 및 논문 수집, Gemini/Ollama를 활용한 요약 및 심층 분석
  - **Distributor**: 구독자 맞춤형 뉴스레터 생성 및 Gmail SMTP 발송
- **Tech Stack**: n8n (Self-hosted), Google Gemini 3 Pro, arXiv API

---

## 🚀 Tech Stack Overview

| Category | Technologies |
|----------|--------------|
| **Frontend** | Next.js 16, React 19, Tailwind CSS 4, Radix UI |
| **Backend** | Kotlin, Spring Boot 4.0.0, Spring Data MongoDB |
| **Search & AI** | Google Gemini 3 Pro, Gemini 2.5 Flash Lite, Ollama (GPT-OSS) |
| **Automation** | n8n, Docker |
| **AI Dev Tools** | Antigravity, Gemini CLI, V0 |
| **Infrastructure** | Vercel (Frontend), Docker Containers (Backend/Agents) |

---

## 📝 AI Prompts

이 프로젝트를 진행하면서 사용된 AI 프롬프트들은 아래 링크에서 확인할 수 있습니다.

- [프롬프트 설계](https://github.com/PaperC0re/.github/tree/main/profile/assets/%ED%94%84%EB%A1%AC%ED%94%84%ED%8A%B8%20%EC%84%A4%EA%B3%84)

---
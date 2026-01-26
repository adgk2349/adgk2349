# 이 승 민 (Seung Min Lee)

**iOS & Full-Cycle Developer** *"남들이 10시간 걸릴 일을 기술과 전략으로 1시간에 끝내는 고효율 엔지니어"*

[📧 Email](mailto:adgk2349b@gmail.com) | [🔗 Github](https://github.com/adgk2349) | [🔗 Blog/Portfolio](https://leesfolio.duckdns.org)

---

## 📌 Professional Summary

* **Product Maker:** 기획부터 디자인, 개발, 배포까지 1인 전 과정을 수행하여 **App Store에 2개의 앱(Lazy Planner, Biblity)을 런칭**하고 운영 중.
* **Problem Solver:** 기존 솔루션의 한계(비용, 호환성)를 극복하기 위해 **On-Device AI 파이프라인**을 구축하고, **OS 레벨의 인코딩 문제**를 해결하는 등 깊이 있는 기술적 탐구 수행.
* **System Engineer:** AWS 비용 절감을 위해 **Linux 기반 온프레미스 서버(NAS 겸용)**를 직접 구축하고, Docker/Nginx를 활용해 포트폴리오 웹사이트를 배포/운영.
* **Global Communication:** **JLPT N1** 수준의 일본어 구사 능력과 영문 기술 문서(Official Docs) 독해 능력을 바탕으로 한 글로벌 협업 가능.

---

## 🛠 Tech Stack

| Category | Skills |
| --- | --- |
| **Mobile** | Swift, SwiftUI, UIKit, Combine |
| **AI & Data** | Python, PyTorch, OpenAI Whisper (Local/API), LLM Prompt Engineering |
| **Backend & Infra** | Django, Nginx, Docker, Linux (Ubuntu), On-premise Server Management |
| **Collaboration** | Git, Github Actions, Figma, Slack |
| **Efficiency** | Cursor/Copilot (AI-Assisted Development & Optimization) |

---

## 🚀 Key Projects & Products

### 1. On-Device AI 음성 인식 자동화 툴 (Whisper Local)
*2025 (Personal Project)*
> **기존 STT 서비스의 용량 제한 및 비용 문제를 해결하기 위한 로컬 기반 음성 변환 프로그램**
* **Role:** 1인 개발 (Python)
* **Key Achievements:**
    * **하이브리드 추론 엔진(Hybrid Inference Engine):** 사용자의 하드웨어(GPU/CPU) 환경을 자동 감지하여 리소스 할당 최적화 (CUDA 가속 등).
    * **Zero Cost & Privacy:** API 호출 없이 로컬 모델을 구동하여 **운영 비용 100% 절감** 및 데이터 프라이버시 보호.

### 2. Lazy Planner (AI 일정 관리 비서)
*2024 (iOS App - **App Store 출시**)*
> **"게으른 완벽주의자"를 위해 음성과 텍스트를 AI로 분석하여 캘린더에 자동 등록하는 앱**
* **Role:** 1인 기획 및 iOS 개발
* **Key Achievements:**
    * **Passive UX 설계:** GPT API와 Whisper를 활용해 사용자의 개입을 최소화한 '말하면 등록되는' 인터페이스 구현.
    * **Prompt Engineering:** 일정 데이터의 구조화(JSON)를 위해 프롬프트를 최적화하여 환각(Hallucination) 최소화.
    * **App Store 런칭:** Apple HIG(Human Interface Guidelines)를 준수하고 심사를 통과하여 실제 마켓 배포.

### 3. Personal Linux Home Server & NAS
*2024 ~ Present (Infrastructure)*
> **포트폴리오 웹사이트 호스팅 및 개인 클라우드(NAS) 구축을 위한 온프레미스 서버 운용**
* **Role:** System Administrator (1인 구축)
* **Key Achievements:**
    * **On-Premise Infra:** AWS/Cloud 의존도를 낮추기 위해 **Ubuntu Linux 기반의 홈 서버**를 직접 구축하여 고정비 0원 달성.
    * **Multi-Service Orchestration:** **Docker**와 **Nginx Reverse Proxy**를 활용해 단일 서버에서 '포트폴리오 웹사이트'와 '개인 NAS' 서비스를 동시에 안정적으로 구동.
    * **Network Management:** DDNS 및 Port Forwarding 설정을 통해 외부 접속 환경을 구성하고 SSL 인증서(Let's Encrypt) 적용.

### 4. Travel Guide (여행 정보 플랫폼)
*2024 (Capstone Design)*
> **사용자 맞춤형 여행지 추천 및 정보 제공 웹 서비스**
* **Role:** Lead Developer (Full-Stack: Frontend & Backend)
* **Key Achievements:**
    * **Crisis Management :** 백엔드 담당 팀원의 갑작스러운 이탈로 프로젝트 중단 위기가 발생했으나, **R&R을 백엔드(Django)까지 확장**하여 API 개발 및 프론트엔드 연동을 주도적으로 완수.
    * **Problem Solving & Polish:** 기존의 불안정한 연동 문제를 해결하기 위해 백엔드 로직을 재설계하고, 사용자 경험(UX)을 고려하여 **UI 디자인 리뉴얼**까지 직접 수행.
    * **Full-Cycle 구축:** AWS 대신 On-premise 리눅스 서버에 Docker와 Nginx를 활용한 배포 환경 직접 구축.

### 5. macOS Safari 한글 깨짐 해결 유틸리티
*2025 (Desktop Utility)*
> **macOS Safari 다운로드 시 발생하는 한글 자소 분리(NFD) 현상 해결 툴**
* **Role:** 1인 개발 (Python)
* **Key Achievements:**
    * **CS Deep Dive:** OS 간 인코딩 방식 차이(Windows NFC vs macOS NFD)를 분석하고 정규화 로직 구현.
    * **Usability:** CLI에 익숙하지 않은 사용자를 위해 GUI 앱으로 패키징하여 배포.

### 6. Biblity (목표/루틴 관리 앱)
*2025 (iOS App - **App Store 출시**)*
* **Role:** 1인 개발
* **Key Achievements:** Custom UI 컴포넌트 개발을 통한 심미적 UX 구현 및 외부 API 연동 안정성 확보.

---

## 🎓 Education

**한신대학교 컴퓨터공학부 (편입)** | *2023.03 ~ 2026.02 (졸업예정)*
* **Academic Leadership:** 전공 심화 스터디 및 독서 토론 등 **다수의 학술 커뮤니티 리더(Leader)** 로서 모임을 조직하고 운영하며 자기주도적 학습 문화를 조성.
* **Self-Funded Growth:** 이러한 활동의 우수 성과를 학교로부터 인정받아, 교내 비교과 우수 장학생 선정 등 **누적 약 400만 원 규모의 연구/활동 지원금(Grant) 수주**.
* **Global Activity:** 교내 국제교류원 근무를 통해 다양한 문화권 학생들과 소통하며 글로벌 커뮤니케이션 역량 배양.

**순천대학교 멀티미디어공학부** | *2021.03 ~ 2022.12*
* **Award:** 학업 성적 우수자로서 1~2학년 전액 성적 장학금 수령.

---

## 🌐 Languages

* **Korean:** Native
* **Japanese:** **Advanced** (JLPT N1 수준, 비즈니스 회화 및 프리토킹 가능)
* **English:** **Intermediate** (기술 문서/원서 독해 및 기본적인 의사소통 가능)

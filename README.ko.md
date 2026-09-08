# 이승민 (Seung Min Lee)

[English](README.md) · [한국어](README.ko.md) · [日本語](README.ja.md)

**iOS & Full-Cycle Developer**  
문제를 빠르게 구조화하고, 제품화까지 연결하는 개발자입니다.

[Email](mailto:adgk2349b@gmail.com) | [GitHub](https://github.com/adgk2349) | [Portfolio](https://adgk2349.github.io)

---

## Professional Summary

- 기획, 개발, 배포까지 1인 사이클로 진행하며 실제 사용 가능한 도구를 지속적으로 만들고 있습니다.
- Swift/SwiftUI 중심의 앱 개발과 Python 기반 자동화 도구 개발을 병행합니다.
- On-device AI, 로컬 실행 환경, 인코딩/호환성 문제 같은 실무형 이슈 해결에 강점이 있습니다.
- Linux + Docker + Nginx 기반으로 개인 서비스 운영 환경을 직접 구성하고 관리했습니다.

---

## Tech Stack

| Category | Skills |
| --- | --- |
| Mobile | Swift, SwiftUI, UIKit, Combine |
| AI & Data | Python, PyTorch, Whisper (Local/API), Prompt Engineering |
| Backend & Infra | Django, Docker, Nginx, Linux (Ubuntu) |
| Collaboration | Git, GitHub Actions, Figma, Slack |

---

## Featured Public Repositories

### 1) PLOS: 데이터와 실행 환경을 직접 통제하는 개인 AI 워크스페이스
- Repo: [PLOS-for-Mac](https://github.com/adgk2349/PLOS-for-Mac)
- 외부 AI 서비스의 데이터 처리 방식에 대한 불확실성을 계기로, GPT·Claude 사용 중 관찰한 동작을 바탕으로 로컬 추론, 출력 처리, 대화 메모리 구조를 직접 설계했습니다.
- 모델 성능이 발전할 때마다 가드레일(sanitizer) 개입 수준을 다시 판단하며, 사용자 정보를 개별 사실 단위로 저장할지 맥락째 보존할지 고민해 메모리 구조를 설계했습니다.

### 2) FlowMap: AI 코딩 중 코드 구조와 변경 영향을 확인하는 도구
- Repo: [FlowMap-AI_Code_Hallucination_Guard_for_Swift](https://github.com/adgk2349/FlowMap-AI_Code_Hallucination_Guard_for_Swift)
- AI 코딩 중 대화가 길어지면 모델이 변수명을 혼동하거나 이전에 구현한 기능을 빠뜨리는 문제를 겪어, 코드 구조와 관계를 그래프로 직접 확인할 수 있도록 개발했습니다.
- 빠른 분석을 위해 핵심 엔진을 Rust로 구현했고, VS Code 확장 배포본에서만 발생한 우클릭 미동작 문제와 노드 겹침으로 인한 가독성 문제를 이후 업데이트에서 개선했습니다.

### 3) Biblity: 매일 가볍게 만나는 성경 구절
- 기존 성경 앱들이 정보량이 많고 화면이 복잡하다고 느껴, 무작위 구절과 알림으로 하나의 구절에 집중할 수 있는 iOS 앱을 만들었습니다.
- 초기 웹 기반 구절 요청 방식에서 데이터 정제 부담, 연속 요청 시 누락, 인터넷 필수라는 제약을 겪어 앱 내부 로컬 DB로 전환했습니다.

### 4) KDecoder for Mac
- Repo: [KDecoder_for_Mac](https://github.com/adgk2349/KDecoder_for_Mac)
- macOS에서 발생하는 한글 파일명 깨짐(NFD/NFC) 문제를 드래그 앤 드롭 방식으로 해결하는 유틸리티입니다.
- 인코딩 정규화 로직을 구현해 실사용 관점의 파일 호환성을 개선했습니다.

### 5) SPSS Converter
- Repo: [SPSS_Converter](https://github.com/adgk2349/SPSS_Converter)
- macOS용 드래그 앤 드롭 기반 SPSS(.sav) → CSV 변환 도구입니다.
- 다중 파일 처리 시나리오를 고려해 반복 작업 시간을 줄이는 데 집중했습니다.

### 6) ArDrone Controller for iPad
- Repo: [ArDrone_Controller_for_iPad](https://github.com/adgk2349/ArDrone_Controller_for_iPad)
- SwiftUI + BLE 기반의 iPad 드론 컨트롤러 프로젝트입니다.
- UI/상태 제어 흐름과 하드웨어 연동을 함께 다룬 iOS 프로젝트입니다.

### 7) YouTube Looper (Safari Extension)
- Repo: [Youtube_Looper](https://github.com/adgk2349/Youtube_Looper)
- macOS Safari에서 YouTube 반복 재생을 지원하는 경량 익스텐션입니다.

---

## Education

- 한신대학교 컴퓨터공학부 (편입) | 2023.03 ~ 2027.02 (졸업예정)
- 순천대학교 멀티미디어공학부 | 2021.03 ~ 2022.12

---

## Languages

- Korean: Native
- Japanese: Advanced (JLPT N1)
- English: Intermediate (기술 문서 독해 및 실무 커뮤니케이션)

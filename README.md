<div align="center">
  <img src="./gemini-svg (1).svg" width="100%" alt="Yani-Studio Lab Banner" />
  
  <p align="center">
    <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+KR&fontSize=22&duration=3000&pause=1000&color=C084FC&center=true&vCenter=true&width=650&height=50&lines=%EB%A8%B8%EC%8B%A0%EB%B9%84%EC%A0%84%20%26%20Edge%20AI;%EC%97%94%ED%84%B0%ED%94%84%EB%9D%BC%EC%9D%B4%EC%A6%88%20AI%20%26%20RAG%20(NL2SQL);%EC%8B%9C%EA%B3%84%EC%97%B4%20%EC%98%88%EC%B8%A1%20%26%20PHM%20(%EC%98%88%EC%A7%80%EB%B3%B4%EC%A0%84);%EC%82%B0%EC%97%85%20%EC%B5%9C%EC%A0%81%ED%99%94%20%26%20Operations%20Research" alt="Typing SVG" />
  </p>
  
  <p>생산 현장의 제한된 하드웨어 리소스를 극복하고, 모델 경량화 및 실시간 데이터 파이프라인을 통해 산업 도메인의 병목을 해결합니다.</p>
</div>

---

## 👨‍💻 Core Competencies

* 🎓 **Education:** 경희대학교 인공지능학과 석사 졸업 (AI 전공) | 경기권 4년제 대학 산업경영공학과·데이터사이언스학과 학사 졸업
* 🎯 **Research Focus:** Machine Vision & Edge AI | Enterprise AI & RAG (NL2SQL) | Time-Series Forecasting & PHM | Operations Research
* ✉️ **Contact:** rbals985865@naver.com | rbals985865@khu.ac.kr

---

## 📊 Project & Research Overview

> 💡 **주요 연구 및 프로젝트 요약 장표** (기술 스택 및 핵심 성과 기반)

| Category | Research & Project | Key Stack | Metric / Impact |
| :--- | :--- | :--- | :--- |
| **Vision & Edge** | 반도체 웨이퍼 결함 분류 초경량화 (SCRBLAA-Net) | PyTorch, t-SNE | **VRAM 3.2GB 절감** / Accuracy **94.98%** (SCIE 1저자) |
| **Vision & Edge** | PCB 결함 분류 엔트로피 앙상블 아키텍처 | PyTorch, OpenCV | Accuracy **99.80% (SOTA)** |
| **Vision & Edge** | SECS/GEM 반도체 장비 결함 탐지 엣지 추론 | C++, ONNX, Threading | **초저지연 엣지 파이프라인** / F1 0.5294 (SOTA) |
| **Enterprise AI** | 로컬 구동형 RAG-NL2SQL 보안 ERP 엔진 | Ollama, Local LLM | **Edge-case 방어율 100%** / 지연시간 1.65ms |
| **Time-Series** | Walmart 공급망 데이터 수요 예측 메타 앙상블 | Python, Pandas | Two-Stage Hurdle 아키텍처 / **F1 0.67** |
| **Optimization** | 대규모 AGV 물류 라우팅 병목 최적화 | Google OR-Tools | **비용 지수 -324** / 이동 거리 **35% 단축** |

---

## 🚀 Core Research & Projects

### 🛠️ 1. Vision AI & Edge Deployment

* **[SCIE 1저자] 반도체 웨이퍼 결함 분류 초경량화 AI (SCRBLAA-Net)**
  * 고차원 특징 분할 및 토큰화 메커니즘을 통해 대규모 비전 모델의 과적합 및 데이터 유실 원천 차단.
  * **VRAM 3.2GB 다이어트**를 달성하여 저사양 현장 장비 이식성 확보, 분류 **정확도 94.98%(+1.67%p)** 기록.
  * 3D t-SNE 구조적 시각화 및 HTML 기반 인터랙티브 웹 시뮬레이터 오픈소스 배포.

* **[전세계 1등 성능] 엔트로피 기반 앙상블 AI 활용 PCB 결함 분류**
  * 50개 이상의 CNN 아키텍처 Ablation Study를 기반으로 ResNet50·MobileNet 구조를 결합한 엔트로피 앙상블 파이프라인 독자 개발.
  * 3단계 전이 학습 및 Explicit Memory 최적화를 통해 글로벌 벤치마크 **결함 분류 정확도 99.80% (SOTA)** 달성.

* **[SECS/GEM] 반도체 장비 결함 탐지 엣지 AI 아키텍처 구축**
  * 225만 개 하이퍼파라미터 조합 탐색 기반의 22개 이기종 모델 스태킹 앙상블로 **미탐률 최소화 및 F1-Score 0.5294 (SOTA)** 확보.
  * ONNX 표준 포맷 최적화 및 Multi-threading 아키텍처 설계로 현장 제어기 수준의 **초저지연 C++ 엣지 추론 엔진** 구현.

* **[캐글 1위] XAI 기반 적외선(IR) 태양광 모듈 초정밀 결함 탐지**
  * 극심한 클래스 불균형 해결을 위한 23개 비전 모델 및 30개 앙상블 조합의 완전 탐색 파이프라인 구축.
  * Grad-CAM 기반의 정밀 국소화(Localization)를 적용하여 **양품 오분류 원천 차단 및 정확도 96.2%(+4.15%p)** 확보.

* **[MVTec AD] 비지도 학습 기반 산업용 고정밀 이상 탐지**
  * 정상 데이터셋만으로 미세 결함을 잡아내는 EfficientAd & Patchcore 병렬 파이프라인 구축.
  * 임계값(Threshold) 정밀 튜닝 기법을 통해 현업의 고질적 문제인 **과검(False Alarm) 0건 달성 및 실질 정확도 2.56%p 향상**.

* **[CoreML] 실시간 다중 차량 인식 경량화 AI 모델**
  * 객체 라벨링 파이프라인 재정비 및 Apple CoreML 가속 하드웨어 연산 최적화.
  * 정밀도 저하 없이 **추론 지연시간 31% 단축 (9.05ms) 및 mAP 32.64%p 향상**.

---

### 🧠 2. Enterprise AI & Large Language Models

* **[100% 온프레미스] 차세대 RAG-NL2SQL 보안형 ERP 엔진**
  * 기업 내부 핵심 자산 유출 방지를 위해 Ollama 기반 100% 로컬 네트워크 구동 RAG 아키텍처 설계.
  * 자가 수정(Reflexion) 피드백 루프 및 자율 튜닝 프로세스를 도입하여 **엣지 케이스 방어율 100%, 1.65ms 내 데이터 일치율 100%** 달성.

* **[전국 공모전 2등] 환각 제어(Hallucination-Free) 식품 과학 RAG 챗봇**
  * LLM 고질병인 환각 현상을 원천 제어하기 위한 검색 증강(RAG) 기반 하이브리드 교차 검증 파이프라인 구축.
  * 도메인 특화 규칙 엔진 결합으로 데이터 탐색 효율 80% 및 **초록 생성 일치율 9배 향상**.

---

### 📈 3. Time Series & Predictive Maintenance (PHM)

* **[Walmart ERP] 4,700만 건 대규모 공급망 수요 예측 메타 앙상블**
  * 데이터 내 80% 이상 존재하는 영과잉(Zero-inflated) 불연속 특성을 극복하기 위해 Two-Stage Hurdle 아키텍처 고안.
  * Zero-copy 메모리 최적화로 대용량 데이터 학습 시간을 15분 이상 단축하고 **최종 예측 F1-Score 0.67** 확보.

* **[NASA C-MAPSS] 항공 엔진 다중 운전 조건 하이브리드 예후진단**
  * CNN-BiLSTM-Attention 복합 아키텍처 기반의 예지보전 모델을 적용하여 고장 시점 사전 예측.
  * 정비 마진 최적화 튜닝을 통해 기존 베이스라인 모델 대비 **FD004 패널티 점수 90.4% 감축**.

* **[BPIC 2012] 금융 워크플로우 사전 병목 예측 스태킹 앙상블**
  * LSTM 임베딩 벡터와 통계적 피처를 결합하여 프로세스 중간 단계에서 병목을 조기 경보하는 아키텍처 설계.
  * 미탐지(False Negative) 리스크를 최소화하여 **정확도 93.39%, F1-Score 86.62%** 확보.

* **[NREL] 풍력 터빈 시계열 데이터 증강 및 데이터 부패 규명**
  * GAN 기반 데이터 증강 기법을 통해 **예측 오차(MSE) 59.2% 절감** (설계 경진대회 1위).
  * 증강 데이터가 원본의 고유 상관구조를 왜곡하는 현상('숨겨진 부패')을 정량 분석 기법으로 역추적 및 규명.

---

### 🎯 4. Operations Research & Industrial Optimization

* **[Google OR-Tools] 대규모 AGV 물류 라우팅 병목 최적화**
  * 차량 경로 최적화(VRP) 프레임워크와 메타휴리스틱(GLS) 알고리즘을 융합하여 물류 이동 중 데드락(교착 상태) 완전 해소.
  * **최적화 비용 지수 -324 감소, 작업 불균형 19% 개선, 총 이동 거리 35% 단축** 달성.

* **[Amazon Scheduler] 메타휴리스틱 기반 교대 근무 로드 밸런싱**
  * OptaPlanner 엔진과 모의 담금질(Simulated Annealing) 알고리즘을 통한 제약 조건 최적화 스케줄러 구현.
  * **작업자 간 배정 격차 85% 해소 및 연속 근무 제약 통제로 업무 피로도 위험성 50% 감소** 검증.

* **[Seoul Healthcare] 공공 헬스케어 선제적 모니터링 아키텍처**
  * Random Forest 모델 기반 12개 비만 그룹별 심박수 관리 상·하한선(Xbar 통제선) 설정 및 이상 징후 알림 체계 구축.
  * 최적화 시뮬레이션을 통해 **연간 약 1,134억 원 규모의 잠재적 의료 비용 절감 모델링** 입증.

* **[Arena] 코엑스 대형 주차장 동선 시뮬레이션 최적화**
  * 비전 기반의 트래픽 흐름 데이터를 추출하고 Arena 시뮬레이션 엔진 프레임워크와 연동 검증.
  * 레이아웃 변경 안을 제시하여 **평균 대기시간 4.9% 단축 및 차량 배회 횟수 30.5% 감소** 유도.

---

## 🛠️ Tech Stack & Arsenal

### Hardware & Compute Infrastructure
| Asset Type | Target System / Environment | Key Specification | Operational Role |
| :--- | :--- | :--- | :--- |
| **Deep Learning Rig** | NVIDIA DGX Spark Server | 128GB System RAM / High-Performance Node | 대규모 비전 모델 학습 및 가상 시뮬레이션 인프라 |
| **Local Workstation** | Apple MacBook Pro M5 | 24GB Unified Memory / Apple Silicon Architecture | 경량화 모델 프로토타이핑, 온프레미스 RAG 인프라 개발 |

<p>
  <img src="https://img.shields.io/badge/NVIDIA_DGX_Spark-76B900?style=for-the-badge&logo=nvidia&logoColor=white"/>
  <img src="https://img.shields.io/badge/128GB_System_RAM-515151?style=for-the-badge&logo=databricks&logoColor=white"/>
  <img src="https://img.shields.io/badge/MacBook_Pro_M5-000000?style=for-the-badge&logo=apple&logoColor=white"/>
</p>

### AI & Data Science Pipeline
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=rstudio&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
</p>

### DevOps, Edge & Enterprise Systems
<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_OR--Tools-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>



<div align="center">
  <h2> 🐾 Welcome to the Yani-Studio Lab! </h2>
  <p><i>"Pushing the boundaries of Edge AI and Manufacturing Intelligence."</i></p>
</div>

---

### 🐾 About Me
*   **Education:** 산업경영공학과 및 데이터사이언스학과 학부 졸업 후, 경희대학교 인공지능학과 석사과정을 졸업했습니다[cite: 3].
*   **Focus:** Vision AI, 엣지 디바이스 알고리즘 경량화, 자율주행 객체 인식, 이상 탐지(Anomaly Detection)
*   **Contact:** rbals985865naver.com , rbals985865@khu.ac.kr

---

### 🐾 Core Research & Projects

현장의 제한된 하드웨어 리소스를 극복하고, 모델 경량화 및 실시간 데이터 처리 파이프라인을 구축하여 실제 산업 도메인의 병목을 해결하는 데 집중합니다.

#### 🐈 1. Vision AI & Edge Deployment (머신비전 및 엣지 AI 배포)
* 🐱 **[SCIE 1저자] 반도체 웨이퍼 결함 분류 초경량화 AI (SCRBLAA-Net)**
  * 고차원 특징 분할 및 토큰화로 대규모 이미지 모델의 과적합 및 데이터 유실 문제 해결.
  * **VRAM 3.2GB 초경량화** 달성 및 결함 분류 **정확도 94.98%(+1.67%p)** 기록.
  * 3D t-SNE 시각화 및 HTML 기반 인터랙티브 웹 시뮬레이터 오픈소스 배포.
* 😸 **[캐글 1위] XAI 기반 적외선(IR) 태양광 모듈 초정밀 결함 탐지**
  * 극심한 데이터 불균형 한계 극복을 위해 23개 비전 모델 및 30개 앙상블 조합 완전 탐색 파이프라인 구축.
  * Grad-CAM(XAI) 통합으로 12종 발열 패턴 정밀 국소화, **양품 오분류 원천 차단 및 정확도 96.2%(+4.15%p)** 달성.
* 😼 **[전세계 1등 성능] 엔트로피 기반 앙상블 AI 활용 PCB 결함 분류**
  * 50개 이상 CNN 아키텍처 절제 연구 및 ResNet50·MobileNet 기반 엔트로피 앙상블 파이프라인 독자 개발.
  * 3단계 전이 학습 및 명시적 메모리 최적화로 **결함 분류 정확도 99.80% (SOTA)** 도달.
* 😽 **[MVTec AD] 비지도 학습 기반 산업용 고정밀 이상 탐지**
  * 정상 데이터만으로 결함을 검출하는 EfficientAd·Patchcore 병렬 파이프라인 구축.
  * 임계값 정밀 튜닝으로 기본 모델의 **과검(False Alarm) 문제 0건 달성 및 실질 정확도 최대 2.56%p 향상**.
* 🙀 **[SECS/GEM] 반도체 장비 결함 탐지 엣지 AI 아키텍처 구축**
  * 225만 개 조합 탐색을 통한 22개 이기종 모델 스태킹 앙상블 구축으로 **미탐률 최소화 및 F1-Score 0.5294(SOTA)** 달성.
  * ONNX 표준 포맷 변환 및 다중 스레딩 적용으로 **초저지연 C++ 엣지 추론 파이프라인** 깃허브 공개.
* 😻 **[CoreML] 실시간 다중 차량 인식 경량화 AI 모델**
  * 객체 라벨 재정비 및 Apple CoreML 가속 포맷 변환으로 엣지 환경 최적화.
  * 정밀도 손실 없이 **추론 지연시간 31% 단축(9.05ms) 및 mAP 32.64%p 수직 향상**.

#### 🐈 2. Enterprise AI & LLM (엔터프라이즈 AI 및 자연어 처리)
* 🐱 **[100% 로컬 구동] 차세대 RAG-NL2SQL 보안형 ERP 엔진**
  * 기업 데이터 유출 방지를 위해 Ollama 활용 100% 로컬 네트워크 구동 RAG 엔진 아키텍처 설계.
  * 자가 수정(Reflexion) 피드백 루프 및 8시간 자율 튜닝 도입으로 **엣지 케이스 방어율 100%, 1.65ms 지연시간 내 값 일치율 100%** 달성.
* 😹 **[전국 공모전 2등] 범용 AI 환각 제어 식품 과학 RAG 챗봇**
  * 환각 현상(Hallucination) 원천 차단을 위한 검색 증강(RAG) 기반 교차 검증 파이프라인 구축.
  * 외부 문서 기반 맞춤형 규칙 적용으로 탐색 효율 80% 및 **초록 생성 일치율 9배 향상**.

#### 🐈 3. Time Series & Predictive Maintenance (시계열 예측 및 예지보전)
* 🙀 **[Walmart ERP] 4,700만 건 ERP 데이터 수요 예측 메타 앙상블**
  * 80% 이상 영과잉(Zero-inflated) 특성 극복을 위한 투 스테이지 허들(Two-Stage Hurdle) 아키텍처 고안.
  * Zero-copy 메모리 최적화로 학습 시간 15분 단축 및 53개 단일모델 전수조사 기반 **최종 F1-Score 0.67** 달성.
* 😿 **[NASA C-MAPSS] 항공 엔진 다중 운전 조건 하이브리드 예후진단(PHM)**
  * CNN-BiLSTM-Attention 등 복합 아키텍처 적용으로 미검출 오진단 억제.
  * 정비 마진 튜닝 및 앙상블 적용으로 베이스라인 대비 **FD004 패널티 점수 90.4% 극적 감축**.
* 😾 **[BPIC 2012] 금융 프로세스 마이닝 기반 사전 병목 예측 AI**
  * LSTM 임베딩 및 통계 피처를 결합해 병목 현상을 워크플로우 중간에 사전 경고하는 스태킹 앙상블 설계.
  * 병목 미탐지(False Negative) 극도 억제로 **정확도 93.39%, F1-Score 86.62%(SOTA), 재현율 85.5%** 확보.
* 😻 **[NREL] 풍력 터빈 시계열 데이터 증강 및 데이터 부패 규명**
  * GAN 기반 증강 기법 도입으로 **예측 오차(MSE) 59.2% 획기적 절감** (설계 대회 1위 수상).
  * 정량 분석을 통해 GAN 증강이 원본의 상관관계 구조를 약 79.7배 왜곡하는 현상('숨겨진 부패')을 역추적 및 규명.

#### 🐈 4. Operations Research & Optimization (산업공학 최적화 및 시뮬레이션)
* 😸 **[Google OR-Tools] 대규모 AGV 물류 라우팅 병목 최적화**
  * 차량 경로 최적화(VRP) 및 메타휴리스틱(GLS) 알고리즘 적용으로 교착 상태 완전 차단.
  * **최적화 비용 지수 -324 감소, 작업 불균형 19% 개선 및 이동 거리 35% 단축** 달성.
* 😸 **[Amazon Scheduler] 메타휴리스틱 기반 교대 근무 로드 밸런싱**
  * OptaPlanner와 모의 담금질 알고리즘을 결합한 스케줄 최적화 엔진 구축.
  * **작업자 간 배정 격차 85% 해소 및 최대 연속 근무 통제로 번아웃 위험 50% 감소** 증명.
* 😻 **[Seoul Healthcare] 서울시 공공 헬스케어 초기 예측 아키텍처 구축**
  * 랜덤포레스트 기반 12개 비만 그룹별 심박수 통제 상·하한선(Xbar) 설정 및 선제적 알림 체계 구축.
  * 데이터 기반 **연간 1,134억 원 규모의 잠재적 의료비 절감 모델링** 입증.
* 😼 **[Arena] 코엑스 주차장 동선 시뮬레이션 최적화**
  * 객체 인식 기반 트래픽 데이터 분석 및 Arena 시뮬레이션 로직 검증.
  * 운영 인건비 절감 도출 및 **평균 대기시간 4.9% 단축, 차량 배회 횟수 30.5% 감소**.

---

### 🦝 Tech Stack & Arsenal

**AI & Data Science Pipeline**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
</p>

**DevOps & Edge Control**
<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
</p>

---

### 🐰 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Yani-Studio&show_icons=true&theme=transparent" alt="Yani-Studio's GitHub stats" />
</div>

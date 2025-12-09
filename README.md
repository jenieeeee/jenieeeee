<!-- 헤더 -->
<h1 align="center">👋 Hi, I'm <b>Choi Jae Eun</b></h1>

<p align="center">
  <img src="https://img.shields.io/badge/KakaoStyle-Search%20%26%20Recommendation-FFE812?style=flat-square&logo=kakaotalk&logoColor=000000"/>
</p>

<p align="center">
  <b>Recommender Systems · Search Quality · Data Analysis</b><br>
  패션 도메인의 검색·추천 품질을 이해하고, 데이터를 기반으로 더 나은 사용자 경험을 만드는 방법을 공부하고 있습니다.
</p>

---

## 🟡 Why I Study Search & Recommendation

> “사용자가 원하는 스타일을 더 빨리, 더 정확하게 찾게 해주는 것”  
> 이게 제가 생각하는 좋은 검색·추천 시스템의 역할입니다.

카카오스타일이 추구하는  
“다양한 스타일이 공존하는 세상”에 공감하면서

- 패션 커머스에서 **어떤 정보들이 검색·추천 품질을 좌우하는지**  
- 사용자의 행동 로그와 상품 메타데이터를 **어떻게 해석하고 활용해야 하는지**

직접 실습하고 정리하며 공부하고 있습니다.

---

## 🟡 About Me

- **추천 시스템과 검색 품질**에 관심을 갖고, Kaggle H&M 패션 데이터를 활용해 실습하고 있습니다.
- EDA → 전처리 → 시계열 분할 → MF → ML 재랭킹 → DeepFM까지  
  **엔드-투-엔드 추천 파이프라인을 직접 구현**해 보며 흐름을 이해하고 있습니다.
- 데이터가 어떻게 쌓이고, 그 안에서 **어떤 패턴을 찾아야 품질을 개선할 수 있을지** 고민하는 것을 좋아합니다.

---

## 🟡 What I’m Practicing

### 검색/추천 품질 관점의 데이터 보기

- 패션 상품 메타데이터(색상, 패턴, 카테고리 등)를 분석하고,  
  **추천 모델의 feature로 활용해보는 실습**을 진행했습니다.
- 사용자–상품 거래 로그를 바탕으로,  
  **시간에 따른 구매 패턴과 인기/상위 상품 변화**를 살펴본 경험이 있습니다.
- 유저 행동 로그를 통해  
  “어떤 상품이 어떤 맥락에서 선택되는지”를 관찰하며,  
  검색·추천 품질 개선에 필요한 관점을 쌓는 중입니다.

### 데이터 품질 검증 & 실험 흐름 이해

- 단순 랜덤이 아닌 **시계열 기반 Train/Valid/Test split**을 적용해,  
  실제 서비스에 가까운 평가 구조를 설계해 보았습니다.
- Negative Sampling, Feature Engineering을 통해  
  implicit feedback 데이터를 **모델이 학습 가능한 구조**로 바꿔본 경험이 있습니다.
- 모델의 추천 결과를 Recall@K, MAP@K 등으로 평가하며,  
  **정량적으로 품질을 비교하는 흐름**을 연습했습니다.

### 커뮤니케이션을 염두에 둔 정리

- 실습 내용을 단순 코드가 아니라,  
  **왜 이런 방식으로 전처리/모델링했는지 Markdown과 주석으로 정리**하는 데 신경 쓰고 있습니다.
- 나중에 다른 직군이 봐도 이해할 수 있도록,  
  “문제 정의 → 데이터 확인 → 접근 방식 → 한계”의 흐름으로 기록하려고 노력 중입니다.

---

## 🟡 Tech Stack

### Languages  
`Python` `SQL`

### Recommender Systems / Search  
`EDA on User–Item Logs`  
`Matrix Factorization (ALS)`  
`Feature Engineering`  
`Negative Sampling`  
`DeepFM (Keras)`  
*(후보 생성 → 재랭킹 구조를 공부하고 있습니다.)*

### Machine Learning / Deep Learning  
`Scikit-learn` `LightGBM` `TensorFlow/Keras`

### Tools  
`Jupyter Notebook` `VS Code` `Git/GitHub`

---

## 🟡 Featured Projects

### 추천시스템 구현 (Recommender Systems Study)

> Kaggle **H&M Personalized Fashion Recommendations** 데이터를 활용해,  
> 패션 도메인 추천 시스템의 전체 흐름을 따라가며 공부한 프로젝트입니다.

- 고객/상품/거래 로그 EDA  
- 시계열 기반 Train/Valid/Test 분할  
- MF(ALS) 베이스라인 → LightGBM 재랭킹 → DeepFM까지 단계적으로 구현  
- 패션 상품 메타데이터(색상, 패턴, 카테고리)를 feature로 활용하는 실습 진행  

🔗 **Repo:** https://github.com/jenieeeee/recommender-systems

---

### KAIST–POSTECH–UNIST 데이터사이언스 경진대회

> 제조/시뮬레이션 데이터를 기반으로  
> 모델 설계, 피처 엔지니어링, 검증 흐름을 직접 구성한 경험입니다.

- 문제 정의 → 데이터 전처리 → 모델링 → 성능 개선 과정을 코드로 정리  
- 실전 경진대회 환경에서 여러 실험을 빠르게 반복하며,  
  **모델링 전략을 선택하고 수정하는 경험**을 쌓았습니다.

🔗 **Repo:** https://github.com/jenieeeee/경진대회-레포-이름을_여기에_맞게_수정해주세요

---

## 🟡 What I’m Learning Now

- 패션 버티컬 커머스에서 **어떤 검색어/상품 조합이 좋은 경험을 만드는지**  
- 후보 생성 및 재랭킹 구조에서 **각 단계가 품질에 미치는 영향**  
- FM/DeepFM, Embedding을 활용한 **고차 feature 상호작용 표현 방식**  
- 검색 품질/추천 품질을 **데이터로 설득력 있게 설명하는 방법**

---

## 🟡 My Goal

- 유저가 “지금 나한테 딱 맞는 스타일”을 더 빨리 찾을 수 있도록,  
  **데이터를 통해 검색·추천 품질을 개선하는 사람**이 되는 것
- 단순히 모델링에 그치지 않고,  
  **문제 정의–가설 설정–데이터 검증–실험 설계**까지 연결할 수 있는 분석가로 성장하는 것
- 카카오스타일의 검색/추천 제품을 이해하고,  
  그 안에서 제가 맡을 수 있는 역할을 점점 넓혀가는 것이 목표입니다.

---

## 🟡 Contact

- **GitHub:** https://github.com/jenieeeee  
- **Email:** cje33333@naver.com

---

<h3 align="center">🟨 꾸준히 배우고, 정리하고, 더 나은 검색·추천 경험을 만들기 위해 성장 중입니다 🟨</h3>


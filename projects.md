### [Category 1] Financial Risk Modeling

1. **신용부도 예측 모델링 (`credit-default-modeling-lab`)**
   - 소스: `Financial-Engineering/chap6_default_prediction.ipynb`, `Financial-Data-Mining/2. Logistic Regression.ipynb`, `Financial-Data-Mining/3. Decision Tree and Ensemble.ipynb`
   - 주제: 분류모형(Logit/Tree/Ensemble) 비교, 불균형 데이터 처리, 리스크 스코어링

2. **금융사기 탐지 팀 프로젝트 (`fraud-detection-case-study`)**
   - 소스: `Financial-Data-Analysis/project/빅데이터와 금융자료 분석_1조_코드.ipynb`, `Financial-Data-Analysis/project/fraud_oracle.csv`
   - 주제: 이상거래/사기 탐지 성능 비교와 threshold 기반 운영 정책

3. **VaR·Copula 리스크 실습 (`market-risk-var-copula-lab`)**
   - 소스: `DFMBA-Assistant/data/Financial-Market-Risk-Management/Homework/VaR.ipynb`, `DFMBA-Assistant/data/Financial-Market-Risk-Management/Homework/copula.ipynb`
   - 주제: 분포 가정별 VaR 추정, 의존구조(Copula) 기반 tail risk 해석

### [Category 2] Derivatives and Risk Management

1. **몬테카를로 가격/리스크 시뮬레이션 (`monte-carlo-pricing-simulation`)**
   - 소스: `Financial-Engineering/chap_3_montecarlo.ipynb`, `Management-Statistics-Analysis/Ep5-Price-Process/Brownian.m`
   - 주제: 확률과정 기반 경로생성, 가격/리스크 민감도 분석

2. **연기금 목표기반 투자 & 시나리오 분석 (`retirement-goal-based-investing`)**
   - 소스: `Pension-Fund/Retirement-Investing/retirement strategy scenario.ipynb`, `Pension-Fund/Retirement-Investing/retirement_strategy.ipynb`, `Pension-Fund/Retirement-Investing/monte.ipynb`
   - 주제: 인플레이션·수익률 시나리오별 목표달성확률, 은퇴 현금흐름 리스크 관리

3. **블랙-리터만 자산배분 실습 (`black-litterman-allocation-lab`)**
   - 소스: `Pension-Fund/Black-Ritterman-Model-Practice/idzorek-allocation.ipynb`
   - 주제: 시장균형수익률+투자자 뷰 결합, 뷰 신뢰도별 포트폴리오 민감도

### [Category 3] Quant Trading Strategy Research

1. **BAB + 모멘텀 팩터 전략 (`quant-bab-momentum-kospi`)**
   - 소스: `Quant-and-Factor-Investment-Strategies/Midterm/Submit/BAB_final.py`, `Quant-and-Factor-Investment-Strategies/Midterm/Submit/momentam_final.py`
   - 주제: 저베타·모멘텀 프리미엄 검증, 누적성과 및 팩터회귀

2. **멀티팩터 종목선정 포트폴리오 (`multi-factor-stock-selection`)**
   - 소스: `Quant-and-Factor-Investment-Strategies/Final/Submit/Multi_Factor_Portfolio_20239047_김민수.ipynb`
   - 주제: 팩터 스코어링·랭킹 기반 종목 선정 및 성과 attribution

3. **Pair Trading & OOS 예측가능성 (`pair-trading-and-predictability`)**
   - 소스: `Management-Statistics-Analysis/Ep5-Price-Process/pairTrading.ipynb`, `Management-Statistics-Analysis/Ep5-Price-Process/Goyal_Welch_OOS.ipynb`
   - 주제: 평균회귀 전략과 예측신호의 표본외 성능 검증

### [Category 4] Financial Data Science

1. **뉴스 크롤링·감성·트렌드 파이프라인 (`financial-news-trend-sentiment-pipeline`)**
   - 소스: `Financial-Big-Data-Analysis/4주차/news_list_crawler.py`, `Financial-Big-Data-Analysis/5주차/news_contents_crawler.py`, `Financial-Big-Data-Analysis/10주차/news_trends.py`, `Financial-Big-Data-Analysis/9주차/add_sentiments.py`
   - 주제: 비정형 금융데이터 수집→정제→감성→집계 자동화

2. **BOK/FRED 거시 데이터 파이프라인 (`macro-data-engineering-bok-fred`)**
   - 소스: `Financial-Database/Exercise 4-1.ipynb`, `Financial-Database/data/bok_item_codes.xlsx`, `LLM-and-RAG-Language-Model/week3/fred_crawler.py`, `LLM-and-RAG-Language-Model/week3/export_sql_to_parquet.py`
   - 주제: API 수집부터 SQL/Parquet 적재까지의 금융 데이터 엔지니어링

3. **RAG 기반 금융 Q&A 실습 (`rag-finance-qa-lab`)**
   - 소스: `LLM-and-RAG-Language-Model/week1/E1-2. RAG Basic.ipynb`, `LLM-and-RAG-Language-Model/week2/news_cluster.py`
   - 주제: 문서 검색증강(RAG)과 금융 텍스트 클러스터링 결합 실험
NLP/LLM 기반 추천 및 예측 모델 개발


# 목차


1. ETRI 주최 'Fashion-How'  경진대회 참여를 통해 자연어 처리(NLP)와 시계열 예측 모델의 실무 적용 능력을 검증하고 상위권에 랭크된 프로젝트입니다.
3. 실습한 llm인 koBERT 프로잭트가 있습니다.
4. Dacon 주최 '한솔데코' 경진대회 프로젝트입니다. (업로드 예정)
5. 그외


✨ Key Features
의미 기반 패션 추천: KoBERT 모델을 미세 조정(Fine-tuning)하여 사용자의 주관적인 텍스트 질의의 문맥적 의미를 파악하고, 코사인 유사도 기반으로 아이템 추천.
시계열 수요 예측: LightGBM, XGBoost 등 그래디언트 부스팅 모델을 활용하여 과거 데이터를 기반으로 미래 자재 수요 예측.
피처 엔지니어링: TF-IDF, Word2Vec 등 NLP 임베딩 기법과 이동 평균, 계절성 등 시계열 피처 추출 기법 적용.
🛠️ Tech Stack
AI/ML: Python, PyTorch, Scikit-learn, LightGBM, XGBoost
NLP: Hugging Face Transformers, KoBERT, TF-IDF, Word2Vec
Data Analysis: Pandas, NumPy, Matplotlib, Seaborn
Tools: Jupyter Notebook, Dacon
🏆 Key Results
ETRI 및 Dacon 주최 AI 경진대회에서 상위권 랭킹 기록.   
Transformer 기반 언어 모델의 미세 조정 및 실제 문제 적용 능력 입증.
제한된 자원 하에서 효율적인 모델을 개발하고 최적화하는 능력 검증.   
🚀 Getting Started
본 프로젝트는 경진대회 플랫폼에서 진행되었으며, 각 과제에 대한 접근 방식과 코드는 아래 링크된 Notion 페이지의 케이스 스터디와 Jupyter Notebook에서 확인하실 수 있습니다.

데이터셋: 각 경진대회 페이지에서 제공 (Dacon, AI Hub).
실행 환경:
Bash

# 필요한 라이브러리 설치
pip install -r requirements.txt
코드 실행:
Bash

# 각 경진대회 폴더의.ipynb 파일을 Jupyter Notebook 또는 Colab에서 실행
jupyter notebook "Fashion-How_KoBERT_Fine-tuning.ipynb"
🧠 Deep Dive & Learnings
사용자의 모호한 텍스트 질의를 처리하기 위해 KoBERT를 선택하고 미세 조정한 과정, 시계열 데이터에서 유의미한 피처를 추출한 방법 등 상세한 기술적 의사결정 과정은 아래 Notion 페이지에 기록되어 있습니다.

➡️ [Notion에서 전체 기술 회고 및 케이스 스터디 읽기]()

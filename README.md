# crowd_funding_prediction
machine learning based funding prediction model

> 20.08.23 AI-JAM-Korea 2020 출품작 (본선진출) <br>
> https://aijam-korea.com/

## 요약
과거 크라우드 펀딩 성공/실패 데이터셋을 이용한 크라우드 펀딩 성공 여부 예측 모델. AI-JAM-Korea 2020 인공지능 창업 해커톤에 출품하였고 아이디어를 활용한 창업 실현 가능성을 분석함. 3인 1팀 으로 구성되어 대회에 참여 하였으며 팀장으로서 PM을 담당.

사용 언어 : Python
IDE : jupyter notebook

* 백준호(팀장)
  * PM, 머신러닝, 데이터 분석 및 시각화, GUI
* 송방원 (홍익대 18)
* 박기정 (홍익대 16)


### 사용 데이터 셋
kaggle에 kickstarter 크라우드 펀딩 히스토리 데이터 <br>
<a href = "https://www.kaggle.com/yashkantharia/kickstarter-campaigns">데이터셋 출처 및 데이터 설명 </a>

### 구성
* data_analysis
  * 데이터 시각화를 통한 데이터 insight 추출
  * Seaborn, Matplotlib
* model_selection
  * 데이터 전처리 및 학습모델 정확도 비교 실험, 파라미터 튜닝
  * sklearn, pandas, pickle
* final_model
  * 최종 선정 모델과 데이터 전처리 셋에 대해 test set 예측 및 평가
  * sklearn, pandas, pickle, matplotlib
* funding_prediction
  * 아이디어 창업 구현을 위한 GUI 프로토타이핑 (naive)
  * PYQT5
* 내 사업이 투자를 받을 수 있을까.pptx
  * AI JAM Korea 2020 대회 발표 프레젠테이션 자료

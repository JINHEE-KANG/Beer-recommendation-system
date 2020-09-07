# Beer-Recommendation-System
2019년 2학기 통계학 세미나 기말 프로젝트
맥주 추천 알고리즘(시스템)

### 수업 정보
- 2019년 2학기(2019.09.02-2019.12.21)
- 경영경제대학/응용통계학과/전공
- 임창원 교수님

## 분석 프로세스
1. 데이터 전처리
2. 머신러닝 - 협업필터링 Collaborative Filtering
  1. 최근접 이웃 기반
    - IBCF
  2. 잠재요인 기반
    - SVD
    - NMF
  3. Surprise 패키지 활용
3. 딥러닝 - 임베딩 Embedding
  - optimizers: Adam, RMSprop, Adadelta, SGD
  - activation functions: relu, sigmoid, tanh
  - dropout: L2
4. 분석 결과
  - 모델 성능 평가: rmse
  - 데이터 시각화


### 생성 파일
- [데이터 전처리](my_df.csv)

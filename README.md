# weather-119-call-prediction

기상청 날씨 빅데이터로 구별 일별 119 신고 건수를 예측.
불쾌지수·열대야 등 날씨 파생변수와 lag1/2·roll7 시계열 변수를 설계하고,
**XGBoost·RandomForest·CatBoost 앙상블 + TimeSeriesSplit 5분할 교차검증**으로 학습 —
2024년은 자기회귀 순차 예측으로 생성 (**RMSE 5.7 · R² 0.64**).


`Python` `pandas` `XGBoost` `RandomForest` `CatBoost` `scikit-learn`

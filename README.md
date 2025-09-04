# Ichimoku_DL
딥러닝을 활용한 일목균형표 전략

본 전략에서는 LSTM이 더 우세하다는 것으로 나타났습니다. 

3-Role LSTM 모델이 가장 성과가 좋았으며
2-Role 기반 LSTM vs LSTM+CNN = LSTM이 더 우세하다는 것으로 나타났습니다.

CNN결합모델:
+전이학습
+다차원, 이미지 특화 특성공학 필요

Optuna 
PROB_THRESHOLD': 0.4568, 'ATR_SL_MULTIPLIER': 2.0905, 'ATR_TP_MULTIPLIER': 4.9610,
'IC_TENKAN': 6, 'IC_KIJUN': 27, 'IC_SENKOU': 56,
'LSTM_UNITS': 32, 'DROPOUT_RATE': 0.1736, 'trial_id': 27

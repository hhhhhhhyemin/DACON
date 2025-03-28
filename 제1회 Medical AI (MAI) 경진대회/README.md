## 제 1회 Medical AI (MAI) 경진대회
- **주제**

H&E 염색된 조직 이미지로부터 유전자 발현 예측
- **사용 모델**

ViT 기반 모델 앙상블 ( SimCLR, DenseNet169, Efficientnet)

- **분석 방법**

  - ViT를 사용하여 이미지 특징 벡터를 학습.
  - 대조 학습(Contrastive Learning)으로 유사한 샘플의 특징 벡터를 가깝게,  다른 샘플은 멀게 조정.
  - 학습된 ViT 백본을 사용하여 유전자 발현 예측을 위한 선형 회귀 모델 적용(Fine-tuning).
 
- ** 결과 **
  
![Image](https://github.com/user-attachments/assets/c25b5452-2a90-424e-ab44-93c2ab3edecb)

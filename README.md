# Whale Identification
[Whale Identification](https://www.notion.so/S4_Whale-Identification-8e4d8a8838dc486798dcd31ebd40649c)

고래 꼬리 모양이 촬영된 이미지를 바탕으로 해당 꼬리를 가진 개체가 등록된 5004 마리 중 어떤 개체인지 추정합니다. 

Data source : [🔗Kaggle Humpback Whale Identification dataset](https://www.kaggle.com/c/humpback-whale-identification/data) 

- CNN 모델을 통한 분류기 학습
- 사전학습된 Google Facenet을 전이학습
- 두 모델에서 모두 정확도가 매우 낮아 실질적인 성과는 없는 프로젝트

---

### 향후 개선 방향
- 꼬리 영역과 주변 배경을 구분하여 마스킹한 데이터로 학습
- triplet loss funciton, Siamese Network 구현 시도
- 기술적으론 '얼굴 인식'과 같은 문제  
비슷한 방식의 해결방법을 적용할 수 있다.

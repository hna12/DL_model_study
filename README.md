# DL_model_study

### Deep learning model training method
1) training a model from scratch </br>
  - model을 처음부터 새롭게 만들고 학습시킴
  - pre-trained 없이 데이터로부터 모델의 가중치를 초기화하고 훈련
  - dataset이 작거나 특별한 작업에 맞는 모델이 없을 때 사용 됨
  - 모델의 architecture를 직접 설계하고 학습 과정을 통해 가중치를 조정
  - 사용하는 이유
    - 이 학습 결과를 low boundary로 지정해 training from scratch로 했을 때의 성능보다 좋게 나온다는 것을 보여주기 위해
    - pretrain 도움 없이 backbone 이후 뒷 단의 layer 만으로 성능을 보기 위해
2) transfer learning
  - pre-trained model 또는 가중치를 사용해 model를 초기화하고 이를 특정 작업에 맞에 fine-tuning하는 법
  - 일반적으로 대규모 img dataset에서 사전 훈련된 CNN model을 가져와 다른 작업에 적용함

### DL 공부에 있어서 scratch가 중요한 이유
1) 기본 이해: DL의 핵심 개념과 원리 이해 가능(model architecture, loss function, backpropagation, 최적화 알고리즘 등)
2) 문제 해결 능력 향상: scratch 학습을 통해 자신만의 모델을 만들고 문제를 해결하는 능력을 키울 수 있다.
3) model design: scratch 학습은 model architecture를 직접 설계하고 조정하는 경험 제공하고 이는 mdoel 개발에 중요
4) 문제의 customizing: 다양한 유형의 문제에 대한 해결책을 만들 수 있으며, 특정 문제에 맞게 모델을 수정하고 조정할 수 있는 능력 키움


ref)
- https://chaelin0722.github.io/concept/scratch_learning/
- https://euhyeji.blogspot.com/2017/05/tf-11-slim-22.html
- chatGPT

🔑 **PRT(Peer Review Template)**

- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
            <img width="413" alt="image" src="https://github.com/hojae-m-choi/aiffel/assets/98305832/157310d5-054c-4575-8abc-24eb17fe2daf">
            <img width="447" alt="image" src="https://github.com/hojae-m-choi/aiffel/assets/98305832/43884fe1-a478-4f17-9c3a-0b837d5af9ad">


- [x]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
    - [ ]  모델 선정 이유
      - 선정 이유는 적혀있지 않았다. 기본의 모델을 사용했다
    - [x]  Metrics 선정 이유
      - MSE, RMSE, MAE 테스트했다. MAE 는 초기에 이상현상이 있었다. 왔다갔다 했음.
    - [x]  Loss 선정 이유
        - MAE 는 초기에 이상현상이 있었다. 왔다갔다 했음. -> MSE 로 선정함.

- [x]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    - [x]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
        - sklearn 의 train_test_split 을 사용함. (train:test = 8:2)
    - [x]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
        - learning rate : 0.1 단위로 시도해 봄.
    - [x]  각 실험을 시각화하여 비교하였나요?
      - age vs prediction, 
    - [x]  모든 실험 결과가 기록되었나요?
      - 
- [x]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
    - [x]  배운 점: 기초단계를 볼수 있어서 좋았다. 
    - [x]  아쉬운 점: 전반적인 시간이 부족해 자세히 살펴보지 못했다.
    - [x]  느낀 점: 코드 작성에 시간을 줄여야함을 느꼈다.
    - [x]  어려웠던 점: 시간관리를 하지 못해서 전반적인 이해도가 떨어졌다.

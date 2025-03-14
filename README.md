# 5가지 맛 판별 인공지능 모델(K프로젝트 II)

## 1. 프로젝트 소개

### 1-1. 프로젝트 개요

인간의 3대 욕구 중 하나는 식욕으로, 맛은 식품 및 음료의 중요한 특성 중 하나로, 소비자의 선택과 만족도에 큰 영향을 미칩니다. 그러나 맛은 주관적이거나 복잡할 수 있기 때문에 이를 단맛, 짠맛, 신맛, 쓴맛, 감칠맛 등 다양한 맛 요소로 분류하여 식품의 맛을 정량화하고 분석하는 것이 중요합니다. 이를 위해 NIR 분광기를 활용한 인공지능 모델을 개발하고자 합니다.

프로젝트에서는 NIR 분광기를 통해 식품의 반사율, 투과율 등을 측정하여 데이터를 추출하고, 이를 활용하여 모델을 학습시킬 예정입니다. 그 후에는 새로운 식품 데이터를 분광기로 측정했을 때, 해당 데이터를 기반으로 5가지 맛 중 어떤 맛과 가장 유사한지를 판별하여 분류할 것입니다.

일반적으로 사람이 요리할 때는 개인의 취향이나 맛에 맞춰서 음식을 조리합니다. 그러나 맛은 주관적이기에, 사람 없이 로봇만으로 요리를 진행하는 데에는 어려움이 있습니다. 따라서 분광기를 통해 학습된 인공지능 기기를 활용하여 맛을 정량화한다면, 향후에는 각 개인의 취향에 맞춘 맞춤 음식을 조리할 수 있는 시스템을 개발할 수 있을 것으로 기대됩니다.

### 1-2. 프로젝트 목표

이 프로젝트의 목표는 NIR 분광기를 통해 5가지 맛의 대표 음식들을 측정하고 이를 분류하는 인공지능 모델을 만드는 것이다. 이후, 새로운 데이터에 대해 맛의 비중을 확률로 나타내며, 가장 확률이 높은 맛으로 분류하는 것이다.

### 1-3. 프로젝트 주요 내용

5가지 맛을 판별하고 맛의 확률을 나타내는 인공지능 모델 개발은 다음과 같이 수행된다.

- 첫 번째는 5가지 맛 데이터를 모은다.
- 두 번째는 모은 5가지 데이터를 인공지능 모델을 선정하고, 학습을 시킨다.
- 세 번째는 학습된 모델에 새로운 데이터를 넣어 분류를 진행한다.

## 2. 파일 구성 및 활동 내용

주 활동 내용은 다음과 같으며, 각 활동에 대한 자세한 내용은 각각의 폴더에 있는 README.md 파일을 참고한다.

1. 선행 연구 조사 및 5가지 맛 대표 음식 조사

2. 데이터 처리 프로세스 설계

3. 샘플 데이터 수집

4. 샘플 데이터 분석 및 전처리

5. 인공지능 모델 선정 및 생성

6. 테스트 데이터 수집

7. 테스트 데이터 분석 및 모델 수정

8. 통합 테스트

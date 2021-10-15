# 지도 학습 
레이블된 데이터를 기준으로 학습하여 예측값을 실제 결과값과 비교하여 직접 피드백한다. 주로 구분 및 예측시 사용.

## 분류(Classification)
![](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FckyJHk%2Fbtq2ze26dqa%2Fm5DDgZjvBBQJGunQOu4tv1%2Fimg.png)

지도 학습의 하위 카테고리로 새로운 데이터를 **범주형 클래스로 예측하는 것이 목표**입니다. (예시 스팸메일 여부 판단, 손글씨 인식 등) 클래스 레이블은 이산적(단절되어 있다.)이고, 순서가 없기 때문에 샘플이 속한 *그룹*을 뜻한다. 즉 새로운 **데이터가 어느 그룹에 속한지 예측**하는 것을 목표로 한다.

클래스의 종류가 스팸메일 여부 처럼 **이진(binary)** 일 경우 이산분류 손글씨 처럼 여러 개일 경우 **다중 분류(multi class)** 로 구분된다.

일련의 데이터를 기준으로 학습하여 데이터의 범주를 구분하여 경계를 나누는 학습을 한다. 새로운 데이터가 들어오면 해당 점이 어느 곳에 위치하느냐에 따라 가까운 카테고리 혹은 학습된 알고리즘에 의해 분류 

### 대표적 알고리즘 
- [KNN(K-Nearest Neighbors)](./KNN.md)
- [SVM(Support Vector Machine)](./SVM.md)
- [의사결정 트리(Decision Tree) ]()
- [랜덤 포레스트(Random Forest)]()
- [Naive Bayes](./NaiveBayes.md)
  
## 회귀 분석(Regression)

### 대표적 알고리즘 
- [선형 회귀 (Linear Regression)]()
- [로지스틱 회귀 (Logistic Regression)]()


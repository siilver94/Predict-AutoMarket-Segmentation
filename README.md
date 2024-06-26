# 자동차 시장 세분화 분류 예측(Predict AutoMarket Segmentation)

<br/>

## 프로젝트 소개

이 프로젝트는 자동차 회사의 고객 데이터를 분석하여 새로운 전략을 수립하기 위해 신규 고객을 네 개의 시장으로 세분화하는 것을 목표로 합니다.

<code><img height = "400"
src=https://github.com/siilver94/Predict-AutoMarket-Segmentation/assets/57824945/5a43127c-2725-488f-a437-d417463a1db1></code>



<br/>


## 프로젝트 구조

- 데이터 준비 및 전처리
- 모델 구축 및 튜닝
- 평가 및 결과 분석

---

### 데이터 Features

**Ever_Married:** 결혼 여부

**Age:** 나이

**Graduated:** 학력

**Work_Experience:** 근무 경력

**Spending_Score:** 소비 점수

**Family_Size:** 가족 규모

**Gender_Female, Gender_Male:** 성별

**Profession_X:** 직업 (Artist, Doctor, Engineer 등)

**Var_1_Cat_X:** 다양한 변수 카테고리


<br/>


## 사용 기술

**데이터 전처리:** `get_dummies`

**모델링:** `RandomForestClassifier`

**튜닝:** `GridSearchCV`


<br/>


### 목표

신규 고객을 네 개의 시장으로 분류하여 전략 수립에 활용하기 위해 모델을 개발합니다.

<br/>


### 평가 지표

`Macro f1-score`와 `Accuracy`를 사용하여 모델의 성능을 평가합니다.


<br/>



## 리뷰

이 프로젝트를 진행하면서 저는 실전 데이터 분석의 복잡성과 흥미로움을 직접 체험하게 되었습니다.
특히, 다양한 변수를 고려하여 고객을 세분화하는 과정에서 데이터의 중요성과 모델 선택의 중요성을 몸소 깨달았습니다. 
처음에는 데이터의 다양성과 복잡성에 대해 조금 당황스러웠지만, 동료들과의 협업과 끊임없는 자기 개선을 통해 이를 극복할 수 있었습니다.

더불어, 모델링 과정에서 발생하는 다양한 문제들을 해결하는 과정에서 많은 것을 배웠습니다. 
특히, GridSearchCV를 통한 하이퍼파라미터 튜닝과 모델의 최적화에 대한 경험이 매우 유익했습니다. 어려움을 겪을 때마다 팀원들과의 협력과 검색을 통해 문제를 해결하는 능력을 향상시키는 데 큰 도움이 되었습니다.

이러한 경험을 통해 데이터 분석 역량뿐만 아니라 문제 해결 능력과 협업 능력을 향상시킬 수 있었습니다. 
이 프로젝트를 통해 얻은 인사이트와 경험은 저의 성장에 큰 밑거름이 되었으며, 앞으로의 프로젝트에서도 이를 바탕으로 더 나은 결과물을 만들어 나갈 것입니다.

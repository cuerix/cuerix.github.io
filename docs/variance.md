---
title: 분산분석
author: Scotty
date: 2024-11-11
category: stats
layout: default
---
## 개요
분산분석(ANOVA, Analysis of Variance)은 **여러 그룹 간 평균 차이를 비교하는 통계 기법**입니다. 집단 간 차이가 우연인지, 특정 요인(factor)에 의해 발생했는지를 검정하는 데 사용됩니다. 독립변수의 개수와 측정 방식에 따라 여러 유형이 있으며, 실험 및 조사 연구에서 널리 활용됩니다.

dd
ddsdsds


DSDD



---

##### 📌 목차
- 분산분석의 개념
- 분산분석의 기본 가정
- 분산분석의 유형
- 실전 예제



### 1. 분산분석의 개념
**분산분석(ANOVA)**은 그룹 간 차이를 분석하기 위해 <span style="background-color:#fff5b1">집단 간 분산(Between-group variance)</span>과 <span style="background-color:#fff5b1">집단 내 분산(Within-group variance)</span>을 비교하여, 평균 차이가 통계적으로 유의미한지를 검정하는 방법입니다.  

#### 📋 개념 설명
- ##### 집단 간 분산(Between-group variance)
각 그룹의 평균 차이가 얼마나 큰지를 측정합니다. 요인(독립변수)의 효과가 클수록 집단 간 분산이 커집니다.  
- ##### 집단 내 분산(Within-group variance, Error variance)
각 그룹 내부의 데이터가 평균값을 중심으로 얼마나 흩어져 있는지를 측정합니다. 개별 데이터의 변동을 의미하며, 이는 측정 오차나 개인차 등에 의해 발생합니다.
- ##### F-통계량 (F-ratio) 계산
집단 간 분산을 집단 내 분산으로 나눈 값입니다. F값이 클수록 집단 간 차이가 크며, 일정 수준 이상이면 유의미한 차이라고 판단합니다.
  - 귀무가설(𝐻0): "집단 간 평균 차이가 없다."
  - 대립가설(𝐻1): "집단 간 평균 차이가 있다."


### 2. 분산분석의 기본 가정
분산분석을 수행할 때 모델이 성립하귀 위해 필요한 가정이 있습니다. 이러한 가정들이 충족되지 않으면 분석 결과가 왜곡될 수 있습니다. 
주요 가정은 다음과 같습니다.

- 정규성(Normality): 종속변수가 정규분포를 따라야 함
- 등분산성(Homogeneity of variance): 모든 그룹의 분산이 유사해야 함 (Levene’s test 사용)
- 독립성(Independence): 각 집단의 샘플이 서로 독립적이어야 함


### 3. 분산분석의 유형

#### 일원 분산분석 (One-way ANOVA)  
- <span style="background-color:#fff5b1">하나의 독립변수(요인, factor)</span>가 여러 개의 수준(level)을 가질 때, 이들 간 평균 차이를 검정하는 방법  
- 예시: 세 개의 교육 방법(A, B, C)이 학생들의 시험 점수에 미치는 영향 분석  

##### ❗️핵심 포인트  
- **독립변수(Factor)**: 하나의 요인  
- **수준(Levels)**: 요인의 여러 그룹(예: 교육 방법 A, B, C)  
- **집단 간 분산(Between-group variance)**: 각 집단 평균 간 차이  
- **집단 내 분산(Within-group variance, Error variance)**: 개별 데이터의 변동  
- **F-검정(F-test)**: 집단 간 차이가 유의미한지 검정  
- **사후 검정(Post-hoc test)**: 유의미한 경우, 어떤 그룹 간 차이가 나는지 추가 분석 (Tukey, Bonferroni 등)  

#### 이원 분산분석 (Two-way ANOVA)  
- <span style="background-color:#fff5b1">두 개의 독립변수(요인)</span>가 있는 경우 평균 차이를 검정  
- 각 독립변수가 종속변수에 미치는 영향과 <span style="background-color:#fff5b1">상호작용 효과(interaction effect)</span> 분석 가능  
- 예시: 교육 방법(A, B, C)과 성별(남, 여)이 시험 점수에 미치는 영향 분석  

##### ❗️핵심 포인트  
- **주효과(Main effect)**: 각 독립변수(X1,X2)가 개별적으로 종속변수(Y)에 미치는 영향  
- **상호작용 효과(Interaction effect)**: 두 독립변수의 결합이 종속변수에 미치는 영향  
- **교차 효과(Cross-effect)**: 두 독립변수의 조합에 따라 결과가 달라지는 경우  
- **F-검정(F-test)**: 각 요인의 영향과 상호작용 효과를 평가  


#### 반복 측정 분산분석 (Repeated Measures ANOVA)   
- 동일한 집단에서 <span style="background-color:#fff5b1">여러 번 측정한 데이터</span>를 비교하는 분산분석  
- 개인별 차이를 통제할 수 있어 효율적인 분석 가능  
- 예시: 동일한 참가자가 1주 차, 2주 차, 3주 차에 걸쳐 수행한 시험 점수 변화 분석  

##### ❗️핵심 포인트  
- **반복 측정(Repeated measures)**: 같은 대상에서 여러 번 측정  
- **이내 집단 설계(Within-subject design)**: 같은 사람이 여러 조건을 경험  
- **시간 효과(Time effect)**: 시간이 지남에 따라 측정값이 변하는지 확인  
- **구형성(Sphericity)**: 반복 측정 간 분산이 유사해야 함 (Mauchly's test로 확인)  
- **대응 t-검정(Paired t-test)과 차이점**: 세 개 이상의 시점 비교 가능  


### 5.사후 검정 (Post-hoc test)
ANOVA는 집단 간 평균 차이가 존재하는지만 검정하므로, <span style="background-color:#fff5b1">각 집단 내 어떤 그룹 간 차이가 나는지</span> 알아보려면 **사후 검정(post-hoc test)**이 필요합니다.
대표적인 방법:
- **Tukey's HSD**: 등분산 가정이 충족될 때 사용
- **Bonferroni**: 다중 비교를 수행할 때 보수적인 방식
- **Dunnett's test**: 한 집단(대조군)과 다른 집단을 비교할 때 사용


## 5. 실전 예제 



<center>
<div style="border: 1px solid grey; width: fit-content;">
  <img width="800" alt="image" src="https://github.com/user-attachments/assets/6b82e666-f9c6-46d4-8219-00b67095d137">
</div>
</center>

#### ✔ 변수 설정방법
##### 일원배치 분산분석
  ➊ 분석할 연속형 변수(측정 대상)를 선택합니다.  
  ➋ 집단을 구분하는 범주형 변수를 선택합니다.  
  ➌ 데이터 분석 아이콘을 클릭해 결과를 확인합니다.  
  
##### 일원배치 분산분석 (반복측정)
  ➊ 분석할 연속형 변수(측정 대상)를 선택합니다.  
  ➋ 반복측정을 위한 범주형 변수를 선택합니다.  
  ➌ 데이터 분석 아이콘을 클릭해 결과를 확인합니다.  
    
  
##### 이원 분산분석  
  ➊ 분석할 연속형 변수(측정 대상)를 선택합니다.
  ➋ 집단을 구분하는 두 개의 범주형 변수를 각각 선택합니다.  
  ➌ 데이터 분석 아이콘을 클릭해 결과를 확인합니다.  
  
  
##### 이원분산분석 (반복측정)  
  ➊ 분석할 연속형 변수(측정 대상)를 선택합니다.
  ➋ 집단 간 비교를 위한 범주형 변수(G1)와 시간 경과를 나타내는 범주형 변수(T1)를 각각 선택합니다.
  ➌ 데이터 분석 아이콘을 클릭해 결과를 확인합니다.
    

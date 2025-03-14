---
title: 비모수 검정
author: Scotty
date: 2024-11-11
category: stats
layout: post
---

### 알아가기
<strong>비모수 검정</strong>은 데이터가 정규분포를 따르지 않는 경우에 사용하는 통계적 분석 방법입니다.  
 비모수 검정은 데이터의 분포에 대한 가정이 필요하지 않으므로, 모수 검정(parametric test)보다 유연하게 적용할 수 있습니다.  
 특히 데이터가 비대칭적이거나 극단값(outliers)이 많을 때 유용하며, 표본 크기가 작거나 측정 척도가 순위형(ordinal scale)일 때 주로 사용됩니다.

 !데이터가 정규분포에 따르는지 여부는 정규성 검정에서 확인하실 수 있습니다.


### 검정 종류
대표적인 비모수 검정 방법은 다음과 같습니다

![Image](https://github.com/user-attachments/assets/de615990-b303-437c-a1da-d198e846b02c)

- ##### 맨-휘트니 U 검정(Mann-Whitney U Test)
  두 집단의 중위수가 동일한지를 검정하는 방법으로, 독립된 두 집단 간의 차이를 비교할 때 사용됩니다.  
이는 모수적 검정인 독립표본 t-검정의 비모수적 대안입니다.
- ##### 윌콕슨 부호 순위 검정(Wilcoxon Signed-Rank Test)
  대응되는 두 집단 간의 차이를 검정하는 방법입니다.  
  대응표본 t-검정의 비모수적 대안으로, 예를 들어 같은 집단에서 처리 전후의 변화를 비교할 때 사용됩니다.
- ##### 크루스칼-월리스 검정(Kruskal-Wallis Test)
  세 개 이상의 독립 집단 간 차이를 검정하는 방법으로, 일원분산분석(ANOVA)의 비모수적 대안입니다.  
  각 집단의 중위수가 동일한지를 확인합니다.
- ##### 프리드만 검정(Friedman Test)
  반복 측정된 세 개 이상의 집단 간 차이를 검정하는 방법입니다.  
  반복 측정 분산분석(repeated measures ANOVA)의 비모수적 대안으로, 같은 집단 내에서 여러 조건을 비교할 때 사용됩니다.  
  비모수 검정은 데이터 분포에 대한 가정이 적어 다양한 상황에 활용 가능하지만, 모수 검정보다 검정력이 낮을 수 있습니다.

<center>
<div style="border: 1px solid grey; width: fit-content;">
  <img width="800" alt="image" src="https://github.com/user-attachments/assets/96677e3f-d860-410c-b095-7d4d4163ed6c">
</div>
</center>

#### ✔ 변수 설정방법  
  
##### 맨-휘트니 U 검정
➊ 분석방법에서 대립가설 및 p값 설정방법을 선택합니다.  
➋ 두 집단에 해당하는 범주형 변수(열)을 선택합니다.  
➌ 분석하고자하는 값인 연속형 변수(열)을 선택합니다.  
➍ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.   
      
##### 윌콕슨 부호 순위 검정  
➊ 분석방법에서 대립가설 및 p값 설정방법을 선택합니다.  
➋ 사전/사후에 분석하고자하는 값인 연속형 변수(열)을 각각 선택합니다.  
➌ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.  
      
##### 크루스칼-월리스 검정  
➊ 세 집단에 해당하는 범주형 변수(열)을 선택합니다.  
➋ 분석하고자 하는 값인  연속형 변수(열)을 선택합니다.  
➌ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.   
      
##### 프리드만 검정  
➊ 반복횟수에 해당하는 범주형 변수(열)을 선택합니다.  
➋ 반복 측정 대상 범주형 변수(열)을 선택합니다.  
➌ 반복측정 결과 연속형 변수(열)을 선택합니다.  
➍ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.  


#### ✔ 결과 해석 
비모수 검정의 가설검정은 다음과 같습니다.

##### 맨-휘트니 U 검정
- 귀무가설: 두 집단의 중위수는 차이가 없다.  
- 대립가설: 두 집단의 중위수는 차이가 있다.

##### 윌콕슨 부호 순위 검정   
- 귀무가설: 한 집단의 사전/사후의 중위수가 차이가 없다.  
- 대립가설: 한 집단의 사전/사후의 중위수가 차이가 있다.    


##### 크루스칼-월리스 검정    
- 귀무가설: 집단 간 중위수는 차이가 없다.
- 대립가설: 집단 간 중위수는 차이가 있다.


##### 프리드만 검정    
- 귀무가설: 반복 측정된 집단의 중위수는 차이가 없다.
- 대립가설: 반복 측정된 집단의 중위수는 차이가 있다.

각 통계량에 따른 p값과 유의수준에 따른 해석은 다음과 같습니다.
- p-value ≥ 0.05(유의수준): 귀무가설 채택  
- p-value < 0.05(유의수준): 귀무가설 기각

#### <예제>
두집단의 중위수 차이를 비교하기 위해, 맨휘트니 검정을 실시하였습니다.  
데이터는 다음과 같습니다.
- n= 20
- 명목형 변수(G): Group 
  - A
  - B
- 연속형 변수(X): Score


![Image](https://github.com/user-attachments/assets/1a83bb04-0f02-4355-bfb2-6aaff6fb1451)

#### 시각화 그래프
막대 그래프에서는 집단간 빈도 비교,  
분포 그래프에서는 집단간 분포 비교,   
box plot에서는 집단 간 중위수 비교를 확인하실 수 있습니다.


#### 검정 결과
맨휘트니(two.sided) 분석 결과에서는 p값이 0.3636으로 유의수준인 0.05보다 크므로
귀무가설을 채택 즉, 두 집단의 중위수는 차이가 없는 것으로 판단할수 있습니다.
 

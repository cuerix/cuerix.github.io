---
title: Data Analzyer
author: Scotty
date: 2024-11-11
category: stats
layout: post
---

# Data Analyzer
분석대상 데이터를 틍해 데이터 분석을 할 수 있습니다.
  <center>
 <img width="800" alt="image" src="https://github.com/user-attachments/assets/81e904d5-1ba4-4a8c-91fe-c2f13bf45155">  
  </center>
</br>  


</br>  



<details>
  <summary>데이터 분석 종류 설명</summary>
  <div class="item">
    <div class="item-content">
      <!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <style>
        body {
                   }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th {
            background-color: #003366;
            color: white;
            padding: 10px;
            text-align: left;
        }
        td {
            padding: 10px;
            border: 1px solid #ddd;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        tr:nth-child(odd) {
            background-color: #ffffff;
        }
     /* 첫 번째 열의 너비 설정 */
        th:first-child, td:first-child {
            width: 15%; /* 필요에 따라 %를 조정하여 열 너비를 조정 */
        }    
    </style>
</head>
<body>

<table>
    <tr>
        <th>분석종류</th>
        <th>설명</th>
    </tr>
    <tr>
        <td>기술통계</td>
        <td>사용자가 선택한 분석 대상 항목 조건별로 평균, 중위수, 표준편차, 분산, 왜도, 첨도, 빈도 분석 결과를 제공합니다.<br> 여러 문항에 대한 기술통계를 동시에 도출하거나, 여러 문항을 차원 축소하여 분석할 수 있습니다.<br> 특정 척도나 기준에 맞는 데이터를 추출하여 개별 문항 또는 차원 축소된 상태의 문항에 대한 분석을 수행할 수 있습니다.<br> 예: 특정 조건의 응답자 데이터에 대해 항목별 또는 항목 간 기술통계 분석 수행합니다.</td>     
    </tr>
    <tr>
        <td>IPA 분석</td>
        <td>중요도-성과 분석 (Importance-Performance Analysis)의 약자로, 전통적인 IPA 분석 방법은 중요도와 만족도를 수집하여 4사분면 그래프에 표시하는 방법입니다.<br> 수정된 IPA 분석은 성과와 여러 항목 간의 상관관계 가중치를 중요도로 사용하여 그래프를 생성하며, 만족도나 인식 등 조사 분석의 필수 도구로 쓰입니다.</td>
    </tr>
    <tr>
        <td>정규성 검정</td>
        <td>데이터셋이 정규분포를 따르는지 검정하는 분석입니다. <br>정규성은 분석 결과의 신뢰성 판단을 위해 중요한 전제조건이며, 분석 전 정규성 검정은 필수적입니다.</td>
    </tr>
    <tr>
        <td>등분산 검정</td>
        <td>두 변수 간 분산이 같은지를 확인하여 분석의 신뢰성을 확보하기 위한 절차입니다.</td>
    </tr>
    <tr>
        <td>카이제곱 검정</td>
        <td>명목척도의 빈도가 기대치와 의미 있게 다른지 검정하는 방법입니다.<br> 예: 성별에 따른 혈압 판정 빈도.</td>
    </tr>
    <tr>
        <td>비모수 검정</td>
        <td>데이터가 정규성을 따르지 않거나 표본이 작은 경우 사용할 수 있는 검정 방법입니다.</td>
    </tr>
    <tr>
        <td>t-검정</td>
        <td>두 집단 간 평균의 차이가 유의미한지를 검정하는 방법입니다.</td>
    </tr>
    <tr>
        <td>분산분석</td>
        <td>3개 이상의 그룹 간 평균 차이를 검정하는 방법입니다.</td>
    </tr>
    <tr>
        <td>상관분석</td>
        <td>두 변수 간 관계의 정도를 계수로 나타내는 방법입니다. x와 y 간의 증감 관계를 분석하지만, 인과관계를 설명하지는 않습니다.</td>
    </tr>
    <tr>
        <td>신뢰도 분석</td>
        <td>동일 조건에서 반복 측정 시 결과 간 일관성을 평가하는 방법입니다.</td>
    </tr>
    <tr>
        <td>탐색적 요인분석</td>
        <td>변수들 간의 상관관계를 통해 유사 항목을 하나의 요인으로 차원 축소하는 방법입니다.<br> 요인 적재 절댓값 0.4 이상인 항목을 차원 축소할 수 있으며, 결과는 변수관리로 내보내어 차원 축소된 변수 설정이 가능합니다.</td>
    </tr>
    <tr>
        <td>확인적 요인분석</td>
        <td>사전 설정한 모델을 통해 데이터에 특정 요인 구조가 적합한지 검증하는 방법입니다. <br>분석 결과로 모델 적합도와 경로 그래프를 제공합니다.</td>
    </tr>
    <tr>
        <td>선형회귀</td>
        <td>독립 변수와 종속 변수 간 인과관계를 모델링하여 독립 변수로 종속 변수를 예측하는 기법입니다.<br> 단순회귀와 다중회귀로 구성됩니다.</td>
    </tr>
    <tr>
        <td>NPS 분석</td>
        <td>순추천지수 (Net Promoter Score) 데이터를 수집하고 자동으로 분석하는 방법입니다. 0~10점 척도에서 9~10점 비율과 0~6점 비율을 비교하여 지수를 나타냅니다.</td>
    </tr>
</table>

</body>
</html>
</details>

   


<details>
  <summary>아이콘/메뉴 설명</summary>
  <div class="item">
    <div class="item-content">
    <span class="item-title">분석 이력</span><br>
   분석한 결과내역을 저장하여 관리하실 수 있습니다. <br><br>
    <span class="item-title">통계분석 / 계량 분석</span><br>
   분석 대상 데이터를 활용하여 데이터 분석을 실시할 수 있습니다. <br><br>
    <span class="item-title">About</span><br>
     통계 및 계량 분석의 전체 리스트를 보여줍니다.
</details>


[[목차로 이동]](#index)


</br>  
</br>  


## 기술통계

 사용자가 선택한 분석 대상 항목 조건별로 평균, 중위수, 표준편차, 분산, 왜도, 첨도, 빈도 분석 결과를 제공합니다.<br> 여러 문항에 대한 기술통계를 동시에 도출하거나, 여러 문항을 차원 축소하여 분석할 수 있습니다.<br> 특정 척도나 기준에 맞는 데이터를 추출하여 개별 문항 또는 차원 축소된 상태의 문항에 대한 분석을 수행할 수 있습니다.<br> 예: 특정 조건의 응답자 데이터에 대해 항목별 또는 항목 간 기술통계 분석 수행합니다</strong>와 더불어 <strong>조사/분석 활용법</strong>을 통해 더욱 효과적으로 활용해 보세요!

<center>

![alt text](image-1.png)

</center>

<details>
  <summary>설정 방법</summary>
  <div class="item">
   <div class="item-content">
  ① 분석대상 설정에서 분석할 데이터 변수(열)을 선택합니다.<br>
  ② 분석결과 항목에서 분석방법을 선택합니다. <br>
  ③ 데이터 분석 아이콘을 클릭하여 결과를 확인합니다. <br><br>

  <span class="item-title">조건별 세부 설정</span><br>
  성별이 남성이면서 직급이 상사인 경우"를 설정하는 방법을 예제로 설명하겠습니다. <br><br>
   ① 분석대상 설정에서 분석할 데이터 변수(열)을 선택합니다. <br>
   ② 조건별 세부설정을 클릭합니다. <br>
   ③ 추출 범위 설정에서 성별에 해당하는 변수(열)과 해당 척도인 남성을 선택하고 추출범위에 추가합니다. <br>
   ④ 추출조건에서 교집합 선택합니다. <br>
   ⑤ 직급에 해당하는 변수(열)과 해당 척도인 상사를 선택하고 추출범위에 다시 추가합니다. <br>
   ⑥ 분석결과 항목에서 분석방법을 선택합니다. <br>
   ⑦ 데이터 분석 아이콘을 클릭하여 결과를 확인합니다. <br>
     </div>
</details>



## IPA 분석
 중요도-성과 분석 (Importance-Performance Analysis)의 약자로, 전통적인 IPA 분석 방법은 중요도와 만족도를 수집하여 4사분면 그래프에 표시하는 방법입니다.<br> 
 수정된 IPA 분석은 성과와 여러 항목 간의 상관관계 가중치를 중요도로 사용하여 그래프를 생성하며, 만족도나 인식 등 조사 분석의 필수 도구로 쓰입니다.</td>

<center>

![alt text](image-2.png)

</center>

<details>
  <summary>설정 방법</summary>
  <div class="item">
   <div class="item-content">
  ① 결과변수<br>
  ② 투입변수분석결과 항목에서 분석방법을 선택합니다. <br>
  ③ 분석대상 표본 크기에 따른 상관분석 방법  확인합니다. <br><br>

  <span class="item-title">조건별 세부 설정</span><br>
  성별이 남성이면서 직급이 상사인 경우"를 설정하는 방법을 예제로 설명하겠습니다. <br><br>
   ① 분석대상 설정에서 분석할 데이터 변수(열)을 선택합니다. <br>
   ② 조건별 세부설정을 클릭합니다. <br>
   ③ 추출 범위 설정에서 성별에 해당하는 변수(열)과 해당 척도인 남성을 선택하고 추출범위에 추가합니다. <br>
   ④ 추출조건에서 교집합 선택합니다. <br>
   ⑤ 직급에 해당하는 변수(열)과 해당 척도인 상사를 선택하고 추출범위에 다시 추가합니다. <br>
   ⑥ 분석결과 항목에서 분석방법을 선택합니다. <br>
   ⑦ 데이터 분석 아이콘을 클릭하여 결과를 확인합니다. <br>
     </div>
</details>
<br>
<br>

## 정규성 검정
<strong>정규성 검정</strong>은 주어진 데이터가 정규분포를 따르는지 확인하는 통계적 방법입니다.  
정규성을 가정하는 분석 방법을 사용할 때, 데이터가 정규분포에 얼마나 부합하는지 검토하는 과정이 필요합니다.  
 정규성을 따르지 않는 경우, 비모수적 방법을 고려하거나 데이터 변환을 적용할 수 있습니다.

### 검정 종류
정규성 검정에서 자주 사용되는 세 가지 방법은 다음과 같습니다.

- #### 샤피로-윌크 검정(Shapiro-Wilk Test)
  샤피로-윌크 검정은 데이터가 정규분포를 따르는지 검정하는 가장 일반적인 방법 중 하나로, 표본 크기가 작은 경우에도 유용합니다.

- #### 단일 표본 콜모고로프-스미르노프 검정(One-Sample Kolmogorov-Smirnov Test)
  이 검정은 데이터가 특정 분포(보통 정규분포)를 따르는지 확인하기 위해 누적분포함수(CDF)를 비교하는 방식입니다.
- #### 이표본 콜모고로프-스미르노프 검정(Two-Sample Kolmogorov-Smirnov Test)
  두 개의 데이터 집합이 동일한 분포를 가지는지 확인하는 데 사용됩니다. 이를 통해 두 집단 간의 분포 차이를 검정할 수 있습니다.
<center>

![alt text](image-3.png)
</center>

<details>
  <summary>변수 설정방법</summary>
  <div class="item">
    <div class="item-content">
    ① 분석할 연속형 변수(열) 선택합니다. <br>
    ② 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다. <br>
</details>
</br> 




 ## 등분산 검정
<strong>등분산 검정</strong>은 여러 그룹 간의 분산이 서로 동일한지 여부를 확인하는 통계적 방법입니다.<br>
등분산성은 분산 분석(ANOVA)과 같은 분석에서 중요한 가정입니다.<br>
만약 그룹 간 분산이 동일하지 않다면, 일부 분석 결과가 왜곡될 수 있으므로 비모수적 방법을 고려하거나 데이터를 변환해야 할 수 있습니다.

### 검정 종류
대표적인 등분산 검정 방법 두 가지는 다음과 같습니다.

- <strong>바틀렛 검정(Bartlett Test)</strong><br>
  바틀렛 검정은 그룹 간의 분산이 정규성을 따를 때 사용됩니다. <br>
  이 검정은 데이터가 정규분포를 따르는 경우에 효과적이며, 분산이 동일한지를 확인하는 데 민감합니다.<br>

- <strong>르빈 검정(Levene Test)</strong><br>
  르빈 검정은 데이터의 정규성에 민감하지 않은 방법으로, 바틀렛 검정보다 더 널리 사용됩니다.<br>
  이는 분산이 정규분포를 따르지 않는 경우에도 적용할 수 있는 검정입니다.

<center>

![alt text](image-4.png)
</center>

<details>
  <summary>변수 설정방법</summary>
  <div class="item">
    <div class="item-content">
    ① 분석할 연속형 변수(열) 선택합니다.<br>
    ② 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다. <br>
</details>
</br> 
        
 ## 카이제곱 검정
<strong>카이제곱 검정</strong>은 범주형 데이터 간의 관계나 분포를 분석하는 데 사용하는 통계적 검정 방법입니다.<br>
이 검정은 관찰된 빈도와 기대되는 빈도 간의 차이를 분석하여 두 변수 간의 독립성이나 분포의 적합성을 확인하는 데 주로 사용됩니다.<br>

### 검정 종류
카이제곱 검정에는 대표적으로 다음 세 가지가 있습니다

- #### 적합성 검정(Goodness of Fit Test)
  적합성 검정은 한 집단의 데이터 분포가 기대되는 이론적 분포(예: 균등 분포, 정규 분포)와 일치하는지를 평가합니다.<br>
 이를 통해 주어진 표본이 가설로 설정한 분포와 얼마나 유사한지를 확인합니다.
- #### 동질성 검정(Test of Homogeneity)
  동질성 검정은 서로 다른 두 개 이상의 집단이 동일한 분포를 가지는지 확인하는 데 사용됩니다. 이는 주로 그룹 간 차이를 비교할 때 유용하며, 각 집단이 동일한 조건에서의 분포를 따르는지 확인합니다.
- #### 독립성 검정(Test of Independence)
  독립성 검정은 두 범주형 변수 간의 관계를 확인하여, 두 변수가 서로 독립적인지 아니면 연관이 있는지를 검정합니다.

<center>

![alt text](image-5.png)
</center>

<details>
  <summary>변수 설정방법</summary>
  <div class="item">
    <div class="item-content">
    ① 분석할 범주형 변수(열) 선택합니다.<br>
    ② 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다. <br>
</details>
</br> 


 ## 비모수 검정
<strong>비모수 검정</strong>은 데이터가 특정 분포(예: 정규분포)를 따르지 않는 경우에 사용하는 통계적 분석 방법입니다.  
 비모수 검정은 데이터의 분포에 대한 가정이 필요하지 않으므로, 모수 검정(parametric test)보다 유연하게 적용할 수 있습니다.  
 특히 데이터가 비대칭적이거나 극단값(outliers)이 많을 때 유용하며, 표본 크기가 작거나 측정 척도가 순위형(ordinal scale)일 때 주로 사용됩니다.

### 검정 종류
대표적인 비모수 검정 방법은 다음과 같습니다

- #### 맨-휘트니 U 검정(Mann-Whitney U Test)
  두 집단의 중위수가 동일한지를 검정하는 방법으로, 독립된 두 집단 간의 차이를 비교할 때 사용됩니다.  
이는 모수적 검정인 독립표본 t-검정의 비모수적 대안입니다.

- #### 윌콕슨 부호 순위 검정(Wilcoxon Signed-Rank Test)

  대응되는 두 집단 간의 차이를 검정하는 방법입니다.  
  대응표본 t-검정의 비모수적 대안으로, 예를 들어 같은 집단에서 처리 전후의 변화를 비교할 때 사용됩니다.

- #### 크루스칼-월리스 검정(Kruskal-Wallis Test)

  세 개 이상의 독립 집단 간 차이를 검정하는 방법으로, 일원분산분석(ANOVA)의 비모수적 대안입니다.  
  각 집단의 중위수가 동일한지를 확인합니다.

- #### 프리드만 검정(Friedman Test)

  반복 측정된 세 개 이상의 집단 간 차이를 검정하는 방법입니다.  
  반복 측정 분산분석(repeated measures ANOVA)의 비모수적 대안으로, 같은 집단 내에서 여러 조건을 비교할 때 사용됩니다.  
  비모수 검정은 데이터 분포에 대한 가정이 적어 다양한 상황에 활용 가능하지만, 모수 검정보다 검정력이 낮을 수 있습니다.

<center>

![alt text](image-6.png)
</center>

<details>
  <summary>변수 설정방법</summary>
  <div class="item">
      <div class="item-content">
      <span class="item-title">맨-휘트니 U 검정</span><br>
    ① 분석방법에서 대립가설 및 p값 설정방법을 선택합니다.<br>
    ② 두 집단에 해당하는 범주형 변수(열)을 선택합니다.<br>
    ③ 분석하고자하는 값인 연속형 변수(열)을 선택합니다. <br>
    ④ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다. <br><br>
      <span class="item-title">윌콕슨 부호 순위 검정</span><br>
    ① 분석방법에서 대립가설 및 p값 설정방법을 선택합니다.
    ② 사전/사후에 분석하고자하는 값인 연속형 변수(열)을 각각 선택합니다.<br>
    ③ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.<br><br>
     <span class="item-title">크루스칼-월리스 검정</span><br>
    ① 세 집단에 해당하는 범주형 변수(열)을 선택합니다.<br>
    ② 분석하고자 하는 값인  연속형 변수(열)을 선택합니다.<br>
    ③ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다. <br><br>
     <span class="item-title">프리드만 검정</span><br>
    ① 반복횟수에 해당하는 범주형 변수(열)을 선택합니다.<br>
    ② 반복 측정 대상 범주형 변수(열)을 선택합니다.<br>
    ③ 반복측정 결과 연속형 변수(열)을 선택합니다.<br>
    ④ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.<br> <br>
</details>
</br> 

 ## t-검정
<strong>t-검정(t-test)</strong>은 두 집단의 평균 차이를 비교하여 유의미한 차이가 있는지 검정하는 통계적 방법입니다.  
일반적으로 데이터가 정규분포를 따른다는 가정하에 사용되며, 표본의 평균이 모집단의 평균과 얼마나 차이가 나는지를 확인하거나 두 집단 간의 평균 차이를 분석할 때 주로 사용됩니다.

### 검정 종류
t-검정의 유형은 분석 목적과 데이터 특성에 따라 다음과 같이 나눌 수 있습니다

- #### 단일 표본 t-검정(One-Sample t-test)

  표본의 평균이 특정 값(모집단의 평균 등)과 유의미하게 다른지 검정합니다.

- #### 독립 표본 t-검정(Independent Samples t-test)

  서로 독립적인 두 집단의 평균 차이를 비교합니다.  
  두 집단 간의 관계가 없는 경우에 사용됩니다.

- #### 대응 표본 t-검정(Paired Samples t-test)

  같은 집단의 두 조건(또는 시간) 간 평균 차이를 검정합니다.  
   즉, 같은 대상에서 반복적으로 측정된 데이터의 차이를 분석하는 경우에 사용됩니다.

<details>
  <summary>변수 설정 방법</summary>
  <div class="item">
    <div class="item-content">
      <span class="item-title">단일 표본</span><br>
      ① 분석할 연속형 변수(열)을 선택합니다.<br>
      ② 예측하는 모평균 값을 입력하고 대립 가설을 설정합니다.<br>
      ③ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.<br><br>
      <span class="item-title">독립 표본</span><br>
      ① 두 집단에 해당하는 범주형 변수(열)을 선택합니다.<br>
      ② 분석하고자 하는 값인 연속형 변수(열)을 선택합니다.<br>
      ③ 대립 가설을 설정합니다.<br>
      ④ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.<br><br>
      <span class="item-title">대응 표본</span><br>
      ① 두 집단에 대응 되는 범주형 변수(열)을 선택합니다.<br>
      ② 분석하고자 하는 값인 연속형 변수(열)을 선택합니다.<br>
      ③ 대립 가설을 설정합니다.<br>
      ④ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.<br><br>
    </div>
</details>
<br>
<br>

## 상관 분석
<strong>상관분석</strong>은 두 변수 간의 관계를 측정하고 평가하는 통계적 방법입니다.  
이를 통해 한 변수의 변화가 다른 변수의 변화와 어떻게 관련되는지, 즉 두 변수 간의 연관성의 방향과 강도를 확인할 수 있습니다.

### 상관관계의 유형
상관관계는 방향과 강도에 따라 다음과 같은 유형으로 구분됩니다.

- #### 양의 상관관계 (Positive Correlation)

  두 변수 간에 같은 방향으로 변화가 일어납니다.    
  상관계수는 0에서 1 사이의 양수 값을 가지며, 값이 1에 가까울수록 강한 양의 상관을 의미합니다.  
  ex) 키가 클수록 몸무게가 증가하는 경우

- #### 음의 상관관계 (Negative Correlation)

  두 변수 간에 반대 방향으로 변화가 일어납니다.  
상관계수는 -1에서 0 사이의 음수 값을 가지며, 값이 -1에 가까울수록 강한 음의 상관을 의미합니다.  
ex)운동 시간이 증가할수록 체지방률이 감소하는 경우  

- #### 무상관 (No Correlation)
  두 변수 간에 규칙적인 관계가 없는 경우로, 한 변수의 변화가 다른 변수에 아무런 영향을 주지 않는 관계입니다.  
상관계수가 0에 가까운 값이며, 두 변수 간에 선형적인 연관이 거의 없음을 의미합니다.  
ex) 사람의 키와 휴대전화 사용 시간과의 관계.


### 검정 종류
상관관계를 평가하는 대표적인 방법은 다음과 같습니다.

- #### 피어슨 상관계수(Pearson Correlation Coefficient)

  두 변수 간의 선형 관계를 측정하며, 연속형 변수와 정규분포를 가정합니다. 상관계수 값은 -1에서 1 사이의 값을 가지며, 1에 가까울수록 강한 양의 상관, -1에 가까울수록 강한 음의 상관을 의미합니다.

- #### 스피어만 상관계수(Spearman Rank Correlation Coefficient)

  순위형 자료나 비선형 관계에서도 적용 가능한 방법으로, 두 변수 간의 비선형 순위 관계를 측정합니다. 피어슨 상관계수와 달리, 정규성을 가정하지 않습니다.

- #### 켄달의 타우(Kendall’s Tau)
  두 변수의 순위 일치 정도를 평가하는 방법으로, 순위형 데이터나 작은 표본에서 사용하기 적합합니다. 스피어만 상관계수와 유사하지만, 작은 표본이나 자료에 대한 민감도가 높습니다.

<center>

![alt text](image-7.png)

</center>

<details>
  <summary>변수 설정 방법</summary>
  <div class="item">
    <div class="item-content">
      ① 분석할 연속형 변수(열)을 선택합니다.<br>
      ② 변수 종류에 따른 분석방법을 선택합니다.<br>
      ③ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.<br>
      </div>
</details>
<br>
<br>



## 신뢰도 분석
<strong>신뢰도 분석(reliability analysis)</strong>은 측정 도구나 설문지가 일관되게 동일한 결과를 도출할 수 있는지를 평가하는 통계적 방법입니다.  
이는 도구나 설문지의 일관성(consistency)과 재현성(reliability)을 확인하는 데 사용됩니다.  
신뢰도 분석을 통해 측정 도구가 반복적으로 일관된 결과를 낼 수 있는지, 즉 신뢰할 수 있는지를 평가합니다.

신뢰도 분석에서 중요한 지표는 신뢰도 계수(reliability coefficient)로, 보통 0과 1 사이의 값을 가지며, 값이 1에 가까울수록 더 높은 신뢰도를 나타냅니다.

### 검정종류

크론바흐 알파(Cronbach's Alpha)
설문 항목들이 동일한 개념을 측정하는지, 즉 내부 일관성(internal consistency)을 평가합니다.  
보통 설문 문항이 여러 개 있을 때, 이 문항들이 얼마나 일관된 답변을 도출하는지 확인합니다.
일반적으로 0.7 이상이면 신뢰도가 높다고 간주되며, 0.8 이상이면 매우 높은 신뢰도를 가진다고 해석합니다.  
1에 가까운 값은 매우 높은 일관성을 의미합니다.
<center>

![alt text](image-8.png)
</center>

<details>
  <summary>변수 설정 방법</summary>
  <div class="item">
    <div class="item-content">
      ① 분석할 연속형 변수(열)을 선택합니다.<br>
      ② 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.<br>
      </div>
</details>
<br>
<br>

## 분산 분석
<strong>분산분석(Analysis of Variance, ANOVA)</strong>은 세 개 이상의 집단 간의 평균 차이를 검정하는 통계적 방법입니다.  
이 방법은 각 집단의 평균이 동일한지 여부를 확인하는 데 사용되며, 집단 간 차이가 우연에 의한 것인지, 아니면 실제로 의미 있는 차이가 존재하는지를 평가합니다.

분산분석은 모집단이 정규분포를 따른다는 가정 하에 사용되며, 두 집단 간 차이를 비교하는 t-검정의 확장 개념으로 이해할 수 있습니다.  
ANOVA는 집단 간의 분산이 집단 내 분산과 비교되어 차이가 유의미한지를 평가합니다.

### 검정 종류

#### 일원 분산분석 (One-Way ANOVA)
하나의 독립 변수(또는 요인)가 세 개 이상의 집단에 미치는 영향을 평가합니다. 
각 집단의 평균이 동일한지 여부를 검정합니다.  
ex) 세 가지 다른 학습법이 학생들의 시험 성적에 미치는 영향을 비교할 때 사용됩니다.

#### 이원 분산분석 (Two-Way ANOVA)

두 개의 독립 변수가 종속 변수에 미치는 영향을 평가하며, 두 변수 간의 상호작용도 고려합니다.  
ex) 성별과 학습 방식이 학생들의 성적에 미치는 영향을 비교하고, 두 변수 간의 상호작용 효과를 분석할 때 사용됩니다.

#### 반복측정 분산분석 (Repeated Measures ANOVA)

같은 대상에서 반복적으로 측정된 데이터를 사용하여 평균 차이를 평가합니다.  
보통 시간에 따른 변화나 처리 전후의 차이를 분석하는 데 사용됩니다.  
ex) 약물의 효과를 평가하기 위해 동일한 환자들에게 여러 차례 치료를 적용한 후 결과를 비교할 때 사용됩니다.

<br>

### 분산분석의 주요 개념

#### 집단 간 분산 (Between-group variance)
각 집단의 평균이 전체 평균과 얼마나 차이가 나는지를 나타냅니다.

#### 집단 내 분산 (Within-group variance)
각 집단 내 개별 데이터가 그 집단의 평균과 얼마나 차이가 나는지를 나타냅니다.

분산분석은 집단 간 차이를 분석하는 데 강력한 도구지만, 집단 간 차이가 유의미한 경우 <strong>사후 분석(post hoc tests)</strong>을 통해 어떤 집단 간에 차이가 있는지를 추가적으로 확인해야 합니다.

<center>

![alt text](image-9.png)
</center>

<details>
  <summary>변수 설정방법</summary>
  <div class="item">
      <div class="item-content">
    <span class="item-title">일원배치 분산분석</span><br>
  ① 분석할 연속형 변수(측정 대상)를 선택합니다.<br>
  ② 집단을 구분하는 범주형 변수를 선택합니다.<br>
  ③ 데이터 분석 아이콘을 클릭해 결과를 확인합니다.<br><br>
  
  <span class="item-title">일원배치 분산분석 (반복측정)</span><br>
  ① 분석할 연속형 변수(측정 대상)를 선택합니다.<br>
  ② 반복측정을 위한 범주형 변수를 선택합니다.<br>
  ③ 데이터 분석 아이콘을 클릭해 결과를 확인합니다.<br><br>
  
  <span class="item-title">이원 분산분석</span><br>
  ① 분석할 연속형 변수(측정 대상)를 선택합니다.<br>
  ② 집단을 구분하는 두 개의 범주형 변수를 각각 선택합니다.<br>
  ③ 데이터 분석 아이콘을 클릭해 결과를 확인합니다.<br><br>
  
  <span class="item-title">이원분산분석 (반복측정)</span><br>
  ① 분석할 연속형 변수(측정 대상)를 선택합니다.<br>
  ② 집단 간 비교를 위한 범주형 변수(G1)와 시간 경과를 나타내는 범주형 변수(T1)를 각각 선택합니다.<br>
  ③ 데이터 분석 아이콘을 클릭해 결과를 확인합니다.<br>
</details>
<br>
<br>


## 변수 관리
변수 관리란, 데이터 분석 과정에서 사용되는 변수들의 생성, 수정, 관리를 담당하는 과정입니다.  

- #### 데이터 변수(열) 정보
  현재 데이터에 있는 변수(열)에 대한 정보를 확인할 수 있습니다.  
데이터셋에서 각 변수의 특성을 이해하고, 필요한 변수들을 선택하여 분석에 활용할 수 있습니다.

- #### 변수 관리 목록  
  차원 축소 변수와 데이터 변환 변수의 구성 정보를 확인할 수 있습니다  
이를 통해 어떤 방식으로 변수들이 변환되었는지, 또는 차원 축소가 어떻게 이루어졌는지 등을 점검할 수 있습니다.

- #### 차원 축소 변수 등록  
  여러 변수(열)들을 하나의 차원으로 축소로 등록하여 분석을 실시할수 있습니다.  
탐색적 요인분석에서 추천된 변수를 등록하여 확인적 요인분석을 실시해보세요.

- #### 데이터 변환 등록
  데이터 변환을 통해 새 변수를 추가할 수 있는 기능을 제공합니다.  
예를 들어 더미, 로그, 제곱근 등을 통해 데이터를 변환 후, 새로운 변수로 추가하여 분석에 활용할 수 있습니다.
<br>
<br>
<center>

![alt text](image-13.png)

</center>



<details>
  <summary>변수 설정방법</summary>
  <div class="item">
      <div class="item-content">
    <span class="item-title">차원축소 등록</span><br>
  <strong>요인분석 추천 변수정보 </strong><br>
  탐색적 요인분석 결과에서 추천 변수정보로 등록한 경우, 다음과 같이 차원축소로 등록하실 수 있습니다.<br>
  ① 요인분석(EFA/CFA) 추천변수 아이콘을 클릭합니다.<br>
  ② 축소변수로 등록할 변수를 선택 후, 변수명 입력, 점수 부여방법을 설정합니다.<br>
  ③ 확인을 클릭하고 데이터 분석 아이콘을 클릭해 결과를 확인합니다.<br>
  ④ 등록된 변수를 적용하여 저장을 클릭하면 변수관리 목록으로 이동합니다.<br><br>
  <strong>새로운 차원 축소 변수등록</strong> <br> 
  ① 축소변수로 등록할 변수명 입력과 변수를 선택 후, 변수점수 부여방법을 설정합니다.<br>
  ② 확인을 클릭하고 데이터 분석 아이콘을 클릭해 결과를 확인합니다.<br>
  ③ 등록된 변수를 적용하여 저장을 클릭하면 변수관리 목록으로 이동합니다.<br><br>
     <span class="item-title">데이터 변환 등록</span><br>
  ① 새로운 데이터 변환 변수등록 아이콘을 클릭합니다.<br>
  ② 데이터 변환할 변수명 입력과 변수를 선택 후, 데이터 변환방법을 설정합니다.<br>
  ③ 확인을 클릭하고 데이터 분석 아이콘을 클릭해 결과를 확인합니다.<br>
  ④ 등록된 변수를 적용하여 저장을 클릭하면 변수관리 목록으로 이동합니다.<br>

</details>
<br>
<br>

## 탐색적 요인 분석
<strong>탐색적 요인분석(Exploratory Factor Analysis, EFA)</strong>은 여러 변수들이 서로 관련되어 있을 때, 이들 변수들을 몇 개의 잠재적인 요인(factor)으로 묶어내는 통계적 기법입니다. 즉, 데이터를 기반으로 변수들 간의 내재된 구조나 패턴을 발견하는 데 사용됩니다. 주로 설문조사나 심리학적 평가 등에서, 많은 변수들(항목)이 공통된 잠재적 요인에 의해 영향을 받는다고 가정할 때 사용됩니다.

탐색적 요인 분석은 "요인"이라는 잠재적 구조를 추정하고, 각 변수들이 이러한 요인들과 얼마나 관계가 있는지를 파악합니다. EFA는 모델링 기법으로, 사전 가설 없이 데이터에서 요인을 추출하는 데 초점을 둡니다.
<center>

![alt text](image-10.png)
</center>

<details>
  <summary>아이콘/메뉴 설명</summary>
  <div class="item">
    <div class="item-content">
        <span class="item-title">추출 요인 수</span><br>
몇 개의 요인을 추출할지를 결정하는 기준으로, 스크리 테스트나 고유값 기준을 사용합니다.<br><br>
    <span class="item-title">요인 적재값 표시기준</span><br>
변수와 요인의 관계 강도를 나타내는 값의 기준을 설정하며, 보통 0.3 이상의 값을 사용합니다.<br><br>
<span class="item-title">요인 추출</span><br>
데이터에서 요인을 식별하는 과정입니다.<br><br>
    <span class="item-title">요인 회전</span><br>
추출된 요인들의 해석 가능성을 높이기 위한 과정으로, 직교 회전과 사선 회전 방법이 있습니다.<br>
     </div>
</details>
<details>
  <summary>변수 설정 방법</summary>
  <div class="item">
    <div class="item-content">
      ① 분석할 연속형 변수(열)을 선택합니다.<br>
      ② 요인분석 옵션에서 추출할 요인 수와 요인 적재값 표시기준을 설정합니다.<br>
      ③ 요인추출방법과 요인회전 방법을 설정합니다.<br>
      ④ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.<br>
      </div>
</details>
<details>
  <summary>추천 변수정보로 등록</summary>
  <div class="item">
    <div class="item-content">
    분석 결과에서 등록할 변수를 선택하고, '추천변수 정보로 등록' 아이콘을 클릭합니다.<br>
       </div>
</details>

<br>
<br>

<br>
<br>


## 확인적 요인 분석
<strong>확인적 요인분석(Confirmatory Factor Analysis, CFA)</strong>은 탐색적 요인분석(Exploratory Factor Analysis, EFA)과는 달리, 이미 가설을 바탕으로 특정한 요인 구조가 데이터를 잘 설명하는지를 검증하는 분석 기법입니다.  
즉, CFA는 연구자가 설정한 요인 구조가 실제 데이터와 얼마나 잘 맞는지를 검증하는 과정으로, 사전에 정의된 요인 모델이 적합한지 확인하는 데 사용됩니다.

<center>

![alt text](image-11.png)

</center>


<details>
  <summary>변수 설정 방법</summary>
  <div class="item">
    <div class="item-content">
      ① 체크박스에서 선택후, 잠재변수명을 입력하고 관측변수에서 해당하는 변수(열)을 선택합니다.<br>
      ③ '변수 추가' 아이콘을 클릭하여 잠재변수를 추가합니다.<br>
      ④ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.<br>
      </div>
</details>
<br>
<br>


## 선형 회귀
<strong>회귀분석(Regression Analysis)</strong>은 하나 또는 여러 독립 변수(설명 변수)가 종속 변수(결과 변수)에 미치는 영향을 분석하는 통계 기법입니다. 회귀분석은 변수들 간의 관계를 모델링하여 예측을 하거나, 인과관계를 이해하려는 데 사용됩니다.

### 회귀분석의 주요 목적
- 예측: 독립 변수들이 주어졌을 때 종속 변수의 값을 예측합니다.  
- 인과 관계 분석: 독립 변수가 종속 변수에 미치는 영향을 분석하여, 변수들 간의 관계를 이해합니다.    
- 모델 평가: 예측 모델의 적합도를 평가하고, 변수들의 중요성을 확인합니다.

### 회귀분석의 종류
- #### 단순 회귀분석 (Simple Linear Regression)
  하나의 독립 변수와 하나의 종속 변수 간의 선형 관계를 모델링하는 분석 방법입니다.  
예) 공부 시간(독립 변수)과 성적(종속 변수)의 관계를 모델링할 때 사용됩니다.


- #### 다중 회귀분석 (Multiple Linear Regression)

  여러 독립 변수가 종속 변수에 미치는 영향을 분석하는 방법입니다.  
여러 개의 독립 변수들이 종속 변수에 미치는 영향을 동시에 평가합니다.  
예) 광고비, 판매 전략, 시즌별 차이 등을 고려하여 매출(종속 변수)을 예측할 때 사용됩니다.

<center>

![alt text](image-12.png)
</center>

 <details>
  <summary>변수 설정 방법</summary>
  <div class="item">
    <div class="item-content">
    <span class="item-title">단순 회귀</span><br>
      ① 종속변수에 해당하는 연속형 변수(열)을 선택합니다.<br>
      ② 독립변수에 해당하는 연속형 변수(열)을 선택합니다.<br>
      ③ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.<br><br>
    </div>

   <div class="item-content">
    <span class="item-title">다중 회귀</span><br>
      ① 종속변수에 해당하는 연속형 변수(열)을 선택합니다.<br>
      ② 독립변수에 해당하는 연속형 변수(열)을 선택합니다.<br>
      ③ 변수추가 아이콘을 클릭하여 독립변수를 추가합니다.<br>
      ③ 다중회귀 변수추가 아이콘을 클릭하여 독립변수를 추가합니다.<br>
      ④ 데이터 분석 아이콘을 클릭하여 분석 결과를 확인합니다.<br>
      </div>
      </details>
<br>
<br>
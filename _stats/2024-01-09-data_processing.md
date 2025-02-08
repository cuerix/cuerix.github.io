---
title: 데이터 전처리
author: Scotty
date: 2024-11-11
category: stats
layout: post
---
### 개요

#### 📌 전처리 규칙 기능
- [전처리 규칙이란?](#전처리-규칙이란?)
- [전처리 규칙 등록](#전처리-규칙-등록) 
- [큐릭스가 제공하는 전처리 규칙 가져오기](#큐릭스가-제공하는-전처리-규칙-가져오기) 
- [전처리 규칙 등록 방법](#전처리-규칙-등록-방법) 

---

### 전처리 규칙이란?  
<strong>전처리 규칙</strong>은 <strong>문자척도</strong>로 수집한 설문조사 데이터를 통계분석을 위해 <strong>숫자 척도로 교체</strong>하는 규칙을 등록 또는 관리합니다.    
예를 들어 설문조사에 사용한 `매우 그렇다`, `그렇다`, `보통`, `그렇지 않다`, `전혀 그렇지 않다`라는 5점 등간척도는 응답자에게 노출된 문자 척도 그대로 데이터가 수집됩니다.    
그런데 이렇게 수집한 문자 척도는 평균, 분산, 표준편차 등을 구할 수 없는 상태입니다. 따라서 이들 척도를 숫자 척도로 변경할 필요가 있습니다.    
전처리 규칙은 이들 척도를 숫자 척도로 어떻게 변경할 것인가를 사전에 등록하고, 분석 대상 데이터에 규칙을 연결한 후 새 이름으로 저장(내보내기) 하여 데이터 분석을 수행하는데 필요한 첫 번째 필요자료 생성과정입니다.  
  
<div style="border: 1px solid #1DA1F2; padding: 15px; border-radius: 5px; background-color: #E8F5FD; color: #333;">
<strong>ℹ️</strong>사용자는 등간 척도 등 점수 척도가 필요한 경우, 반드시 <strong>[기본규칙 가져오기]</strong>를 통해 전처리 기본규칙을 생성한 후, 설문지를 디자인해야 합니다. 기본규칙 외에 별도의 점수 척도 변환이 필요한 경우, 해당 척도를 척도 셋에 등록한 후 설문지를 디자인하십시오. <span style="color:red">&#8251;설문지 디자인에 사용한 척도 셋과 전처리 규칙에 등록된 척도 셋이 일치해야만 문자 척도를 점수 척도로 전환할 수 있습니다. </span> </div>
         
<br>

<center>
<div style="border: 1px solid grey; width: fit-content;">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/f8925c60-f849-4719-964b-23815b377d15">
</div>
</center>

#### 🗂️ 아이콘/메뉴 설명

|메뉴/아이콘|설명|
|------|---|
|![Image](https://github.com/user-attachments/assets/02948537-5040-44f8-93ff-13bfb4249bc9)|큐릭스에서 제공하는 기본 전처리 규칙으로, 설문 디자인의 '척도 예제'에서 사용된 문자척도를 수치척도로 전환한 규칙입니다. |
|![Image](https://github.com/user-attachments/assets/516800e4-a8fc-43cf-a63f-82e5fc92343a)|새로운 규칙을 등록합니다. 설문디자인의 척도예제를 활용하지 않고, 직접 입력한 경우 새로운 규칙을 통해서 전처리 규칙을 연결할 수 있습니다.|
|![Image](https://github.com/user-attachments/assets/c3bcddf9-c1fc-4531-b15a-6e82306a7f31)|동기화 기능입니다. |




 <div style="border: 1px solid #FFD700; padding: 15px; border-radius: 5px; background-color: #FFFACD; color: #333;">
 💡 등록한 전처리 규칙을 분석 대상 데이터에 연결하세요.
</div>

---

### 전처리 규칙 등록
전처리 규칙 등록에서는 해당 문항에 대한 결측치 처리 및 문자척도를 숫자척도로 전환하여 원활한 데이터 분석을 실시 할수 있습니다.
#### 🔑 전처리 규칙의 적용 원칙
사용자는 분석 대상 데이터 상세 보기에서 전처리 해당 분석 대상 데이터에 여러 개의 규칙을 연결하고, 연결된 규칙 중 1개의 규칙을 선택하여 전처리 규칙을 적용한 분석 대상 데이터를 다른 이름으로 저장해 데이터 분석을 수행할 수 있습니다. 
 
  <center>
<div style="border: 1px solid grey; width: fit-content;">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/1ab9ae5d-e2b1-425e-83fc-5f56d1e8e9c2">  
</div>
</center>
    
#### 🗂️ 아이콘/메뉴 설명

|메뉴/아이콘|설명|
|------|---|
|결측지 처리|데이터에 결측지가 있는 경우, 결측지 유지하거나, 행을 삭제, 지정한 데이터로 모두 교체할 수 있습니다.|
|![Image](https://github.com/user-attachments/assets/4cef5c80-78e8-4c92-9931-82372292633e)|추가 변경할 척도 셋을 추가하는 버튼입니다. |

---

### 큐릭스가 제공하는 전처리 규칙 가져오기
Survey Canvas에서 설문지를 디자인할 때, 1개 선택에서 척도찾기를 통해 디자인 한 경우, 척도찾기의 예제에 맞게 설정한 전처리 규칙을 사용하시면 편리합니다. 

### 기본 규칙 가져오는 방법
![Image](https://github.com/user-attachments/assets/deefd818-2bad-49ca-a468-374ae5bfec22)   
➊ 상단에 데이터 전처리 기본규칙 가져오기 아이콘을 선택합니다.
  

---

### 전처리 규칙 등록 방법  

![Image](https://github.com/user-attachments/assets/1d5de6d6-bb49-4289-81ba-761b6c122b32)  
➊ 상단에 <img src="https://github.com/user-attachments/assets/516800e4-a8fc-43cf-a63f-82e5fc92343a" width="5%"> 아이콘을 클릭합니다.  
  
  
![Image](https://github.com/user-attachments/assets/14a7dcbb-f123-4eff-8675-45f525c1354e)

➋ <strong>전처리 규칙 정의명</strong>을 입력합니다.    
  
➌ <strong>결측치 처리 방식</strong>을 설정합니다.   
-  결측치 처리에서는 결측치가 있는 경우, 결측지를 유지하거나 행을 삭제 또는 지정한 데이터로 모두 교체할 수 있습니다.
  
➍ 좌측에는 **문자척도 데이터**와 우측에는 교체할 **수치척도 데이터**를 각각 입력합니다.  
  

![Image](https://github.com/user-attachments/assets/5a3ee06d-dd4b-4e91-a741-99e6eea64edd)  
➎ 추가 변경할 척도가 있다면 상단 우측에 <img src="https://github.com/user-attachments/assets/4cef5c80-78e8-4c92-9931-82372292633e" width="5%"> 아이콘을 클릭하여 추가 입력합니다.  
  
➏ 설정이 끝났으면 <img src="https://github.com/user-attachments/assets/cbcb9ea5-d235-4801-8b35-aa3ac5102122" width="5%">을 클릭합니다.




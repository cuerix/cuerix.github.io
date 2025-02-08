---
title: 설문 디자인
author: Scotty
date: 2024-11-11
category: stats
layout: post
---



## 개요
<strong>설문 디자인</strong>에서는 Survey Canvas의 설문 도구를 활용하여 설문지를 디자인하고, 이를 바탕으로 설문 배포 설정을 통해 설문 조사를 진행할 수 있습니다.

    

#### 📌 설문지 디자인 기능
- [설문 디자인 메인 화면](#설문지-디자인-메인-화면)
- [Survey Canvas](#Survey-Canvas) 
- [설문지 기본정보](#설문지-기본정보)
- [문항 간 건너뛰기 설정](#문항-간-건너뛰기-설정)
- [설문조사 설정](#설문조사-설정)
- [빠른분석 설정](#빠른-분석-설정)

### 순서
- [x]  **설문 디자인**  
- [ ]  설문 조사 설정  
- [ ]  설문 조사 진행  
- [ ]  전처리 규칙  
  [ ]  데이터 분석  

--

### 설문지 디자인 메인 화면

설문지 디자인 메인화면에서는 디자인한 설문지를 관리하는 곳으로 새로운 설문지 등록하거나 삭제 또는 설문지 작성을 위한 Survey Canvas 기능이 있습니다.

<center>
<img width="800" alt="image" src="https://github.com/user-attachments/assets/91d233fe-2021-42de-8012-e625b39658c0"> 	
</center>

#### 메뉴 아이콘 설명

##### 🆕 새로 만들기
새로운 설문지를 생성합니다.

##### 🔄  새로고침
동기화 기능입니다.
 
##### 🖌️ 설문지 디자인 상태  

- ##### ❌ No Design 
설문지 이름만 등록하고 문항을 디자인하지 않은 상태입니다.   

- ##### ⏳ Design(Ing)  
설문지 문항을 디자인하고 있습니다. 
Design(Ing) 상태 표시는 No Design 상태에서 설문 문항을 등록하면 자동으로 변환되지만, 설문조사 설정을 위해서는 사용자가 설문지 기본정보에서 Complete로 변경해야 합니다. Complete는 같은 페이지와 방법으로 Design(Ing)로 변경할 수 있습니다.

- ##### ✅ Complete  
설문지 디자인을 완료해 설문조사를 시작할 수 있는 상태입니다.  
Complete 상태 표시는 설문지 이름을 클릭하고 나타난 상세보기에서 사용자가 직접 상태 표시를 Complete로 변경해야 합니다.  

##### 🎨 Survey Canvas
설문지 디자인을 할 수 있는 Survey Canvas로 이동합니다.
    
##### 🗑️ 휴지통
설문지를 삭제합니다. 

 
<br>
<div style="border: 1px solid #FFD700; padding: 15px; border-radius: 5px; background-color: #FFFACD; color: #333;">
 💡   새로운 설문지를 등록하였으면, 설문 디자인을 위해 <strong>Survey Canvas</strong>으로 이동 하세요.
</div>

  
#### ➕ 새로운 설문지 만들기  
![Image](https://github.com/user-attachments/assets/b5ddfa83-71ef-46ae-82e5-dbdabc242278)  

 ➊ 우측 상단에 <img src="https://github.com/user-attachments/assets/2d9e66c5-a2e7-4072-af99-7d6e4231114f" width="7%"> 아이콘을 클릭합니다.   
 ➋ 설문지 이름을 입력하고 확인을 클릭합니다.  


#### 🔗 Survey Canvas으로 이동하기  
![Image](https://github.com/user-attachments/assets/bfc397aa-e9db-4c5a-a639-b547a719007c)  

 ➊ 설문도구 활용한 설문지 작성을 위해 <img src="https://github.com/user-attachments/assets/9de883b7-4f48-4357-8748-3fc8c8eb3af6" width="3%"> 아이콘을 클릭합니다.


</div>
  
--          
       
### Survey Canvas  
설문지를 디자인하기 위한 도구 모음입니다.   
사용자는 다양한 설문도구를 필요에 따라 꺼내 문항을 디자인할 수 있습니다.  
Canvas는 컴퓨터 모니터와 휴대전화 크기로 변경해 설정할 수 있으며, 더 상세한 설정은 설정 가능을 활용하세요.

<center>
<img width="800" alt="image" src="https://github.com/user-attachments/assets/d20cd4b3-3845-4b02-afe2-5a5d0298cf9e">
</center>


### 📋 설문 도구 설정 기능
#### 기본 설문 도구  
![Image](https://github.com/user-attachments/assets/ccd4ccae-4e7b-48d6-aaba-001c7b5bf7cc)  

**ℹ️ 설명글**
- 목적: 설문 항목에 대한 추가 안내나 설명을 제공
- 예시: "다음은 서비스 만족도에 관한 질문입니다. 각 항목을 평가해 주세요."
- 용도: 응답자가 질문을 이해하거나 특정 형식을 따르도록 유도
- 사용설명:

**🔘 1개 선택**
- 목적: 여러 보기 중 하나만 선택하는 방식
- 형식: 라디오 버튼 형태
- 예시: "가장 좋아하는 색깔을 선택하세요." (① 빨강 ② 파랑 ③ 초록)
- 용도: 응답자가 명확한 선택을 해야 할 때 사용
-  사용설명:


**☑️ 다중 선택**
- 목적: 여러 보기 중 여러 항목을 선택 가능
- 형식: 체크박스 형태
- 예시: "좋아하는 과일을 선택하세요." (① 사과 ② 바나나 ③ 포도)
- 용도: 여러 항목에 대한 응답을 수집할 때 유용
- 사용설명:

**🔢 수치 입력**
- 목적: 숫자 값을 직접 입력 받는 방식
- 형식: 텍스트 입력란, 숫자만 허용 가능
- 예시: "연령을 입력하세요."
- 용도: 연령, 점수, 금액 등 정량적인 데이터를 수집할 때 사용
- 사용설명:

**🔤 텍스트 입력**
- 목적: 자유롭게 텍스트를 입력받는 방식
- 형식: 단답형 또는 장문형 텍스트 상자
- 예시: "의견을 적어 주세요."
- 용도: 자세한 설명이나 주관적인 의견을 받을 때 사용

**🔽 드롭다운**
- 목적: 목록에서 하나의 옵션을 선택하도록 유도
- 형식: 목록에서 선택
- 예시: "국가를 선택하세요." (▼ 한국, 미국, 일본)
- 용도: 선택지가 많을 때 공간을 절약하며 깔끔하게 제공
- 사용설명:



#### 계량 분석 설문 도구  
![Image](https://github.com/user-attachments/assets/e962b208-15da-4116-98ea-90b9bec56af1)


##### 📊 NPS (Net Promoter Score, 순추천지수) 문항 
- **목적**: 고객 충성도 측정
- **예시 문항**:  
  "이 제품/서비스를 친구나 동료에게 추천할 가능성이 얼마나 되나요?"  
  (0~10점 척도로 응답)
- **분류**:
  - **9~10점**: 추천자 (Promoters)
  - **7~8점**: 중립자 (Passives)
  - **0~6점**: 비추천자 (Detractors)
- **계산 방법**: 추천자 비율 - 비추천자 비율

NPS 분석에 대한 보다 자세한 내용과 문항설정 및 분석방법은 다음버튼을 클릭하세요.

##### 🏗️ AHP (Analytic Hierarchy Process, 계층 분석법) 문항
- **목적**: 여러 대안 간의 중요도 평가 및 우선순위 도출
- **예시 문항**:  
  "A와 B 중 어느 요소가 더 중요하다고 생각하나요?"  
  (1~9점 척도 사용: 1은 동등, 9는 매우 중요)
- **분류**: 두 요소를 비교하여 상대적 중요도를 평가

AHP 분석에 대한 보다 자세한 내용과 문항설정 및 분석방법은 다음버튼을 클릭하세요.

##### 💲 PSM (Price Sensitivity Meter, 가격 민감도 측정) 문항
- **목적**: 소비자가 생각하는 적정 가격 범위 측정
- **예시 문항**:  
  "이 제품의 가격이 너무 비싸서 구매하지 않을 가격은 얼마인가요?"  
  "이 제품을 구매하기 위한 적정 가격은 얼마인가요?"
- **주요 질문**:
  1. 너무 비싸서 구매하지 않을 가격
  2. 비싸지만 고려할 가격
  3. 저렴하지만 품질을 의심할 가격
  4. 매우 저렴하여 구매할 가격
- **목적**: 가격 민감도를 파악하고, 적정 가격 범위를 도출

PSM 분석에 대한 보다 자세한 내용과 문항설정 및 분석방법은 다음버튼을 클릭하세요.


##### 💰 CVM (Contingent Valuation Method, 조건부 가치 측정법) 문항
- **목적**: 시장에서 거래되지 않는 재화(예: 환경 보호, 공공 서비스)의 가치를 평가
- **예시 문항**:  
  "이 서비스를 이용하기 위해 얼마를 지불할 의향이 있나요?"  
  또는  
  "이 환경 보호 프로젝트에 참여하기 위해 얼마를 기부할 의향이 있나요?"
- **응답 방식**:  
  - 지불 의향 금액(WTP, Willingness to Pay)  
  - 보상 요구 금액(WTA, Willingness to Accept)  
- **목적**: 비시장적 재화의 경제적 가치를 추정

CVM 분석에 대한 보다 자세한 내용과 문항설정 및 분석방법은 다음버튼을 클릭하세요.


#### 설문지 디자인 설정  
![Image](https://github.com/user-attachments/assets/e6ec59f8-40e6-4b6e-8b1e-2279b8b8fbe6) 

설문 디자인 설정에서는 설문지 템플릿을 설정하실 수 있습니다.



-- 


  
  
### 📂 설문지 디자인 기본정보   
설문지 디자인 기본정보는 권한(플랜), 설문지 이름, 생성일, 디자인 진행상태 정보를 제공합니다.  

 <div style="border: 1px solid #1DA1F2; padding: 15px; border-radius: 5px; background-color: #E8F5FD; color: #333;">
    <strong> ℹ️ </strong>  설문지 디자인 진행상태에서 <strong>Complete 상태인 설문지</strong>는 '설문조사' 메뉴에 <strong>설문조사가 가능한 설문</strong>으로 표시되며, 설문지 배포를 위한 <strong> URL/QR코드</strong>를 생성할 수 있습니다. <strong><span style="color:blue"> 빠른 IPA 분석 설정과 문항 간 건너뛰기 설정 또한 Complete 상태를 원칙으로 합니다. </span> </strong>
 </div>  
 <br>  
   
 <center>   
 <div style="border: 1px solid grey; width: fit-content;">
 <img width="800" alt="image" src="https://github.com/user-attachments/assets/d92172c2-71ff-4f6e-964b-d8081eb8a4e5">
</div>
</center>

#### 🗂️ 하위 메뉴 설명
- ##### 🎨 Survey Canvas  
  설문지 디자인을 할 수 있는 Survey Canvas로 이동합니다.  
- ##### 📂 상세 보기  
    다른 메뉴 이동 후, 현재 페이지로 이동합니다.  
- ##### 📝 설문조사 설정  
  설문조사 배포, 빠른 IPA 등을 설정할 수 있습니다.  
- ##### 📄 설문지 복사  
  현재 설문지를 다른 이름으로 복사할 수 있습니다. 복사한 설문지는 survey canvas에서 수정, 편집할 수 있습니다.  
- ##### ↩️ 문항 간 건너뛰기 설정  
  응답자가 특정 문항에 대한 답변을 건너뛰거나, 이전의 선택에 따라 다음에 보여질 문항을 조절할 수 있습니다.  
- ##### 📚 아이템 북 게시  
  설문지 템플릿으로 등록하여 사용할 수 있습니다.    
- ##### 🗑️ 폐기  
  설문지를 삭제합니다.  
<br>
 <div style="border: 1px solid #FFD700; padding: 15px; border-radius: 5px; background-color: #FFFACD; color: #333;">
 💡 설문지 디자인을 완료하였으면, 설문지 디자인 기본정보로 이동해 설문조사 설정을 하세요.
</div>
    
  
### 문항 간 건너뛰기
응답자가 특정 문항에 대한 답변을 건너뛰거나, 이전의 선택에 따라 다음에 보여질 문항을 조절할 수 있습니다.  
<center>               
<div style="border: 1px solid grey; width: fit-content;">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/d8f58d02-fe8f-41d8-b319-3b927467b563">
</div>
</center>
<br>
<div style="border: 1px solid #1DA1F2; padding: 15px; border-radius: 5px; background-color: #E8F5FD; color: #333;">
ℹ️ '문항간 건너뛰기' 사용 시, 건너뛴 문항은 결측치가 발생되므로 반드시 결측처리를 유념한 통계분석을 수행해야 합니다.
</div>   
<br>
#### ✔️ 문항간 건너뛰기 설정 방법
  ➊ <strong>경로 목록</strong>에서 경로명을 입력하고,  
  ➋  <strong>경로 상세설정</strong>에서 출발 문항의 해당 척도를 선택 후, 도착 문항을 선택합니다.  
  ➌  <strong>경로 구조설정</strong>에서 설정할 경로구조명을 선택/추가하여 적용 아이콘을 클릭합니다.  


--  
       
### 📝 설문조사 설정
<strong>설문조사 설정</strong>은 디자인한 설문지를 바탕으로 설문조사를 진행하기 위한 설정 과정입니다.  
디자인를 완료한 설문지는 <strong>설문조사 설정</strong>으로 이동하여 <strong>'빠른 분석'</strong><strong>'설문조사 배포 설정'</strong>을 하실 수 있습니다.   

#### 🔗 설문조사 배포 설정
설문조사 배포 설정에서는 설문 응답을 수집하기 위한 배포방법, 응답 기간, 공개여부 등을 설정합니다.
<center>
<div style="border: 1px solid grey; width: fit-content;">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/6b4a9639-a0de-4cbe-9989-e795de549222">
</div>
</center>

#### ⏱️ 빠른 분석 
빠른 분석 설정은 학습자 앞에서 데이터 분석 조건을 설정해 분석 결과 공유대상을 기다리게 하는 불편함을 없애기 위해 설문조사 전 단계에서 필요한 분석 조건을 설정하는 과정입니다.  

##### 빠른 분석의 특징
- 즉시 결과 공유: 분석 조건을 미리 설정하여 결과를 빠르게 확인하고 즉시 공유할 수 있습니다.
- 시간 절약: 설문조사 후 분석 조건을 설정하는 불편함을 없애고, 데이터를 수집하는 동시에 분석이 가능해 시간과 노력을 절감할 수 있습니다.
- 효율적인 작업 흐름: 설문 조사와 분석을 동시에 진행할 수 있어, 결과를 기다리는 시간을 단축시킬 수 있습니다.
- 사전 준비: 설문 전에 필요한 분석 조건을 설정해두면, 결과가 바로 도출되므로 데이터를 빠르고 정확하게 처리할 수 있습니다.
- 결과의 즉각적 활용: 설문이 끝나자마자 분석 결과를 바로 활용할 수 있어, 의사결정 및 전략 수립에 유리합니다.

<center>
<div style="border: 1px solid grey; width: fit-content;">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/a4ba50a7-e3a8-41a3-b8c0-1c8b8911506b">
</div>
</center>

#### ✔️ STEP 1. 설문조사 설정  
##### 설문조사 설정으로 이동  
설문지 디자인을 완료하였으면 다음과 같이 설정합니다.  
➊ 설문지 기본정보 하위메뉴에서  <strong>설문조사 설정</strong>을 클릭합니다.    
<div style="border: 1px solid grey; width: fit-content;">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/16aa7654-adec-4259-9997-e59f50817ec6">    
</div>  

➋ 설문 진행을 위해 <strong>확인</strong>을 클릭합니다.  
<div style="border: 1px solid grey; width: fit-content;">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/f65fcd8e-94e9-40fa-872d-81558bd7a8e0">
</div>             
   
#### ✔️ STEP 2. 빠른 IPA 설정 (선택)   
##### 빠른분석 설정화면으로 이동  
설문조사 정보에서 우측 <strong>빠른분석 설정</strong>아이콘을 클릭합니다.    
<div style="border: 1px solid grey; width: fit-content;">
<img width="800" alt="image" src="https://github.com/user-attachments/assets/daca7054-c87b-410e-9158-ea8d630d2411">  
</div>  

##### 빠른분석 설정  


➊ 빠른 분석 사용여부에 <strong>사용</strong>을 선택합나다.   
➋ <strong>분석 데이터 제목</strong>입력합니다.  
➌ <strong>전처리 규칙</strong>을 연결합니다.          
<div style="border: 1px solid #1DA1F2; padding: 15px; border-radius: 5px; background-color: #E8F5FD; color: #333;">
<strong ℹ️</strong>설문디자인에서 설정한 문항들이 <strong>척도찾기 예제</strong>를 활용하였다면,  큐릭스에서 제공하는 <strong>‘데이터 전처리 기본규칙’</strong>을 연결할 수 있습니다. 만약 <strong>척도입력</strong>을 통해 문항을 설정하였다면, <strong>데이터 전처리에서 규칙을 등록</strong>하셔야합니다.     
<span style="color:red">&#8251;전치리 규칙에 대한 자세한 설명은 <strong>'데이터 전처리 규칙'</strong>에서 확인하세요. </span>
</div> 
 <br>   
    
➍ 분석할 <strong>분석모듈</strong>을 체크하고<strong>설정사항 보기</strong>아이콘을 클릭합니다.    
➎ 설정을 완료하였으면 <strong>확인</strong>버튼을 누릅니다.  
<img width="800" alt="image" src="https://github.com/user-attachments/assets/a4ba50a7-e3a8-41a3-b8c0-1c8b8911506b">  
  
##### [분석모듈] 기술 통계 설정  
기술 통계를 분석할 문항(열)을 선택하고 완료 버튼을 클릭합니다.    
<div style="border: 1px solid #1DA1F2; padding: 15px; border-radius: 5px; background-color: #E8F5FD; color: #333;">
<strong>ℹ️</strong> 기술통계는 숫자(단일선택/수치) 유형의 문항(열)만 선택하여 분석이 가능합니다. 
</div>
<br>
 
 <div style="border: 1px solid grey; width: fit-content;">
 <img width="800" alt="image" src="https://github.com/user-attachments/assets/27516d09-a07f-4776-80e7-ae062d554767">      
 </div>    
 
##### [분석모듈] IPA 분석 설정  
➊ 설문디자인 단계에서 결과변수로 설정한 문항을 선택하고 변수명을 입력합니다.  
➋ 선행요인에 해당하는 문항을 선택하고 변수명을 입력합니다.  
➌ 변수추가를 아이콘을 클릭하여 추가 선행요인 변수를 설정합니다.  
➍ 모든 설정을 설정완료 버튼을 클릭합니다.  
<div style="border: 1px solid #1DA1F2; padding: 15px; border-radius: 5px; background-color: #E8F5FD; color: #333;">
<strong> ℹ️ </strong>IPA 분석에서는 숫자(단일선택/수치) 유형의 문항(열)만 선택하여 분석이 가능합니다. </strong>
</div>  
<br>
<div style="border: 1px solid grey; width: fit-content;">    
<img width="800" alt="image" src="https://github.com/user-attachments/assets/6d058ff8-e71c-404a-8797-9bb9dd906c02">
</div>

##### ✔️STEP 3. 설문 배포 설정 방법   
➊ 다음과 같이 <strong>설문조사 정보를 입력</strong>하여 설정합니다.  
➋ 설문조사 정보를 모두 입력하고, <strong>조사를 진행합니다</strong>아이콘을 클릭합니다.  

<div style="border: 1px solid grey; width: fit-content;">
    <img width="800" alt="image" src="https://github.com/user-attachments/assets/6b4a9639-a0de-4cbe-9989-e795de549222">  
</div>       
<br>
- ##### 설문 조사명       
설문 조사의 제목을 설정하는 항목입니다.  
- ##### 설문조사 메모       
설문 조사를 준비하면서 필요하거나 중요한 정보를 기록하는 공간입니다. 설문 조사와 관련된 메모나 주의사항, 추가적인 설명 등을 입력하여 관리할 수 있습니다.    
- ##### 기간 설정  
설문 조사를 진행할 시작일과 종료일을 설정하는 옵션입니다.    
<img width="800" alt="image"  src="https://github.com/user-attachments/assets/ec155d4d-c6bd-4f2f-ab50-4279348f751c">  
- ##### 설문 조사 수량       
조사할 응답자의 수량을 지정할 수 있는 항목입니다.    
- ##### 설문조사 수량       
설문 조사의 제목을 설정하는 항목입니다.    
- ##### 설문조사 공개여부       
설문 조사의 공개 여부를 설정합니다. 공개 여부에 따라 특정 그룹만 응답할 수 있도록 제한할 수 있습니다. 비공개로 설정할 경우, 비밀번호를 설정할 수 있으며, 답자는 해당 비밀번호를 입력해야만 설문조사에 참여할 수 있습니다.    
- ##### 설문 조사 시작일 자동조사 전환 여부       
설문 조사 시작일에 자동으로 조사가 진행될지 여부를 선택하는 옵션입니다.    
##### 설문조사 응답요청 메세지       
응답자에게 설문 참여를 요청하는 메시지를 작성할 수 있는 항목입니다.    
- ##### 문항 건너뛰기 설정       
설문 디자인 단계에서 문항 건너뛰기를 설정한 경우 사용여부를 묻습니다.    

 <div style="border: 1px solid #FFD700; padding: 15px; border-radius: 5px; background-color: #FFFACD; color: #333;">
   
 💡 설문조사 설정을 완료하였으면,  <a href="https://example.com" target="_blank" style="color: #0066cc;">설문조사<a>에서 URL/QR를 배포하세요.

</div>


 

---
title: 데이터 분석
author: Scotty
date: 2024-11-11
category: stats
layout: post
---
분석 대상으로 등록된 데이터는 설문조사를 통해 수집된 <strong>'설문조사 응답정보'</strong> 데이터와  데이터 등록에서 등록한 <strong>'스프레드 시트 파일 업로드'</strong> 데이터로 구성됩니다.    

설문조사 응답정보 문항 척도는 대부분 문자척도인 경우가 대부분입니다. 예를 들어, 5점 척도의 <strong>‘매우 그렇다’, ‘그렇다’, ‘보통이다’, ‘그렇지 않다’, ‘전혀 그렇지 않다’</strong>와 같은 응답은 문자로 되어 있습니다.   
이러한 문자척도는 데이터 분석을 위해 숫자척도로 변환해야 하므로, 분석 설정에서 데이터 전처리 규칙을 연결해야 합니다.

<div style="border: 1px solid #1DA1F2; padding: 15px; border-radius: 5px; background-color: #E8F5FD; color: #333;">
       <strong> ℹ️ 분석대상으로 등록된 데이터와 통계분석 목적에 따라 전처리 또는 다른 이름으로 저장한 데이터 목록이 혼재되어 있습니다.  
분석 대상 데이터는 원칙적으로 데이터 분석을 즉시 수행할 수 있습니다.
그런데 설문조사 데이터는 설문지에 노출된 척도를 그대로 수집하므로 대부분 문자 척도를 포함할 가능성이 높습니다. 문자척도는 기술통계 등 통계분석 대상이 아닙니다.  </strong>
</div>
</br>

<center>
<img width="800" alt="image" src="https://github.com/user-attachments/assets/031b3002-62b4-41bc-9f7b-a00a68deccab">  
</center>
</br>

<details>
  <summary> STEP 1. 전처리 규칙 연결 (설문 응답정보) </summary>
  <div class="item">
    <div class="item-content"> 
     다음은 응답자가 응답한 설문 조사 데이터에서 <strong>문자척도를 숫자척도를 변환</strong>하기 위한 설정으로 먼저 분석 대상 데이터로 등록 후, 전처리 규칙을 연결합니다. <br><br>
      <span class="item-title">분석 대상 데이터로 등록</span><br>
    ① 설문조사 화면에서 '현재 조사중인 설문'의 해당 설문 우측에 있는 <strong>'분석'</strong> 아이콘을 클릭합니다. <br>
   <img width="800" alt="image" src="https://github.com/user-attachments/assets/289030e2-7059-4e34-93d0-1efb12dca158"> <br>
② 분석대상으로 등록할 <strong>데이터 제목</strong>을 입력하고 저장합니다.
   <img width="800" alt="image" src="https://github.com/user-attachments/assets/e61373f8-6dbb-4098-bd36-414ad75c6916"> <br><br>

③ 저장된 데이터는 <strong>데이터 기본정보</strong>로 이동합니다. <br>
데이터 기본정보에서 <strong>전처리 규칙 연결</strong>을 클릭합니다.<br>
   <img width="800" alt="image" src="https://github.com/user-attachments/assets/4b22c841-9d54-4d19-a26b-48305bc420e1"> <br><br>

<span class="item-title">전처리 규칙 연결</span><br>
④ 데이터 전처리 규칙 연결에서 <strong>해당 전처리 규칙 이름</strong>을 클릭하고 <strong>규칙 적용</strong> 아이콘을 클릭합니다.

  <div style="border: 1px solid #1DA1F2; padding: 15px; border-radius: 5px; background-color: #E8F5FD; color: #333;">
       <strong> ℹ️</strong> 설문디자인에서 설정한 문항들이 <strong>척도찾기 예제</strong>를 활용하였다면,  큐릭스에서 제공하는 <strong>‘데이터 전처리 기본규칙’</strong>을 연결할 수 있습니다.</strong> <br> 만약 <strong>척도입력</strong>을 통해 문항을 설정하였다면, <strong>데이터 전처리에서 규칙을 등록</strong>하셔야합니다. <br> <span style="color:red"> &#8251; 전치리 규칙에 대한 자세한 설명은 <strong>'데이터 전처리 규칙'</strong>에서 확인하세요. </span>
  </div><br>
       
  <img width="800" alt="image" src="https://github.com/user-attachments/assets/e4362260-77f1-4c43-8446-29bb6e8d8200"> <br><br>


⑤ 전처리 규칙 연결 여부를 묻는 질문으로서, 연결하고자 하는 전처리 규칙이 해당 척도와 일치하는지 재확인 후, <strong>적용</strong> 아이콘을 클릭합니다.
   <img width="800" alt="image" src="https://github.com/user-attachments/assets/fe441258-4e6d-425b-9cfc-9e574d9c6341"> <br><br>

⑥ 분석대상으로 등록된 데이터에 전처리 규칙을 연결한 후 다른이름으로 저장합니다.  
등록할 <strong>데이터 제목</strong>을 입력하고 <strong>데이터 내보내기</strong> 아이콘을 클릭합니다.  
저장된 데이터는 데이터 분석 목록에서 확인하실 수 있습니다.
   <img width="800" alt="image" src="https://github.com/user-attachments/assets/a52db872-8fd4-413c-b387-62f8bb66ae5e"> <br><br>
</details>
<details>
  <summary>STEP 2. Data Analzyer으로 이동</summary>
    <div class="item">
    <div class="item-content">
    <strong>Data Analzyer</strong>은 분석 대상 데이터를 활용하여 분석을 실시할 수있습니다. <br><br>
    '데이터 기본 정보' 우측 <strong>하위 메뉴</strong>에서 <strong>Data Analzyer</strong> 아이콘을 클릭하여 이동합니다. <br>
      <img width="800" alt="image" src="https://github.com/user-attachments/assets/708c1ed0-14c4-4c09-8305-e84e9bd08bae"> <br><br>
</details>

<details>
  <summary>메뉴/아이콘 설명</summary>
  <div class="item">
    <div class="item-content">
    <span class="item-title">큐릭스 설문조사 응답정보</span><br>
     설문조사를 통한 응답된 데이터입니다.<br><br>
    <span class="item-title">스프레드시트 파일 업로드 데이터</span><br>
    데이터 등록에서 등록된 데이터입니다.<br><br>
    <span class="item-title">전처리 규칙</span><br>
     전처리 규칙과 관계만 연결했을 뿐 전처리 규칙에 맞게 데이터를 교체했다는 것을 의미하지는 않습니다.<br><br>
    <span class="item-title">데이터 연결</span><br>
     어떤 데이터를 다른 이름으로 저장하면 원래 데이터 목록에는 다른 이름으로 저장한 데이터 개수를 표시합니다. 데이터 연결 1은 이 데이터를 다른 이름으로 1번 저장했다는 것을 의미합니다.따라서 설문조사 데이터는 다음 절차에 따라 숫자/점수 척도로 데이터를 전처리하는 과정이 필요합니다.<br><br>
      <span class="item-title">데이터 기본정보</span><br>
     데이터명을 클릭하면 데이터 기본정보로 안내합니다. 설문 기본정보는 데이터 등록일, 데이터 유형을 제공하고, 설문조사 응답정보 데이터인 경우, 설문배포 정보를 제공합니다. 또한, 전처리 규칙을 연결하여 데이터 분석을 할 수 있는 Data Analzyer로 이동합니다.<br><br>
</details>





## 데이터 기본정보
데이터 분석 화면에서 데이터명을 클릭하면 데이터 기본정보로 이동합니다.   
데이터 기본정보에서는 전처리 규칙을 연결하여 Data Analyzer로 이동하여 데이터 분석을 수행할 수 있습니다.

<center>
<img width="900" alt="image" src="https://github.com/user-attachments/assets/7430b29d-ccf0-426d-9052-6cb346c087c3">  
</center>
</br>  

<details>
  <summary>하위 메뉴 설명</summary>
  <div class="item">
    <div class="item-content">
    <span class="item-title">데이터 보기/편집</span><br>
    사용자가 선택한 데이터를 다른 이름으로 저장, 다운로드 할 수 있고, 데이터 셀 단위의 수정을 수행할 수 있습니다. 데이터의 변경이 있는 경우 새 이름으로 저장해 원본 데이터를 보호하십시오. <br><br>
    <span class="item-title">삭제</span><br>
      데이터를 삭제합니다. 데이터를 삭제하면 복구할 수 없으므로 신중한 결정이 필요합니다.<br><br>
    <span class="item-title">전처리 규칙 연결</span><br>
     하나의 데이터는 여러개의 전처리 규칙을 연결할 수 있으며, 규칙을 연결하는 행위가 데이터 전처리 작업완료를 의미하는 것은 아닙니다. 분석 대상 데이터 상세 보기에서 연결된 전처리 규칙을 선택하여 <span style="color:blue"> 전처리 규칙을 적용한 새로운 데이터를 저장하여 데이터 분석을 수행 하십시오.</span><br><br>
      <span class="item-title">Data Analzyer</span><br>
     해당 데이터를 분석하기 위한 분석도구 화면으로 이동합니다. Data Analyzer는 기술통계, 통계분석, 계량분석 등 다양한 분석 도구를 포함하고 있습니다.  
<br><br>

</details>





[[목차로 이동]](#index)

</br>  
</br>  

# 데이터 등록
분석대상 데이터로 등록합니다.
<center>
<img width="900" alt="image" src="https://github.com/user-attachments/assets/5cda754f-4b65-403e-9e90-f7c4a84bea00">  
</center>
</br>  
<details>
  <summary>데이터 등록 방법</summary>
  <div class="item">
    <div class="item-content">
       분석 대상 데이터 제목을 입력하고, 스프레드시트 파일(.xlsx)를 업로드하여 등록합니다.<br>

</details>


</br>
<div style="border: 1px solid #FFD700; padding: 15px; border-radius: 5px; background-color: #FFFACD; color: #333;">
 등록한 데이터를 분석하려면 '데이터 분석'에서 Data Analyzer로 이동하세요.
</div>
</br>



[[목차로 이동]](#index)
</br>  
</br>  
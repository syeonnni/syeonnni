<h3 align="center"> 👋SKN07-1st-Mini Project-4Team👋 </h3>
<br>

## 전기차 통합 정보 사이트 제공
> **팀원 : 김서진, 김재혁, 정승연, 이재철**
><br/> **프로젝트 기간 : 2024.11.13 ~ 2024.11.14** 
<br>

## 1. 프로젝트 개요 및 소개
2024년 전기 자동차 판매량이 크게 증가하며 전 세계적으로 1,700만 대가 판매될 것으로 예상되고 있습니다. 이는 2023년에 판매된 1,400만 대보다 증가한 수치로, 전기차가 전 세계 자동차 판매량의 20% 이상을 차지하게 되어 도로 운송을 위한 석유 수요를 줄일 수 있을 것이라는 전망입니다. 
</br>
하지만 높은 판매량에 비해, 전기차 정비 업체와 충전소의 수요는 부족한 현실입니다. 지역 별 전기차 등록 현황, 정비소 및 충전기 현황 등 다양한 데이터 분석을 통해 급증하는 전기차 수요 대비 현 실상에 대한 인사이트를 제공합니다.
</br>
<br>


## 2. Tech Stack 

>### <span style="color:Black"> Data Pipeline </span>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=Pandas&logoColor=white">  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">

>### <span style="color:cyan"> UI </span>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white">

>### <span style="color:cyan"> Co-Work Tools </span>
 <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=Discord&logoColor=white">  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=Github&logoColor=white">
<br>
<br>

## 3. Flow Chart

  ![alt text](flowchart.png)
<br>

## 4. Architecture
<br>

## 5. ER(Entity Relation) 다이어그램

  ![alt text](ERD.png)
<br>

## 6. UI Prototype  
* **메인페이지**
<br>

## 7. 디렉토리 구조

데이터 수집 
1. 전기차 등록 현황 https://chargeinfo.ksga.org/front/statistics/evCar / 지역별 크롤링
2. 전기차 정비 가능업체 현황 <자동차365> https://www.car365.go.kr/web/contents/running_e_repairshop.do / 차량 대표모델 8개 브랜드 크롤링
 - 아우디, 벤츠, BMW, 현대, 기아, 한국르엠(삼성), 포르쉐, 볼보, 르노코리아 
3. 전기차 충전소 현황 https://chargeinfo.ksga.org/front/statistics/evCar / 지역별 누적 

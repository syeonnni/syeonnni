# SKN07-1st-4Team

# 전기차 통합 정보 사이트 
> **SK Networks AI CAMP 7기** <br/> **개발기간: 2024.11.13 ~ 2024.11.14** 


## 팀원 소개
| 김서진 | 김재혁 | 정승연 | 이재철 |


## 1. 프로젝트 개요 및 소개

## 2. Tech Stack 
>### <span style="color:cyan"> Data </span>
<table>
  <tr>
    <td>BE IDE & Language</td>
    <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
  </tr> 

>### <span style="color:cyan"> Data Store </span>
<table>
  <tr>
    <td>BE IDE & Language</td>
    <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"> 
    ![HeidiSQL](https://img.shields.io/badge/HeidiSQL-3776AB?style=for-the-badge&logo=HeidiSQL&logoColor=white)
  </tr> 

>### <span style="color:cyan"> Craweling </span>
<table>
  <tr>
    <td>BE IDE & Language</td>
    <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"> 
  </tr> 

>### <span style="color:cyan"> UI </span>
<table>
  <tr>
    <td>BE IDE & Language</td>
    <img src="https://img.shields.io/badge/streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"> 
  </tr>  
 
>### <span style="color:cyan"> Co-Work Tool </span>
<table>
  <tr>
    <td>Communication & Messenger</td>
    <td><img src="https://img.shields.io/badge/Discord-5865F2?style=flat&logo=Discord&logoColor=white"/></td>
  </tr>
  <tr>
    <td>Development & Merge</td>
    <td><img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white"/></td>
    <td><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white"/></td>
  </tr>  
</table>


## Flow Chart

## Architecture

## ERD 설계 

  ![alt text](ERD.png)

## 결과 화면
* **메인페이지**
    

## 디렉토리 구조

데이터 수집 
1. 전기차 등록 현황 https://chargeinfo.ksga.org/front/statistics/evCar / 지역별 크롤링
2. 전기차 정비 가능업체 현황 <자동차365> https://www.car365.go.kr/web/contents/running_e_repairshop.do / 차량 대표모델 8개 브랜드 크롤링
 - 아우디, 벤츠, BMW, 현대, 기아, 한국르엠(삼성), 포르쉐, 볼보, 르노코리아 
3. 전기차 충전소 현황 https://chargeinfo.ksga.org/front/statistics/evCar / 지역별 누적 

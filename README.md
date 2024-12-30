# ShowTimeNow - 통합 영화 예매 관리 시스템
<p align="center">
    <img src="https://github.com/user-attachments/assets/24881a4d-a482-4b5f-9928-9004a3a452b9" alt="DBDBDEEP 팀의 ShowTimeNow 프로젝트 로고" width="500" height="500">
</p>

## DBDBDEEP 팀원들의 소개
| <img src="https://github.com/user-attachments/assets/98231e0d-e3fd-4d49-88d9-886dfa0c9f58" alt="최유진" width="150" height="150"> | <img src="https://github.com/user-attachments/assets/6ac2b1d3-3dae-426f-9dbe-39d8da6a6d67" alt="홍재민" width="150" height="150"> | <img src="https://github.com/user-attachments/assets/01e546d9-8fff-484f-8e2e-4e49675a3769" alt="김민석" width="150" height="150"> | <img src="https://github.com/user-attachments/assets/690a2aa0-9019-4809-a4a3-88f9d349b24e" alt="이성훈" width="150" height="150"> | <img src="https://github.com/user-attachments/assets/5f1dec4a-33a3-43f7-ad4b-b3bb1865a4f9" alt="김도윤" width="150" height="150"> |
|---|---|---|---|---|
| 최유진 | 홍재민 | 김민석 | 이성훈 | 김도윤 |

## 목차 
1. [프로젝트 개요](#프로젝트-개요) 
2. [프로젝트 목적](#프로젝트-목적) 
3. [주요 기능](#주요-기능)
4. [프로젝트 필요성](#프로젝트-필요성) 
5. [기대 효과](#기대-효과) 
6. [대상사용자](#대상-사용자)

## 프로젝트 개요
ShowTimeNow는 사용자가 원하는 영화를 보다 효율적으로 찾고 예매할 수 있도록 돕기 위해 설계된 통합 영화 예매 관리 시스템입니다.

## 프로젝트 목적
이 프로젝트는 사용자가 원하는 영화를 보다 효율적으로 찾고 예매할 수 있도록 돕기 위해 설계되었습니다. 특정 영화가 모든 영화관에서 상영되지 않는 경우가 많아, 사용자는 어떤 영화관에서 원하는 영화를 상영하는지 확인하기 위해 여러 플랫폼을 탐색해야 하는 불편함을 겪고 있습니다. 이를 해결하기 위해, 영화 정보를 통합적으로 제공하고 지역별 영화관 현황을 쉽게 파악할 수 있는 시스템을 구축하고자 합니다.

## 주요 기능
- **회원 관리**
  - 회원가입 및 로그인 기능 제공
  - 사용자 정보를 데이터베이스에 안전하게 저장 및 관리
- **영화 정보 제공**
  - CGV, 메가박스, 롯데시네마의 영화 상영 정보를 한눈에 확인 가능
  - 특정 지역에서 상영 중인 영화와 해당 영화관 정보 제공
- **영화 예매**
  - 사용자가 영화관, 상영 시간, 좌석을 선택하여 예매 가능
  - 예매 내역 저장 및 관리 기능 제공
- **영화관별 상영 현황**
  - 선택한 영화가 어느 영화관에서 상영 중인지 조회
  - 지역별로 근처 영화관 및 상영 영화 정보를 제공하여 사용자 편의성 증대

## 프로젝트 필요성
영화는 문화생활의 중요한 부분으로 자리 잡고 있지만, 상영 정보의 분산으로 인해 사용자는 원하는 영화를 찾기 위해 여러 웹사이트를 방문해야 하는 불편함이 존재합니다. 이 시스템은 사용자에게 통합된 정보를 제공하여 시간을 절약하고, 효율적인 영화 선택 및 예매 경험을 제공합니다.

## 기대 효과
- 사용자 편의성 향상: 지역별 영화관 및 상영 정보 통합 제공
- 예매 프로세스 간소화: 한 플랫폼에서 영화 정보를 검색하고 예매까지 완료 가능
- 통합된 사용자 경험 제공: 다양한 영화관 정보를 한곳에서 관리 가능

## 대상 사용자
영화 관람을 즐기는 일반 사용자

## 기술 스택
<div style="display: flex; justify-content: space-around;">
    <img src="https://img.shields.io/badge/mariaDB-003545?style=for-the-badge&logo=mariaDB&logoColor=white" alt="mariaDB">
    <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="git">
</div>

## ERD
<https://www.erdcloud.com/d/cSNA6njwwhbjBmBGs>
![ERD](https://github.com/beyond-sw-camp/be13-1st-DBDBDEEP/blob/main/ERD.png)
---
## 💻SQL개발
### DDL
<details>
  <summary>DDL</summary>

  

  <details>
    <summary>ACTOR_PROFILE</summary>
    <img src="https://github.com/user-attachments/assets/777daafe-f947-4484-bda7-1d371896d959" alt="ACTOR_PROFILE">
    <img src="https://github.com/user-attachments/assets/783a5382-9c8f-4848-a479-14198d4ea0a7" alt="ACTOR_PROFILE_CON">
  </details>

  <details>
    <summary>CINEMA</summary>
    <img src="https://github.com/user-attachments/assets/589a4da5-6b17-4fb4-82de-0c7bce1aa55b" alt="CINEMA">
    <img src="https://github.com/user-attachments/assets/97105901-24c0-4eba-892f-8b2d8eff6ba3" alt="CINEMA_CON">
  </details>

  <details>
    <summary>CINEMA_COMPANY</summary>
    <img src="https://github.com/user-attachments/assets/fcac5bc7-ef54-4681-8957-69ac1a8d780b" alt="CINEMA_COMPANY">
    <img src="https://github.com/user-attachments/assets/5a7e3dd3-1527-4631-8107-aa891859ae93" alt="CINEMA_COMPANY_CON">
  </details>

  <details>
    <summary>COUPON</summary>
    <img src="https://github.com/user-attachments/assets/f3ecd9cb-1981-4f1e-a066-139921eec295" alt="COUPON">
    <img src="https://github.com/user-attachments/assets/400382a1-e74d-4e97-85bb-b1654e7a2485" alt="COUPON_CON">
  </details>

  <details>
    <summary>GENRE</summary>
    <img src="https://github.com/user-attachments/assets/e5f5f434-f07c-4af6-9e12-deec55a1ca2c" alt="GENRE">
  </details>

  <details>
    <summary>GRADE</summary>
    <img src="https://github.com/user-attachments/assets/948ab911-1aa4-4db6-bea5-03408e782f78" alt="GRADE">
  </details>

  <details>
    <summary>ITEM</summary>
    <img src="https://github.com/user-attachments/assets/a2a780f9-cfd6-4d95-a9ef-36498271de5e" alt="ITEM">
    <img src="https://github.com/user-attachments/assets/d28de0c7-d123-4136-9eec-af6cb67f7ab8" alt="ITEM_CON">
  </details>

  <details>
    <summary>MOVIE</summary>
    <img src="https://github.com/user-attachments/assets/c54c6c9f-cfaa-4b40-b0c2-92ba57686d2a" alt="MOVIE">
    <img src="https://github.com/user-attachments/assets/9ac1c7b5-09e9-4bbf-a58e-e5c17395f91f" alt="MOVIE_CON">
  </details>

  <details>
    <summary>MOVIE_ACTOR</summary>
    <img src="https://github.com/user-attachments/assets/62485548-427c-4c76-bd20-efee86df4a92" alt="MOVIE_ACTOR">
    <img src="https://github.com/user-attachments/assets/b7e4ab10-5932-42c9-a7f8-fb5ec7043f9a" alt="MOVIE_ACTOR_CON">
  </details>

  <details>
    <summary>MOVIE_REVIEW</summary>
    <img src="https://github.com/user-attachments/assets/5deb4b12-5785-4b58-af44-da3a27bff675" alt="MOVIE_REVIEW">
    <img src="https://github.com/user-attachments/assets/00a08b71-231d-44db-879e-2283608ba59a" alt="MOVIE_REVIEW_CON">
  </details>

  <details>
    <summary>MOVIE_SCHEDULE</summary>
    <img src="https://github.com/user-attachments/assets/ae734b46-1220-4d6e-a115-5082d2c38ed7" alt="MOVIE_SCHEDULE">
    <img src="https://github.com/user-attachments/assets/7d054f8a-b302-4715-9f51-a4263239365b" alt="MOVIE_SCHEDULE_CON">
  </details>

  <details>
    <summary>MOVIE_SEAT</summary>
    <img src="https://github.com/user-attachments/assets/9a055f93-d64d-4750-ab2f-b8b4acc0dc76" alt="MOVIE_SEAT">
    <img src="https://github.com/user-attachments/assets/f05becc8-ef68-4b52-a6ed-45fa255ee067" alt="MOVIE_SEAT_CON">
  </details>

  <details>
    <summary>MOVIE_THEATERS</summary>
    <img src="https://github.com/user-attachments/assets/4e41780e-3d0e-4858-bf30-1bc5e63f4cdf" alt="MOVIE_THEATERS">
    <img src="https://github.com/user-attachments/assets/61b80bec-3166-43cb-8f7e-8d1a60c8b872" alt="MOVIE_THEATERS_CON">
  </details>

  <details>
    <summary>ORDER</summary>
    <img src="https://github.com/user-attachments/assets/1d1c469d-df18-4931-aac5-46c039a2cb92" alt="ORDER">
    <img src="https://github.com/user-attachments/assets/0af1823b-6edc-4c58-83f5-dca708a5de4f" alt="ORDER_CON">
  </details>

  <details>
    <summary>PAYMENT</summary>
    <img src="https://github.com/user-attachments/assets/fd0b49d8-0dfc-4c7f-ae9f-8f6424320d2d" alt="PAYMENT">
    <img src="https://github.com/user-attachments/assets/670a9d27-27d8-46ec-87b5-a01ee6f287b2" alt="PAYMENT_CON">
  </details>

  <details>
    <summary>USER</summary>
    <img src="https://github.com/user-attachments/assets/bcbe62ac-7de4-4a41-937f-e8c6c12f812d" alt="USER">
    <img src="https://github.com/user-attachments/assets/8b0abaa5-efdf-4a85-9abd-64327eab70c8" alt="USER_CON">
  </details>

  <details>
    <summary>USER_COUPON</summary>
    <img src="https://github.com/user-attachments/assets/6a43adb9-8d98-4657-bdce-ef5d163d89f4" alt="USER_COUPON">
    <img src="https://github.com/user-attachments/assets/4b299bf8-ab2f-4457-ad4c-781d8fdec6ed" alt="USER_COUPON_CON">
  </details>

  <details>
    <summary>USER_MOVIE_RESERV</summary>
    <img src="https://github.com/user-attachments/assets/1709a74b-24a8-47d5-9a5c-99a1ed2164dc" alt="USER_MOVIE_RESERV">
    <img src="https://github.com/user-attachments/assets/37546031-8d05-4ea6-9aaf-f1e3ffabc64c" alt="USER_MOVIE_RESERV_CON">
  </details>

</details>

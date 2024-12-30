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
7. [기술 스택](#기술-스택)
8. [ERD](#erd)
9. [요구사항 명세서](#요구사항-명세서)
10. [테이블 명세서](#테이블-명세서)
11. [WBS](#wbs)
12. [💻SQL개발](#sql개발)

## 프로젝트 개요
ShowTimeNow는 사용자가 원하는 영화를 보다 효율적으로 찾고 예매할 수 있도록 돕기 위해 설계된 통합 영화 예매 관리 시스템입니다. 이 시스템은 영화관과 사용자를 연결하여 영화 정보, 예매, 리뷰 등 다양한 기능을 제공합니다. ShowTimeNow는 단순한 영화 예매 시스템을 넘어, 사용자 경험을 극대화하고 영화 관람을 더욱 즐겁고 편리하게 만들기 위한 종합 솔루션입니다.

## 프로젝트 목적
이 프로젝트는 사용자가 원하는 영화를 보다 효율적으로 찾고 예매할 수 있도록 돕기 위해 설계되었습니다. 특정 영화가 모든 영화관에서 상영되지 않는 경우가 많아, 사용자는 어떤 영화관에서 원하는 영화를 상영하는지 확인하기 위해 여러 플랫폼을 탐색해야 하는 불편함을 겪고 있습니다. 이를 해결하기 위해, 영화 정보를 통합적으로 제공하고 지역별 영화관 현황을 쉽게 파악할 수 있는 시스템을 구축하고자 합니다.

## 주요 기능

## 1. 사용자
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

## 2. 관리자

- **영화등록**
  - 관리자가 상영할 영화를 추가
  - 영화 정보가 movie 데이터베이스에 저장
- **신 메뉴 등록**
  - 관리자가 새로운 메뉴를 추가
  - 새로운 메뉴 정보가 item 데이터베이스에 저장

## 프로젝트 필요성
영화는 문화생활의 중요한 부분으로 자리 잡고 있지만, 상영 정보의 분산으로 인해 사용자는 원하는 영화를 찾기 위해 여러 웹사이트를 방문해야 하는 불편함이 존재합니다. 이 시스템은 사용자에게 통합된 정보를 제공하여 시간을 절약하고, 효율적인 영화 선택 및 예매 경험을 제공합니다.

## 기대 효과
- 사용자 편의성 향상: 지역별 영화관 및 상영 정보 통합 제공
- 예매 프로세스 간소화: 한 플랫폼에서 영화 정보를 검색하고 예매까지 완료 가능
- 통합된 사용자 경험 제공: 다양한 영화관 정보를 한곳에서 관리 가능

## 대상 사용자
 - 영화 관람을 즐기는 일반 사용자
 - 영화 리뷰와 평점을 보고 싶어하는 사용자
 - 시간과 노력을 절약하고자 하는 사용자

## 기술 스택
<div style="display: flex; justify-content: space-around;">
    <img src="https://img.shields.io/badge/mariaDB-003545?style=for-the-badge&logo=mariaDB&logoColor=white" alt="mariaDB">
    <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="git">
</div>

## ERD
<https://www.erdcloud.com/d/cSNA6njwwhbjBmBGs>
![ERD](https://github.com/beyond-sw-camp/be13-1st-DBDBDEEP/blob/main/ERD.png)
---

## 요구사항 명세서
![beyond_13_1st_Showtimenow - 시트1_1](https://github.com/user-attachments/assets/c0f0dee6-86bb-446a-9af1-e5e66901081a)

## 테이블 명세서
![테이블_명세서_1](https://github.com/user-attachments/assets/2522f020-951e-4d61-8413-400037755b2f)
![테이블_명세서_2](https://github.com/user-attachments/assets/fe085171-b9fb-45a9-b1aa-533a631a3563)
![테이블_명세서_3](https://github.com/user-attachments/assets/1cafd0e6-2e9e-454d-953c-afc0b780776c)

## WBS (Work Breakdown Structure)
![image](https://github.com/user-attachments/assets/1f36e5da-71a9-427d-b903-55bdf80f463f)

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

### DML
<details>
  <summary>매점</summary>
    
  <details>
    <summary>결제 정보 입력</summary>
<img width="717" alt="결제 정보 입력" src="https://github.com/user-attachments/assets/3993f5c5-e274-464c-80a3-526df56d3109" />
  </details>

  <details>
    <summary>결제 정보 확인</summary>
<img width="1422" alt="결제 정보 확인" src="https://github.com/user-attachments/assets/45aa8cb5-e6dd-49a0-afab-58e4405ab7ae" />
  </details>

  <details>
    <summary>매점 대기번호 확인</summary>
<img width="862" alt="매점 대기번호 확인" src="https://github.com/user-attachments/assets/66ef866b-3c67-4b23-9908-672145f3ab74" />
  </details>

  <details>
    <summary>매점 메뉴 가격 확인</summary>
<img width="687" alt="매점 메뉴 가격 확인" src="https://github.com/user-attachments/assets/b20ec4e1-6867-43a9-be8c-be90ae2defd5" />
  </details>

  <details>
    <summary>매점 신메뉴 등록</summary>
<img width="970" alt="매점 신메뉴 등록" src="https://github.com/user-attachments/assets/01d020ac-eea9-4551-9a36-55b94ed30687" />
  </details>

  <details>
    <summary>매점 재고 추가</summary>
<img width="676" alt="매점 재고 추가" src="https://github.com/user-attachments/assets/b1b79bf4-3c9f-4456-a936-af04ae07fbac" />
  </details>

  <details>
    <summary>매점 재고 확인</summary>
<img width="702" alt="매점 재고 확인" src="https://github.com/user-attachments/assets/bcdcb1f6-3f11-4334-93ea-ef8f96ba70fd" />
  </details>

  <details>
    <summary>매점 주문 확인</summary>
<img width="1383" alt="매점 주문" src="https://github.com/user-attachments/assets/79332e81-9809-485d-b193-d9ec20ada437" />
  </details>

  <details>
    <summary>총 주문 금액 조회</summary>
<img width="813" alt="총 주문 금액 조회" src="https://github.com/user-attachments/assets/28501e0e-fdfc-4161-bdf1-16742e5ba191" />
  </details>

  <details>
    <summary>사용자 주문 내역 확인</summary>
<img width="813" alt="사용자 주문 내역 확인" src="https://github.com/user-attachments/assets/b8ad47bd-dfdd-4f9b-8c3e-0b79376b8dc6" />
  </details>
</details>



<details>
  <summary>사용자</summary>
    
  <details>
    <summary>결제내역</summary>
<img width="757" alt="결제내역" src="https://github.com/user-attachments/assets/6445fea2-f9ae-42e5-98fa-79c5c78aaa93" />
  </details>

  <details>
    <summary>과거예매내역</summary>
<img width="806" alt="과거예매내역" src="https://github.com/user-attachments/assets/ec189a1f-ceca-4177-825a-d2aa3056783d" />
  </details>

  <details>
    <summary>등급확인</summary>
<img width="789" alt="등급확인" src="https://github.com/user-attachments/assets/04c3fb92-37ef-4ddb-9ea7-9593d14a7951" />
  </details>

  <details>
    <summary>아이디 찾기</summary>
<img width="757" alt="아이디 찾기" src="https://github.com/user-attachments/assets/7f118fe3-f0f1-42b8-995e-7f8aab7a77a4" />
  </details>

  <details>
    <summary>예매 할인 내역</summary>
<img width="434" alt="예매 할인 내역" src="https://github.com/user-attachments/assets/b3b44e0c-4b0d-459b-874a-f034c94cc5e3" />
  </details>

  <details>
    <summary>예매정보 확인</summary>
<img width="584" alt="예매정보 확인" src="https://github.com/user-attachments/assets/fac7749c-3d1f-40ee-92f2-03cf0bc90190" />
  </details>

  <details>
    <summary>쿠폰</summary>
<img width="622" alt="쿠폰" src="https://github.com/user-attachments/assets/b6922436-3a7a-46b7-9d48-58df570b083a" />
  </details>

  <details>
    <summary>프로필 수정</summary>
<img width="790" alt="프로필 수정" src="https://github.com/user-attachments/assets/6da38114-47aa-4163-a0cb-5f878018391b" />
  </details>

  <details>
    <summary>회원 로그인</summary>
<img width="632" alt="회원 로그인" src="https://github.com/user-attachments/assets/8c1b5c28-04d2-4d46-9467-6c06d458bade" />
  </details>

  <details>
    <summary>회원가입</summary>
<img width="663" alt="회원가입" src="https://github.com/user-attachments/assets/22bacaf3-5371-40d7-b9a3-d5df6c79000d" />
  </details>
</details>

<details>
  <summary>매점</summary>
    
  <details>
    <summary>MOVIE_ACTOR</summary>

  </details>

  <details>
    <summary>MOVIE_REVIEW</summary>

  </details>

  <details>
    <summary>MOVIE_SCHEDULE</summary>

  </details>

  <details>
    <summary>MOVIE_SEAT</summary>

  </details>

  <details>
    <summary>MOVIE_THEATERS</summary>

  </details>

  <details>
    <summary>ORDER</summary>

  </details>

  <details>
    <summary>PAYMENT</summary>

  </details>

  <details>
    <summary>USER</summary>

  </details>

  <details>
    <summary>USER_COUPON</summary>

  </details>

  <details>
    <summary>USER_MOVIE_RESERV</summary>

  </details>
</details>

<details>
  <summary>매점</summary>
    
  <details>
    <summary>MOVIE_ACTOR</summary>

  </details>

  <details>
    <summary>MOVIE_REVIEW</summary>

  </details>

  <details>
    <summary>MOVIE_SCHEDULE</summary>

  </details>

  <details>
    <summary>MOVIE_SEAT</summary>

  </details>

  <details>
    <summary>MOVIE_THEATERS</summary>

  </details>

  <details>
    <summary>ORDER</summary>

  </details>

  <details>
    <summary>PAYMENT</summary>

  </details>

  <details>
    <summary>USER</summary>

  </details>

  <details>
    <summary>USER_COUPON</summary>

  </details>

  <details>
    <summary>USER_MOVIE_RESERV</summary>

  </details>
</details>

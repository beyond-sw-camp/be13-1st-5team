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
![ACTOR_PROFILE](https://github.com/user-attachments/assets/777daafe-f947-4484-bda7-1d371896d959)
![ACTOR_PROFILE_CON](https://github.com/user-attachments/assets/783a5382-9c8f-4848-a479-14198d4ea0a7)
    <details>
      <summary>CINEMA</summary>
![CINEMA](https://github.com/user-attachments/assets/589a4da5-6b17-4fb4-82de-0c7bce1aa55b)
![CINEMA_COMPANY](https://github.com/user-attachments/assets/412a335e-0292-461b-94c5-9b719c123dcd)

      내용 3

      <details>
        <summary>네 번째 토글</summary>

        내용 4

        <details>
          <summary>다섯 번째 토글</summary>

          내용 5

          <details>
            <summary>여섯 번째 토글</summary>

            내용 6

            <details>
              <summary>일곱 번째 토글</summary>

              내용 7

              <details>
                <summary>여덟 번째 토글</summary>

                내용 8

                <details>
                  <summary>아홉 번째 토글</summary>

                  내용 9

                  <details>
                    <summary>열 번째 토글</summary>

                    내용 10

                    <details>
                      <summary>열한 번째 토글</summary>

                      내용 11

                      <details>
                        <summary>열두 번째 토글</summary>

                        내용 12

                        <details>
                          <summary>열세 번째 토글</summary>

                          내용 13

                          <details>
                            <summary>열네 번째 토글</summary>

                            내용 14

                            <details>
                              <summary>열다섯 번째 토글</summary>

                              내용 15

                              <details>
                                <summary>열여섯 번째 토글</summary>

                                내용 16

                                <details>
                                  <summary>열일곱 번째 토글</summary>

                                  내용 17

                                  <details>
                                    <summary>열여덟 번째 토글</summary>

                                    내용 18

                                    <details>
                                      <summary>열아홉 번째 토글</summary>

                                      내용 19

                                    </details>

                                  </details>

                                </details>

                              </details>

                            </details>

                          </details>

                        </details>

                      </details>

                    </details>

                  </details>

                </details>

              </details>

            </details>

          </details>

        </details>

      </details>

    </details>

  </details>

</details>

<div align="center">

<img src="https://user-images.githubusercontent.com/89060425/183419558-884b9655-167e-4d05-8169-d071313268ad.jpg" width="450px" />

우리 동물 친구가 어떤 사료를 좋아할지 고민되시나요? <br>
**츄라잇**에서 샘플 사료로 먼저 **try it!** 해보세요.

</div>

<br>

## 프로젝트 배경
반려동물의 사료를 샀는데 안먹을 경우 처치가 곤란해집니다.😓<br>
그래서 샘플 사료를 먼저 먹여보고 싶은 분들이 많은데요.
하지만 사료 샘플을 구하려면 각 브랜드 사이트에서 샘플 사료를 신청해 구매해야 해요.<br> 
이럴 경우 여러 사료들을 한 곳에서 찾아 볼 수 없고, 여러 브랜드의 샘플 사료를 구매할 경우 배송비가 중복으로 발생하는 불편함이 있죠.

이러한 불편함을 개선하고자 다양한 브랜드의 사료 샘플을 모아볼 수 있고 구매할 수 있는 쇼핑몰 프로젝트를 구상하게 되었어요!

<br>

## 기술 스택

- Java
- Spring Boot
- Spring Data JPA
- Spring Security
- Thymeleaf
- MySQL

<br>

## 팀원 및 역할


|                                        Backend                                         |                                        Backend                                         |                                        Backend                                        |
|:--------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------:|
| <img src="https://avatars.githubusercontent.com/u/93319948?v=4" width=180px alt="정현"/> | <img src="https://avatars.githubusercontent.com/u/89060425?v=4" width=180px alt="쿠릉"/> | <img src="https://avatars.githubusercontent.com/u/91456818?v=4" width=180px alt="앤"/> |
|                         [김정현](https://github.com/Kimjunghyunn)                         |                           [김대준](https://github.com/kureung)                            |                            [임앤유정](https://github.com/an2z)                            |

- 김정현
    - 로그인 : 시큐리티
    - 결제 : 카카오 주소 API 연동
    - AWS EC2
- 김대준
    - 주문
    - 공지/QnA 게시판
- 임앤유정
    - 상품
    - 장바구니
    - AWS S3 이미지 업로드

## ERD

![erd](https://github.com/user-attachments/assets/868e5e3e-1e68-4638-b73b-56cc4413f8bb)


## 컨벤션

### 브랜치 전략
|        태그         |        설명         |
|:-----------------:|:-----------------:|
|   `feat/#이슈번호 `   |     기능 개발일 경우     |
| `refactor/#이슈번호 ` |     리팩토링일 경우      |
|  `build/#이슈번호 `   |   프로젝트 세팅일 경우     |
|   `style/#이슈번호`   | 오타 수정 및 코드 포맷일 경우 |

### 커밋 메세지 규칙
|      태그      |        설명         |
|:------------:|:-----------------:|
|   `feat: `   |     기능 개발일 경우     |
| `refactor: ` |     리팩토링일 경우      |
|  `build: `   |    프로젝트 세팅일 경우    |
|  `style: `   | 오타 수정 및 코드 포맷일 경우 |

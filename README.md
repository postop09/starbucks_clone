# starbucks_clone
스타벅스 페이지 클론

## 🟢프로젝트 설명
스타벅스 페이지 클론 4인 스터디 그룹의 프로젝트다.(윤식, 누리님, 상돈님, 정배님)

가장 빈번하게 사용되는 게시판 형태의 스타벅스의 메뉴 페이지를 제작하기로 했다. (학습의 여유가 있다면 랜딩페이지까지)

스타벅스 페이지 메뉴탭의 각자 한 페이지씩 작성하며, 코드리뷰를 통해 서로의 부족한 점을 채워주고 잘한 점을 보고 배울 수 있다.

- 프로젝트 기간 10일
- 페이지 개인 작성
- 2일에서 3일 간격으로 코드리뷰 : 내가 무엇을 고려하고 왜 이렇게 코드를 짰는지 알고, 팀원의 코드를 보며 궁금하거나 좋은 코드를 나눌 수 있다.
- 매일 22시 전 커밋 의무화로 팀원 전체가 확인하고 지속적인 피드백 가능

**페이지 분담**

- 음료[https://www.starbucks.co.kr/menu/drink_list.do]: 윤식
- 푸드[https://www.starbucks.co.kr/menu/food_list.do]: 누리님
- 상품[https://www.starbucks.co.kr/menu/product_list.do]: 정배님
- 카드[https://www.starbucks.co.kr/menu/card_list.do]: 상돈님


### 👽공식페이지
스타벅스: https://www.starbucks.co.kr/index.do

## 🟢빌드 및 실행방법
github 페이지: https://postop09.github.io/starbucks_clone/beverage.html

- 누리님 제작 페이지[https://nurimeansworld.github.io/clone_starbucks/html/food_list.html]
- 정배님 제작 페이지[https://tood21.github.io/starbucks_clone/item.html]
- 상돈님 제작 페이지[https://sangdon1029.github.io/Starbucks-clone/]

## 🟢개발 환경
- 개인 페이지 작업
- HTML/CSS
- 반응형(media query)
- JavaScript
- MDN문서 활용
- 오픈 카카오톡 채팅을 활용하여 수시로 의견 공유

## 🟢제작 과정
- 스터디 모집 및 계획 설명/의견 공유, 페이지 분담
- 박스 레이아웃
- 마크업
- 클래스 네이밍
- 부족한 점/ 의문점 정리
- 스타일 작성
- 코드 리뷰 및 피드백
- 코드 개선
- media query 작성
- JavaScript 작성
- 배운점/느낀점 기록
- 1차 제작 종료 12-19

---

## 🟢문제점 및 궁금했던 점/개선방안 및 배운점
### 👽문제점
- 음료 목록의 이미지가 원본페이지처럼 축소되는 반응이 구현되지 않은 문제
- 상세보기 드롭박스에서 체크박스를 넣어야하는 문제
- 축소된 콜드브루 목록 이미지에 mouseOver했을 때, `overflow: hidden`이 하단에 적용되지 않는 문제
- `radio box` 포커싱이 잡히지 않는 문제
- tab키로 이동 했을 때 소메뉴 탭이 나오지 않는 문제

### 👽궁금했던 점
- 스타벅스 원본 페이지에서 미디어 쿼리가 많이 나누어져있는 듯한 기분이다.

### 👽개선방안 및 배운점
- 기존 `flex-wrap`으로 구현하던 것을 `float`속성을 이용하고, `media query`에서 너비에 %값을 이용해서 유동적이 되도록 수정
- 일반 드롭박스에서 버튼과 목록, 스타일을 이용해 드롭박스의 형태처럼 만들어 작동하도록 수정
- 개발자도구를 통해 이미지를 감싸는 부모가 미세하게 감싸지 못하는 하단 여백을 발견, `vertical-align: bottom`속성으로 조치

## 🟢느낀점
이번 스터디 그룹을 계획하게 된 목표는 그동안 수업을 들으며, 실제로 배운것에 대해 복습할 시간과 동기부여가 부족하다는 점을 생각했다.
그동안의 HTML/CSS는 잊지않고 잘 활용할 수 있을지, JavaScript를 작업하며 사용해본 경험이 아얘 없었기에 꼭 하고자 하는 마음을 가졌다.
나는 웹 접근성에 대해 내가 아는 것을 나누고 싶었고, 또 타인과 함께하며 타인의 강점을 배워 더 성장할 수 있을 것이라는 생각을 가지고 스터디 그룹을 모집했다.
수업과 함께 진행하면서도 같이 열심히 해주는 팀원들에게 많은 자극을 받으며 함께 할 수 있었다.

코드 리뷰를 통해 '내가 왜 이런 코드를 사용했는지' 설명하며 개념을 다시 정리할 수 있었고, 팀원으로부터 더 좋은 방법도 피드백받을 수 있었다.
그리고 팀원들에게 내가 알고있는 지식을 전달해주며 함께 성장했다. 앞으로도 다양한 사람들과 많은 정보를 교류하는 사람이 되고자 한다!

## 🟢추가 목표
이번 1차 프로젝트를 마치며, 원래는 끝났어야할 우리가 모두의 긍정적 피드백과 의견을 모아 앞으로 2차 프로젝트를 이어나가고자 한다.

차후 계획 수립은 12-26에 이루어질 예정이다.

- 구현하지 못한 JavaScript 구현 (상세보기탭, 메뉴탭, 카테고리, 음료정보)

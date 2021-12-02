# RIDIBOOKSL 2nd PROJECT
<img width="1660" alt="스크린샷 2021-10-31 오후 3 38 04" src="https://user-images.githubusercontent.com/81367886/139572236-777383f0-dfa0-4c6f-aa20-1e49056b26aa.png">

## 프로젝트 소개
[리디북스](https://ridibooks.com/) 를 모티브로 한 팀 프로젝트<br>
웹툰/웹소설, 전자책, 만화까지 취향에 딱 맞는 다양한 컨텐츠를 제안하고 제공하는 웹사이트
- 기간 : 2021. 10. 18. ~ 2021. 10. 29.
- [Backend GitHub](https://github.com/wecode-bootcamp-korea/25-2nd-RIDIBOOKSL-backend)
- [프로젝트 시연 영상](https://youtu.be/AiPwNHyOqH4)
- 초기 세팅부터 직접 구현하였으며, 모든 데이터는 프론트와 백의 통신으로 받아왔습니다.

## 인원 구성
- **Frontend**: 김수민, 김용현, 박세연, 이나영
- **Backend**: 이기용, 이정아

## 프로젝트 선정이유
- 최근 다양한 e-book 컨텐츠들이 생산되고 수요도 지속적으로 증가함에 따라 커져가고 있는 e-컨텐츠 시장에서 큰 점유율로 시장을 선도하고 있는 리디북스 사이트를 모티브로 하였습니다. 
- 단순히 e-컨텐츠를 판매만 하는 것이 아닌 다양한 방법으로 e-컨텐츠들을 소개하고 누구나 쉽게 접할 수 있도록 다양한 검색기능이나 미리보기 기능들을 제공하는 것이 매력적인 포인트라고 생각하였습니다.
- 사용자가 쉽게 이용할 수 있는 심플하면서도 직관적인 깔끔한 UI가 매력적이라고 생각하였습니다.


## 사용한 기술 스택
- **Frontend**: `HTML/CSS` `JSX` `React(CRA)` `Styled-components` (Library: `React-router-DOM`, `React-pdf`, `React-slick`)
- **Backend**: `Python`, `Django Web Framework`, `AWS`, `MySQL`
- **Common**: 버전관리 `Git & GitHub`, 소통 `Slack`,  일정관리 [Trello](https://trello.com/b/zSVgJt0Z/%EB%A6%AC%EB%94%94%EB%B6%81%EC%8A%AC%EB%B6%81%EC%8A%ACridibooksl)

## 내가 구현한 부분
- **소셜 로그인**: 카카오 로그인 API와 JWT를 이용하여 소셜 로그인 레이아웃 및 기능구현
- **카테고리**: Mock data를 이용하여 도서 카테고리 및 기타 세부 카테고리 레이아웃 및 기능구현
- **카트 & 위시리스트**: 카트에 담긴 컨텐츠 선택 및 삭제, 총 결제 금액 확인 페이지 레이아웃 및 기능구현
- **상세 페이지**: react-pdf 라이브러리를 이용하여 e-book 미리보기 뷰어 레이아웃 및 기능구현 

## 이 프로젝트를 통해 배운점 및 느낀점
- 내 필요에 맞게 적절하게 라이브러리를 이용하여 작업효율을 높일 수 있다는 것, 그렇지만 무조건적으로 라이브러리를 쓰는것이 좋은 것만은 아니다라는 것을 배울 수 있었다.
- 요즘 거의 모든 사이트에서 볼 수 있는 소셜 로그인 기능을 구현하면서 OAuth 2.0 개념에 대해서 이해할 수 있었다.
- Styled-Components를 사용하여 처음 프로젝트를 진행하면서 좀 더 익숙해질 수 있었다.
- react-hook을 이용하여 함수형 컴포넌트에서 상태를 관리하고 렌더링 직후 작업 설정하는 과정에 익숙해질 수 있었다.

## 레퍼런스
- 이 프로젝트는 [리디북스](https://ridibooks.com/) 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.


# 프로젝트 소개
![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/66675699/180681932-cf47ff6c-718a-464c-b40b-06e437539264.gif)

## 프로젝트명 'DREAM'

- 한정판을 거래하는 [KREAM](https://kream.co.kr/)을 클론하는 프로젝트
- 입찰기능을 제외한 클론 사이트
- 개발 기간: 2022-07-11 ~ 2022-07-29
- 개발 인원: 6명<br>
  FE : 손소희, 정진우, 유관희<br>
  BE : 최수진, 김예찬, 최정훈

### GitHub 주소

- [Dream Frontend Github](https://github.com/wecode-bootcamp-korea/justcode-5-2nd-dream-front)
- [Dream Backend Github](https://github.com/wecode-bootcamp-korea/justcode-5-2nd-dream-back)

## 적용 기술

- DB : mySQL, Prisma, DB-diagram
- FE : HTML, JAVASCRIPT, REACT, SCSS, STYLED-COMPONENTS
- BE : Node.js, Express.js, bcrypt, jsonwebtoken
- 공통 : RESTful API, MVC Pattern, Github, Slack, Notion

### 협업 도구

- Github, Slack, Notion

## DB Modeling

![](https://velog.velcdn.com/images/jeongssi94/post/49cca761-78e9-4331-96bc-8f130f913e3a/image.png)

#### 멤버별 기능 분담

손소희

- 마이 페이지
- SHOP 페이지

정진우

[로그인 / 회원가입]

- 정규표현식을 활용한 유효성 검사 기능 구현
- 카카오 로그인 시 query-string 라이브러리를 활용하여 <br>
  redirect url으로 전달되는 데이터를 로컬 스토리지에 저장하는 기능 구현

<div style="display:flex">
<img src="https://user-images.githubusercontent.com/66675699/180680873-d5628187-1fb9-48d1-9dd8-6d7ccf16592c.png" style="width:500px; height:500px"/>
<img src="https://user-images.githubusercontent.com/66675699/180680940-6fb506f2-8bf1-4b4c-bc1d-07f946f0d388.png" style="width:500px; height:500px"/>
</div>

<br><br>
[제품 상세 페이지]

- 백엔드와 통신을 통한 제품 상세 정보를 가져오기 기능 구현
- 관심상품 등록 및 해제 기능 구현
- 사이즈 모달 구현
- 구매 전 확인 부분 토글 기능 구현
- 다른 상품 페이지로 이동하는 기능 구현

<div style="display:flex">
<img width="500" alt="스크린샷 2022-07-23 오후 8 42 12" src="https://user-images.githubusercontent.com/66675699/180681125-d6af9f88-ea97-4f1d-a875-9c76bb0ee1a6.png">
  <img width="500" height="250" alt="스크린샷 2022-07-23 오후 8 42 48" src="https://user-images.githubusercontent.com/66675699/180681147-75615acd-3b5c-4018-bfe6-3714c1ee18a7.png">
  <img width="500" height="350" alt="스크린샷 2022-07-23 오후 8 42 54" src="https://user-images.githubusercontent.com/66675699/180681166-d9a1ef36-5118-4224-bf66-a9bd1913b810.png">
 
 <img width="500"  height="350" alt="스크린샷 2022-07-23 오후 9 23 10" src="https://user-images.githubusercontent.com/66675699/180682883-a0bc0acf-c205-4c67-b14f-37c9fd4b805e.png">
</div>

- react-slick을 활용한 슬라이더 구현

![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/66675699/180682591-562698be-6dae-4854-9976-1c06b9f66820.gif)

<br>
[구매 / 판매 페이지]

- useState와 useEffect 훅을 활용해 체크 박스 체크 여부 확인 기능 구현
- 페이지 이동 시 구매 및 판매에 필요한 정보들을
  state로 넘겨주는 기능 구현<br>
  ![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/66675699/180681576-6d815391-1f7c-49d7-aa50-933d9c2b761a.gif)
  ![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/66675699/180681790-b1a9427f-1284-44f7-9121-d0cbaaf0597e.gif)

유관희

- 메인 페이지
- Header / Footer 구현
- STYLE

최수진

- 회원가입,로그인 API/소셜 로그인(카카오)
- SHOP 페이지 API
- 제품 상세 페이지 API

김예찬

- 메인 페이지 API
- STYLE 페이지 API
- 관심상품 API

최정훈

- 마이 페이지 API
- 구매 / 판매 페이지 API

## Reference

이 프로젝트는 크림 사이트를 참조하여 학습목적으로 만들었습니다.
실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
이 프로젝트에서 사용하고 있는 사진 대부분은 위코드에서 구매한 것이므로 해당 프로젝트 외부인이 사용할 수 없습니다.

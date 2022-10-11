리액트 라우터를 활용한 SPA 개발<br/>

<img width="592" alt="홈 페이지" src="https://user-images.githubusercontent.com/102382351/195000436-fdbe8b95-c462-4326-85b4-77fbb21e27fe.png">
- 링크 컴포넌트를 사용하여 페이지 이동<br/>
- 중첩된 라우트를 통해 공통 레이아웃 사용<br/>
- Header에서는 useNavigate를 사용하여 뒤로가기, 게시글 목록으로 이동<br/>
<br/>
<img width="723" alt="소개 페이지" src="https://user-images.githubusercontent.com/102382351/195000284-64e4d47d-c25d-4a83-871a-bb01923a8ab0.png">
- 쿼리스트링을 사용하여 detail, mode 표시<br/>
<br/>
<img width="613" alt="프로필 페이지" src="https://user-images.githubusercontent.com/102382351/195000289-cfa8a388-b270-46ce-90b1-678d7114420e.png">
- URL 파라미터를 사용하여 프로필 페이지 이동<br/>
- URL 파라미텅 이름은 라우트 설정 시 Route 컴포넌트의 path props를 설정<br/>
<br/>
<img width="590" alt="게시글 페이지" src="https://user-images.githubusercontent.com/102382351/195000280-c039c833-e842-4248-8a9b-e066c2d8170e.png">
- 중첩된 라우트, Outlet 컴포넌트 사용<br/>
- NavLink를 사용하여 링크 경크 경로와 라우트 경로가 일치하는 경우, 특정 CSS 적용<br/>
<br/>
<img width="588" alt="로그인 페이지" src="https://user-images.githubusercontent.com/102382351/195000276-d7a5a3f6-57b7-4e0c-94c4-76a13bc9af29.png">
- Navigate 컴포넌트를 사용하여 /mypage에서 /login 페이지로 이동<br/>

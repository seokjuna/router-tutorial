리액트 라우터를 활용한 SPA 개발
<br/>
<img width="634" alt="홈 페이지" src="https://user-images.githubusercontent.com/102382351/194698268-9ea54175-4c00-4606-aede-611f5d66fd8e.png">
- 링크 컴포넌트를 사용하여 페이지 이동<br/>
- 중첩된 라우트를 통해 공통 레이아웃 사용<br/>
- Header에서는 useNavigate를 사용하여 뒤로가기, 게시글 목록으로 이동<br/>
<br/>
<img width="635" alt="소개 페이지" src="https://user-images.githubusercontent.com/102382351/194698280-a2c0fcf9-71c8-4078-88bc-7103e1fbdd99.png">
- 쿼리스트링을 사용하여 detail, mode 표시<br/>
<br/>
<img width="633" alt="프로필 페이지" src="https://user-images.githubusercontent.com/102382351/194698285-5a70a8c2-4fa7-4fe4-92c9-1f9eecf9495f.png">
- URL 파라미터를 사용하여 프로필 페이지 이동<br/>
- URL 파라미텅 이름은 라우트 설정 시 Route 컴포넌트의 path props를 설정<br/>
<br/>
<img width="633" alt="게시글 페이지" src="https://user-images.githubusercontent.com/102382351/194698291-08fdd06c-a8e8-429f-99bb-569d14c0e18b.png">
- 중첩된 라우트, Outlet 컴포넌트 사용<br/>
- NavLink를 사용하여 링크 경크 경로와 라우트 경로가 일치하는 경우, 특정 CSS 적용<br/>
<br/>
<img width="633" alt="로그인 페이지" src="https://user-images.githubusercontent.com/102382351/194698304-9c72f160-e49e-4da3-8b99-022dee0c1df6.png">
- Navigate 컴포넌트를 사용하여 /mypage에서 /login 페이지로 이동<br/>

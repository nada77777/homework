# 마크업
    
### 아이디와 비밀번호 필수 입력 서식
- required 속성을 사용
  
<hr/>

### IP 보안 텍스트 클릭 시 ip_secruity.html 파일 새창에 보이도록 구현
- target="_blank" 속성을 사용

<hr/>

### 로그인 상태유지와 IP 보안 ON/OFF 스위치 키보드로도 조작 가능 기능
- 기본으로 키보드로 접근이 가능해서? 일단 넘겼다

<hr/>

# 스타일링

### 반응형으로 구현 (768px 미만 모바일 / 768px 이상 데스크탑)
- @media (min-width: 768px) 미디어 쿼리 사용

<hr/>

### 글자 크기 및 여백 모두 rem 단위로 설정할 것
- 1rem = 16px
- 기본 글자 크기 및 기본 색상은 변수처리

<hr/>
    
### 모바일 환경에서 IP 보안 ON/OFF 스위치는 사용자에게 제공되지 않도록 구현
- 모바일 환경에서는 해당 요소에 display:none, 데스크탑 모드에서는 display:flex를 사용

<hr/>

### 로그인 상태 변경에 따라 체크박스 배경 이미지 교체
- 해당 input checkbox 요소에 unchecked.svg를 배경 이미지를 기본으로 설정
-  input checkbox 상태가 true로 변경시 input:checked style을 사용해 배경 이미지를 checked.svg로 변경

<hr/>

WAI-ARIA를 접근성 준수에 대한 이해가 더 필요한 것 같다
화면 넓이에 따른 박스 컨테이너 크기(반응형) 연습 필요
많이 배워서 재료가 많아져도 어디에 어떻게 적용해야 하는지를 숙지해야겠다






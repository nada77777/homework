
## 수행 과정

### 아바타 이미지 간의 간격

- .avatar:nth-child(n + 2)를 사용하여 첫 요소를 제외하고 margin-left 20px를 적용
- 상하 간격은 margin: 10px 0를 사용하여 적용

<hr/>

### 아바타의 상태 정보

- 복수 클래스를 사용해 아바타 상태 정보의 배경색을 적용
- 이미지와 상태 정보를 묶고있는 부모 요소에 relative, 상태 정보에 absolute 적용해서 위치 설정

<hr/>

### flex를 지원하는 환경

- flex지원 환경에서 행 반전을 위해 아바타를 4개씩 하나의 부모 요소로 묶고 flex-direction의 column-reverse을 적용

<hr/>

설명을 들을 당시 이해를 했다 생각해도<br/>막상 혼자서 해보니 배운 내용을 모두 사용해 구현이 어렵고<br/>결국 주먹구구식으로 하나하나 적용하게 되었다

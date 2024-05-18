# apple 제품 카드

그리드를 사용하여 구현하고 구현 결과를 움직이는 이미지로 생성하여 삽입해주세요.

# 마크업
    
### 해상도에 따라 그리드 설정 변경하기
- 기본 열을 ```grid-template-columns: 1fr 1fr``` 설정
-``` .ipad-pro,
  .ipad-air,
  .iphone-pro {
    grid-column: 1/3;
  }```
  
<hr/>

### 화면이 작아질때 배경 이미지 변경
-```@media (max-width: 1024px) {.iphone-pro {
    background-image: image-set(
      url(/products/iphone15_pro.jpeg) 1x,
      url(/products/iphone15_pro_2x.jpeg) 2x);
  }
}```


# 설치

```
npm i
```

# 실행

```
npm run start
```

# 사용법

`targetUrls` 배열에 원하는 상품후기 페이지 url을 기입하면됨. 1개씩만 크롤링하는 것을 권장 여러개하면 차단될 수 있음.

```
const targetUrls = [
  'https://www.musinsa.com/review/goods/3447526',
  //'https://www.musinsa.com/review/goods/3987163',
];
```

크롤링 결과는 result 폴더에 상품 코드명이름의 csv파일로 저장됨

## 사용된 라이브러리

`playwright`, `xlsx`

# 업데이트

- 24.9.20  
  무신사 요소 클래스명 최신화

- 24.9.24  
  리뷰 총 갯수 정규표현식으로 가져오도록 변경

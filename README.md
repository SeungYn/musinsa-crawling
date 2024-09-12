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

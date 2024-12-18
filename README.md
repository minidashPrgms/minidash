# minidash

MiniDash는 Lodash에서 영감을 받은 경량화되고 간소화된
JavaScript 유틸리티 라이브러리로, JavaScript 코딩을 더 쉽고
효율적으로 만들어 줍니다. 배열, 객체, 문자열 작업에 일반적으로
사용되는 유틸리티 함수 세트를 제공하여, 소형에서 중형 크기의 웹
프로젝트에 완벽한 선택입니다.

## 특징

-  배열, 객체, 문자열을 다루기 위한 사용하기 쉬운 API 제공
-  외부 의존성 없는 경량화
-  누구에게나 열여있는 오픈소스

## 설치

```bash
npm install minidash
```

## 사용 방법

```js
const minidash = require('minidash');

checkeArr([1, 2]); // true
capitalize('aBCDefg'); // Abcdefg
findEvenNums([1, 2, 3, 4]); // [2, 4]
findOddNums([1, 2, 3, 4]); // [1, 3]
```

## 기여하는 방법

1. 저장소를 fork 해주세요.
2. 새 브랜치 만들고 수정 사항을 푸쉬해주세요.
3. PR을 요청하고 문서 양식 맞춰서 내용 기입해 주세요.

## 라이센스

MIT 라이센스에 따라 제공되는 오픈 소스 소프트웨어입니다.

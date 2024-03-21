# 나눔스퀘어
<a href="https://help.naver.com/service/30016/contents/18088?osType=PC&lang=ko">나눔스퀘어 라이선스 안내</a>   
<a href="http://hangeul.naver.com/2016/nanum">나눔스퀘어 시스템 폰트 다운로드</a>  
<br>

**옵션**   
Regular(400), Bold(700), Extra Bold(800), Light(300) 지원됩니다. + ac(R, B, EB, L) 추가  

<br>

**사용방법**   
## CSS 설정
```css
font-family: 'NanumSquare';
```
## 링크방식
**HTML**
```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/moonspam/NanumSquare@2.0/nanumsquare.css">
```

## 임포트방식
**CSS**
```css
@import url(https://cdn.jsdelivr.net/gh/moonspam/NanumSquare@2.0/nanumsquare.css);
```   

## CSS 적용예
```
body		{ font-family: 'NanumSquare', sans-serif }
.normal		{ font-weight: 400 }
.bold		{ font-weight: 700 }
.bolder		{ font-weight: 800 }
.light		{ font-weight: 300 }
```   

## AC 적용예
```
body { font-family: 'NanumSquareAc', sans-serif }
```   

## 파일로 적용
<a href="https://github.com/moonspam/NanumSquare">나눔스퀘어 웹폰트 다운로드</a>

```css
@font-face {
 font-family: 'NanumSquare';
 font-weight: 300;
 src: url(NanumSquareL.eot);
 src: local('☺'),
      url(NanumSquareL.eot?#iefix) format('embedded-opentype'),
      url(NanumSquareL.woff2) format('woff2'),
      url(NanumSquareL.woff) format('woff'),
      url(NanumSquareL.ttf) format('truetype');
}
@font-face {
 font-family: 'NanumSquare';
 font-weight: 400;
 src: url(NanumSquareR.eot);
 src: local('☺'),
      url(NanumSquareR.eot?#iefix) format('embedded-opentype'),
      url(NanumSquareR.woff2) format('woff2'),
      url(NanumSquareR.woff) format('woff'),
      url(NanumSquareR.ttf) format('truetype');
}
@font-face {
 font-family: 'NanumSquare';
 font-weight: 700;
 src: url(NanumSquareB.eot);
 src: local('☺'),
      url(NanumSquareB.eot?#iefix) format('embedded-opentype'),
      url(NanumSquareB.woff2) format('woff2'),
      url(NanumSquareB.woff) format('woff'),
      url(NanumSquareB.ttf) format('truetype');
}
@font-face {
 font-family: 'NanumSquare';
 font-weight: 800;
 src: url(NanumSquareEB.eot);
 src: local('☺'),
      url(NanumSquareEB.eot?#iefix) format('embedded-opentype'),
      url(NanumSquareEB.woff2) format('woff2'),
      url(NanumSquareEB.woff) format('woff'),
      url(NanumSquareEB.ttf) format('truetype');
}

/* AC */
@font-face {
 font-family: 'NanumSquareAc';
 font-weight: 300;
 src: url(NanumSquareAcL.eot);
 src: local('☺'),
      url(NanumSquareAcL.eot?#iefix) format('embedded-opentype'),
      url(NanumSquareAcL.woff2) format('woff2'),
      url(NanumSquareAcL.woff) format('woff'),
      url(NanumSquareAcL.ttf) format('truetype');
}
@font-face {
 font-family: 'NanumSquareAc';
 font-weight: 400;
 src: url(NanumSquareAcR.eot);
 src: local('☺'),
      url(NanumSquareAcR.eot?#iefix) format('embedded-opentype'),
      url(NanumSquareAcR.woff2) format('woff2'),
      url(NanumSquareAcR.woff) format('woff'),
      url(NanumSquareAcR.ttf) format('truetype');
}
@font-face {
 font-family: 'NanumSquareAc';
 font-weight: 700;
 src: url(NanumSquareAcB.eot);
 src: local('☺'),
      url(NanumSquareAcB.eot?#iefix) format('embedded-opentype'),
      url(NanumSquareAcB.woff2) format('woff2'),
      url(NanumSquareAcB.woff) format('woff'),
      url(NanumSquareAcB.ttf) format('truetype');
}
@font-face {
 font-family: 'NanumSquareAc';
 font-weight: 800;
 src: url(NanumSquareAcEB.eot);
 src: local('☺'),
      url(NanumSquareAcEB.eot?#iefix) format('embedded-opentype'),
      url(NanumSquareAcEB.woff2) format('woff2'),
      url(NanumSquareAcEB.woff) format('woff'),
      url(NanumSquareAcEB.ttf) format('truetype');
}
```

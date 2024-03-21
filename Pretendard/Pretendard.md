# 프리텐다드 글꼴 웹폰트 적용방법

[참조사이트](https://creativestudio.kr/3179)   
[시스템폰트 다운로드](./Pretendard-sy.zip)   
[웹폰트 다운로드](./Pretendard.zip)

## CSS설정
```css
    font-family: 'NanumSquareNeo';
```

## 일반적인 경우  
**CSS**
```css
@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');
```   

**HTML**
```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css" />
```
   
<br>

## 다이나믹 서브젯 웹폰트
다소 웹폰트 용량이 무겁게 느껴진다면 동적 서브셋을 제공하는 다이나믹 서브젯으로 적용하면 된다. 페이지에 포함된 글자만 선택적으로 다운로드 하는 방식이며, 위의 경우보다 훨씬 빠른 웹페이지 로딩이 장점이다.

**CSS**
```css
@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard-dynamic-subset.css');
```   

**HTML**
```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard-dynamic-subset.css" />
```
   
<br>

## 가변 글꼴로 적용
이 방법은 가변글꼴로 적용하는 방식이며, font-weight 속성을 선언하여 보다 다양한 굵기에서도 선명함이 유지된다.

**CSS**
```css
@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/variable/pretendardvariable.css');
```   

**HTML**
```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/variable/pretendardvariable.css" />
```
   
<br>

## 파일로 적용
이 방법은 가변글꼴로 적용하는 방식이며, font-weight 속성을 선언하여 보다 다양한 굵기에서도 선명함이 유지된다.

**CSS**
```css
@font-face {
	font-family: 'Pretendard Variable';
	font-weight: 45 920;
	font-style: normal;
	font-display: swap;
	src: local('Pretendard Variable'), url('./images/PretendardVariable.woff2') format('woff2-variations');
}

@font-face {
    font-family: 'Pretendard';
    src: url('./images/Pretendard-Thin.woff') format('woff');
    font-weight: 100;
    font-display: swap;
}
@font-face {
    font-family: 'Pretendard';
    src: url('./images/Pretendard-ExtraLight.woff') format('woff');
    font-weight: 200;
    font-display: swap;
}
@font-face {
    font-family: 'Pretendard';
    src: url('./images/Pretendard-Light.woff') format('woff');
    font-weight: 300;
    font-display: swap;
}
@font-face {
    font-family: 'Pretendard';
    src: url('./images/Pretendard-Regular.woff') format('woff');
    font-weight: 400;
    font-display: swap;
}
@font-face {
    font-family: 'Pretendard';
    src: url('./images/Pretendard-Medium.woff') format('woff');
    font-weight: 500;
    font-display: swap;
}
@font-face {
    font-family: 'Pretendard';
    src: url('./images/Pretendard-SemiBold.woff') format('woff');
    font-weight: 600;
    font-display: swap;
}
@font-face {
    font-family: 'Pretendard';
    src: url('./images/Pretendard-Bold.woff') format('woff');
    font-weight: 700;
    font-display: swap;
}
@font-face {
    font-family: 'Pretendard';
    src: url('./images/Pretendard-ExtraBold.woff') format('woff');
    font-weight: 800;
    font-display: swap;
}
@font-face {
    font-family: 'Pretendard';
    src: url('./images/Pretendard-Black.woff') format('woff');
    font-weight: 900;
    font-display: swap;
}
```   
<br>

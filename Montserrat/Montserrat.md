# Montserrat
[참조사이트](https://wess.tistory.com/483)  
[시스템폰트 다운로드](https://fonts.google.com/specimen/Montserrat)
[웹폰트 다운로드](https://github.com/webfontworld/Montserrat)

## 폰트두께
- 100 ~ 900

## CSS 설정
```css
font-family: 'Montserrat';
```

## HTML (Link)
```html
<link href="https://webfontworld.github.io/Montserrat/Montserrat.css" rel="stylesheet">
```

## CSS (Import)
```css
@import url('https://webfontworld.github.io/Montserrat/Montserrat.css');
```

## CSS (font-face)
```css
@font-face {
    font-family: 'Montserrat';
    font-weight: 100;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Thin.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Thin.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Thin.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Thin.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Thin.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Montserrat';
    font-weight: 200;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-ExtraLight.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-ExtraLight.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-ExtraLight.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-ExtraLight.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-ExtraLight.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Montserrat';
    font-weight: 300;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Light.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Light.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Light.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Montserrat';
    font-weight: 400;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Regular.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Regular.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Regular.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Montserrat';
    font-weight: 500;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Medium.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Medium.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Medium.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Medium.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Montserrat';
    font-weight: 600;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-SemiBold.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-SemiBold.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-SemiBold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-SemiBold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-SemiBold.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Montserrat';
    font-weight: 700;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Bold.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Bold.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Bold.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Montserrat';
    font-weight: 800;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-ExtraBold.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-ExtraBold.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-ExtraBold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-ExtraBold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-ExtraBold.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Montserrat';
    font-weight: 900;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Black.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Black.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Black.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Black.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Montserrat/Montserrat-Black.ttf') format("truetype");
    font-display: swap;
} 
```
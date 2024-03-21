# Poppins
[참조사이트](https://wess.tistory.com/496)  
[시스템폰트 다운로드](https://fonts.google.com/specimen/Poppins?query=po)
[웹폰트 다운로드](https://github.com/webfontworld/Poppins)

## 폰트두께
- 100
- 200
- 300
- 400
- 500
- 600
- 700
- 800
- 900

## CSS 설정
```css
font-family: 'Poppins';
```

## HTML (Link)
```html
<link href="https://webfontworld.github.io/Poppins/Poppins.css" rel="stylesheet">
```

## CSS (Import)
```css
@import url('https://webfontworld.github.io/Poppins/Poppins.css');
```

## CSS (font-face)
```css
@font-face {
    font-family: 'Poppins';
    font-weight: 100;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Thin.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Thin.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Thin.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Thin.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Thin.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Poppins';
    font-weight: 200;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-ExtraLight.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-ExtraLight.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-ExtraLight.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-ExtraLight.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-ExtraLight.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Poppins';
    font-weight: 300;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Light.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Light.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Light.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Poppins';
    font-weight: 400;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Regular.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Regular.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Regular.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Poppins';
    font-weight: 500;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Medium.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Medium.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Medium.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Medium.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Poppins';
    font-weight: 600;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-SemiBold.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-SemiBold.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-SemiBold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-SemiBold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-SemiBold.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Poppins';
    font-weight: 700;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Bold.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Bold.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Bold.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Poppins';
    font-weight: 800;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-ExtraBold.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-ExtraBold.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-ExtraBold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-ExtraBold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-ExtraBold.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'Poppins';
    font-weight: 900;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Black.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Black.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Black.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Black.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/Poppins/Poppins-Black.ttf') format("truetype");
    font-display: swap;
} 
```
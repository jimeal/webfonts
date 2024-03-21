# BC 카드체
[참조사이트](https://wess.tistory.com/244)  
[시스템폰트 다운로드](https://paybooc.co.kr/app/paybooc/RPastEventDetail.do?evntNo=2020040025)   
[웹폰트 다운로드](https://github.com/webfontworld/bccard)

## CSS설정하기
```css
font-family: 'BCcard';
```

## HTML (link)
```html
<link href="https://webfontworld.github.io/bccard/BCcard.css" rel="stylesheet">
```

## CSS (Import)
```css
@import url('https://webfontworld.github.io/bccard/BCcard.css');
```

## CSS (font-face)
```css
@font-face {
    font-family: 'BCcard';
    font-weight: 400;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/bccard/BCcardLight.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/bccard/BCcardLight.eot?#iefix') format('embedded-opentype'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/bccard/BCcardLight.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/bccard/BCcardLight.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/webfontworld/bccard/BCcardLight.ttf') format("truetype");
    font-display: swap;
} 
@font-face {
    font-family: 'BCcard';
    font-weight: 700;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/bccard/BCcardBold.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/bccard/BCcardBold.eot?#iefix') format('embedded-opentype'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/bccard/BCcardBold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/bccard/BCcardBold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/bccard/BCcardBold.ttf') format("truetype");
    font-display: swap;
}
```
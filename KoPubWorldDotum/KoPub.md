# KoPubWorld 돋움체
[참조사이트](https://wess.tistory.com/264)  
[시스템폰트 다운로드](https://www.kopus.org/biz-electronic-font2/)  
[웹폰트 다운로드](https://github.com/webfontworld/kopus)

## 폰트두께
- 300
- 500
- 700

## CSS설정하기
```css
font-family: 'KoPubWorldDotum';
```

## HTML (Link)
```html
<link href="https://webfontworld.github.io/kopus/KoPubWorldDotum.css" rel="stylesheet">
```

## CSS (Import)
```css
@import url('https://webfontworld.github.io/kopus/KoPubWorldDotum.css');
```

## CSS (font-face)
```css
@font-face {
    font-family: 'KoPubWorldDotum';
    font-weight: 300;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumLight.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumLight.eot?#iefix') format('embedded-opentype'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumLight.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumLight.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumLight.ttf') format("truetype");
    font-display: swap;
}
@font-face {
    font-family: 'KoPubWorldDotum';
    font-weight: 500;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumMedium.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumMedium.eot?#iefix') format('embedded-opentype'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumMedium.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumMedium.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumMedium.ttf') format("truetype");
    font-display: swap;
}
@font-face {
    font-family: 'KoPubWorldDotum';
    font-weight: 700;
    font-style: normal;
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumBold.eot');
    src: url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumBold.eot?#iefix') format('embedded-opentype'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumBold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumBold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/webfontworld/kopus/KoPubWorldDotumBold.ttf') format("truetype");
    font-display: swap;
}
```
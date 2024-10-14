# 어비 세현체

[배포처 바로가기](http://uhbeefont.com/font/w/UhBeeSe_hyun.html)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `UhBee Sehyun`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/UhBeeSehyun/UhBeeSehyun.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/UhBeeSehyun/UhBeeSehyun.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'UhBee Sehyun';
  font-weight: normal;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/UhBeeSehyun/UhBeeSehyun.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/UhBeeSehyun/UhBeeSehyun.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/UhBeeSehyun/UhBeeSehyun.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/UhBeeSehyun/subsets/UhBeeSehyun-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/UhBeeSehyun/subsets/UhBeeSehyun-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "UhBee Sehyun", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
방송, 서적, 이모티콘 제작 등 상업적 사용에도 무료입니다. 단, 어비폰트 자체를 사고 파는 행위자체는 불법입니다. 
상업적 사용된 곳은 font@uhbee.net 메일로 결과물이 어디에 쓰여졌는지만 알려주세요. 출처 안쓰셔도 되며, 허락 안받으셔도 됩니다. 
주의점: 어비폰트는 무료로 제공되는 폰트입니다. 
어비폰트를 가공하여 apk, WebFont 등의 모든 변환 결과물들은 무료로 제공되어야만 합니다. 
유료판매나 조건부 교환은 법적책임을 물게 됩니다.  

어비폰트는 상업적 용도에도 무료입니다. (인쇄, 방송, 인터넷 등 모든 사용가능) 
문의 사항 font@uhbee.net  

-안내사항 
폰트가 다운로드 되지 않는 경우 아래 사이트에서 다운로드 바랍니다. 
http://uhbeefont.com/
```

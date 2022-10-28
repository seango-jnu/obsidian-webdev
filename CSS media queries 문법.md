> 참조
> https://developer.mozilla.org/ko/docs/Web/CSS/Media_Queries/Using_media_queries

## Media types
- all
- screen
- print
- speach

## link 태그 문법
```html
<!--기본 문법-->
<link rel="stylesheet" media="_mediatype_ and|not|only (_expressions_)" href="print.css">
```
### 예제
```html
<link rel="stylesheet" media="print" href="print.css">
```
## Media query 문법
```css
@media not|only _mediatype_ and (_expressions_) {  
	_CSS-Code;_
}
```
### 예제
```css
@media screen and (min-width: 480px) {  
	#leftsidebar {width: 200px; float: left;}  
	#main {margin-left: 216px;}
}
```
## 대표적인 expressions
- max-width
- min-width
- orientation: portrait | landscape
- (-webkit-min-device-pixel-ratio: 1.5)
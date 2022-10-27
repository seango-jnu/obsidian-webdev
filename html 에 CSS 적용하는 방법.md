### Inline style
<iframe height="200" style="width: 100%;" src="https://codepen.io/seango-jnu/embed/LYrEXVy?default-tab=html%2Cresult&editable=true" ></iframe>

### Style tag 이용
<iframe height="300" style="width: 100%;" src="https://codepen.io/seango-jnu/embed/bGKNQVO?default-tab=html%2Cresult&editable=true"></iframe>

### css file 이용
#### css 파일
```css
/* ex : common.css file*/
.beautiful-css { color: turquoise; }
```
#### html 파일
```html
<!DOCTYPE html>  
<html lang="ko">  
<head>  
    <meta charset="UTF-8">  
    <title>Index</title>  
    <link rel="stylesheet" type="text/css" href="common.css">  
</head>  
<body>  
    <h2 class="beautiful-css">외부 파일 css</h2>  
</body>  
</html>
```
# HTML
## HTML의 기본틀
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
1. `<title></title>`  
    : Chrome Tab의 이름 설정
2. `<body></body>`  
    : 화면상으로 보이는 내용물들


## `<body></body>`
1. `<h1></h1>`  
    : 계층을 표시할때 사용하는 태그, 1~6까지 있으며 숫자가 작을 수록 글자의 크기는 크다.
2. `<p></p>`  
    : 본문 내용을 넣는 태그, 내용을 `<strong></strong>` or `<b></b>`테그로 감싸면 강조해주는 역할을 한다.
3. `<ul></ul>` and `<ol></ol>`  
    : ul과 ol둘다 리스트를 만들어주는 태그, ul태그는 **순서가 없는**태그, ol은 **순서가 있는**태그.  
    3-1. `<li></li>`  
        : 리스트로서 표현할 내용을 감싸는 태그
4. `<a></a>`  
    : 하이퍼링크를 정의하는 태그, `href=""`속성을 추가하여 이동하는 페이지의 URL을 입력한다.
5. `<img src="./dog.jpg">`  
    : 이미지를 보여줄 수 있는 태그, `src=""`로 보여주고자 하는 이미지의 경로를 작성. **태그가 쌍이 아닌 하나로 구성**
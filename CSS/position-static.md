## position-static
<br/>

모든 요소의 기본값이며 가장 일반적인 상태입니다

top, right, bottom, left, z-index 속성이 아무런 영향도 주지 않습니다

index.html

```html
<body>
        <div id="a">A</div>
        <div id="b">B</div>
        <div id="c">C</div>
    </body>
```

style.css

```css
div {
    width: 100px;
    height: 100px;
}

#a {
    background-color: red;
    position: static;
}

#b {
    background-color: green;
    position: static;
}

#c {
    background-color: blue;
    position: static;
}
```

static 속성은 설정 전, 후가 같습니다
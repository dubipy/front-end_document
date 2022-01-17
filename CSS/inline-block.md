## inline-block
<br/>

inline-blcok는 말 그대로 Inline에 block 능력을 덮어서 같이 사용할 수 있습니다 기본적인 가로로 흐름과 동시에 블록처럼 영역을 잡을 수 있습니다

index.html

```html
<body>
        <span class="span"></span>
        <span class="span"></span>
        <span class="span"></span>
        <span class="span"></span>
        <span class="span"></span>
        <span class="span"></span>
        <span class="span"></span>
        <span class="span"></span>
        <span class="span"></span>
        <span class="span"></span>
        <span class="span"></span>
        <span class="span"></span>
    </body>
```

style.css

```css
span {
    width: 100px;
    height: 100px;
    color: red;
    background-color: seagreen;
    display: inline-block;
}
```

<img src="./inline-block/1.png">

성질 자체는 Inlin과 비슷합니다 동일 라인에 여러 태그를 붙일 때 쓸 수 있고, inline에선 사용하지 못하는 아래 항목과는 달리 inline-block는 사용 가능합니다 그러니 inline 대신 우리는 inline-block를 더 많이 사용하게 될 것입니다

(inline 적용시 사용못함 → inline-block는 사용가능)

<img src="./inline-block/2.png">
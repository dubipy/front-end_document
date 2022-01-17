## background-attachment
<br/>

요소가 스크롤 될 때 배경 이미지의 스크롤 여부(특성) 설정
<br/>

|값|의미|기본값|
|------|---|---|
|scroll|배경 이미지가 요소를 따라서 같이 스크롤 됨|scroll|
|fixed|배경 이미지가 뷰포트(Viewport)에 고정되어,<br/>요소와 같이 스크롤 되지 않음||
|local|요소 내 스크롤 시 배경 이미지가 같이 스크롤됨||

<br/>

예시
```html
<div class="box"></div>
```
```css
body {
    height: 3000px;
}

.box {
    width: 500px;
    height: 350px;
    border: 2px dashed lightgray;
    background-image: url("https://lh3.googleusercontent.com/proxy/HLE_xccz7qnXinNGfe-Oz_mEZvrltIKAqlxvjlXZV4bnBFrR0g7xIANF7rPLSH8ECLXbNxRpsF1a-gBulUsD-OPU5hsihlHIAEhi3KyWmnYY0RVjiw");
    background-repeat: no-repeat;
    background-attachment: scroll;
}
```

```css
.box {
    width: 500px;
    height: 350px;
    border: 2px dashed lightgray;
    background-image: url("https://lh3.googleusercontent.com/proxy/HLE_xccz7qnXinNGfe-Oz_mEZvrltIKAqlxvjlXZV4bnBFrR0g7xIANF7rPLSH8ECLXbNxRpsF1a-gBulUsD-OPU5hsihlHIAEhi3KyWmnYY0RVjiw");
    background-repeat: no-repeat;
    background-attachment: fixed;
}
```
## background-position
<br/>

배경 이미지의 위치를 설정한다
<br/>

|값|의미|기본값|
|------|---|---|
|%|왼쪽 상단 모서리는 0% 0%,<br/>오른쪽 하단 모서리는 100% 100%|0 % 0% 앞은 X축 뒤는 Y축을 의미|
|방향|방향을 입력하여 위치 설정<br/>top, bottom, left, right, center||
|단위|px, em, cm 등 단위로 지정||

<br/>

값이 방향일 경우
<br/>

```html
background-position: 방향1 방향2;
```

<br/>

값이 단위( %, px 등)일 경우
<br/>

```html
background-position: x축 y축;
```
<br/>

예시
<br/>

```html
<div class="box"></div>
```
```css
.box {
    width: 500px;
    height: 350px;
    border: 2px dashed lightgray;
    background-image: url("https://lh3.googleusercontent.com/proxy/HLE_xccz7qnXinNGfe-Oz_mEZvrltIKAqlxvjlXZV4bnBFrR0g7xIANF7rPLSH8ECLXbNxRpsF1a-gBulUsD-OPU5hsihlHIAEhi3KyWmnYY0RVjiw");
    background-size: 100px;
    background-repeat: no-repeat;
    background-position: bottom left;
    background-position 값만 보고 x축 y축을 설정하였다
}
```
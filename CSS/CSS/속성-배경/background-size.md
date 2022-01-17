## background-size
<br/>

배경 이미지의 크기를 지정
<br/>

|값|의미|기본값|
|------|---|---|
|auto|- px, em, % 등 단위로 지정<br/>- width height 형태로 입력 가능(100px 200px)<br/>- width만 입력하면 비율에 맞게 지정됨(120px)|auto|
|cover|- 배경 이미지의 크기 비율을 유지하며<br/>요소의 더 넓은 너비에 맞춰짐<br/>- 이미지가 잘릴 수 있음||
|contain|- 배경이미지의 크기 비율을 유지하며,<br/>요소의 더 짧은 너비에 맞춰짐<br/>- 이미지가 잘리지않음|테스트3|

<br/>

```html
<div class="box"></div>
```
```css
.box {
    width: 400px;
    height: 300px;
    border: 2px solid blue;
    margin: 50px;
    background-image: url("https://lh3.googleusercontent.com/proxy/HLE_xccz7qnXinNGfe-Oz_mEZvrltIKAqlxvjlXZV4bnBFrR0g7xIANF7rPLSH8ECLXbNxRpsF1a-gBulUsD-OPU5hsihlHIAEhi3KyWmnYY0RVjiw");
    background-repeat: no-repeat;
    background-size: 200px;
    이미지에 대한 값을 정확히 모른다면 width값만 지정하는 것이 좋다
}
```

```css
.box {
    width: 400px;
    height: 300px;
    border: 2px solid blue;
    margin: 50px;
    background-image: url("https://lh3.googleusercontent.com/proxy/HLE_xccz7qnXinNGfe-Oz_mEZvrltIKAqlxvjlXZV4bnBFrR0g7xIANF7rPLSH8ECLXbNxRpsF1a-gBulUsD-OPU5hsihlHIAEhi3KyWmnYY0RVjiw");
    background-repeat: no-repeat;
    background-size: cover;
    세로보단 가로가 더 넓고 cover는 요소의 더 넓은 너비에 맞춰지므로 가로 사이즈에 맞게 만들어진다
}
```
```css
.box {
    width: 400px;
    height: 300px;
    border: 2px solid blue;
    margin: 50px;
    background-image: url("https://lh3.googleusercontent.com/proxy/HLE_xccz7qnXinNGfe-Oz_mEZvrltIKAqlxvjlXZV4bnBFrR0g7xIANF7rPLSH8ECLXbNxRpsF1a-gBulUsD-OPU5hsihlHIAEhi3KyWmnYY0RVjiw");
    background-repeat: no-repeat;
    background-size: contain;
    contain은 cover과 다르게 짧은 너비에 맞춰진다
}
```
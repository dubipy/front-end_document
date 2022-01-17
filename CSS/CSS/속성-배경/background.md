## background
<br/>

요소의 배경을 설정한다<br/>

|값|의미|기본값|
|------|---|---|
|background-color|배경 색상|transparent|
|background-image|하나 이상의 배경 이미지|none|
|background-repeat|배경 이미지의 반복|repeat|
|background-position|배경 이미지의 위치|0 0|
|background-attachment|배경 이미지의 스크롤 여부|scroll|
<br/>

```css
.box {
    background: orange url ('../img/image.jpg') no-repeat left top scroll;
    색상 / 이미지 경로 / 반복 위치 스크롤 특성
}
```
<br/>

```css
.box2 {
    background: url("../img/image.jpg") no-repeat right 100px;
    이미지경로 반복 위치
}
```

<br/>

```css
.box3 {
   background: red;
   색상 조절 
}
```
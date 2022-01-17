## background-image
<br/>

요소의 배경에 하나 이상의 이미지를 삽입
<br/><br/>

<table>
    <tr>
        <td>값</td>
        <td>의미</td>
        <td>기본값</td>
    </tr>
    <tr>
        <td>none</td>
        <td>이미지없음</td>
        <td>none</td>
    </tr>
    <tr>
        <td>url("경로")</td>
        <td>이미지 경로(URL)</td>
        <td></td>
    </tr>
<table>

<br/>

```html
background-image: url("경로");
```

<br/>

```css
.box {
    background-image: url("../img/image.jpg");
    width: 120px;
    height: 80px;
    배경 이미지 삽입 시, 요소의 크기가 설정되어 있어야 배경 이미지가 보일 수 있다
}
```
 
<br/>

<table>
    <tr>
        <td colspan="2" align="center">background-repeat 속성을 사용하면 배경이미지의 반복을 지정할 수 있다</td>
    </tr>
    <tr>
        <td>repeat</td>
        <td colspan="2">배경이미지가 반복적으로 적용된다</td>
    </tr>
    <tr>
        <td>repeat-x</td>
        <td colspan="2">배경이미지가 가로방향으로만 반복 적용된다</td>
    </tr>
    <tr>
        <td>repeat-y</td>
        <td colspan="2">배경이미지가 세로방향으로만 반복적으로 적용된다</td>
    </tr>
    <tr>
        <td>no-repeat</td>
        <td colspan="2">배경이미지가 반복적으로 적용되지 않고 한번만 적용된다</td>
    </tr>
</table>

<br/>
하나 이상의 배경 이미지를 삽입할 경우 , 로 구분한다 먼저 작성된 이미지가 더 위에 쌓이며, 다중이미지는 IE8 이하 버전엔 사용 불가하다
<br/>

```css
개별속성

.box01 {
    background-image: url("../img/i1.jpg"),
                      url("../img/i2.jpg"),
                      url("../img/i3.jpg");
}
```

<br/>

```css
단축속성

.box01 {
    background-image: url("../img/i1.jpg") no-repeat,
                      url("../img/i2.jpg") no-repeat 100px 50px,
                      url("../img/i3.jpg") repeat-x;
}
```


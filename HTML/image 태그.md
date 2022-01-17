## image 태그
<br/>
이미지 파일을 브라우저에게 전달해줘야할 때 사용하는 태그입니다<br/><br/>

**src** 속성은 전달 역할을 해주는 형식이며 링크를 적용하는 공간입니다<br/>
**alt**는 대체 텍스트 라는 뜻을 가지며, 이미지의 대안을 나타낸다 이미지를 외부자원을 삽입시킨 것이기 때문에 이미지 파일 자체를 해석하여 읽어줄 순 없다<br/>
우리는 이미지가 보이지 않는 환경의 사용자들을 위해 이미지에 대한 최소한의 정보를 제공할 의무가 있으며 이때 사용하는 속성이 **alt**이다<br/>

#
## 절대경로 | 상대경로
<br/>
절대경로는 웹페이지의 주소이며 상대경로는 이미지 파일을 경로에 지정합니다<br/><br/>

### 절대경로

```html
<img src="https://media.istockphoto.com/photos/monthly-kitten-british-shorthair-isolated-on-white-background-picture-id689835428" alt="하얀 고양이 사진">
```
<br/>

### 상대경로

```html
<img src=".photo/image/cat.jpg" alt="하얀 고양이 사진">
```
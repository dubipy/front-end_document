## font awesome
<br/>

폰트어썸 폰트 형태로 아이콘을 제공하는 사이트입니다 폰트형태라서 사이즈도 조절이 가능하고 색상도 마음대로 지정이 가능합니다

<img src="./font%20awesome_img/1.png">

폰트어썸 메인 홈페이지를 들어가서 회원가입을 합니다

<img src="./font%20awesome_img/2.png">

로그인 한 뒤에 오른쪽 위에 프로필을 누르면 kits 메뉴가 보입니다

kits 메뉴 클릭하고

<img src="./font%20awesome_img/3.png">

생성된 키값에서 저 빨간박스 부분을 클릭합니다

<img src="./font%20awesome_img/4.png">

이 스크립트 코드를 우리가 사용할 코드 에디터에 적용을 시켜야 폰트 어썸을 제대로 사용이 가능합니다 Copy kit code를 누르면 자동 복사가 됩니다

head 태그 안에 넣어야합니다

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style.css">
    <title>test</title>

    <script src="https://kit.fontawesome.com/27b2ad561b.js" crossorigin="anonymous"></script>
</head>

<body>
</body>

</html>
```

폰트어썸도 전체 아이콘이 무료가 아닙니다 약 5000개 쯤 되는데 거기서 무료는 1500개 가량 된다고 합니다 그러므로 해당 사이트와 정말 똑같이 만들고 싶다면 프리미엄 버전을 통해 구입하시거나 다른 아이콘 사이트를 찾으면됩니다 폰트어썸만 있는 것은 아니니까요

다시 폰트어썸 사이트로 돌아와서 이제 검색을 해보면서 찾고자 하는 것을 찾아봅시다

<img src="./font%20awesome_img/5.png">

첫 번째 아이콘은 집 모양을 닮았으니 home이라고 검색해보면 비슷한 아이콘이 많이 나올거같아요

<img src="./font%20awesome_img/6.png">

왼쪽에 Free 를 체크하고 확인해보면 그래도 사용 가능한 아이콘이 정말 많은 것을 볼 수 있어요

<img src="./font%20awesome_img/7.png">

빨간박스안에 있는 부분을 클릭하면 자동 복사가 됩니다 해당 코드가 위에서 설명한 부분인데요 잘 보면 우리가 공부한 class가 있죠? 폰트어썸에서 fas는 아마 무슨 모양을 지칭하려고 만든 것일테고 fa-house-user은 아이콘을 뜻하는 것이에요 class에 적혀져 있는대로 코드를 작성하면 우리가 지정한 폰트어썸 스크립트를 통해 불러져 오게 됩니다

그럼 에디터에 적용해봅시다

```html
<body>
    <i class="fas fa-house-user"></i>
    Home
</body>
```

<img src="./font%20awesome_img/8.png">

제대로 적용이 되었네요

약간 크기를 바꾸고 싶다면 간단하게 설정도 가능합니다

```html
<body>
    <i class="fas fa-house-user fa-lg"></i>
    Home

    <i class="fas fa-house-user fa-2x"></i>
    Home

    <i class="fas fa-house-user fa-3x"></i>
    Home

    <i class="fas fa-house-user fa-4x"></i>
    Home

    <i class="fas fa-house-user fa-5x"></i>
    Home
</body>
```

<img src="./font%20awesome_img/9.png">

나머지 카테고리도 한번 만들어보시길 바랍니다
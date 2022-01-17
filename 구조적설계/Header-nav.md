## Header-nav
<br/>

nav태그는 문법적으로 heading 태그가 무조건 있어야 합니다 문서간의 이동 할 수 있는 요소를 포함하는 경우 문서 페이지간의 핵심 메뉴 중 하나일 때 nav 태그를 사용합니다

global-nav.html

```html
<nav>
				<h1>Menu</h1>
</nav>
```

대등한 병렬적인 요소가 반복되기 때문에 list 태그를 사용하고 각각 링크가 있으니 link 태그도 사용합니다

```html
<nav>
        <h1>Menu</h1>
        <ul>
            <li>
                <a href="#">
                    <!-- icon -->
                    Home
                </a>
            </li>
        </ul>
    </nav>
```

총 메뉴가 8개니까 내용을 복붙해서 만들어줍니다

```html
<nav>
        <h1>Menu</h1>
        <ul>
            <li>
                <a href="#">
                    <!-- icon -->
                    Home
                </a>
            </li>
            <li>
                <a href="#">
                    <!-- icon -->
                    Explore
                </a>
            </li>
            <li>
                <a href="#">
                    <!-- icon -->
                    Notifications
                </a>
            </li>
            <li>
                <a href="#">
                    <!-- icon -->
                    Messages
                </a>
            </li>
            <li>
                <a href="#">
                    <!-- icon -->
                    Bookmarks
                </a>
            </li>
            <li>
                <a href="#">
                    <!-- icon -->
                    Lists
                </a>
            </li>
            <li>
                <a href="#">
                    <!-- icon -->
                    Profile
                </a>
            </li>
            <li>
                <a href="#">
                    <!-- icon -->
                    More
                </a>
            </li>
        </ul>
    </nav>
```

아래 버튼도 있으니 버튼까지 추가합니다 리스트 형식은 아니니까 리스트가 끝나는 그 밑에 새로 만들어줍니다

```html
<button type="button">
        twitter
    </button>
```
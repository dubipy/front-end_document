## footer
<br/>

<img src="./footer/1.png">

footer은 Sectioning Elements가 아니므로 꼭 heading를 사용할 필요는 없습니다

```html
<body>
    <footer>
        Terms
        Privacy policy
        Cookies
        Ads info

        About
        Status
        Businesses
        Developers

        © 2019 Twitter, Inc.
    </footer>
</body>
```

해당 글은 모두 이동이 되는 형식이므로 a 태그를 사용합니다

```html
<body>
    <footer>
        <a href="#" target="_blank">Terms</a>
        <a href="#" target="_blank">Privacy policy</a>
        <a href="#" target="_blank">Cookies</a>
        <a href="#" target="_blank">Ads info</a>
        <button type="button">
            More
            <!--icon-->
        </button>
        <div>
            <a href="#" target="_blank">About</a>
            <a href="#" target="_blank">Status</a>
            <a href="#" target="_blank">Businesses</a>
            <a href="#" target="_blank">Developers</a>
        </div>
        <span>© 2019 Twitter, Inc.</span>
    </footer>
</body>
```
## Form - 기본구조
<br/>
폼은 사용자로부터 정보나 데이터(input)을 받기 위한 태그입니다<br/><br/>
폼을 사용할 땐 브라우저에게 알려줘야 합니다<br/><br/>

```html
<form action=“” method=“”> </form>
```
<br/>
form의 값을 가지고 처리할 것이 있으니까 action="API 주소"를 적습니다<br/>

method에선 대부분 **POST**를 이용하는 것이 좋습니다 **GET**을 이용하게 되면 input 내에 개인정보를 넣고 서버에 넘어가게된다면 모든 정보가 URL에 표시 되기 때문입니다

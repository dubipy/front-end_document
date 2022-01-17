## Form - input 태그 
<br/>

회원가입 창 같은 곳에 보면 안내문구가 적혀져 있다 해당 속성은 **placeholder**라고 적는다<br/>
```html
<input type="text" placeholder="이름을 입력하세요." />
```
<br/>

<br/>

아이디를 입력하려고 하는데 10자리 이상 넘길 수 없게 만들고 싶다면 maxlength 속성을 이용합니다
```html
<input type="text" placeholder="이름을 입력하세요." maxlength="10" />
```
<br/>

<br/>

반대로 최소 5자 이상은 입력해야한다고 할 때는 minlength를 사용합니다
```html
<input type="text" placeholder="이름을 입력하세요." maxlength="10" minlength="5" />
```
<br/>


<br/>

```html
<form action="" method="GET">
    <input type="text" placeholder="이름을 입력하세요." maxlength="10" minlength="5" />
    <button>제출</button>
</form>
```
<br/>


<br/>

required 속성을 추가하면 추가한 폼 안에 내용을 적을 때 까지 다음 페이지로 넘어가지 않고 알람 메시지가 뜨게 됩니다
```html
<input type="text" placeholder="이름을 입력하세요." maxlength="10" minlength="5" required />
```
disabled 속성을 추가하면 해당 박스에 아무것도 입력할 수 없습니다

<br/>

Value 속성은 placeholder과 비슷하지만 Value로 만든 내용은 복사가 가능합니다
```html
<input type="text" value="이름을 입력해주세요." />
```

input type엔 여러가지 타입이 있습니다

email, password, number, url 등등
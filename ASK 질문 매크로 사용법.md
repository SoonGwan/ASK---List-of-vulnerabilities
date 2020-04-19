# ASK-Questions-AUTO
## ASK 질문 매크로

### 사용방법 : 개발자 도구를 켠 다음에 console창에 저렇게 원하는 질문이랑 유저 아이디 이름 적어서 엔터 누르면 댐
```javascript
  for(let i = 0;i<10000;i++){
    document.getElementById('ask_content').value = "(여기 원하는 질문)" + i;
    ask_post('유저이름');
}

```
:)

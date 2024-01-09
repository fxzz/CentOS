### grep (find는 폴더,파일을 찾아줘 지만 grep는 파일 안에서 찾아달라는 개념)
<br>
netstat -atunp 을 하면 네트워크 상태를 볼수있다
<br><br>
실제 서비스가 실행되고 있고 처리되고 있으면 네트워크 정보가 많이 생긴다
<br><br>

클라이언트가 접속한 정보를 확인할수있음

<br><br>

![1](https://github.com/fxzz/CentOS/assets/3148006/eb5b0c25-921c-401f-a51f-c52bd6bef9da)

<br><br>

netstat -atunp | grep "111" 이렇게 111번이 있으면 그것만 찾아달라고 하면 된다

<br><br>
리눅스에서 파이프란 앞에 결과를 뒤에 전달해준다는 뜻이다
<br><br>

![2](https://github.com/fxzz/CentOS/assets/3148006/830c582d-5ed9-4735-a351-4965214b52b3)



### 예시
<br><br>
1111파일 안에 1111이라고 저장되어있다
<br><br>

![3](https://github.com/fxzz/CentOS/assets/3148006/b1003671-4046-4724-b064-a78d92668b10)

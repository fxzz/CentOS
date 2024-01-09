### grep
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

![2](https://github.com/fxzz/CentOS/assets/3148006/830c582d-5ed9-4735-a351-4965214b52b3)

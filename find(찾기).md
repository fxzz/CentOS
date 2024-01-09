
## find

루트 계정으로 su 로 접속해
find / -name "passwd" 로 찾는다
/는 최상위부터 찾는것이고 -name "passwd"는 이름으로 찾는다는 뜻이다
경로를 알려준다 

![1](https://github.com/fxzz/CentOS/assets/3148006/0b2a7db5-f0d7-4125-a9db-090b3345c8a2)



<br>

폴더를 찾는 방법 (-type d) 파일은 (-type f)


find / -name "pass*" -type d 에서 -type d 는 d는 디렉토리다

<br>

![1](https://github.com/fxzz/CentOS/assets/3148006/1d58c0cc-343a-4957-adbf-85cf87c22549)

<br>

자세하게 보기

<br>
-exec 라는 옵션을 추가했을때 뒤에 오는 명령어를 수행한다 행 마다 {}에 넣어서 ls -l 명령어 수행한다
중요한 것은 마지막에 ; 해줘야함 ;는 의미가 있어서 의미를 제거하려고 엔터위에 W;를 사용한다

![1](https://github.com/fxzz/CentOS/assets/3148006/da6edc14-0c1a-4848-85b1-962b40642d91)

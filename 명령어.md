
![1](https://github.com/fxzz/CentOS/assets/3148006/488747f1-6ef5-44fb-aafb-8d226e1776f4)

$는 유저  #는 관리자




su 를 쓰고 비밀번호를 입력하면 root 계정으로 가진다

pwd는 현재 작업 중인 작업 디렉토리의 전체 경로를 출력

exid를 사용하면 root 계정에서 나간다

![2](https://github.com/fxzz/CentOS/assets/3148006/36c04c15-3ea2-46a9-af0a-749005eb9009)


### ls

ls 는 현재 폴더의 내용물의 리스트를 보여준다

![3](https://github.com/fxzz/CentOS/assets/3148006/82d27e85-cf97-40ee-88c6-53536565a8a8)


ls -l 은 자세하게 보여준다

$ ls -l
<br>
drwxr-xr-x 2 user user 4096 Jan  1 10:00 directory/
<br>
-rw-r--r-- 1 user user 1024 Jan  1 10:00 file.txt
<br><br>
앞에 d면 폴더(디렉토리) -면 파일

![4](https://github.com/fxzz/CentOS/assets/3148006/4deb0b51-b395-4254-89cd-126197aa182d)




소유주 소유그룹 일반이 있다

소유주(rwxr)는 읽기 쓰기 실행 권환이 있고 소유그룹은 그 다음 - 이다 x는 실행권한

![5](https://github.com/fxzz/CentOS/assets/3148006/bc823221-4586-4d1f-ad2c-95272c448ca7)

![6](https://github.com/fxzz/CentOS/assets/3148006/1082a924-f2c1-417f-bf6a-e78d95a546f1)


ls -a 를 하면 .붙은 숨긴 파일까지 전부 보여준다
![7](https://github.com/fxzz/CentOS/assets/3148006/9321465e-6277-4e5f-9301-a6f67b5968c6)


ls -al 도 가능하다


![8](https://github.com/fxzz/CentOS/assets/3148006/bc74ca7d-23be-43fa-9832-85cf9fc312d7)




### cd (체인지 디렉토리)

cd 하면 이동

cd ./tmp 는 .현재 디렉토리의 /tmp로 이동 상대경로
절대경로는 /home/user 이렇게 이동

<br>
./는 현재 디렉토리인 /home/user/documents를 나타냅니다. <br>
../는 상위 디렉토리인 /home/user를 나타냅니다. <br>
../../는 상위의 상위 디렉토리인 /home를 나타냅니다. <br>

![9](https://github.com/fxzz/CentOS/assets/3148006/1fed7e74-9f0c-4ecb-b9f7-566605ef03d0)




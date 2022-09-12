# Have a donut :D

![image](https://user-images.githubusercontent.com/1134397/189466661-e8aa5fff-0ad6-484c-9659-cf82bff8b37d.png)


# Overview

얼마전에 [유튜브 비디오](https://youtu.be/sW9npZVpiMI) 보다가 재밌기도 하고 궁금 하기도 해서 한번 따라해 본거에요.

[원본 코드](https://www.a1k0n.net/2011/07/20/donut-math.html) 를 그대로 돌리면 에러가 나더라고요. 

왜냐하면 쓰던 코드가 조금 오래되서 몇개 라이브러리 function 들이 더이상 support 되지 않아요.

그래서 한번 고쳐봤어요.

모든 Credit 은 원본 코드 만드신 분께 가요.

# Prerequisite (필요한거)

- gcc

# Getting started 


1. 터미널에서 `src/donut.c` 파일을 빌드

## Windows
```
$ gcc -o donut src/donut.c
```

## Linux/MacOS
```
$ gcc -o donut src/donut.c -lm
```

2. 실행 파일이 생성

  - `donut.exe` (Windows)
  - `donut` (linux/MacOS)

3. 터미널에서 파일 실행

## Windows
```
$ ./donut.exe
```

## Linux/MacOS
```
$ ./donut
```

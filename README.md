# Have a donut :D

![image](https://user-images.githubusercontent.com/1134397/189466661-e8aa5fff-0ad6-484c-9659-cf82bff8b37d.png)

# Overview

## English

Inspired by one of `Joma Tech` [youtube vieo](https://youtu.be/sW9npZVpiMI). I found it interesting and had urge to try it.

`Andy Sloan` was the original creatior of donut. [Blog post](https://www.a1k0n.net/2011/07/20/donut-math.html)

Few functions didn't work because those libraries no longer exists, so had to replace them with newer functions.

All the credit goes to 2 above.

## Korean

얼마전에 [유튜브 비디오](https://youtu.be/sW9npZVpiMI) 보다가 재밌기도 하고 궁금 하기도 해서 한번 따라해 본거에요.

[원본 코드](https://www.a1k0n.net/2011/07/20/donut-math.html) 를 그대로 돌리면 에러가 나더라고요. 

왜냐하면 쓰던 코드가 조금 오래되서 몇개 라이브러리 function 들이 더이상 support 되지 않아요.

그래서 한번 고쳐봤어요.

모든 Credit 은 원본 코드 만드신 분께 가요.

# Prerequisite

- gcc
  - windows : Mingw [download](https://www.mingw-w64.org/)
  - linux/mac os : standard package install `gcc`

(optional )
- cmake
-  make


# Getting started 


1. Build `src/donut.c`

## Option 1. gcc
### Windows
```
$ gcc -o donut src/donut.c
```

### Linux/MacOS

```
$ gcc -o donut src/donut.c -lm
```

## Opton 2. make

- run cmake
 ```
$ cmake CmakeList.txt
 ```

- run make then you will see executables
 ```
$ make
```

  - `donut.exe` (Windows)
  - `donut` (linux/MacOS)


3. run the executable

## Windows
```
$ ./donut.exe
```

## Linux/MacOS
```
$ ./donut
```


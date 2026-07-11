# 01. C 언어

- 개요

---

### C 언어 기초

```c
#include <stdio.h>

int main(){
	printf("Hello World!\n");
	return 0;
}
```

C 언어는 컴퓨터에 특정한 명령을 내리기 위한 프로그래밍 언어 중 세계적으로 가장 많이 사용되는 언어이다.

위 코드는 컴퓨터가 Hello World! 라는 문자열을 출력하도록 시키는 코드이다.

리눅스 운영체제에서 실행해 본다.

---

C 언어는 Compile Language 이다.

**컴파일 언어**는 인터프리터 언어와 반대되는 개념으로, 코드 전체를 하나의 **실행 파일**(흔히 말하는 .exe 파일과 같다)로 만들어서 **컴퓨터에게 전달**하는 것 이다. 

이와 같은 과정을 “**컴파일**” 이라고 한다.

위 C코드를 실행파일로 만들기 위해서는 컴파일을 도와주는 **컴파일러**가 존재한다.

많은 컴파일러 중 가장 유명한 GCC라는 컴파일러를 이용해서 실행 해본다.

---

`$ vi helloworld.c`

vi로 편집기를 열어 helloworld.c 파일에 C언어 코드를 작성한다.

```bash
$ cat helloworld.c
#include <stdio.h>

int main(){
	printf("Hello World!\n");
	return 0;
}
```

이제 gcc를 이용해서 helloworld.c 파일을 컴파일해 본다.

```bash
#gcc <filename>
$ gcc helloworld.c

#성공적으로 컴파일 했을 경우 a.out 파일이 생성되어야 한다.
$ ls
a.out helloworld.c

# -o 옵션을 이용해서 실행파일 이름을 정할 수 있다.
$ gcc helloworld.c -o helloworld
```

컴파일된 실행 파일인 a.out 파일을 실행해본다.

```bash
#실행파일 이름을 입력해주면 자동으로 실행
$ ./a.out
Hello World!
```

Hello World! 가 출력됐다면 성공적으로 프로그래밍 된 것이다.

### 코드 분석

```c
#include <stdio.h>

int main(){
	printf("Hello World!\n");
	return 0;
}
```

1. include file

`#include <stdio.h>`

#include 는 뒤에 나오는 파일을 포함시키겠다는 의미이다. (stdio.h 파일을 포함하겠다는 의미)

stdio는 standard input/output을 의미하며 printf, scanf 등 출력과 입력의 기능을 하는 함수들이 들어 있다.

1. main function

`int main(){` 

main 함수를 선언한다. 프로그램이 실행되면 main함수 내부에 있는 코드가 실행되게 된다. 

1. printf function

`printf("Hello World!\n");`

printf 함수를 호출한다. printf 뒤 괄호 내부에 있는 문자열을 출력해주게 된다. 이 “Hello World\n” 문자열을 함수에 전달한 **인자**라 부른다.

C언어에서 모든 명령 마지막에는 ;(세미콜론)이 붙어야 한다.

1. Return statement

`return 0;`

컴퓨터에게 0을 반환하고 main 함수를 종료하겠다는 의미이다.

0을 반환하는 이유는 일반적으로 아무 오류 없이 종료되었다~ 라고 사용되기 때문이다.

꼭 0일 필요는 없으며, 큰 의미가 존재하지 않는다.

이 역시 하나의 명령이기 때문에 ; 을 꼭 붙여줘야 한다.

프로그램을 만드는 법을 알아야 해킹하는 법을 습득할 수 있다.

기초가 중요하다.

---

<aside>
<img src="https://app.notion.com/icons/push-pin_gray.svg" alt="https://app.notion.com/icons/push-pin_gray.svg" width="40px" />  학습정리

- C언어는 컴파일(코드 전체를 하나의 실행 파일로 만들어서 컴퓨터에게 전달) 언어이다.
- C언어를 실행 파일로 만들기 위해서 GCC 컴파일러를 이용해서 실행이 가능하다.
- 모든 명령어 마지막에는 ; (세미콜론)이 붙어야 한다.
</aside>

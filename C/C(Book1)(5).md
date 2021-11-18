# 기본 이론

## 변수 선언

C 언어에서 변수를 선언할 때는 반드시 스코프가 시작된 직후에 해야하며, 다른 연산 코드가 수행된 후에는 절대로 변수를 선언하지 말아야 한다.

## 변수 이름 규칙

- 첫글자는 반드시 영문이어야 한다.

- 대부분의 특수 문자를 사용할 수 없다.

- 한글 이름은 허용되지 않는다.

- 반드시 명명(Naming) 규칙이 있어야 한다.

### 헝가리안 표기법

unsigned char: by

char: c

int: n

unsigned int: u

char*: sz   
string array: sz

float: f

long: l

double: d

boolean(C++): b

## 주석

- //: 이후 한 행을 주석으로 처리한다.

- /* " " */: 특정 스코프를 주석으로 처리한다.

## 연습문제

### 1

```
#include <stdio.h>

void main() {
	int nData = 10;         // F9 누르면 중단점
	int* pnData = &nData;

	*pnData = 5;
}
```

### 2

```
0x009bfe2c
```

### 3

```
0x009BFE2C
```

___

## 참조

- [열혈강의 최호성의 C 프로그래밍](https://cafe.naver.com/windev/7880)
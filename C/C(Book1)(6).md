# 제 4장 기본 입출력 함수

## 문자 입출력 함수

### getchar() / putchar()

int getchar(void)

인자: 없다.

반환값: 입력문자 하나를 반환한다. 오류가 발생하면 EOF(-1)를 반환한다.

설명: 표준 입력 장치(stdin)로부터 문자 한 글자를 읽어 와서 반환한다. 만일 표준 입력 장치에서 버퍼(메모리)가 비어 있다면 사용자로부터 입력을 받아 반환하고 그렇지 않으면 버퍼에서 가져와서 반환한다.

___

int putchar(int c)

인자: C: 출력할 문자 상수이다.

반환값: 출력 문자 하나를 반환한다. 오류가 발생하면 EOF(-1)를 반환한다. 

설명: 표준 출력 장치(stdout)로 한 글자를 출력한다.

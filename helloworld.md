# Python

### 파이썬의 자료형
> 숫자, 문자열, 불
변수, 리스트, 튜플
딕셔너리, 집합

<details>
<summary>숫자형</summary>
정수형, 실수, 컴퓨터 지수 표현 방식
8진수, 16진수

- 사칙연산
    ```
    a = 3   a + b   a * b    a / b
    b = 4   >>> 7   >>> 12   >>> 0.75
    ```
- 제곱
    ```
    a = 3   a ** b
    b = 4   >>> 81
    ```
- % 연산자
    ```
    7 % 3   3 % 7
    >>> 1   >>> 3
    ```
- / 연산자
    ```
    7 / 4       7 // 4
    >>> 1.75    >> 1
    ```
</details>

<details>
<summary>문자열 자료형</summary>

- 문자열에 따옴표 표함시키기
    ```
    food = "Python's favorite food is kimchi"
    say = '"Python is very easy." he says'
    food = 'Python\'s favorite food is kimchi'
    say = "\"Python is very easy.\" he says"
    ```
- 여러 줄로 이루어진 문자열
    ```
    line = "Life is too short\n You need Python"
    ```
    - 문자열 더해서 연결하기
    ```
    head = "Python"
    tail = "is fun!"
    head + tail
    >>> Python is fun!
    ```
- 문자열 곱하기
    ```
    a = "Python"
    a * 2
    >>> PythonPython
    ```
- 슬라이싱
    ```
    a = "Life is too short, You need Python"
    a[0:4]
    >>> LIFE

    a = "20220714Rainy"
    date = a[:8]
    weather = a[8:]
    >>> 20220714(date값)
    >>> Rainy(weatehr값)
    ```
- 문자열 포매팅
    ```
    "I ate %d apples." % 3
    >>> I ate 3 apples.

    number = 10
    day = "three"
    "I ate %d apples. so I was sick for %s days." % (number, day)
    >>> I ate 10 apples. so I was sick for three days.
    ```
- 정렬과 공백
    ```
    "%3s" % "hi"
    >>>  '   hi'

    "%-3sjoon." % "hi" 
    >>> 'hi   joon."
    ```
- 소수점 표현
    ```
    "0.4f" % 3.15923421
    >>> 3.1592
    ```
- 문자열 개수 세기
    ```
    a = "hobby"
    a.count('b')
    >>> 2
    ```
- 위치 알려주기
    ```
    a = "Python is best choice"
    a.find('b')
    >>> 10
    a.find('k')
    >>> -1
    ```
- 문자열 삽입
    ```
    a = ","
    a.join('abcd')
    >>> a,b,c,d
    ```
- 소문자를 대문자로 바꾸기
    ```
    a = "hi"
    a.upper()
    >>> HI
    ```
- 대문자를 소문자로 바꾸기
    ```
    a = "HI"
    a.lower()
    >>> hi
    ```
- 양쪽 공백 지우기
    ```
    a = " hi "
    a.strip()
    >>> hi
    ```
- 문자열 바꾸기
    ```
    a = "Life is too short"
    a.replace("Life", "Your leg")
    >>> Your leg is too short
    ```
- 문자열 나누기
    ```
    a = "Life is too short"
    a.split()
    >>> ['Life', 'is', 'too', 'short']

    a = "a:b:c:d"
    a.split(':')
    >>> ['a', 'b', 'c', 'd']
    ```
</details>



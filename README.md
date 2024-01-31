# 파이썬 기초 2024
부경대 2024 IoT 개발자 과정 기초 프로그래밍 언어 - 파이썬

## 1일차
- 개발 환경 구축
    - 코딩 폰트 - 나눔고딕코딩
    - Notepad++ 설치
    - Python 설치
    - Visual Studio Code 설치
    - Git 설치
        - TortoiseGit 설치
        - Github 가입
        - Github Desktop 설치
    
- 파이썬 기초
    - 콘솔 출력
    - 주석  
    - 변수
    - 자료형
    - 연산자

    ```python
    # 이부분은 주석입니다.
    var01 = 10 # 정수, 실수, 불, 문자열 모두 가능
    print(var01)
    print(type(var01))

    print(5 + 4 / 2) # 7.0
    print(5 == 4) # False
    ```

## 2일차
- 파이썬 기초
    - 흐름제어
        - if
            - if 문 문법 # 참과 거짓으로 조건을 나눔 (다른 언어 switch)
            - int(input()) # 입력 방법
            - import datetime 을 사용한 현재 시간 을 처리하는 if문
        - for : 반복문 기본 (다른 언어 foreach)
        - while : 반복문 변형 (다른언어 do~while)
    - 복합 자료형 + 연산자
        - list
        - tuple
        - dictionary
        - range()
    - 출력 포맷, 입력 방법
    - 구구단 + 디버깅
    ```python
    # debugging
    # F5(디버그 시작), F10(한줄씩 실행), F11(함수 안으로 진입), F9(중단점 토글)
    print('구구단 시작!!')
    for x in range(2,9+1): # 2부터 9까지 반복
        print(f'{x}단 -------------------------------------------------------------------------------------------------------------------')
        for y in range(1,9+1): # 1부터 9까지 반복
            print(f'{x} x {y} = {x*y :2d}', end ='   ') # end = 는 엔터대신 공백으로 대체
        print() # 안쪽 for문이 끝나면 마지막 enter를 추가

    ```

    ## 3일차
    - 파이썬 기초
        - 입력 방법
            - input(), map() 함수의 활용
        - 별찍기
        - 함수, 람다함수는 나중에..
        - 객체지향 OOP
            - 객체는 명사와 동사의 집합
            - 명사는 변수, 동사는 함수
            - 변수와 함수를 모두 모아둔 곳 : 클래스 (class) ==> class 는 객체가 아니다. class에서 나온 것이 객체이다!!
            - class에서 하나씩 생성 : 객체 (object)
            - class ghkdkdkdk
# Comnet-team6
ComputerNetwork

IDLE로 실행함
>>> str = input("input_str : ")    #str에 입력하겠다
input_str : abcde     #input_str : 이 바로 출력됨,  abcde은 본인이 입력했음
>>> print(str)        #str을 출력
abcde

>>> str = input()    #3.4.3 버전에서는 공백도 출력가능하게 바뀌었나봅니다.
hello world!        #입력
>>> print(str)
hello world!     #출력됨

#--- 프로토콜에 맞추기 위해서 append를 해보았다.---
>>> str2 = "MS:" + str      #  + 기호를 이용해서 append가능
>>> print(str2)                   #출력해봄
MS:hello world!             #잘 붙어있다.


>>> str2 = "MS:" + str + ';'        #완성시키기위해서(명세에 맞춰서) ; 을 추가함
>>> print(str2)
MS:hello world!;           #ptr2를 send하면 메세지를 서버한테 보내는 것이 된다.

(문자열을 명세에 따라서 문자열을 붙일수가 있음) -> 명세에 맞게 문자열을 붙일 수 있다.
이후에는 문자열을 분리하는 것을 알아보자(그래야 받은 사람이 뜯어볼 수가 있다.)

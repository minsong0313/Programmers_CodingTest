# 코딩테스트 공부
- 코딩테스트 문제를 공부하면서 알게된 개념 및 함수 정리

## SQL
### 1. 비트연산자 '&' 
- 특정 비트가 포함되었는지를 확인하는 [문제](https://github.com/minsong0313/Programmers_CodingTest/blob/master/SQL/SELECT/%EC%A1%B0%EA%B1%B4%EC%97%90%20%EB%A7%9E%EB%8A%94%20%EA%B0%9C%EB%B0%9C%EC%9E%90%20%EC%B0%BE%EA%B8%B0.txt)
- 특정 비트 확인 방법
  * AND 연산을 사용하여 해당 비트 검사
  * 결과가 그 비트 값과 같다면 해당 비트가 포함된 것
  * EX) 400 에 256이 포함되었는지 확인하기: (400 & 256) = 256 -> 포함O

# Day43

---

### <2023-05-16>

> **********************풀이문제**********************
>
- 다음 큰 숫자
    - 2진수 변환 메소드를 직접 만들어서 주어진 제한 숫자까지 반복해서 1의 개수를 비교함
        - 효율성 문제에서 시간 초과로 에러 발생
    - Integer.bitCount(정수) ⇒ 2진수로 변환된 1의 개수(true bit)를 반환하는 메소드를 사용해서 풀이
- 이진 변환 반복하기
    - 10진수 ⇒ 2진수 변환하는 알고리즘에서 시간 초과가 계속되어 Integer.toBinaryString() 메소드를 이용함
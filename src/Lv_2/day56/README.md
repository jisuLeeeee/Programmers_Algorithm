# Day56

---

### <2023-06-12>

> ********************풀이 문제********************
>
- 괄호 회전하기(다른 사람 풀이 참조)
    - 문자열의 괄호를 회전하는 부분을 문자열 substring()을 사용해서 오른쪽으로 한 글자씩 밀어주고, Stack클래스를 사용해서 열린 괄호를 추가한 다음 닫힌 괄호가 나오면 pop(), 마지막에 stack.isEmpty()가 true이면 answer++;
- 행렬의 곱셈
    - 3중 for문을 사용함
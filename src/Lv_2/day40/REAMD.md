# Day40

---

### <2023-05-08>

> ************************풀이문제************************
>
- 가장 가까운 글자
    - lastIndexOf() 사용
        - 문자열을 누적하는 문장을 반복문 처음에 작성해서 오류가 발생했었음
- 2016년
- 최댓값과 최솟값
    - “ “을 기준으로 String 배열을 생성, 배열을 정렬하고 최솟값과 최댓값을 문자열 변수에 저장
- JadenCase 문자열 만들기
    - 주어진 문자열을 한 글자씩 검사하면서 공백이면 그 다음 글자를 대문자로 변경 후 한 단어에 대문자가 있다면 소문자로 변경함
    - 첫 글자가 소문자인 경우 대문자로 변경하는 조건문을 작성했고 마지막글자가 공백인 경우의 조건도 작성
    - 주어진 문자열을 소문자로 만들고 boolean값으로 공백을 확인해서 풀이(다른 사람 풀이 참조)
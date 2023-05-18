# Day45

---

### <2023-05-18>

> ******************풀이문제******************
>
- 예상 대진표
    - while문 조건에 참가자 번호 차이가 1이면 끝낸다고 단순히 생각했지만 [8, 4, 5]가 들어왔을 때 둘은 서로 다른 상대방과 붙고 3번째 경기에서 만나는 반례가 있었음
        - 차이가 1이어도 번호 중 최댓값이 홀수이면 다른 참가자와 경쟁한다는 증거의 조건을 추가
- 점프와 순간이동
    - 입출력 예시로 구조를 생각해보려 했으나 적당한 알고리즘이 생각나지 않음
        - 주어진 숫자를 2로 나누다가 나머지가 생기면 -1해서 점프횟수를 누적해서 리턴(다른사람 풀이 참조)
- 추억점수
    - 배열에서 원하는 단어의 인덱스를 찾기 위해 Arrays.asList(array).indexOf(”문자열”))을 사용
        - 위 문장을 배열[해당문장] 했을 때 만약 원하는 문자열이 없다면 -1이 반환되어 인덱스 -1은 찾을 수 없다고 오류 발생
- 폰켓몬
    - 처음으로 HashSet을 사용(다른사람 풀이 참조)
        - 중복 제거를 위해 사용
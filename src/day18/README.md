# Day18

---

## 문제풀이 열여덟번째날 <2023-2-4>

> ********************풀이 문제********************
>
- 캐릭터의 좌표
    - 맵의 크기에 대한 설정과 부등호 설정을 잘못해서 다른 테스트 케이스에서 에러 발생

      x좌표가 음수일 때 맵의 크기도 음수로 비교해야함

- 종이자르기
    - 가로, 세로를 곱한 값에서 -1
- 직사각형의 넓이 구하기
    - 4 꼭짓점의 좌표에서 x,y의 최댓값과 최소값을 구하기 위해 각각 배열을 만들어서 정렬하고, 최대값 - 최소값으로 가로와 세로의 길이를 구해서 곱함
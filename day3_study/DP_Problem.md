길이가 N인 막대기가 있다. 막대기를 길이가 자연수가 되도록 여러 조각으로 자를 수 있다.
막대기는 자르는 길이에 따라 값이 정해져 있다. 막대를 자르는 값어치의 합이 최대가 되게끔 막대기를 자르자.
예를 들어, 길이가 4인 막대기를 자를 때, 길이 별 받을 수 있는 값이 아래와 같다고 하자.

Length Cost
 1	1
 2	5
 3	8
 4	9

이 경우에 길이 2에 cost 5인 막대기 두 개가 되게끔 자르면 전체 값어치가 10으로 최대로 값을 받을 수 있을 것이다.

첫 줄에 막대기 길이 N(1<= N <= 3000)이 주어지고,
두번째 줄에 1000이하의 자연수 N 개가 공백으로 구분되어 주어진다. i번째 자연수는 길이 i 막대기의 값을 의미한다.

첫 줄에 값어치 합이 최대가 되도록 막대기를 자를 때, 값어치 합을 출력한다.


예제 입력 : 
4
1 5 8 9

예제 출력 : 10
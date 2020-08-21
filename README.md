# Greedy

> 현재 상황에서 지금 당장 좋은 것만 고르는 방법

> 매 순간 최선을 다하며 현재의 선택이 나중에 미칠 영향에 대해서는 고려x

> 모든 선택지를 골해보고 그 중 가장 좋은 것을 찾는 방법이 Divide conquer or dp 였다면 greedy 는 각 단계마다 지금 당장 가장 좋은 방법만을 선택하는 해결 방법이다.

> 탐욕법은 동적 계획법보다 수행 시간이 훨씬 빠르기 때문에 유용하다. 많은 경우 최적해를 찾지 못하고 적용될 수 있는 경우가 두 가지로 제한된다.

>> 탐욕법을 사용해도 항상 최적해를 구할 수 있는 경우

>> 시간이나 공간적 제약으로 최적해 대신 근사해를 찾아서 해결하는 경우

## Greedy에 관한 문제 풀이 접근

+ 최적화 문제에서, 각 단계를 선택해 나가는 과정에서 이 답이 실제 답에 포함이 되야한다.
+ 이 답이 최적답인지를 증명할 수 있어야 한다.
+ 정렬알고리즘과 함께 사용되는 경우가 많다.
+ 모든 선택지를 골해보고 그 중 가장 좋은 것을 찾는 방법이 Divide conquer or dp 였다면 greedy 는 각 단계마다 지금 당장 가장 좋은 방법만을 선택하는 해결 방법이다. 
+ 탐욕법은 동적 계획법보다 수행 시간이 훨씬 빠르기 때문에 유용하다. 많은 경우 최적해를 찾지 못하고 적용될 수 있는 경우가 두 가지로 제한된다.

1. 문제의 답을 만드는 과정을 여러 조각으로 나눈다.
2. 각 조각마다 어떤 우선순위로 선택을 내려야 할지 결정한다. 작은 입력을 손으로 풀어본다.
3. 다음 두 속성이 적용되는지 확인해본다.
4. 탐욕적 성택 속성 : 항상 각 단계에서 우리가 선택한 답을 포함하는 최적해가 존재하는가
5. 최적 부분 구조 : 각 단계에서 항상 최적의 선택만을 했을 때, 전체 최적해를 구할 수 있는가

## 문제 풀면서 나온 아이디어, 반성할 점

1. 배열의 최대 최소값을 필요로 하는 문제는 입력받을 때 처리해 버리자

2. 자료구조, 수열을 다루는 문제에서 공통되는 부분이 있다면 그 부분을 묶어서 최대한 반복회수를 줄이자

3. 연산관련 문제에서 1로 만든다거나 등등 줄여나가는 문제에서 배수, 약수를 생각해보자

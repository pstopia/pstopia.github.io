---
layout: page
title: Fenwick Tree
---

결합법칙, 교환법칙이 성립하는 operator * 가 있을 때,
prefix value P[x] = a[1] * a[2] * ... * a[x] 를
빠르게 구할 때 쓸 수 있는 트리 자료구조이다. 구현이 간단해서 자주 쓰인다.

operator * 의 역원이 존재한다면, 역원을 이용해 임의의 구간의 값도 빠르게 계산할 수 있다.
예를 들면 합/곱 같은 것이 가능하다. 최대/최소는 불가능하다.

  * 공간 복잡도 : O(n)
  * 시간 복잡도
    * 한 점 업데이트 : O(logn)
    * prefix value 계산 : O(logn)

{% gist bb82babd9a0359ff3bd7b140e273b69c %}

## Fenwick Tree 2D

평범한 펜윅트리의 구현을 응용하면 다차원 펜윅트리도 만들 수 있다.

{% gist 58ef1dcea3adde3bc746501784048be8  %}

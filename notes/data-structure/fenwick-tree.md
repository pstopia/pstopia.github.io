---
layout: page
title: Fenwick Tree
---

prefix value를 빠르게 구해야할 때 쓸 수 있는 트리 자료구조이다. 구현이 간단해서 자주 쓰인다.

prefix value를 이용해 특정한 연속된 구간의 대표값을 빠르게 구할 수 있는 경우가 있다. 합, 차 같은 경우가 가능하다. 최대, 최소는 불가능하다.

  * 공간 복잡도 : O(n)
  * 시간 복잡도
    * 한 점 업데이트 : O(logn)
    * prefix value 계산 : O(logn)

{% gist bb82babd9a0359ff3bd7b140e273b69c %}

## Fenwick Tree 2D

평범한 펜윅트리의 구현을 응용하면 다차원 펜윅트리도 만들 수 있다.

{% gist 58ef1dcea3adde3bc746501784048be8  %}

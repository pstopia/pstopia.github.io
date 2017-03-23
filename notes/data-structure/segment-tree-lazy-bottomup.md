---
layout: page
title: Segment Tree with Lazy Propagation - Bottom Up
---

결합법칙, 교환법칙이 성립하는 operator * 가 있을 때,
구간 [s, e] 의 원소들 각각에 연산을 적용하거나
a[l] * a[l+1] * ... * a[r-1] * a[r] 을 빠르게 구할 때 쓰는 자료구조이다.

  * 공간 복잡도 : O(n)
  * 시간 복잡도
    * 구간 업데이트 : O(logn)
    * 구간 쿼리 : O(logn)

{% gist e38504f7c879d9195e9012d54f6b3897 %}

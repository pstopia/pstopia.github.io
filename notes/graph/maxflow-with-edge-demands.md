---
layout: page
title: Maximum Flow with Edge Demands
---

flow 문제 중에 간선 e 마다 d(e) <= f(e) <= c(e) 를 만족하는
flow f(e) 가 존재하는지, 그 때 maximum flow 는 얼마인지를 계산하는 문제다.

이 것을 계산하는 자세한 알고리즘과 그 증명은
[여기](http://jeffe.cs.illinois.edu/teaching/algorithms/notes/25-maxflowext.pdf)를
참고하면 됨.

{% gist a3c9b75b405e4d18dd560dd66a6e8bd1 %}

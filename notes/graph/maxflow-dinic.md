---
layout: page
title: Maximum Flow (Dinic)
---

[Dinic's algorithm](https://en.wikipedia.org/wiki/Dinic%27s_algorithm).
[Maximum flow](https://en.wikipedia.org/wiki/Maximum_flow_problem) 를 계산하는 알고리즘 중 하나.
구현이 적당히 간단한 알고리즘 중에선 시간복잡도 상으로 제일 빠른 성능을 보인다.

  * 시간복잡도 : O(V^2 * E)
    * 모든 간선이 unit capacity 를 가질 때 : O(min(V^(2/3), E^(1/2)) * E)

{% gist 286db0cdff41810131eb5c233eb0bf1c %}

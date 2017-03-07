---
layout: page
title: SCC (Tarjan)
---

[SCC](https://en.wikipedia.org/wiki/Strongly_connected_component)를 구하는 알고리즘 중 하나.

이 알고리즘의 성질 중 하나는 SCC들을 SCC번호 순으로 늘어놓으면 SCC를 하나의 노드로 묶은 DAG에서 위상정렬한 순서가 되는 것이다.

  * 시간복잡도 : O(V + E)

{% gist c2ead05dd1e56778cd77e872134723ee %}

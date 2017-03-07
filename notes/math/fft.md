---
layout: page
title: Fast Fourier Transform
---

두 다항식의 곱을 O(n^2) 보다 빠르게 계산하기 위해 사용한다. 좀 더 정확히는 [DFT](https://en.wikipedia.org/wiki/Discrete_Fourier_transform)를 O(nlogn) 에 구하고 그것을 이용해 O(n) 만에 두 다항식의 곱을 계산하게 된다. 여기서 DFT를 O(nlogn) 에 구하는 방법이 바로 [Fast Fourier Transform](https://en.wikipedia.org/wiki/Fast_Fourier_transform) 이다.

{% gist 5aee7152c76f5ba329058e763e6dff7c %}

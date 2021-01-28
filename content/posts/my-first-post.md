---
title: 첫 포스트
slug: my-first-post
date: 2021-01-27T11:33:16+09:00
draft: false
tags: ["tag1", "tag2", "tag3"]
summary: 이 글은 제 첫 번째 포스트입니다. 블로그에서 글이 정상적으로 보이는지 확인합니다.
katex: true
---

## 안녕하세요

이 글은 제 첫 번째 포스트입니다.

## 기능 점검

### 기본 마크다운 문법

1. 일어나기
2. 커피 마시기
   1. 원두 갈기
   2. 물 끓이기
   3. 커피 내리기
3. 책 읽기
   - [Introduction to Algorithms](https://mitpress.mit.edu/books/introduction-algorithms-third-edition)
   - [C Programming: A Modern Approach](http://knking.com/books/c2/)

### 사진

![새](/img/quarter.png)

### 수식

이차방정식 \\(ax^2 + bx + c = 0\\)의 근 \\(x\\)의 값은 다음 근의 공식으로 구할 수 있습니다.

$$ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}. $$

많은 웹사이트에서 수식을 KaTeX 또는 MathJax로 렌더링합니다. Markdown에서는 \\(x_a\\)와 같은 subscript를 처리하기가 까다롭습니다.

### 코드

재귀함수를 이용하여 `n`번째 피보나치 수를 구합니다.

```python
from functools import lru_cache

@lru_cache(max_size=1)
def fib(n):
    if n < 2:
        return n
    return fib(n-1) + fib(n-2)
```

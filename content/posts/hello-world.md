---
title: "Hello, meiander'log"
date: 2026-07-02
draft: false
tags: [meta]
categories: [notes]
math: true
ShowToc: true
---

First post. A place to check that math, code, and tables all render.

## Math

Inline math like $e^{i\pi} + 1 = 0$ should render. Display math too:

$$
\mathcal{L}(\theta) = -\mathbb{E}_{x \sim p_{\text{data}}} \big[ \log p_\theta(x) \big]
$$

## Code

```python
def softmax(x):
    z = x - x.max()
    e = np.exp(z)
    return e / e.sum()
```

## Table

| Model    | Params | Notes            |
| -------- | -----: | ---------------- |
| Small    |    12M | quick baseline   |
| Medium   |   125M | main comparison  |
| Large    |   350M | best on holdout  |

## Next

More coming. The point of this log is to think out loud.

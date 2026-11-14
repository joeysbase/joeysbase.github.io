---
title: 'Hello, World'
description: 'The first post on this blog, and a quick check that code blocks and math render correctly.'
pubDate: 'Nov 14 2026'
---

This is the first post. Future posts will cover computer vision, machine learning,
and whatever else I'm working through.

A couple of things this template supports out of the box, worth checking once before
writing a real post:

**Code blocks**, with syntax highlighting:

```python
def harris_response(gray, block_size=2, aperture_size=3, k=0.04):
    return cv2.cornerHarris(gray, block_size, aperture_size, k)
```

**Math**, via KaTeX:

The Harris corner response is computed from the eigenvalues $\lambda_1, \lambda_2$ of the
structure tensor:

$$
R = \lambda_1 \lambda_2 - k (\lambda_1 + \lambda_2)^2
$$

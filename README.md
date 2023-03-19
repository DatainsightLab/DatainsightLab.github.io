# Perceptron

## 퍼셉트론이란?
### Threshold Logic Unit

## 퍼셉트론 학습 알고리즘
**퍼셉트론** 학습 알고리즘은 오분류된 점들과의 거리를 최소로 하는 **하이퍼플레인**을 찾는 알고리즘이다.

- $y_i=1$이 오분류인 경우 $x_i^t\beta + \beta_0 <0 $
- $y_i=1$이 오분류인 경우 $x_i^t\beta + \beta_0 >0 $

따라서 퍼셉트론 알고리즘의 목표는 다음 값을 최소로 하는 $\beta$를 찾는 것이다.

$$ D(\beta,\beta_0) = - \sum_{\cal M} y_i (x_i^t\beta + \beta_0) $$

```math
E = mc^2
```

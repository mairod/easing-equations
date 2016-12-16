# Easing Equations

Some mathematics easing equations

## Simple linear tweening

No easing, no acceleration

```
Math.linearTween = function (t, b, c, d) {
    return c*t/d + b;
};
```

## Quadratic easing in

Accelerating from zero velocity

```
Math.easeInQuad = function (t, b, c, d) {
    t /= d;
    return c*t*t + b;
};
```

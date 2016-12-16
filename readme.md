# Simple easing functions

Some mathematics easing equations

Only considering the t value for the range [0, 1]

## Simple linear tweening

No easing, no acceleration

```
Math.linear = function (t) { return t }
```

## Quadratic easing in

Accelerating from zero velocity

```
Math.easeInQuad = function (t) { return t*t }
```

## Quadratic easing out

Decelerating from zero velocity

```
Math.easeOutQuad = function (t) { return t*(2-t) }
```

## Quadratic easing in-out

Acceleration until halfway, then deceleration

```
Math.easeInOutQuad = function (t) { return t<.5 ? 2*t*t : -1+(4-2*t)*t }
```

## Cubic easing in 

Accelerating from zero velocity

```
Math.easeInCubic = function (t) { return t*t*t }
```

## Cubic easing out 

Decelerating to zero velocity

```
Math.easeOutCubic = function (t) { return (--t)*t*t+1 }
```

## Cubic easing in-out 

Acceleration until halfway, then deceleration

```
Math.easeInOutCubic = function (t) { return t<.5 ? 4*t*t*t : (t-1)*(2*t-2)*(2*t-2)+1 }
```

## Quart easing in 

Accelerating from zero velocity

```
Math.easeInQuart = function (t) { return t*t*t*t }
```

## Quart easing out 

Decelerating to zero velocity

```
Math.easeOutQuart = function (t) { return 1-(--t)*t*t*t }
```

## Quart easing in-out 

Acceleration until halfway, then deceleration

```
Math.easeInOutQuart = function (t) { return t<.5 ? 8*t*t*t*t : 1-8*(--t)*t*t*t }
```

## Quint easing in 

Accelerating from zero velocity

```
Math.easeInQuint = function (t) { return t*t*t*t }
```

## Quint easing out 

Decelerating to zero velocity

```
Math.easeOutQuint = function (t) { return 1-(--t)*t*t*t }
```

## Quint easing in-out 

Acceleration until halfway, then deceleration

```
Math.easeInOutQuint = function (t) { return t<.5 ? 8*t*t*t*t : 1-8*(--t)*t*t*t }
```


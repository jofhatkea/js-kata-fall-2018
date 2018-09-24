# JS-KATA

## Week 5, Day 2

### Dice Roll Generator

Is `Math.random()` really random?

Let's figure it out

### Your task

Generate X random numbers from 1-6 (both including), and visualize the amount of times a certain value was generated.

It could be as simple as

| Value | Times |
| ----- | ----- |
| 1     | 231   |
| 2     | 212   |
| 3     | 200   |
| 4     | 300   |
| 5     | 297   |
| 6     | 301   |

Or go crazy and show me a graph :-)

### Hints

1. You could create an object to hold the values, initializing it with zero, like

```js
const values = {
  totalRolls: 0,
  1: 0,
  2: 0,
  3: 0,
  4: 0,
  5: 0,
  6: 0
};
//Remember, you can access a property in two ways
values.totalRolls; // using dot notation
values["totalRolls"]; //as an array, but (it's not)
//but you CANNOT DO THIS
// values.1
```

2. or use an array

### Optional

1. Use [chart.js](https://www.chartjs.org/). It's not easy, and not impossible.

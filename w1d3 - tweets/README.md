# JS-KATA

## Week 1, Day 2

### Re-capping fetch

Today you're gonna work with `fetch`, again. This time to fetch tweets

Work with this endpoint:

https://kea-alt-del.dk/twitter/api/

It takes two additional parameters

`?count=50` (up to 100)

`?hashtag=word` which fetches tweets with a certain hastag

Use it to output some div's with some interesting tweets. Be creative

## Hints

If 2nd semester is far away to you, here's the common flow

1.  create a `<template />`
2.  `fetch` the data
3.  When you have the data, `clone` the `<template />`, something like

```javascript
let template = document.querySelector("#myTemplate").content;
let clone = template.cloneNode(true);
```

4.  Run through your data with `forEach`, if it's an array
5.  For each element in the data, change the content in the clone (like `clone.querySelector(".header").textContent=data.header`)
6.  Finally, `appendChild` to add the clone to the DOM

### Optional

Make it interactive by

- allowing the user to enter / chose the hashtag
- allowing the user to choose how many tweets are returned

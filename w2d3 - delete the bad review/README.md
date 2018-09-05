# JS-KATA

## Week 2, Day 3

### Delete the bad review

We have a website with a lot of reviews, some of them are bad, we need you to remove them

### Your task

Copy the html & css files from into `mysolution` and work with those.

The HTML file contains a list of reviews, remove the bad ones, e.g. all reviews with a score of 5 or less

### Hints

1. Use https://developer.mozilla.org/en-US/docs/Web/API/ChildNode/remove to remove the element
2. Use `.querySelectorAll` to select all the reviews
3. `forEach` to loop through them
4. Remove all reviews `<li>` with a score of 5 or less

### Optional

Turn your code in to a function that takes two arguments

1. A selector to use for `.querySelectorAll`
2. The minimum score accepted

# JS-KATA

## Week 4, Day 3

### The Distortion Bar

Hi Devs, It's Distortion time, so your task is to create a data-visualization for a bar called FooBar.

The bar needs a visualization on how many people are currently in queue to get a cold beer. You can see the data right here:

https://kea-alt-del.dk/kata-distortion/

The data refreshes every 10 seconds, so if you could set up the script to fetch every 10 seconds or so, that would be great.

## Requirements

- You must create a service that shows the amount of people in queue.
- The service must ask for data regularly, like every 10-20 seconds
- The visualization should be more than just a number (you can find inspiration below)

## The visualization

- The amount of people in queue can never be greater than 25
- Feel free to come up with something interesting
- Animations are awesome
- How about a "speed gauge?"
- Or a chart?
- Or ...

### Hints & Suggestions

With new data every 10 seconds, can you come up with a way of showing the changes?

- You could simply log the information on the screen (good first step)
- But, how about an element that animates to a new state whenever there's new data?

# JS-KATA

## Week 2, Day 4

### Digital Clock

In the early days of the web - around 20 years ago - it was considered cool to have a clock on your webpage. As if
the user wouldn't be allowed to look away from the webpage, to the clock on her own computer.

Anyways - your old-school boss has asked you to create such a clock on a webpage - and to keep it extra old-school,
you must use the digits in the image `7segment.jpg`. So you have to somehow display a portion of that image in an 
HTML element for each digit ...

There are some files in the `materials`-folder to get you started.

### Challenges

This task contains several challenges:
1. Create CSS-classes for each digit (there are some to get you started)
2. Get the hours, minutes and seconds for the current time
3. Make sure you get two digits for each value - the first may be a 0.
4. Remember to add, to each span, both the generic .digit-class and the class for the specific digit you want
5. Figure out how to select the spans, without modifying the HTML

### Hints

You can use `element.className = ""` to clear an elements classes. You can also set it to something else than ""

You can use `const today = new Date();` and then `today.getHours()`, `today.getMinutes()`, `today.getSeconds()` to get the various 
values. 

You can use `:nth-child` to select a specific child-element.

Do one challenge at a time. Make the visual work with manual digits, then get the clock to console log, then add
classes, then make sure you also clear unnessary classes.

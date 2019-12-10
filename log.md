# 100 Days Of Code - Log

### Day 1: 9th December, 2019

**Today's Progress**: I fixed an issue with the React Datepicker displaying behind the edges of it's parent component.

React Datepicker has an option to pass in a portal component to keep the date picker outside of the restricting element in the HTML. Therefore, removing the overflow restriction.

**Thoughts:** Interesting fact: `The computed values of ‘overflow-x’ and ‘overflow-y’ are the same as their specified values, except that some combinations with ‘visible’ are not possible: if one is specified as ‘visible’ and the other is ‘scroll’ or ‘auto’, then ‘visible’ is set to ‘auto’.`
Basically, this:
```
overflow-x: visible;
overflow-y: auto;
```
turns into this:
```
overflow-x: auto;
overflow-y: auto;
```

**Link to info:** [CSS Tricks](https://css-tricks.com/popping-hidden-overflow/)


### Day 2: 10th December, 2019

**Today's Progress**: I did a little re-factor of my latest project and added in React Modal

**Thoughts:** I'm interested in working out how to style the modal to be a little more neat. Maybe a little smaller on the page.

It's also interesting that it's just as easy to implement the modal in both a Class and Function component.

**Link to info:** [React Modal on Github](https://github.com/reactjs/react-modal)

# Mustache

Mustache is a logic-less template syntax. It can be used for HTML, config files, source code - anything. It works by expanding tags in a template using values provided in a hash or object.

We call it "logic-less" because there are no if statements, else clauses, or for loops. Instead there are only tags. Some tags are replaced with a value, some nothing, and others a series of values.
mustache-and-flexbox

# Flexbox

FlexBox is a css property to make our life much easier with layouting out webpages.

```
.container {
  display: flex; /* or inline-flex */
}
```

above code used to make our container a flexbox

```
.container {
  flex-direction: row | row-reverse | column | column-reverse;
}
```

by defualt our flex direction is row.

```
.container {
  flex-wrap: nowrap | wrap | wrap-reverse;
}
```

to make the flex items wrap we need to set flex-wrap to wrap

```
.container {
  justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right ... + safe | unsafe;
}
```

we use justify content to destribute our items as the given property on the x axis

```
.container {
  align-items: stretch | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end + ... safe | unsafe;
}
```

we use align items to destribute our items as the given property on the y axis

```
.item {
  order: 5; /* default is 0 */
}
```

order used to change the order of the flex items

```
.item {
  flex-grow: 4; /* default 0 */
}
.item {
  flex-shrink: 3; /* default 1 */
}
```

we use flex shrink and grow to tell the items how scale on screen size changing

```
.item {
  flex-basis:  | auto; /* default auto */
}
```

flex basis used to give our items a defualt width

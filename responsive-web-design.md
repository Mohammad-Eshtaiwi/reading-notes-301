# Responsive Web Design

In responsive design use flexible layouts and units
Relative Viewport Lengths

CSS3 introduced some new relative length units, specifically related to the viewport size of the browser or device. These new units include vw, vh, vmin, and vmax. Overall support for these new units isn’t great, but it is growing. In time they look to play a large roll in building responsive websites.

- vw Viewports width
- vh Viewports height
- vmin Minimum of the viewport’s height and width
- vmax Maximum of the viewport’s height and width

## Media Queries

we use media queries to control the sytle for different screen widths.

example:

```
/* @media Rule */
@media all and (max-width: 1024px) {...}

/* @import Rule */
@import url(styles.css) all and (max-width: 1024px) {...}

```

## Mobile First

One popular technique with using media queries is called mobile first. The mobile first approach includes using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.

# Floats

Float is a CSS positioning property that can be used to create layout of web pages.

example of valid values:

```
float:right
float:left
```

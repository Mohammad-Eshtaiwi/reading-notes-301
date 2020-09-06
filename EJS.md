# EJS

EJS is templting languge that use to genarate html files at the end. It used in need to a way to create dynamic content to the web page based on the data comming from the api and OFC we can't get that goal by static html.

## features

-   Features
-   Fast compilation and rendering
-   Simple template tags: <% %>
-   Custom delimiters (e.g., use [? ?] instead of <% %>)
-   Sub-template includes
-   Ships with CLI
-   Both server JS and browser support
-   Static caching of intermediate JavaScript
-   Static caching of templates
-   Complies with the Express view system

## Install

```

$ npm install ejs

```

# Include

```
let ejs = require('ejs');
let people = ['geddy', 'neil', 'alex'];
let html = ejs.render('<%= people.join(", "); %>', {people: people});
```

# EJS Partials

Partials is a way to create reusable components that can be simply included in any page for example the navbar is the same in every page also the footer

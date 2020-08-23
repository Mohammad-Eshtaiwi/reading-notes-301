# jQuery

jQuery is js liblary used to help developers to write less code and make js eazier to them. and can be used to acompliched:

- select elements
- perform tasks
- handle events

css selector:

```
$("p")
```

\$() shortcut for the jQuery ()

it is better to store the result of \$("p") into variable because creating new object take long time. With jQuery, when a selector returns multiple elem ents, you can update all of them using the one method. There is no need to use a loop. which is woooow.

Most methods used to update
the jQuery selection can be
chained. However the methods that retrieve information from the DOM (or about the browser)cannot be chained.

```
$( document ).ready(function() {
  // Handler for .ready() called.
});
```

the code above used to make sure our code work after the htmp page loaded.

[cheat sheet](https://oscarotero.com/jquery/)

# pair programming

pair programming means to collaborate with another programer to enhance your work and think and do tasks together

## How does pair programming work?

- driver: its main job to focus on writing the code and directly interact with it
- navigator: its main job to give the driver the instructions and the ideas and to help him avoid mistakes

the pair programing will make your code take a little bit longer to write but will save time later by making less time to debug and test. Also, will make the programmers focus more and relay on each other. Also, each one has his skills pool when 2 share their skills they will learn from each other and give them more soft skills and make them work better with teams

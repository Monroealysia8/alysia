(taken from homework reading 2)
Being a “constant” just means that a variable’s value never changes. But some constants are known before execution (like a hexadecimal value for red) and some constants are _calculated_ in run-time, during the execution, but do not change after their initial assignment.

For instance:

``` `const` pageLoadTime `=` `/* time taken by a webpage to load */``;` ```

The value of `pageLoadTime` is not known before the page load, so it’s named normally. But it’s still a constant because it doesn’t change after the assignment.

In other words, capital-named constants are only used as aliases for “hard-coded” values.d properties](https://javascript.info/object#literals-and-properties)



(what is the difference between this and a function?) they both use the css format {}

-objects

-arrays

INSERTING INTO HTML
id and div

There is a general programming term “closure”, that developers generally should know.

A [closure](https://en.wikipedia.org/wiki/Closure_(computer_programming)) is a function that remembers its outer variables and can access them. In some languages, that’s not possible, or a function should be written in a special way to make it happen. But as explained above, in JavaScript, all functions are naturally closures (there is only one exception, to be covered in [The "new Function" syntax](https://javascript.info/new-function)).

That is: they automatically remember where they were created using a hidden `[[Environment]]` property, and then their code can access outer variables.

When on an interview, a frontend developer gets a question about “what’s a closure?”, a valid answer would be a definition of the closure and an explanation that all functions in JavaScript are closures, and maybe a few more words about technical details: the `[[Environment]]` property and how Lexical Environments work.
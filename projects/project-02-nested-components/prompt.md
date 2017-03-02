# You Do: Add Nested Comments To Blog (15 minutes) #

Amend your __Post__'s render method to include reference to a variable, __comments__, that is equal to the return value of generating multiple __<Comment /__> elements. Make sure to pass in the __comment__ body as an argument to each __Comment__ component. Then render the __comments__ some where inside the UI for a __Post__.

> __NOTE:__ If you'd like, you can use __.map__ in __Post__'s __render__ method to avoid having to hard-code all your __Comment__s. Read more about it [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map) and [here](http://cryto.net/~joepie91/blog/2015/05/04/functional-programming-in-javascript-map-filter-reduce/).

> __HINT I:__ If you're using __.map__, you should only have to return one __<Comment />__ inside of __.map__.

> __HINT II:__ Remember that whenever you write vanilla Javascript inside of JSX, you need to surround it with single brackets (__{}__).

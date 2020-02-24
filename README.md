# what-i-learned-in-week-5

## Preamble

During week 5 I didn't learn very new things but stead was focused on strengthening while and for loops. Along with learning how to manipulate arrays and using its various methods to mutate and use array as a tool for advancement of more functional software creation.

## Arrays

Arrays are lists of data that are very useful in various situation. They can also be one dimensional meaning a list that contains only one level of list or a list within a list which makes more dimensions into an array.

declaring an array can be with _let_ or _const_ equals [_within these square brackets put a list of items in order from left to right or from index 0 to end of the list separated by a coma for each individual item_] example:  

_let exampleArr = ['apples', 'oranges', 'bananas']_

Methods:  

* isArray() - checks if an object is an array
* indexOf() - returns position of index of a list item  
* pop() - removes last item and returns its value (could be used to remove from original list and create a new one with that last item into an array)  
* join('_separator example string added_') - creates a string out all items in an array
* reverse() - reverses order of index items in an array
* valueOf() - fancy way to express what is in array same as array itself
* push() - adds new value to end of an array
* shift() - similar to pop but instead removes First item and return that value
* unshift() - add new value to the beginning of an array and return new value similar to push
* slice(_start value, end value(not including)_) - using start index number value and end value not incuding that end value returns a new array with those values
* splice(_index at, howmanyX, item1,...itemX ) - adds or removes items from an array. if items are not specified removes items and returns them otherwise adds items and returns.
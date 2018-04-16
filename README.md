# Secret-Message-App

## Using Arrays and array methods to decode a secret message in a classic tale.

Excerpt from The Odyssey, By Homer Book 1, first two paragraphs. Can you decipher the secret message?

### What I learned:

#### Arrays

Array are Javascript's way of making lists. These arrays can store any data types (including strings, numbers, and booleans)

##### Property Access

* Arrays are 'ordered', meaning each item in the array has a numbered position.
* * to access an individual item in an array, use its numbered position, remembering that the first index position in an array is [0], not [1]
* * you can also change or rename an element in an array, by referencing it's index when you reassign it.

##### Common Array Methods

* 'array.length()' - returns the number of elements in the array.
* 'array.push('thing1', 'thing2')' - adds elements to the end of the array
* 'array.pop()' - removes the last item in an array
* 'array.join()' - joins all elements of an array into a string
* 'array.slice()' - extracts a section of an array, and returns a _new_ array
* 'array.splice()' - adds / removes elements from an array
* 'array.shift()' - removes the first element from an array, and returns that element
* 'array.unshift()' - adds one or more elements to the front of the array, and returns the new length of an array.
* 'array.concat()' - returns a new array, comprised of this array joined with other arrays values.

##### Arrays with Let and Const

* arrays that are declared with const are _mutable_, or change-able. This means we can change the contents of the array, but we cannot reassign the variable name or data type.

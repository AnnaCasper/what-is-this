## What is this??

To get started, install node http-server:

```
npm install http-server -g
```

Run the http-server from within the 'what-is-this' directory:
```
http-server
```

Then open your browser to http://localhost:8080/ and open up the console.

As you go through the exercise, complete the associated writeup.

##Answers
##Rule 1:
- 'This', when not attached to an object, will refer to the global space in which it is running, in this case the entire window object.

##Rule 2:
- 'This' will always refer to the object upon which it is called. When called as a function from an object function, the parent object becomes 'this'. In this case, 'this' refers to the window object.

##Rule 3:
- 'This' will always refer to the object upon which it is called. When called as a function from an object function, the parent object becomes 'this'. In this case, 'this' refers to the window object.

##Rule 4:
- .call() will allow you to declare, in the first argument, the object in which to call the function on. Other arguments are in a list.
- .apply() will allow you to declare, in the first argument, the object in which to call the function on. Other arguments are in an array.
- .bind() will establishes a 'this' for the entire function and will call that function on the declared 'this' for all future function calls.

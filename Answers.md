1. Describe the biggest difference between `.forEach` & `.map`.
    The biggest difference between these two methods is that .map actually return a new array and .forEach does not.

2. What is the difference between a function and a method?
    functions are created by the programmer and assigned a name, methods are functions that are already built in to javascript and can be run on objects.


3. What is closure?
    Closures are created any time you create a function. Closure gives you access to an outer function's scope from an inner function and describes this process in terms of the lexical environment.


4. Describe the four rules of the 'this' keyword.


    a. Window Binding - When using the 'this' keyword, if you don't point it to anything, it will automatically bind to the window object.


    b. Implicit Binding - Implicit binding is used in the majority of the cases where the 'this' keyword is used. What it means is that it is pointing the the 'this' keyword to whatever is to the left of the method.


    c. Explicit Binding - means that we are explicitely telling the function what we
    want this bound to. We have 3 different methods to do that with and they are:
    .call, .apply and .bind


    d. New Binding - the new operator creates blank js object and links it to the constructor or another object and passes the newly created object as the 'this' context.



5. Why do we need super() in an extended class?
    We need super() to reference the parent class.


1. Describe the biggest difference between .forEach & .map.
	.forEach is a method used to execute a function once for each element in an array, whereas while .map also performs the function on each element of the array, it also creates a new array with the results of calling that function on the array.

2. What is the difference between a function and a method?
	A function is a reusable piece of code that can be defined outside of an object and not be associated with an object, however, when a function is defined inside of an object it is a method.

3. What is closure?
	Closure refers to the scope that we write JavaScript in - when an inner function has access to data outside of itself, ie in addition to accessing the data within its own scope (inside its curly braces), it can access the outer functions data, as well as anything that is in the global scope.

4. Describe the four rules of the 'this' keyword.
	Principle 1: Window/Global Object Binding - When we use "this" in a window or global object binding, "this" will be the window itself or the console.

	Principle 2: Implicit Binding - When we use "this" in an implicit binding, the value of "this" will be based on whatever precedes (is to the left of) the dot when called.
	
	Principle 3: Explicit Binding - When we use an explicit binding, for example .call and .apply, we are able to override the values that were had been originally set for the object with a constructor function.  We are able to use arrays to overried these values when we use the .apply method, or individual methods alone when we use the .call method.
	
	Principle 4: New Binding - When we use "this" in a new binding, the value of "this" is beign used as part of the constructor function to create a new object.

5. Why do we need super() in an extended class?
	The super() function calls on the base class's attributes (or the class it needs to inherit from) to pass them to the extended class.  This allows us to no longer need to use .call method nor to use the Object.create() method.
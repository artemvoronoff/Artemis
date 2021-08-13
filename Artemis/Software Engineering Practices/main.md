Software Engineering Practices

1.) Don't repeat yourself.
	a.) Modularization allows you to reuse parts of your code. Generalize and attempt to consolidate repeated (repeatable) code in functions or loops.

2.) Abstract out logic to improve readability.
	a.) Creates less repetitive coder, and improves readability, with descriptive function names. BE WEARY: abstracting too much logic in to functions,
		  prone to over-engineering and having too many modules.

3.) Minimize the number of entities (functions, classes, modules, etc).
	a.) There are trade-offs to having function calls instead of inline logic. If you create to many unecessary entities, you'll be jumping around all day,
			and therefore will result in ineffective modularization.

4.) Functions should do one thing.
	a.) If a function is doing multiple things at once, it becomes less "re-usable"-- if so, consider refactoring.

5.) Arbitrary variable names can be more effective in certain functions.
	a.) Arbitary variable name sin general functions can actulaly make it more readable and reusable.

6.) Try to use fewer than three arguments per function.
	a.) Remember we are modularizing to simplify our code and make it more efficient. If your function has a lot of parameters, you may want to rethink how you 
			are splitting this up.
	

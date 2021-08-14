# Testing Code

Testing your code is essential before deployment. It helps you catch errors and faulty conclusions before they make any major impact. Today, employers are looking for data scientists with the skills to properly prepare their code for an industry setting, which includes testing their code.

### Testing and Data Science

	Problems that could occur in data science aren't always easily detectable; you might have values being encoded incorrectly, 
	features being used inappropriately, or unexpected data breaking assumptions.

	To catch these errors, you have to check for the quality and accuracy of your analysis in addition to the quality of your code.
	Proper testing is necessary to avoid unexpected surprises and have confidence in your results.

	Test-driven development (TDD): A development process in which you write tests for tasks before you even write the code to implement those tasks.

	Unit test: A type of test that covers a "unit" of code--usually a single function--indepenedently from the rest of the program.


### Unit Tests

We want to test our functions in a way that is repeatable and automated. Ideally, we'd run a test program that runs all our unit tests and cleanly lets us know which ones failed and which ones succeeded. Fortunately, there are great tools available in python that we can use to create effective unit tests! 
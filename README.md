Unit Testing
	Automated code that ensures a unit of work (function) yields the expected value.

Unit Testing Framework
	Prewritten library of function that provide assertions

Unit Test
	A set of assertions for a single unit (function).

Test Coverage
	The % of functionality that is "covered by your unit test"

Test Suite
	Set of all unit tests in your project

Ways that we've "tested,"" thus far...
	"Invoking the log method on the console."
Unit Testing (Raine's Definition)
	Code that calls your functions with test inputs and verifies the output

The smallest unit testing library.

var assert = function (a,b) {
	if (a !== b) {
	console.error('Expected', a, 'to equal', b);
}
else {
	console.log('Test passed!', a, 'equals', b);
}
};


.DOT Notation
	-Always executes left to right.
	window.prompt('What is your name?').length

Function composition
	-Executes inside to outside, via order of operations
	parseInt(prompt('Age?'));
		Must have the result of prompt to execute parseInt

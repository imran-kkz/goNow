# Notes

golang is a statically typed language - meaning that the type of a variable is known at compile-time instead of at run-time.
	- examples of dynamically typed langs are python, groovy, perl


Variable declaration
	- var foo int
	- foo:= 42
		- this will declare the variable and let go assign the correct type 

	- can't redeclare variables, but can shadow them
	- all variables must be used

Visibility
	- lower case first letter for package scope
	- upper case first letter to export
	- no private scope

Naming conventions:
	- longer names for longer lives
	- as short as reasonably possible
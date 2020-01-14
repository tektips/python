
## Example One - greet.py

def greet(name):
	
> This function calls the greet method and and displays the name passed in the method
	
	print("Hello, " + name + ". Good morning dude!")
	
 greet("Mat") 

_Hello, **Mat.** Good morning dude_


## Example Two 

> If we intend the greet method, we get the below errors  

def greet(name):
	
> This function calls the greet method and and displays the name passed in the method. The greet method is __indented to cause an syntax error__
	
	print("Hello, " + name + ". Good morning dude!")
	
      greet("Mat") 


**IndentationError: unindent does not match any outer indentation level**

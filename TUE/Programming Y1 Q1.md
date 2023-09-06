## Classes
Example:
```java
class Test {
	// prints hello world
	private void hello() {
		System.io.println("Hello World");
	}
	public static void main(String[] args) {
		new Test().hello();
	}
}
```
Writes the text "Hello World" on the screen.
Notice that the part after the "//" isn't interpreted.
A class is a collection of functions and variables which abstract something.
When a java project is called the compiler will try to find any class that has a "static" function called main that takes an array of strings.

## Functions
is a visibility followed by a return type, the parameter's and a block of java code.
Void can be used when there is no return type.

## Visibility
|name | use|
|---|---|
|public | Can be accesed from any where.|
|private | Can only be accessed from within the parent class|
|None| Almost the same as private.|

## Static vs non-static
Static means that something can be accessed without a object of that type. If the static keyword is not used, you need an object of that type to use the variable or function.

## Basic Types
### String
### Int
### Float/Double
### Array: `(int[])`
### ArrayList
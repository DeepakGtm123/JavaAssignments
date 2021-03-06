# **Default Method Interface**
*Default methods* enable us to add new functionality to the interfaces of your libraries and ensure binary compatibility with code written for older versions of those interfaces.
In a typical design based on abstractions, where an interface has one or multiple implementations, if one or more methods are added to the interface, all the implementations will be 
forced to implement them too. Otherwise, the design will just break down.
Default interface methods are an efficient way to deal with this issue. They allow us to add new methods to an interface that are automatically available in the implementations. Thus, 
there's no need to modify the implementing classes.
In this way, backward compatibility is neatly preserved without having to refactor the implementers.

CODE Example
```Java                      
      interface TestInterface { 
 	public void square(int a); 
	default void show() { 
     		System.out.println("Default Method Executed"); 
    	} 
     } 
     class TestClass implements TestInterface { 
     	public void square(int a) { 
     		System.out.println(a*a); 
   	 } 
	public static void main(String args[]){ 
     		TestClass d = new TestClass(); 
     		d.square(4); 
     		d.show(); 
     	} 
     }
 ```

### 1. What is the difference between C and C++?

<table border="0">
 <tr>
 <td><b style="font-size:30px">C </b></td>
    <td><b style="font-size:30px">C++</b></td>
 </tr>
 <tr>
    <td>
    	<ul>
        	<li> C language is a procedure <br> oriented programming language </li>
  		<li> It follows top-down approach</li>
  		<li> It doesn't support function or <br> operator overloading </li>
            	<li> C language doesn't support <br> virtual and friend function </li>
  		<li> C language have 32 keywords </li>
	</ul>
   </td>
   <td>
    	<ul>
  		<li> C++ is partially object oriented <br> programming language </li>
  		<li> It follows bottom-up approach </li>
  		<li> It supports function as well as <br> function overloading </li>
            	<li> C++ language supports both <br> virtual and friend functions </li>
  		<li> C++ language have 52 keywords</li>
	</ul>
  </td>
</tr>
</table>

### 2. What are classes and objects in C++?

 A class is a user-defined datatype members and member functions and <br> is defined with the keyword class.
 Objects are defined as an instance of a class. Once the object is created, <br> then it can operate on both data members and member functions.

### 3. What are access modifiers?

Access modifiers are used to define accessibility for the class members. <br> It defines how the members of the class are accessed outside the class scope. <br> There are three types of access modifiers: 
* Private
* Public
* Protected

### 4. What are C++ OOPs concept? 
* Object
* Class
* Inheritance 
* Abstraction
* Encapsulation 
* Polymorphism 

### 5. What is an object in C++?
An object is an instance of a class with the class's own methods or procedures <br> and data variables.

### 6. What is class in C++?
A class is a user-defined data type that we can use in our program, and it works <br> as an object constructor, or a "blueprint" for creating objects. 

### 7. What is the inheritance in C++?
Inheritance is one of the main features of object-oriented programming in C++, <br> allowing us to inherit another class's properties.

### 8. What is meant by abstraction in C++? 
Data abstraction refers to providing only essential information to the outside <br> world and hiding their background details.

### 9. What is Encapsulation in C++?
Encapsulation is an Object Oriented Programming concept that binds together <br> the data and functions that manipulate the data, and that keeps both safe from <br> outside interference and misuse.

### 10. What is Polymorphism in C++?
What is Polymorphism in C++? Polymorphism in C++ means, the same entity <br>(function or object) behaves differently in different scenarios.

### 11. What is a Vector in STL?
Vectors are the same as dynamic arrays with the ability to resize itself automatically <br> when an element is inserted or deleted, with their storage being handled automatically <br> by the container.

### 12. What is a List in STL?
Lists are sequence containers that allow non-contiguous memory allocation. <br> As compared to vector, the list has slow traversal, but once a position has been <br> found, insertion and deletion are quick.

### 13. What is a Map in STL?
Maps are associative containers that store elements in a mapped fashion. <br> Each element has a key value and a mapped value. No two mapped values <br> can have the same key values.

### 14. What is a Constructor?
A constructor is a member function taht is invoked whenever we create an object, <br> it has the same name as that of the class. <br> There are 2 types of constructors:
* Default constructor 
* Parameterized constructor 

### 15. What is a Destructor?
A destructor is a member function that is invoked automatically when the object goes out <br> of scope or is explicitly destroyed by a call to delete.

### 16. What is operator overloading in C++?
It's a type of polymorphism in which an operator is overloaded to give it the user-defined <br> meaning. C++ allows us to specify more than one definition for a function name or an operator <br> in the same scope, which is called function overloading and operator overloading, respectively.

### 17. What is a pointer?
A pointer is a variable that stores the memory address of another variable as its value. <br> Pointers are used extensively in both C and C++ for three main purposes: to allocate new <br> objects on the heap, to pass functions to other functions. to iterate over elements in arrays <br> or other data structures.

### 18. What is a reference?
A reference variable is an alias, that is, another name for an already existing variable. <br> Once a reference is initialized with a variable, either the variable name or the reference <br> name may be used to refer to the variable.

### 19. What is the difference between reference and pointer?
References are used to refer an existing variable in another name whereas pointers <br> are used to store address of variable. References cannot have a null value assigned <br> but pointer can. A reference variable can be referenced by pass by value whereas a <br> pointer can be referenced by pass by reference.

### 20. What is an enum?
An enumeration, or Enum , is a symbolic name for a set of values. Enumerations are <br> treated as data types, and you can use them to create sets of constants for use with <br> variables and properties.

### 21. What is the difference between Vector and List?
<table border="0">
 <tr>
 <td><b style="font-size:30px">Vector</b></td>
    <td><b style="font-size:30px">List</b></td>
 </tr>
 <tr>
    <td>
    	<ul>
        	<li> It has contiguous memory </li>
  		<li> It is synchronized </li>
  		<li> Vector may have a default size </li>
            	<li> In vector, each element only <br> requires the space for itself only </li>
  		<li> Random access of elements is possible </li>
	</ul>
   </td>
   <td>
    	<ul>
  		<li> It has non-contiguous memory </li>
  		<li> It is not synchronized </li>
  		<li> List does not have default size </li>
            	<li> In list, each element requires <br>
		extra space for the node which holds <br>
		the element, including pointers to the <br>
		next and previous elements in the list. </li>
  		<li>Random access of elements is not possible</li>
	</ul>
  </td>
</tr>
</table>
 
 

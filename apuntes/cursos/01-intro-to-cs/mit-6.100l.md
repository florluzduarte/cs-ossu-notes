# MIT 6.100L: Introduction to Computer Science and Programming using Python   

----

Course Link: https://ocw.mit.edu/courses/6-100l-introduction-to-cs-and-programming-using-python-fall-2022/pages/lecture-1-introduction/  

----
## **Lecture 1 - Introduction** 

Date: 2025/02/19  
### **a. What is an algorithm?**

A sequence of simple steps, that uses flow of control process to specify when each step is executed and, a means of determining when to stop.  

Algorithms are recipes / Recipes are algorithms 

A computer will only do what you tell it to do (using algorithms).


### **b. Aspects of Languages**

Anything computable in one language is computable in any other programming language.  

In programming languages the primitive constructs of the language are: numbers, strings and simple operators (at least for Python).  

The syntax of a language are the rules that are allow in the process of combining the primitive constructs. 

The semantics of a language is the meaning associated with a syntactically correct string of symbols with no static semantic errors. 

Natural languages can have many meanings associated to the same expression, because the brain can understand the phrase in context, and derive it's meaning from that context.

But in programming, each statement can have only one meaning, because computers can only follow instructions literally, but the problem is the meaning may not be what the programmer intended (bug).  


### **c. Objects**

Programs manipulate data objects. Objects have a type that defines the kinds of things programs can do to them.

For different types we have different operations available. 

For example:
	- For numbers we can perform mathematical operations, etc.  
	- For strings we can extract substrings, uppercase, lowercase, etc. 

In Python there are two types of objects:

1. Scalar Objects (cannot be subdivided, primitive values)
	- Numbers
	- Booleans
	- None 
2. Non-Scalar Objects (have an internal structure that can be accessed)
	- Lists
	- Dictionaries
	- Strings  

We can use the `type()` method to determine the type of an object. 

Types of Scalar Objects:
- int > represents integers
- float > represent real numbers 
- bool > Boolean values True and False 
- None Type > special type that has one value > None


### **d. Expressions**

Combine objects and operators to form expressions (3 + 5). An expression has a value, which has a type. Python evaluates expressions and stores the value in memory. It doesn't store expressions. 

```
Syntax for a simple expression
<object> <operator> <object>
3 + 2
```

> TIP 💡
> Replace complex expressions by ONE value 


### **e. Variables**

Computer Science variables are different than math variables. 

Math Variables:
- Are Abstract
- Can represent many values

CS Variables:
- Are bound to one value at a given time 
- Can be bound to an expression (but expressions always evaluate to one value that gets stored in memory)  

The = (equal) sign is an assignment statement. An assignment binds a value to a name we can use to invoque that value. 

Why give names to values of expressions?
- To reuse names instead of values
- It makes code easier to read and modify 

We need to choose variable names wisely. Code needs to be simple to read at any given time (today, tomorrow, next year, etc.) by you and others. Some rules apply and some names can't be use to assign variables (don't start with a number, don't use reserved expressions, don't use expressions as names).   

We can re-bind variable names using new assignment statements (in Python it works, in other languages might not work). The previous value may still be stored in memory, but we lost the handle for it, so we can't invoque it again.  

*Additional material* > All you need to know about different data types in Python:  https://medium.com/@jyotiranjanmishra1990/all-you-need-to-know-about-different-data-types-in-python-a71d632897c7 


----

## **Lecture 2 -** 

Date: 
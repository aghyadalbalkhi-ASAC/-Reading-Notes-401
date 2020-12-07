# Read: 07 - Readings: Python Scope


*Today Topic will be a about*
- Python Scope


## Python Scope

> What Is Python Scope?

![PythonScope](images/Python-Variable-Scope-01-1200x900.jpg)

*The concept of scope rules how variables and names are looked up in your code. It determines the visibility of a variable within the code. The scope of a name or variable depends on the place in your code where you create that variable. The Python scope concept is generally presented using a rule known as the LEGB rule.*

*The letters in the acronym LEGB stand for Local, Enclosing, Global, and Built-in scopes. This summarizes not only the Python scope levels but also the sequence of steps that Python follows when resolving names in a program*

* Global scope: The names that you define in this scope are available to all your code.

* Local scope: The names that you define in this scope are only available or visible to the code within the scope.

*Scope came about because early programming languages (like BASIC) only had global names. With this kind of name, any part of the program could modify any variable at any time, so maintaining and debugging large programs could become a real nightmare. To work with global names, you’d need to keep all the code in mind at the same time to know what the value of a given name is at any time. This was an important side-effect of not having scopes.*



*Some languages like Python use scope to avoid this kind of problem. When you use a language that implements scope, there’s no way for you to access all the variables in a program at all locations in that program. In this case, your ability to access a given name will depend on where you’ve defined that name.*

*The names in your programs will have the scope of the block of code in which you define them. When you can access the value of a given name from someplace in your code, you’ll say that the name is in scope. If you can’t access the name, then you’ll say that the name is out of scope.*

`Names and Scopes in Python` Since Python is a dynamically-typed language, variables in Python come into existence when you first assign them a value. On the other hand, functions and classes are available after you define them using def or class, respectively. Finally, modules exist after you import them. As a summary, you can create Python names through one of the following operations


| Operation       | Statement  |
|-------------------------|----------------------------------------------------------------------------------------------------|
| Assignments      | x = value  |
| Import operations	      | import module or from module import name  |
| Function definitions	      | def my_func()  |
| Argument definitions	      | in the context of functions def my_func(arg1, arg2,... argN):  |
| Class definitions	      | class MyClass  |

**Python Scope vs Namespace:**

- These dictionaries are commonly called namespaces.
- These are the concrete mechanisms that Python uses to store names.
- They’re stored in a special attribute called .dict.



## Contact Info : 
**Please Feel Free To Contact Me When You Need help ^_^**
* [www.facebook.com/aghyadalbalkhi](www.facebook.com/aghyadalbalkhi)
* Email : aghyadalbalkhi@gmail.com
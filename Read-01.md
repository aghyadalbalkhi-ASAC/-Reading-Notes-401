# Read: 01 - Big O and Names,Values in Python

*Today Topic will be a about*
- Big O
- Names & Values in Python 

## Big O

> What is Big O?

![Big O](images/big-O.png)

*Let’s talk about the Big O notation and time complexity here. To measure the performance of a program we use metrics like time and memory. The amount of time it takes for the algorithm to run and the amount of memory it uses.*

*Lesser the time and memory consumed by the algorithm, the better it is considered. However, time and memory are metrics that often increase with the size of the input. The same algorithm will take more time and memory for a larger input.*

`The common standard is to express the running time of an algorithm as a function of the input size [f(n)].`

**we have three cases**

* Worst case : Considers the input for which the algorithm takes the longest time.
* Best case : Considers the input for which the algorithm runs the fastest.
* Average case : Considers a random input.

**Commonly seen Big-O Notations**


- `O(1)` : describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.


- `O(N)` : describes an algorithm whose performance will grow linearly and in direct proportion to the size of the input data set.

- `O(N2)` : represents an algorithm whose performance is directly proportional to the square of the size of the input data set.

- `O(2N)` :  denotes an algorithm whose growth doubles with each additon to the input data set.

**For Example**

```
for(i=1;i<=n;i++)
m=m+2; // constant time 
```

Here the statement inside the loop will run n number of times. So the time complexity is :`O(n)`

## Names & Values in Python 

> Names in Python

![Python](images/python.png)

**Rules for Python variables:**

* A variable name must start with a letter or the underscore character
* A variable name cannot start with a number
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Variable names are case-sensitive (age, Age and AGE are three different variables)

*The behavior of `names` and `values` in Python can be `confusing.` Like many parts of Python, it has an underlying simplicity that can be hard to discern, especially if you are used to other programming languages.*

As in many programming languages, a Python assignment statement associates a symbolic name on the left-hand side with a value on the right-hand side. In Python, we say that names refer to values, or a name is a reference to a value

`x = 23`

*An important fact about assignment:*

`Fact: Assignment never copies data.`
When values have more than one name, it’s easy to get confused and think of it as two names and two values:

```
x = 23
y = x

```

Assigning a value to a name never copies the data, it never makes a new value. Assignment just makes the name on the left refer to the value on the right.


Python is dynamically typed, which means that names have no type. Any name can refer to any value at any time. A name can refer to an integer, and then to a string, and then to a function, and then to a module.

Just as names have no type, values have no scope. When we say that a function has a local variable, we mean that the name is scoped to the function: you can’t use the name outside the function, and when the function returns, the name is destroyed. But as we’ve seen, if the name’s value has other references, it will live on beyond the function call. It is a local name, not a local value.

## Contact Info : 
**Please Feel Free To Contact Me When You Need help ^_^**
* [www.facebook.com/aghyadalbalkhi](www.facebook.com/aghyadalbalkhi)
* Email : aghyadalbalkhi@gmail.com
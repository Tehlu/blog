# Blog

Hello, this is a blog where I'll be adding my thoughts as it relates to tech, programming, etc.


## Article #1 Python vs Javascript
Two of my favorite languages. I love Python because of its versatility and simpler syntax.
I love Javascript because it's ubiquitous throughout the web.
I can highlight some of the differences. 

***Function declaration***<br>
Python: def funcName(par: type):<br>
Javascript: function funcName(par) {}
Hoisting(calling before definition) allowed in Js, No hoisting in Py
Doctrings for Py

***Variable***<br> 
Python: Dynamic, No command for declaring variables. i.e x=5, x=True, etc 
Javascript: Dynamic, uses var, let, const to declare variables.

***Spacing, Indentation***<br>
Python must use a four tabs indent on each level. No mixing of tabs and spaces.
Js has just best practices(similar to Python btw) but no indent requirements. Examples: space after commas in list, space between Classes(2), methods(1) etc



***Control Flow (Loops & Conditionals)***<br>
Python uses indentation to control flow whereas Javascript uses parentheses and curly braces.

  Python:<br>
  ```
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
  ```

JS:<br>
```
if (age >= 18) {
    console.log("You are an adult.");
} else {
    console.log("You are a minor.");
}
```
For loops, python uses a more readable approach while JS uses the traditional, index-based loop. We must note that, however, index can be used for python and for JS ES6 introduced a newer syntax similar to Python.<br>
Python<br>

```
fruits = ["Apple", "Banana","Cherry"]
for fruit in fruits:
    print(fruit)
```
Javascript<br>
```
let fruits = ["Apple", "Banana", "Cherry"];
for(let i=0; i<fruits.length; i++){
    console.log(fruits[i]);
}
```
ES6 <br>
```
for (let fruit of fruits) {
    console.log(fruit);
}
```
Output f"{}" vs `${}` <br>

***Use Case***<br>
Python is popular in Data Science, Machine Learning, IOT, security, automation
JS is mainly used in web applications. 
However, both languages have frameworks and libraries we can use to create desktop and mobile apps. (console apps A)
We'll explore more when it comes to developing libraries, or even applications close to the hardware (embedded systems, kernels, OS, etc)

***Paradigm***<br>
Both languages are considered multi-paradigm languages. Can be used in object-oriented, functional, and imperative programming developments.
Because of its event-driven nature, JS is closer to Functional Programming than the rest.

*Rabbit-trail*<br> Functional Programming is based on mathematical functions and focuses on what to solve. Characteristics: Data immutable, pure fns(no side effect), first class fns(can be returned from another fn, assigned to variables and can pass as an argument. Often uses recursion instead of loops.
              Declarative programming describes the desired state of the program and data. The control flow is abstracted away. We don't tell how to do it but what to do. 
              i.e numbers = [1, 2, 3, 4, 5] squares = [x * x for x in numbers]
Imperative programming is the opposite of declarative programming as it requires the writing of step by step instructions on how to solve the problem(arrive at the desired state of the program). It takes care of the how.


***List Comprehension***<br> 
Python has list comprehension-> shorthand of creating a list based on an existing list i.e newlist = [expression for item in iterable if condition == True].
While there's no direct equivalent in Javascript, we can achieve the same thing using methods like map(), reduce(), and filter().

***Asynchronus Operations***<br>
Python uses libraries like asyncio to handle asynchronus tasks while JS has native tools like promises, async/await, callbacks etc

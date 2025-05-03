## Article #1 Python vs Javascript
Two of my favorite languages. I love Python because of its versatility and simpler syntax.
I love Javascript (JS) because it's ubiquitous throughout the web.
I can highlight some of the differences. 

***Function declaration***<br>
Python: def funcName(par: type):<br>
Javascript: function funcName(par) {}
Hoisting(calling before definition) allowed in Js, No hoisting in Py.
Doctrings for Py.

***Variable***<br> 
Python: Dynamic, No command for declaring variables. i.e x=5, x=True, etc 
Javascript: Dynamic, uses var, let, const to declare variables. In JS, variables declared with var are hoisted up (Can be used before declaration) unlike const and let.

***Spacing, Indentation***<br>
Python must use a four tabs indent on each level. No mixing of tabs and spaces.
Js has just best practices (similar to Python btw) but no indent requirements. Examples: space after commas in list, space between Classes(2), methods(1) etc.

***Comments***<br>
Python's single line comments use a hash symbol (#). While it doesn't have a syntax for multiline comments, one can use the triple quotes '''multiline comment''' (or """) representing unassigned strings.<br>
JS uses double forward slash // for single line and slash+asterisk for multiline comments /*multiline comment*/.

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

# Using index
for i,fruit in enumerate(fruits):
    print(f"fruit number {i} is {fruit}")
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
Output <br>
To include expressions or values, Py uses f-strings f"{expression}" whereas JS uses template literals `${expression}` <br>
i.e <br>
Py <br>
```
name = "World"
print(f"Hello, {name}!") # Output: Hello, World! <br>
```
JS<br>
```
const name = "World";
console.log(`Hello, ${name}!`); // Output: Hello, World!
```
Switch-Case Statement<br>
Python uses the classic switch-case or match-case(more powerful) construct for pattern matching. Javascript uses only switch-case.

***Use Case***<br>
Python is popular in Data Science, Machine Learning, IOT, security, automation
JS is mainly used in web applications. 
However, both languages have frameworks and libraries we can use to create desktop and mobile apps. (console apps A)
We'll explore more when it comes to developing libraries, or even applications close to the hardware (embedded systems, kernels, OS, etc).

***Paradigm***<br>
Both languages are considered multi-paradigm languages. Can be used in object-oriented, functional, and imperative programming developments.
Because of its event-driven nature, JS is closer to Functional Programming than the rest.

*Rabbit-trail*<br> Functional Programming is based on mathematical functions and focuses on what to solve. Characteristics: Data immutable, pure fns(no side effect), first class fns(can be returned from another fn, assigned to variables and can pass as an argument. Often uses recursion instead of loops.
              Declarative programming describes the desired state of the program and data. The control flow is abstracted away. We do not tell how to do it but what to do. 
              i.e numbers = [1, 2, 3, 4, 5] squares = [x * x for x in numbers]
Imperative programming is the opposite of declarative programming as it requires the writing of step by step instructions on how to solve the problem(arrive at the desired state of the program). It takes care of the how.


***List Comprehension***<br> 
Python has list comprehension-> shorthand of creating a list based on an existing list i.e newlist = [expression for item in iterable if condition == True].
```
# Example: Filter and transform in one step
even_squares = [x**2 for x in range(1, 11) if x % 2 == 0]
print(even_squares)
# prints [4, 16, 36, 64, 100]
```
While there's no direct equivalent in Javascript, we can achieve the same thing using methods like map(), reduce(), and filter().

***Asynchronus Operations***<br>
Python uses libraries like asyncio to handle asynchronus tasks while JS has native tools: promises, async/await, callbacks etc.


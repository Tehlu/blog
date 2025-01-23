# Intro

Hello, this is a blog where I'll be adding my thoughts as it relates to tech, programming, etc.


Article #1 Python vs Javascript
Two of my favorite languages. I love Python because of its versatility and simpler synthax.
I love Javascript because it's ubiquitous throughout the web.
I can highlight some of the differences. 

Function declaration: 
Python: def funcName(par: type):
Javascript: function funcName(par) {}
Hoisting(calling before definition) allowed in Js, No hoisting in Py
Doctrings for Py

Variable: 
Python: Dynamic, No command for declaring variables. i.e x=5, x=True, etc 
Javascript: Dynamic, uses var, let, const to declare variables.

Spacing, Indentation:
Python must use a 4 tabs indent on each level. No mixing of tabs and spaces.
Js has just best practices(similar to Python btw) but no indent requirements. Examples: space after commas in list, space between Classes(2), methods(1) etc

Use Case
Python is popular in Data Science, Machine Learning, IOT, security, automation
JS is mainly used in web applications. 
However, both languages have frameworks and libraries we can use to create desktop and mobile apps. (console apps A)
We'll explore more when it comes to developing libraries, or even applications close to the hardware (embedded systems, kernels, OS, etc)

Paradigm
Both languages are considered multi-paradigm languages. Can be used in object-oriented, functional, and imperative programming developments.
Because of its event-driven nature, JS is closer to Functional Programming than the rest.

Rabbit-trail: Functional Programming is based on mathematical functions and focuses on what to solve. Characteristics: Data immutable, pure fns(no side effect), first class fns(can be returned from another fn, assigned to variables and can pass as an argument. Often uses recursion instead of loops.
              Declarative programming describes the desired state of the program and data. The control flow is abstracted away. We don't tell how to do it but what to do. 
              i.e numbers = [1, 2, 3, 4, 5] squares = [x * x for x in numbers]
Imperative programming is the opposite of declarative programming as it requires the writing of step by step instructions on how to solve the problem(arrive at the desired state of the program). It takes care of the how.



# Learning Environments

These tools are designed to highlight one particular skill or feature of programming.  You will find these tools indispensable at the beginning of your programming journey. But don't think these are just toys for beginners!  We regularly use these tools ourselves when we develop our own projects, try to master new skills, or keep our old skills up to date.

### JavaScript Only:
* [Variables & Execution Context](#pythontutor)
* [Syntax Structures & Logic](#parsonizer)
* [How to describe this one?](#khan-javascript)
* [Flowchart Generators](#flowchart-generators)
* [Live Testing](#tdd-bin)
* [Asynchronous Behavior](#loupe)
* [Online Node.js Environment](#replit)

### Development Sandboxes:
* [Khan: HTML, CSS & JS](#khan-html-css-js)
* [Glitch](#glitch)

___

## [PythonTutor](http://www.pythontutor.com/javascript.html#)

Being able to accurately predict how [JavaScript executes code behind the scenes](https://github.com/elewa-academy/js-notional-machine) is one of the most valuable skills you can have as a developer.  This is also one of the most challenging things to learn, so be regular and be diligent. 

To learn the notional machine as effectively as possible, step carefully through clear code examples with PythonTutor.  You will learn the most if you write down your predictions of what will happen next before clicking the "forward" button.

_PyTut Guide_

__Primitive Types__:
* live directly in the PythonTutor Frames.
* undefined, number, string, ...
* things that don't hold other things
* each variable pointing to a primitive stores it's own copy

__Object Types__:
* live in the Objects column of PythonTutor
* variables point to these. 
  * ie: modfying one variable's object will show up in others
* things that store other things
* functions, objects, arrays, ...

__Frames__: 
* called Execution Contexts outside of PyTut
* a new one is created each time a function is executed
* and closes when that function returns
* contain their own variables
* have access to variable in parent (higher) frames
* cannot access variables in lower frames

__Arrows (pointers)__:
* these indicate what object a variable is referencing

_Additional Resources:_
* [Intro Video](https://www.youtube.com/watch?v=u0FbLpRDcxU)
* [Intro Article](http://pgbovine.net/python-tutor-live.htm)
* [GitHub Repo](https://github.com/pgbovine/OnlinePythonTutor)
* [About PythonTutor](https://www.youtube.com/watch?v=sVtXLdBRfyE)

[TOP](#learning-environments)

___

## [Parsonizer](https://elewa-academy.github.io/parsons/)

With parsons problems you will be presented with a randomly organized set of lines of code.  Your task is simply to place them in order.  But it's not always as easy as it sounds!  Beware of indenting (code style) and extra lines.

When you find a particularly interesting example of JavaScript syntax, design pattern, solution strategy, step through it and provide a link in your JavaScript Reference.

Or create your own problems and challenge your friends!  Parsons problems are also a great way to practice syntax, logical strategies, and programming design patterns. 


[TOP](#learning-environments)

___

## [Khan: JavaScript](https://www.khanacademy.org/computer-programming/new/pjs)

Khan Academy has created an outstanding visual-interactive coding environment that will help you build an understanding of syntax, code behavior, and algorithms.  You can go straight to the coding environment above or check out [their introduction](https://www.khanacademy.org/computing/computer-programming/programming) or their [hour of code](https://www.khanacademy.org/computing/hour-of-code/hour-of-drawing-code/v/welcome-hour-of-code) first.

Try it out for yourself, a picture ...

[TOP](#learning-environments)

___

## Flowchart Generators

* [Bogdon Lyashenko](https://bogdan-lyashenko.github.io/js-code-to-svg-flowchart/docs/live-editor/index.html) - live, online flowchart generator
* [Code 2 Flow](https://code2flow.com/app) - live, online flowchart generator
* [Flow Maker](https://marketplace.visualstudio.com/items?itemName=speks.flowmaker) - Visual Studio plugin

These live editing environments converts your code into a diagram that illustrates control flow.  It will help you translate between strategy and code by making your code's behavior visually clear.  You can also export these diagrams to include in your notes or challenge write-ups.



[TOP](#learning-environments)

___

## [TDD Bin](http://tddbin.com)

A live Mocha+Assert testing environment, perfect learning to use tests and write test cases. Copy your functions into this site, write your own test cases, and see how you did!

[TOP](#learning-environments)

___

## [Loupe](http://latentflip.com/loupe/?code=JC5vbignYnV0dG9uJywgJ2NsaWNrJywgZnVuY3Rpb24gb25DbGljaygpIHsKICAgIHNldFRpbWVvdXQoZnVuY3Rpb24gdGltZXIoKSB7CiAgICAgICAgY29uc29sZS5sb2coJ1lvdSBjbGlja2VkIHRoZSBidXR0b24hJyk7ICAgIAogICAgfSwgMjAwMCk7Cn0pOwoKY29uc29sZS5sb2coIkhpISIpOwoKc2V0VGltZW91dChmdW5jdGlvbiB0aW1lb3V0KCkgewogICAgY29uc29sZS5sb2coIkNsaWNrIHRoZSBidXR0b24hIik7Cn0sIDUwMDApOwoKY29uc29sZS5sb2coIldlbGNvbWUgdG8gbG91cGUuIik7!!!PGJ1dHRvbj5DbGljayBtZSE8L2J1dHRvbj4%3D)

JavaScript's execution environment is pretty confusing, and very different from almost every other programming language. It's asynchronous behavior is tricky to get a hang of without strong visuals and a good explanation.  Enter: Loupe.



[TOP](#learning-environments)

___

## [Replit](https://repl.it)

There are many JS runtime environments and not each one treats JS exactly the same way. Node.js is one of the most important JS runtimes and it [behaves differently](http://voidcanvas.com/node-vs-browsers/) from Browser runtime environments.

Check out Replit to explore the Node runtime without having to install anything.



[TOP](#learning-environments)

___


## [Khan: HTML, CSS & JS](https://www.khanacademy.org/computer-programming/new/webpage)

Learn how JS, HTML & CSS integrate to make static websites.   This is a great place to start, but do move on to Glitch as soon as you're comfortable.

[TOP](#learning-environments)

___

## [Glitch](https://glitch.com)

Glitch is a powerful online sandbox that allows you to easily build and deploy simple websites with HTML, CSS & JS.  Of all the sandboxes out there, Glitch will prepare you the most for your transition to the full development environment (Visual Studio, Chrome Dev Console, Terminal, GitHub).

If that weren't enough, you can also use Glitch to build and test simple Fullstack applications.

[TOP](#learning-environments)

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>
# InterviewPrep

## Table of Contents:

- [Behavioral](#behavioral)
- [Gaining Experience](#gaining-experience)
- [Mock Interviews](#mock-interviews)
- [Helpful Links](#helpful-links)
- [Company Interview Questions](#company-interview-questions)
- [Questions for an Interviewer](#questions-for-an-interviewer)
- [Language Questions](#language-questions)
- [Bash](#bash)
- [Docker](#docker)
- [SQL/NoSQL](#sql)
- [Relational Databases](#relational-databases)
- [API Design](#api-design)
- [HTTP](#http)
- [AWS](#aws)
- [Software Testing](#software-testing)
- [Parallel Processing](#parallel-processing)
- [System Design](#system-design)
- [Statistics / Probability](#statistics-probability)
- [ML Prep](#ml-prep)
- [TODO](#todo)

----------------------------------------------------------------
## Behavioral:

Tell me about yourself:
- I graduated from St Mary’s College of Maryland, where I received a bachelor’s in Mathematics and Computer Science. 
- I am currently part time pursuing a Masters in Data Analytics
- I recently completed a data science internship at Smartronix, where I delivered a successful product to the team.
- Outside of work I have been taking part in Kaggle competitions and learning about ML. As well as contributing to an open source project LightGBM.

https://www.linkedin.com/in/weston-king-leatham/
https://github.com/WestonKing-Leatham
Elevator pitch
Current Role -headline
College
Post College / Current Role - details
Outside of work

Career goal - I would love to find myself working in a position with impact, where I can work  with a team to create meaningful products and insights.
Unique - I love learning and expanding my skill sets. Outside of work I will continue to code.

----------------------------------------------------------------

## Gaining Experience:

- Resume Projects
- Kaggle
- Restful API
- SQL database
- Open Source Projects
	projectIdeas https://docs.google.com/document/d/1F5zvCBt9BhMFUidWIGYNFsTGABmXrU03zl-7QMcOWwI/edit#

----------------------------------------------------------------

## Mock interviews:
https://interviewing.io/
https://www.pramp.com/#/
https://www.swecareers.com/mock-interviews


----------------------------------------------------------------

## Company Interview Questions

What do you know about ___ and why did you decide to apply here?  What drew you to us?
Do research on company applying too
I’m interested in what kind of work you do
You seem to have good work environment

What are you looking for?
A company where I can spend some time at and create some meaningful impact at.

What makes you a good fit for the company? 

Story Time: Can you tell me about a time that you _____? 
Nugget first
	Start with a nugget that succinctly describes what your response will be about.

STAR method
	Situation / Task -> Action -> Result
Describe a conflict you had with a team member. How did you handle the conflict and what was the outcome? 
My team member was struggling and not contributing. I organized more in person meetings to work with and beside the other person.

Tell me about a time where you had to persuade a group of people to make a change.
Change to react and api - lowering scope

Tell me about a challenging interaction with a teammate.
Change to api or Coworker did not know python delegated/split work

Tell me about a time where you dealt with ambiguity?
What do you do when faced with adversity?

How do you approach a new project and technology?
Look at similar project examples
Examine why they used the technology
Read documentation explaining things
Get hands on and try tutorials and experiment

Do you enjoy working alone or on a team more?
How would your boss describe you?

How do you handle working under pressure?
Well -> During my last internship it was abbreviated due to covid and to create a useful product quickly. I had to quickly assess the project constraints and create a plan where I covered the essentials.

Tell me your:
Strength:
	Self motivated, enjoy learning, dedicated
Enjoy a challenge/prb solving
Weakness:
	Perfectionism- I may spend too long on a problem trying to achieve the best solution
	
## Questions for an interviewer:
- What would my normal day look like?
- Can you tell me about whom I will be working with?
- How is mentorship approached?
- What would be your definition of success for this role?
- What is your tech stack?
- Do you enjoy your role in the company? What do you enjoy about your job?
- Do you like your company?
- What brought you to this company?
- Remote work?
- What are the standard working hours?
- How long is the interviewing process?
- What is the growth potential for me?

## Technical Questions Overview:
What do you look for when reviewing code?
- Bottlenecks
- Unnecessary work
- Duplicated work

* What is an Object and a class, what's the difference between them ?  
A class is a template for objects. A class defines object properties and behaviors including a valid range of values, and a default value 
An object is a member or an "instance" of a class. An object has a state in which all of its properties have values that you either explicitly define or that are defined by default settings.

* What are the pillars of OOP?
	- Abstraction- ability to hide things
	- Encapsulation- binding data and functions for protection
	- Inheritance- inheriting features of parent class
	- Polymorphism- the ability to redefine methods for derived classes

Recursion:
	A function which calls itself recursively
	Consists of a base case (stopper) and a recursive case(recurser).

What's the difference between a stack and a queue ?  
Stacks "pop" data off the stack, using last-in first out (LIFO) (ex: books/pancakes)
Queues use first-in, first-out (FIFO) (think of a pipe)

Heap
Priority Queue
Trees

Mixin- a class that contains methods for other classes without having to be the parent class

----------------------------------------------------------------

- Big O Notation:
Coding-interview university github

- Dynamic Programming + Recursion:
- BFS and DFS:
- Trees:
- Linked lists:	
- Stacks:
- Heaps / Priority Queues:
- Binary Search:
- Two Pointers:
- Divide and Conquer:
- Hashing/dictionaries:
- Greedy Algorithms:
- Backtracking:
- Sliding Window:
- Union Find:
- Graphing:
- Sorting Algorithms: (Quick, Merge, Selection, Tim)
- Bit Manipulation:
- SQL:

----------------------------------------------------------------

# Language Questions:

## Python Questions: 

Python is a high-level, interpreted, dynamically typed, general-purpose programming language.

What are the lists and tuples and what are their differences:
- Both sequence data types (can hold multiple types)
- Lists are mutable - changeable
- Tuples are immutable

Lambda is an anonymous function in Python that can accept any number of arguments, but can only have a single expression. It is generally used in situations requiring an anonymous function for a short time period.

__init__ is a constructor method in Python and is automatically called to allocate memory when a new object/instance is created. All classes have a __init__ method associated with them. It helps in distinguishing methods and attributes of a class from local variables.

Self is a keyword in Python used to define an instance or an object of a class. In Python, it is explicitly used as the first parameter, unlike in Java where it is optional. It helps in distinguishing between the methods and attributes of a class from its local variables

Decorators in Python are essentially functions that add functionality to an existing function in Python without changing the structure of the function itself. They are represented by the @decorator_name in Python and are called in bottom-up fashion.

*args can be used to pass multiple  positional arguments
**kwargs can be used to pass multiple  keyword/named arguments

Functions are first-class objects. This means that they can be assigned to variables, returned from other functions and passed into functions. Classes are also first class objects

PEP8: Python Enhancement Proposal. It is a set of rules that specify how to format Python code for maximum readability.

----------------------------------------------------------------

## JavaScript Questions:

JavaScript is a high level interpreted oop language that is single threaded (no parallelism). It is dynamically typed, and has first-class functions. Multiparadigm language supports: event-driven, functional, and imperative programming styles. Sets the behavior of web pages.

https://www.youtube.com/watch?v=6Wzj7kxfRdI

What is the difference between let and var?
- The let statement declares a block scope local variable. Hence the variables defined with let keyword are limited in scope to the block, statement, or expression on which it is used. Whereas variables declared with the var keyword used to define a variable globally, or locally to an entire function regardless of block scope.

Events are "things" that happen to HTML elements. When JavaScript is used in HTML pages, JavaScript can react to these events.

What is a prototype in javascript?
- All javascript objects inherit properties and methods from a prototype.

What is the meaning of the keyword this in javascript?
- This is a reference to the object it belongs to

The setTimeout() method is used to call a function or evaluate an expression after a specified number of milliseconds. 

What is a promise and what is a callback?
- A promise is an object that may produce a single value some time in the future with either a resolved value or a reason that it’s not resolved(for example, network error). It will be in one of the 3 possible states: fulfilled, rejected, or pending.
- A callback function is a function passed into another function as an argument. This function is invoked inside the outer function to complete an action.
https://github.com/sudheerj/javascript-interview-questions#what-is-a-prototype-chain

---------------------------------------------------------------------------

## Java

Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers write once, run anywhere (WORA)

Unlike C++, Java does not support operator overloading or multiple inheritance for classes, though multiple inheritance is supported for interfaces.

The keyword public denotes that a method can be called from code in other classes, or that a class may be used by classes outside the class hierarchy. The class hierarchy is related to the name of the directory in which the .java file is located. This is called an access level modifier. Other access level modifiers include the keywords private (a method that can only be accessed in the same class) and protected (which allows code from the same package to access). If a piece of code attempts to access private methods or protected methods, the JVM will throw a SecurityException

The keyword static in front of a method indicates a static method, which is associated only with the class and not with any specific instance of that class. Only static methods can be invoked without a reference to an object. Static methods cannot access any class members that are not also static. Methods that are not designated static are instance methods and require a specific instance of a class to operate.

The keyword void indicates that the main method does not return any value to the caller. If a Java program is to exit with an error code, it must call System.exit() explicitly.
The method name main is not a keyword in the Java language. It is simply the name of the method the Java launcher calls to pass control to the program. A Java program may contain multiple classes that have main methods, which means that the VM needs to be explicitly told which class to launch from.

What is a singleton class in java?
- A singleton class is a class that can have only one object (an instance of the class) at a time. After the first time, if we try to instantiate the Singleton class, the new variable also points to the first instance created.

---------------------------------------------------------------------------

## Node.js

A backend JavaScript runtime environment which can execute javaScript outside of a web browser. Node lets you use command line tools and for server-side scripting where dynamic web page content is produced before the page is sent to the user’s browser.

Here is how PHP or ASP handles a file request:
1. Sends the task to the computer's file system.
2. Waits while the file system opens and reads the file.
3. Returns the content to the client.
4. Ready to handle the next request.

Here is how Node.js handles a file request:
1. Sends the task to the computer's file system.
2. Ready to handle the next request.
3. When the file system has opened and read the file, the server returns the content to the client.
Node.js eliminates the waiting, and simply continues with the next request.

Node.js runs single-threaded, non-blocking, asynchronous programming, which is very memory efficient.
- Node.js can generate dynamic page content
- Node.js can create, open, read, write, delete, and close files on the server
- Node.js can collect form data
- Node.js can add, delete, modify data in your database

--------------------------------------------------------------------------

## Bash
The Bourne Again SHell. It is a Unix shell and command language. 
https://www.gnu.org/software/bash/manual/bash.html#What-is-Bash_003f

It offers functional improvements over sh for both programming and interactive use. In addition, most sh scripts can be run by Bash without modification.
The improvements offered by Bash include:
command-line editing,
unlimited size command history,
job control,
shell functions and aliases,
indexed arrays of unlimited size,
integer arithmetic in any base from two to sixty-four.
Example commands:
	Cd, break, continue, exec.
Name:
A word consisting solely of letters, numbers, and underscores, and beginning with a letter or underscore. Names are used as shell variables and function names. Also referred to as an identifier.

--------------------------------------------------------------------------

## Docker
Docker is an open platform for developing, shipping, and running applications. Docker provides the ability to package and run an application in a loosely isolated environment called a container. https://docs.docker.com/get-started/overview/#the-docker-daemon

Docker architecture
Docker uses a client-server architecture. The Docker client talks to the Docker daemon, which does the heavy lifting of building, running, and distributing your Docker containers. The Docker client and daemon can run on the same system, or you can connect a Docker client to a remote Docker daemon. The Docker client and daemon communicate using a REST API, over UNIX sockets or a network interface. Another Docker client is Docker Compose, which lets you work with applications consisting of a set of containers.

The Docker daemon
The Docker daemon (dockerd) listens for Docker API requests and manages Docker objects such as images, containers, networks, and volumes. A daemon can also communicate with other daemons to manage Docker services.

The Docker client
The Docker client (docker) is the primary way that many Docker users interact with Docker. When you use commands such as docker run, the client sends these commands to dockerd, which carries them out. The docker command uses the Docker API. The Docker client can communicate with more than one daemon.


Docker registries
A Docker registry stores Docker images. Docker Hub is a public registry that anyone can use, and Docker is configured to look for images on Docker Hub by default. You can even run your own private registry.

When you use the docker pull or docker run commands, the required images are pulled from your configured registry. When you use the docker push command, your image is pushed to your configured registry.

Docker objects
When you use Docker, you are creating and using images, containers, networks, volumes, plugins, and other objects.

Images

An image is a read-only template with instructions for creating a Docker container. Often, an image is based on another image, with some additional customization. For example, you may build an image which is based on the ubuntu image, but installs the Apache web server and your application, as well as the configuration details needed to make your application run.

You might create your own images or you might only use those created by others and published in a registry. To build your own image, you create a Dockerfile with a simple syntax for defining the steps needed to create the image and run it. Each instruction in a Dockerfile creates a layer in the image. When you change the Dockerfile and rebuild the image, only those layers which have changed are rebuilt. This is part of what makes images so lightweight, small, and fast, when compared to other virtualization technologies.

Containers
A container is a runnable instance of an image. You can create, start, stop, move, or delete a container using the Docker API or CLI. You can connect a container to one or more networks, attach storage to it, or even create a new image based on its current state.

By default, a container is relatively well isolated from other containers and its host machine. You can control how isolated a container’s network, storage, or other underlying subsystems are from other containers or from the host machine.

A container is defined by its image as well as any configuration options you provide to it when you create or start it. When a container is removed, any changes to its state that are not stored in persistent storage disappear.


===========================================================
## TODO
add all the links
add images
add everything to table of contents

# InterviewPrep

## Table of Contents:

- [Behavioral](#behavioral)
- [Gaining Experience](#gaining-experience)
- [Mock Interviews](#mock-interviews)
- [Helpful Links](#helpful-links)
- [Company Interview Questions](#company-interview-questions)
- [Questions for an Interviewer](#questions-for-an-interviewer)
- [Language Questions](#language-questions)
	- [Python](#python)
	- [Java](#java)
	- [JavaScript](#javascript)
	- [Node.js](#node.js)
	- [Bash](#bash)
- [Docker](#docker)
- [Git](#git)
- [SQL/NoSQL](#sql/nosql)
- [Relational Databases](#relational-databases)
- [API Design](#api-design)
- [HTTP](#http-request-methods-(http-verbs))
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
- Current Role -headline
- College
- Post College / Current Role - details
- Outside of work

- Career goal
- Unique fact about yourself

----------------------------------------------------------------

## Gaining Experience:

- Resume Projects
- [Kaggle](kaggle.com)
- Rest API
- Web applications
- SQL database
- Open Source Projects

Random helpful links:
* https://github.com/jwasham/coding-interview-university
https://github.com/jwasham/computer-science-flash-cards

Web.dev.learn/

Data Science / analytics:
https://www.sharpestminds.com/landing-a-data-job-the-course
https://business.linkedin.com/talent-solutions/resources/interviewing-talent/data-analyst

*https://github.com/cdeweyx/DS-Career-Resources/blob/master/Interview-Resources.md

https://github.com/andkret/Cookbook

https://developers.google.com/learn
https://developers.google.com/machine-learning/crash-course
https://developers.google.com/learn/pathways

Tools:
- Tripe Byte Triplebyte Prep, Crossover, Canvas, Angellist, Smartr
- Pathrise, Sharpest minds, Cognixia
- Leetcode, hackerrank, stratascratch
- mode

----------------------------------------------------------------

## Mock interviews:
https://interviewing.io/
https://www.pramp.com/#/
https://www.swecareers.com/mock-interviews


----------------------------------------------------------------

## Company Interview Questions

What do you know about ___ and why did you decide to apply here?  What drew you to us?
- Research company you're applying to
	- Work environment
	- Growth potential
	- type of work

What are you looking for?
- A company where I can spend some time at and create some meaningful impact at.

What makes you a good fit for the company? 

Story Time: Can you tell me about a time that you _____?   
Nugget first
- Start with a nugget that succinctly describes what your response will be about.

**STAR** method
- Situation / Task -> Action -> Result
	
Tell me about a time where you had to persuade a group of people to make a change.

Tell me about a challenging interaction with a teammate.

Describe a conflict you had with a team member. How did you handle the conflict and what was the outcome? 

Tell me about a time where you dealt with ambiguity.

What do you do when faced with adversity?

How do you handle working under pressure?

What are the things that are most important to you in a job?

Tell me about a time where you demonstrated leadership skills.

How do you approach a new project and technology?
- Look at similar project examples
- Examine why they used the technology
- Read documentation explaining things
- Get hands on and try tutorials and experiment

Do you enjoy working alone or on a team more?

How would your boss describe you?

Tell me your greatest strength and weakness:
	
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

----------------------------------------------------------

## Technical Questions Overview:
What do you look for when reviewing code?
- **B** ottlenecks
- **U** nnecessary work
- **D** uplicated work

* What is an **Object** and a **Class**, what's the difference between them ?  
A **class** is a template for objects. A class defines object properties and behaviors, including a valid range of values, and a default value 
An **object** is a member or an "instance" of a class. An object has a state in which all of its properties have values that you either explicitly define or that are defined by default settings.

* What are the pillars of OOP?
	- Abstraction- ability to hide things
	- Encapsulation- binding data and functions for protection
	- Inheritance- inheriting features of parent class
	- Polymorphism- the ability to redefine methods for derived classes

method overloading vs overriding

**Recursion:**
	- A function which calls itself recursively
	- Consists of a base case (stopper) and a recursive case(recurser).

What's the difference between a stack and a queue ?  
- Stacks "pop" data off the stack, using last-in first out (LIFO) (ex: books/pancakes)
- Queues use first-in, first-out (FIFO) (think of a pipe)

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

**Python** is a high-level, interpreted, dynamically typed, general-purpose programming language.

What are lists and tuples and what are their differences:
- Both sequence data types (can hold multiple types)
- Lists are mutable - changeable
- Tuples are immutable

**Lambda** is an anonymous function in Python that can accept any number of arguments, but can only have a single expression. It is generally used in situations requiring an anonymous function for a short time period.

**__init__** is a constructor method in Python and is automatically called to allocate memory when a new object/instance is created. All classes have a __init__ method associated with them. It helps in distinguishing methods and attributes of a class from local variables.

**Self** is a keyword in Python used to define an instance or an object of a class. In Python, it is explicitly used as the first parameter, unlike in Java where it is optional. It helps in distinguishing between the methods and attributes of a class from its local variables

**Decorators** in Python are essentially functions that add functionality to an existing function in Python without changing the structure of the function itself. They are represented by the @decorator_name in Python and are called in bottom-up fashion.

*args can be used to pass multiple  positional arguments
**kwargs can be used to pass multiple  keyword/named arguments

**Functions** are first-class objects. This means that they can be assigned to variables, returned from other functions and passed into functions. Classes are also first class objects

**PEP8:** Python Enhancement Proposal. It is a set of rules that specify how to format Python code for maximum readability.

----------------------------------------------------------------

## JavaScript Questions:

JavaScript is a high level interpreted oop language that is single threaded (no parallelism). It is dynamically typed, and has first-class functions. Multiparadigm language supports: event-driven, functional, and imperative programming styles. Sets the behavior of web pages.

https://www.youtube.com/watch?v=6Wzj7kxfRdI

What is the difference between *let* and *var*?
- The *let* statement declares a block scope local variable. Hence the variables defined with let keyword are limited in scope to the block, statement, or expression on which it is used. Whereas variables declared with the *var* keyword used to define a variable globally, or locally to an entire function regardless of block scope.

Events are "things" that happen to HTML elements. When JavaScript is used in HTML pages, JavaScript can react to these events.

What is a **prototype** in javascript?
- All javascript objects inherit properties and methods from a prototype.

What is the meaning of the keyword ***this*** in javascript?
- ***This*** is a reference to the object it belongs to

What is a **promise** and what is a **callback?**
- A **promise** is an object that may produce a single value some time in the future with either a resolved value or a reason that it’s not resolved(for example, network error). It will be in one of the 3 possible states: fulfilled, rejected, or pending.
- A **callback** function is a function passed into another function as an argument. This function is invoked inside the outer function to complete an action.
https://github.com/sudheerj/javascript-interview-questions#what-is-a-prototype-chain

---------------------------------------------------------------------------

## Java

**Java** is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers write once, run anywhere (WORA)

Unlike C++, Java does not support operator overloading or multiple inheritance for classes, though multiple inheritance is supported for interfaces.

The keyword **public** denotes that a method can be called from code in other classes, or that a class may be used by classes outside the class hierarchy. The class hierarchy is related to the name of the directory in which the .java file is located. This is called an access level modifier. Other access level modifiers include the keywords **private** (a method that can only be accessed in the same class) and **protected** (which allows code from the same package to access). If a piece of code attempts to access private methods or protected methods, the JVM will throw a SecurityException

The keyword **static** in front of a method indicates a static method, which is associated only with the class and not with any specific instance of that class. Only static methods can be invoked without a reference to an object. Static methods cannot access any class members that are not also static. Methods that are not designated static are instance methods and require a specific instance of a class to operate.

The keyword **void** indicates that the main method does not return any value to the caller. If a Java program is to exit with an error code, it must call System.exit() explicitly.

The method name **main** is not a keyword in the Java language. It is simply the name of the method the Java launcher calls to pass control to the program. A Java program may contain multiple classes that have main methods, which means that the VM needs to be explicitly told which class to launch from.

What is a **singleton class** in java?
- A **singleton class** is a class that can have only one object (an instance of the class) at a time. After the first time, if we try to instantiate the Singleton class, the new variable also points to the first instance created.

![JVM](https://upload.wikimedia.org/wikipedia/commons/thumb/d/dd/JvmSpec7.png/220px-JvmSpec7.png)

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
- command-line editing,
- unlimited size command history,
- job control,
- shell functions and aliases,
- indexed arrays of unlimited size,
- integer arithmetic in any base from two to sixty-four.
Example commands:
	Cd, break, continue, exec.
	
Name:
A word consisting solely of letters, numbers, and underscores, and beginning with a letter or underscore. Names are used as shell variables and function names. Also referred to as an identifier.

--------------------------------------------------------------------------

## Docker
Docker is an open platform for developing, shipping, and running applications. Docker provides the ability to package and run an application in a loosely isolated environment called a container. https://docs.docker.com/get-started/overview/#the-docker-daemon

![Docker](https://docs.docker.com/engine/images/architecture.svg)

**Docker architecture**
Docker uses a client-server architecture. The Docker client talks to the Docker daemon, which does the heavy lifting of building, running, and distributing your Docker containers. The Docker client and daemon can run on the same system, or you can connect a Docker client to a remote Docker daemon. The Docker client and daemon communicate using a REST API, over UNIX sockets or a network interface. Another Docker client is Docker Compose, which lets you work with applications consisting of a set of containers.

**The Docker daemon**
The Docker daemon (dockerd) listens for Docker API requests and manages Docker objects such as images, containers, networks, and volumes. A daemon can also communicate with other daemons to manage Docker services.

**The Docker client**
The Docker client (docker) is the primary way that many Docker users interact with Docker. When you use commands such as docker run, the client sends these commands to dockerd, which carries them out. The docker command uses the Docker API. The Docker client can communicate with more than one daemon.

**Docker registries**
A Docker registry stores Docker images. Docker Hub is a public registry that anyone can use, and Docker is configured to look for images on Docker Hub by default. You can even run your own private registry.

When you use the docker pull or docker run commands, the required images are pulled from your configured registry. When you use the docker push command, your image is pushed to your configured registry.

**Docker objects**
When you use Docker, you are creating and using images, containers, networks, volumes, plugins, and other objects.

**Images**
An image is a read-only template with instructions for creating a Docker container. Often, an image is based on another image, with some additional customization. For example, you may build an image which is based on the ubuntu image, but installs the Apache web server and your application, as well as the configuration details needed to make your application run.

You might create your own images or you might only use those created by others and published in a registry. To build your own image, you create a Dockerfile with a simple syntax for defining the steps needed to create the image and run it. Each instruction in a Dockerfile creates a layer in the image. When you change the Dockerfile and rebuild the image, only those layers which have changed are rebuilt. This is part of what makes images so lightweight, small, and fast, when compared to other virtualization technologies.

**Containers**
A container is a runnable instance of an image. You can create, start, stop, move, or delete a container using the Docker API or CLI. You can connect a container to one or more networks, attach storage to it, or even create a new image based on its current state.

By default, a container is relatively well isolated from other containers and its host machine. You can control how isolated a container’s network, storage, or other underlying subsystems are from other containers or from the host machine.

A container is defined by its image as well as any configuration options you provide to it when you create or start it. When a container is removed, any changes to its state that are not stored in persistent storage disappear.

------------------

## Git

[Git book](https://git-scm.com/book/en/v2)

My initial project workflow:
- git init repo in directory
- git add files
- git status
- git commit -m "asdf"
- git pull origin master (if remote branch chaged)
- git push -u origin master

--------------------------------------------------
## SQL/NoSQL

Format of a SQL query:
- SELECT
- FROM
- WHERE
- GROUP BY
- HAVING
- ORDER BY

What are the sql aggregate functions?
- COUNT
- MAX/MIN
- AVG
- GROUP BY
- CASE
- DISTINCT
- JOINS

SQL | NoSQL
------------ | -------------
vertically scalable | horizontally scalable
table based | document, key-value, graph or wide-column stores
better for multi-row transactions | better for unstructured data like documents or JSON

-----------------------------------

## Relational Databases:

**Primary Key (PK):**
A column with a unique value for each row. Although not all database management systems (DBMS) require you to put a PK into each table, from a design perspective a PK is a requirement. No table should be without one.

**Foreign Key (FK):**
These define relationships between tables. When you want a row in one table to be linked to a row in another table, you place a FK column in the child table and use the value of the parent row's PK as the value of the FK field.

**Composite Key:**
This is a key that is made up of more than one column. This is typically used when you want to prevent a table from using the same combination of values twice. For example, in a table that lists item prizes for shops, you would only want each shop to have a single price for each item. So, you create a FK for the shop and a FK for the item, and then you create a composite PK out of those two columns. This would cause the DBMS to forcefully restrict entries that would create rows where the combined values of these fields are duplicated. - This type of key is commonly used in N:M relationships.

**One-To-One (1:1) relationship:**
A relationship between two tables, where a single row in one table is linked to a single row in another table.

This type of relationship is practically non-existent in normalized relational designs. They exist mostly to get around limitations in databases like Access, where the number of columns was limited, thus creating the need to split tables up. They are also sometimes used to optimize the performance of the database.

**One-To-Many (1:N) relationship:**
A relationship between two tables, where multiple rows in a child table can be linked to a single row in a parent table.
This is in fact the only "real" type of relationship in a relational database.

**Many-To-Many (N:M) relationship:**
A relationship between two tables, where multiple rows in one table can be linked to multiple rows in another table. This type is "artificial" in a a way, because this kind of relationship can not be created directly between tables. To accomplish this type of relationship you need to create a third table; an intermediary table that contains FKs to both parents, linked via a set of 1:N relationships.

## Normalization:
To help us properly design our tables we have a set of guidelines which, if followed properly, will help reduce the redundancy and chance of data corruption. We call this "Normalization". https://www.dreamincode.net/forums/topic/179103-relational-database-design-normalization/
https://dba.stackexchange.com/questions/4622/when-should-you-denormalize/15798#15798

There are several steps involved in normalizing a database. The steps are referred to as "Normal Forms". There are at least 7 NF. Each NF requires that the NF before it has also been satisfied. The spot between 3NF and 4NF is reserved for the BCNF (Boyce-Codd normal form), which was developed later as a slightly stronger version of the 3NF. Tables that have reached the 3NF are generally considered "normalized".
- 1NF: tables must not contain repeating groups of data
- 2NF: no field should only be partially dependent on any candidate key
- 3NF: columns should depend only upon the primary key of the table

**B-Tree**
A self balancing tree used as a database
http://20bits.com/article/interview-questions-database-indexes

## ETL (Extract, Transform, Load)
Extract Transform Load is the procedure for copying data into a different system. We do this to gather and clean data and transfer the data into an easily stored and queryable form.

MapReduce

## Data Pipeline

## CI/CD
- Jenkins

-----------------------------------------------------

## API Design:

**RESTful API**:
- An architectural style for an application program interface (API) that uses HTTP requests to access and use data. That data can be used to GET, PUT, POST and DELETE data types, which refers to the reading, updating, creating and deleting of operations concerning resources.

REST = REpresentational State Transfer

**CRUD** - persistent data
	- Create = post
	- Read = get
	- Update = put
	- Delete = delete

- GET to retrieve a resource;
- PUT to change the state of or update a resource, which can be an object, file or block;
- POST to create that resource; and
- DELETE to remove it.

**Persistence** is said to be ["orthogonal"](https://en.wikipedia.org/wiki/Orthogonality#Computer_science) or "transparent" when it is implemented as an intrinsic property of the execution environment of a program. An orthogonal persistence environment does not require any specific actions by programs running in it to retrieve or save their state.

**Non-orthogona**l persistence requires data to be written and read to and from storage using specific instructions in a program, resulting in the use of persist as a transitive verb: On completion, the program persists the data.
The advantage of orthogonal persistence environments is simpler and less error-prone programs

**GraphQL:**
- A query/manipulation language for your API and a runtime for fulfilling queries with existing data

**OLTP vs OLAP** - [link](https://techdifferences.com/difference-between-oltp-and-olap.html#:~:text=OLTP%20and%20OLAP%20both%20are,is%20an%20analytical%20processing%20system.&text=The%20basic%20difference%20between%20OLTP,online%20database%20query%20answering%20system.)
- Both are online processing systems. OLTP is a transactional processing sys which modifies data while OLAP is an analytical processing system which queries.

------------------------------------------------------

## HTTP (Hypertext Transfer Protocol)

([HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)) is an [application-layer](https://en.wikipedia.org/wiki/Application_Layer) protocol for transmitting hypermedia documents, such as HTML. It was designed for communication between web browsers and web servers, but it can also be used for other purposes. HTTP follows a classical [client-server model](https://en.wikipedia.org/wiki/Client%E2%80%93server_model), with a client opening a connection to make a request, then waiting until it receives a response. HTTP is a [stateless protocol](https://en.wikipedia.org/wiki/Stateless_protocol), meaning that the server does not keep any data (state) between two requests. Though often based on a TCP/IP layer, it can be used on any reliable [transport layer](https://en.wikipedia.org/wiki/Transport_Layer), that is, a protocol that doesn't lose messages silently like UDP does. RUDP — the reliable update of UDP — is a suitable alternative.

![http](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwhatis.techtarget.com%2Fdefinition%2FHTTP-Hypertext-Transfer-Protocol&psig=AOvVaw11Yu_ZmorklJJ1s8OaixnV&ust=1633460155989000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCIjjzbW3sfMCFQAAAAAdAAAAABAD)

http vs https:
![http vs https](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.tutorialsmate.com%2F2020%2F07%2Fhttp-vs-https.html&psig=AOvVaw11Yu_ZmorklJJ1s8OaixnV&ust=1633460155989000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCIjjzbW3sfMCFQAAAAAdAAAAABAK)

https://www.tutorialspoint.com/http/http_overview.htm
 
Caching: https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching
 
**Cookies:**
- a small piece of data that a server sends to the user's web browser. The browser may store it and send it back with later requests to the same server. Typically, it's used to tell if two requests came from the same browser — keeping a user logged-in, for example. It remembers stateful information for the stateless HTTP protocol.
 
Cookies are mainly used for three purposes:
- Session management
	- Logins, shopping carts, game scores, or anything else the server should remember
- Personalization
	- User preferences, themes, and other settings
- Tracking
	- Recording and analyzing user behavior

How a browser works:https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/

## HTTP request methods (HTTP verbs):

Indicate the desired action to be performed for a given resource. Each of them implements a different semantic, but some common features are shared by a group of them: e.g. a request method can be [safe](https://developer.mozilla.org/en-US/docs/Glossary/Safe), [idempotent](https://developer.mozilla.org/en-US/docs/Glossary/Idempotent), or [cacheable](https://developer.mozilla.org/en-US/docs/Glossary/cacheable).

- GET
	- The GET method requests a representation of the specified resource. Requests using GET should only retrieve data.
- HEAD
	- The HEAD method asks for a response identical to that of a GET request, but without the response body.
- POST
	- The POST method is used to submit an entity to the specified resource, often causing a change in state or side effects on the server.
- PUT
	- The PUT method replaces all current representations of the target resource with the request payload.
- DELETE
	- The DELETE method deletes the specified resource.
- CONNECT
	- The CONNECT method establishes a tunnel to the server identified by the target resource.
- OPTIONS
	- The OPTIONS method is used to describe the communication options for the target resource.
- TRACE
	- The TRACE method performs a message loop-back test along the path to the target resource.
- PATCH
	- The PATCH method is used to apply partial modifications to a resource.

**WebSockets:**
- Provide a persistent connection between a client and server that both parties can use to start sending data at any time.
https://blog.teamtreehouse.com/an-introduction-to-websockets

The client establishes a WebSocket connection through a process known as the WebSocket handshake. This process starts with the client sending a regular HTTP request to the server. An Upgrade header is included in this request that informs the server that the client wishes to establish a WebSocket connection.

Here is a simplified example of the initial request headers.
> - GET ws://websocket.example.com/ HTTP/1.1
> - Origin: http://example.com
> - Connection: Upgrade
> - Host: websocket.example.com
> - Upgrade: websocket

TCP/IP

## Model View Controller (MVC)    

- Model
	- The central component of the pattern. It is the application's dynamic data structure, independent of the user interface. It directly manages the data, logic and rules of the application. It receives user input from the controller.
- View
	- Any representation of information such as a chart, diagram or table.
- Controller
	- Accepts input and converts it to commands for the model or view
![mvc](https://www.google.com/url?sa=i&url=https%3A%2F%2Fdeveloper.mozilla.org%2Fen-US%2Fdocs%2FGlossary%2FMVC&psig=AOvVaw3IHH8UQTqf3HKeevGM-D2x&ust=1633460356012000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCPCG9ZS4sfMCFQAAAAAdAAAAABAW)

------------------------------------------------------
## AWS

### Amazon Web Services / Cloud Data Principles

**Serverless:** an AWS architectural design principle based, where developers focus on the applications that they want to put into AWS resources, and serverless solutions such as AWS Lambda will then interpret the application and provision the compute and storage power required for execution.

**Virtual Private Cloud (VPC):****
a plot of virtual space within the Amazon Cloud to work within. A user or account may have many VPCs, but must have at least one VPC to act as a designated workspace to house your AWS cloud resources. VPC is a backbone principle of AWS cloud architecture, and they can connect to one another to create complex private and public networks. VPC has 4 main subcomponents – SUBNET, INTERNET GATEWAY, ROUTE, TABLE, NETWORK ACCESS CONTROL LIST (NACL).

**Elastic Compute Cloud (EC2):** a scalable computing capacity or virtual machine (VM) powered by AWS. A backbone resource of AWS that supports application hosting, remote network logins and gateways, database hosting and more.

**Simple Storage Service (S3):** has a simple web services interface that you can use to store and retrieve any amount of data, at any time, from anywhere on the web. This data is stored in buckets, and you pay as you go for the size of storage you need. S3 is not able to be queried like a database and is not designed for frequent or mass request access. S3 buckets can be used to house the files such as HTML, JS, and CSS for a static web site, and then host that static website.

**Relational Database Service (RDS):** RDS makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups. It frees you to focus on your applications so you can give them the fast performance, high availability, security and compatibility they need. Amazon RDS is available on several database instance types - optimized for memory, performance or I/O - and provides you with six database engines to choose from, including Aurora, PostgreSQL, MySQL, MariaDB, Oracle Database, and SQL Server.

**Amazon Aurora:** is a MySQL/PostgreSQL compatible relational database built for the cloud. Aurora is up to 5x faster than standard MySQL databases and 3x faster than standard PostgreSQL databases. Aurora is fully managed by Amazon (RDS), which automates time-consuming administration tasks like hardware provisioning, database setup, patching, and backups. Aurora features a distributed, fault-tolerant, self-healing storage system that auto-scales up to 128TB per database instance. It delivers high performance and availability with up to 15 low-latency read replicas, point-in-time recovery, continuous backup to Amazon S3, and replication across 3(AZs).

**Elastic Block Store (EBS):** is a block-storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction intensive workloads at scale. A broad range of workloads, such as relational and non-relational databases, enterprise applications, containerized applications, big data analytics engines, file systems, and media workflows are deployed on Amazon EBS. You may only mount one EC2 to an EBS at a time. Designed for mission-critical systems, EBS volumes are replicated within an Availability Zone (AZ) and can easily scale to petabytes of data. Also, you can use EBS Snapshots with automated lifecycle policies to back up your volumes in S3, while ensuring geographic protection of your data and business continuity.

**Elastic File System (EFS):** a network file system (NFS), that is scalable and fully managed by AWS. Amazon EFS is designed to provide massively parallel shared access to thousands of Amazon EC2 instances. Customers can use EFS to lift-and-shift existing enterprise applications to the AWS Cloud. Other use cases: big data analytics, web serving and content management, application development and testing, media workflows, database backups, and container storage. EFS is a regional service storing data within and across multiple (AZs) for high availability and durability. Amazon EC2 instances can access your file system across AZs, regions, and VPCs, while on-premises servers can access using AWS Direct Connect or AWS VPN. Not supported for Windows EC2 Instances.

**FSx:** see above EFS. Comparable to EFS but built on Windows Server and supports Windows EC2, Linux, and MacOS Compute Instances.

**Identity and Access Management (IAM):** AWS Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users and groups, and use permissions.

**AWS Lambda:** is a serverless compute service that lets you run code without provisioning ormanaging servers, creating workload-aware cluster scaling logic, maintaining event integrations, or managing runtimes. Just upload your code as a ZIP file or container image, and Lambda allocates compute execution power and runs your code based on the incoming request or event. You can set up your code to automatically trigger from 140 AWS services or call it directly. You can write Lambda functions in any language and use both serverless and container tools, such as AWS SAM or Docker CLI, to build, test, and deploy your Functions.

**Amazon SageMaker:** is a fully-managed service that enables data scientists and developers to quickly and easily build, train, and deploy machine learning models at any scale. 

-------------------------------------------------

## Software Testing:
There are many approaches available in [software testing](https://en.wikipedia.org/wiki/Software_testing). Reviews, walkthroughs, or inspections are referred to as static testing(verification), whereas executing programmed code with a given set of test cases is referred to as [dynamic testing](https://en.wikipedia.org/wiki/Dynamic_testing)(validation)

Automation Testing: Selenium and Katalon Studio

### White Box Testing:
an internal perspective of the system, as well as programming skills, are used to design test cases. This testing is usually done at the unit level.
- [API testing](https://en.wikipedia.org/wiki/API_testing): testing of the application using public and private APIs (application programming interfaces)
- [Code coverage](https://en.wikipedia.org/wiki/Code_coverage): creating tests to satisfy some criteria of code coverage (e.g., the test designer can create tests to cause all statements in the program to be executed at least once)
- [Fault injection methods](https://en.wikipedia.org/wiki/Fault_injection): intentionally introducing faults to gauge the efficacy of testing strategies
- [Mutation testing methods](https://en.wikipedia.org/wiki/Mutation_testing)
- [Static testing methods](https://en.wikipedia.org/wiki/Static_testing)

### Black Box Testing:
testing method in which testers evaluate the functionality of the software under test without looking at the internal code structure.
- Black-box testing methods include: equivalence partitioning, boundary value analysis, all-pairs testing, state transition tables, decision table testing, fuzz testing, model-based testing, use case testing, exploratory testing, and specification-based testing.
It can be applied to all levels of software testing, usually used at higher levels.

### Grey Box Testing:
involves having knowledge of internal data structures and algorithms for purposes of designing tests while executing those tests at the user, or black-box level.

## Testing Levels: 
1. Unit Testing
	- Unit testing refers to tests that verify the functionality of a specific section of code, usually at the function level. In an object-oriented environment, this is usually at the class level, and the minimal unit tests include the constructors and destructors. 
	- Unit testing might include static code analysis, data-flow analysis, metrics analysis, peer code reviews, code coverage analysis and other software testing practices.

2. Integration Testing
	Integration Testing is the process of testing the connectivity or data transfer between a couple of unit tested modules.
	
3. System Testing
	A completely integrated system to verify that the system meets its requirements. For example, a system test might involve testing a login interface, then creating and editing an entry, plus sending or printing results, followed by summary processing or deletion (or archiving) of entries, then logoff.

4. Acceptance Testing 
	Operational readiness of the system to be supported and integrated. Final Step to see if it doesn’t break anything else.

## Testing types, techniques and tactics:

Installation testing: self explanatory

**Compatibility** testing: 
	- Testing compatibility with other applications or OS or versions.
	
**Smoke** and **Sanity** testing: 
- Sanity testing determines whether or not to test further
- Smoke testing consists of minimal attempts to operate the software

**Regression testing:**
	- Method for finding defects after a major code change. To find regressions (degraded or lost features). 

**Acceptance testing:**
	- A smoke test or acceptance testing by the customer.

**Alpha/beta testing:** user acceptance testing by the customer/ testers

**Functional** vs **non-functional** testing: test if it fits specifications vs performance and scalability

**Continuous** testing: using automated tests as part of the delivery pipeline

**Destructive** testing: attempts to cause the software to fail

Talk to me about which debuggers/testing software you have used in order to fix programming errors?  
- Python assert()
- VS Code
- Pypy
- Mypy

Test Driven Development: (develop tests before coding)
- Cypress
- jest

------------------------------------------------

## Parallel Processing:
> Multiple processes done in separate memory locations
Both processes and threads are independent sequences of execution. The typical difference is that threads (of the same process) run in a shared memory space, while processes run in separate memory spaces.
- A [Fork](https://en.wikipedia.org/wiki/Fork_(system_call)) is when a process creates a copy of itself.

### Process
Each [process](https://en.wikipedia.org/wiki/Process_(computing)) provides the resources needed to execute a program. A process has a virtual address space, executable code, open handles to system objects, a security context, a unique process identifier, environment variables, a priority class, minimum and maximum working set sizes, and at least one thread of execution. Each process is started with a single thread, often called the primary thread, but can create additional threads from any of its threads.

### Thread
A thread is an entity within a process that can be scheduled for execution. All threads of a process share its virtual address space and system resources. In addition, each thread maintains exception handlers, a scheduling priority, thread local storage, a unique thread identifier, and a set of structures the system will use to save the thread context until it is scheduled. The thread context includes the thread's set of machine registers, the kernel stack, a thread environment block, and a user stack in the address space of the thread's process. Threads can also have their own security context, which can be used for impersonating clients.

Concurrency:
https://en.wikipedia.org/wiki/Concurrency_(computer_science)

Daemon:
https://en.wikipedia.org/wiki/Daemon_(computing)

### ASYNC Await
- Async makes a function return a Promise
- Await makes a function wait for a Promise
Fake synchronous checks if we are not breaking the execution thread

A **Promise** is a proxy for a value not necessarily known when the promise is created. It allows you to associate handlers with an asynchronous action's eventual success value or failure reason. This lets asynchronous methods return values like synchronous methods: instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in the future.

A **Promise** is in one of these states:
- Pending: initial state, neither fulfilled nor rejected.
- Fulfilled: meaning that the operation was completed successfully.
- Rejected: meaning that the operation failed.

Consider the standard producer-consumer problem. Assume, we have a buffer of 4096-byte length. A producer thread collects the data and writes it to the buffer. A consumer thread processes the collected data from the buffer. The objective is, both the threads should not run at the same time. 

Using **Mutex**: 
- A **mutex** provides mutual exclusion, either producer or consumer can have the key (mutex) and proceed with their work. As long as the buffer is filled by the producer, the consumer needs to wait, and vice versa. 
- At any point of time, only one thread can work with the entire buffer. The concept can be generalized using **semaphore**. 

Using **Semaphore**: 
- A semaphore is a generalized mutex. In lieu of a single buffer, we can split the 4 KB buffer into four 1 KB buffers (identical resources). A semaphore can be associated with these four buffers. The consumer and producer can work on different buffers at the same time.

A **mutex** is a locking mechanism used to synchronize access to a resource. Only one task (can be a thread or process based on OS abstraction) can acquire the mutex. It means there is ownership associated with a mutex, and only the owner can release the lock (mutex). 

**Semaphore** is a signaling mechanism (“I am done, you can carry on” kind of signal). For example, if you are listening to songs (assume it as one task) on your mobile phone and at the same time, your friend calls you, an interrupt is triggered upon which an interrupt service routine (ISR) signals the call processing task to wake up. 

===========================================================
## TODO
add all the links
add images
add everything to table of contents

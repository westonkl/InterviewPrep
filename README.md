# Interview Prep <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="50">

## Table of Contents
- [Purpose of this guide :clipboard:](#purpose-of-this-guide)
- [Applying :magnet:](#applying)
- [Helpful Links :paperclip:](#misc-helpful-links)
	- [Mock Interview Resources :microphone:](#mock-interviews)
- [The Behavioral Interview :telephone_receiver:](#the-behavioral-interview)
	- [Questions for an Interviewer :speech_balloon:](#questions-for-an-interviewer)
- [Technical Questions Overview :microscope:](#technical-questions-overview)
	- [Data Structures and Algorithms :crossed_swords:](#data-structures-and-algorithms)
- [Programming Languages :scroll:](#programming-languages)
	- [Python :snake:](#python)
	- [Java :coffee:](#java)
	- [JavaScript](#javascript)
	- [Bash](#bash)
	- [C](#c)
	- [C++](#c-1)
	- [Scala](#scala)
- [Tools :toolbox:]()
	- [Git :octocat:](#git)
	- [Docker :whale:](#docker)
	- [Node.js](#node-js)
	- [React :electron:](#react)
- [SQL / NoSQL](#sql-and-nosql)
- [Relational Databases](#relational-databases)
	- [Normalization](#normalization)
- [CI/CD :rocket:](#ci-and-cd)
- [API Design :gear:](#api-design)
- [HTTP (Hypertext Transfer Protocol) :shield:](#http)
- [AWS :cloud:](#aws)
- [Software Testing :hammer_and_wrench:](#software-testing)
- [Parallel Processing :thread:](#parallel-processing)
- [System Design :building_construction:](#system-design-preparation)
	- [ACID :alembic:](#acid-alembic)
	- [CAP Theorem](#cap-theorem-for-distributed-computing)
	- [SOLID design](#solid)
- [Statistics and Probability :four_leaf_clover:](#statistics-and-probability)
	- [Distributions](#distributions)
- [Data :bar_chart:](#data)
	- [Analysis Types](#analysis-types)
	- [Hypothesis Testing](#hypothesis-testing)
		- [A/B Testing](#ab-testing)
	- [Data Cleaning :toilet:](#data-cleaning)
	- [Spark :sparkles:](#spark): WIP
	- [Hadoop](#hadoop): WIP
- [ML Prep :brain:](#ml-prep)
	* [Evaluation Metrics :dart:](#evaluation-metrics)
- [NLP :writing_hand:](#nlp)
- [TODO](#todo): this is a WIP

-------------

## Purpose of this guide:
<img align="right" height="150" src="https://media0.giphy.com/media/xT9DPIBYf0pAviBLzO/200w.webp?cid=ecf05e47wp3u03qd5ypxxp7zal7yp7fq8m5mvulj0dwk0huw&rid=200w.webp&ct=g">

:notebook_with_decorative_cover: This guide is intended to provide short info snippets on a variety of coding topics and the interview process.  
I have attempted to shorten guides to provide a quick studying experience and to ask questions, but some topics deserve a deeper dive through links provided. :warning: This is a work in progress, feel free to contributute.  
:climbing: I hope you pass your interviews, become a better programmer, and land your dream job!!

## Resume Help
:page_with_curl: Look up [Mayuko](https://www.youtube.com/watch?v=J5gy9iqjwXM) and [Ken Jee](https://www.youtube.com/watch?v=DM1eE_Coh6g&list=PL2zq7klxX5ARnFpk83JauioZb5zyxNZek) for the best resume advice.  
General guidelines include keeping it to one page, demonstrating impact at past positions, and [demonstrating knowledge](gaining-experience) of tools and languages. 

## Applying
:magnet: I recommend applying to as many places that fit your resume/skillset as possible and as early as possible.  
- [Best times to apply](https://betterprogramming.pub/the-software-engineering-application-timeline-f0b064927a1f)
- [How recruiting works in tech (video)](https://www.youtube.com/watch?v=1DvPu3BEzZc)
- [How to find Software Engineering job openings (video)](https://www.youtube.com/watch?v=KObiuTFYTkM)
  
Good application sites include:
- [Linkedin](https://www.linkedin.com/feed/) has expensive job postings so mostly big companies are posting and they are quite competitive.
- Consider using [Indeed](https://www.indeed.com/)
- [Tripe Byte](https://triplebyte.com/?ref=ga_20180823_search_brand_t1&gclid=EAIaIQobChMI77a43rS28wIVh4zICh2DVA58EAAYASAAEgJGA_D_BwE): A great resource to first take a coding multiple choice test, then with a project walk through to 'pre'-interview
- [Angellist](https://angel.co/): the best startup search tool
- [Canvas](https://www.canvas.com/app/discover/jobs), [Smartr](https://www.smartr.me/), [The Muse](https://www.themuse.com/)
- [Pathrise](https://www.pathrise.com/), [Sharpest minds](https://www.sharpestminds.com/landing-a-data-job-the-course)  

Try to add keywords to your linkedin profile, and make sure it is kept up to date. Recruiters will come to you and it is a great way to get a foot in the door. Pay attention to job descriptions and try to learn the skills and technologies to make yourself relevant to the field you would like to get into. Additionally reaching out through a well thought out message to a recruiter or manager may help you get an interview.  

**Motivation** 
* [How to study everyday (video)](https://www.youtube.com/watch?v=kICh_d6tHQk&list=WL&index=1)
* [How to focus on learning (video)](https://www.youtube.com/watch?v=wlCz8nkDNqo&list=WL&index=7)
* :books: Atomic Habbits by James Clear

## How to Land a SWE Internship :climbing:
[Mayuko how to land a SWE internship (video)](https://www.youtube.com/watch?v=LECIcEqHP-4&list=PLIin1ELTMmjYRmbQo_fYwU2vWtaK5CXxp&index=1)  
[Nicholas how to land a SWE internship (video)](https://www.youtube.com/watch?v=DUZbHbntY4c&list=PLIin1ELTMmjYRmbQo_fYwU2vWtaK5CXxp&index=1)  
[Tina Ultimate Guide to a Data Science internship (video)](https://www.youtube.com/watch?v=kO_LUVkKdJM&list=PLIin1ELTMmjYRmbQo_fYwU2vWtaK5CXxp&index=1)

## Last Step
:tada: Congratulations!! <img align="center" width="50" height="50" src="https://media0.giphy.com/media/PxqXdxK85QWmk/200.webp?cid=ecf05e47k5ofp5ul94jnl7sdjw0da5gi1zv4fyfvizqxum42&rid=200.webp&ct=g)">  
[Negotiating an offer (video)](https://www.youtube.com/watch?v=u9BoG1n1948)  
[Level.fyi](https://www.levels.fyi/?compare=Google,Facebook,Microsoft&track=Software%20Engineer)

## Gaining Experience:
> :star: Creating and working on meaningful personal projects is incredibly important towards demonstrating your experience.

Expanding your resume/portfolio:  
- :brain: [Kaggle](kaggle.com)
- Creating a RESTful API
- Web applications (with persistent memory)
- :bar_chart: SQL analysis (tableau, powerbi)
- :octocat: Contributing to [open source](https://github.com/firstcontributions/first-contributions) projects - look for good first issue tags

**Portfolio Resources:**  
[Build a Data Science portfolio playlist (videos)](https://www.youtube.com/watch?v=1aXk2RViq3c&list=PL2zq7klxX5AQ3Dkl7113VO9t1rm3e4FLA)  
[More Data Science portfolio tips (video)](https://www.youtube.com/playlist?list=PL2zq7klxX5ARnFpk83JauioZb5zyxNZek)  
[Software Engineering Projects and tips (video)](https://www.youtube.com/watch?v=n4t_-NjY_Sg)

## Misc helpful links:
- [Leetcode](https://leetcode.com/problemset/all/) - best technical problem source :point_left: **use this!!**
- [Codewars](https://www.codewars.com/kata/search/my-languages?q=&&beta=false&order_by=popularity%20desc): easier problems
- [Mode (SQL)](https://mode.com/sql-tutorial/)
- [StrataScratch](https://www.stratascratch.com/)

**Other Helpful Repos:**  :octocat:
- [Coding Interview Help](https://github.com/jwasham/coding-interview-university): lots of videos
- [Related Interview Help Flash Cards](https://github.com/jwasham/computer-science-flash-cards)
- [CS Guide](https://github.com/Olshansk/interview#readme): lots of articles and books
- [A CS Interview Guide](https://github.com/schmatz/cs-interview-guide): very short
- [Interactive Coding Challenges](https://github.com/donnemartin/interactive-coding-challenges)
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [The Complete FAANG Preparation](https://github.com/AkashSingh3031/The-Complete-FAANG-Preparation)
- [Data Science Interview Resources](https://github.com/cdeweyx/DS-Career-Resources/blob/master/Interview-Resources.md)
- [Great Big Data Cookbook](https://github.com/andkret/Cookbook)
- [ML Interview](https://github.com/theainerd/MLInterview)
- [DevOPs Guide](https://github.com/Tikam02/DevOps-Guide)
- [Sites Every Programmer Should Visit](https://github.com/sdmg15/Best-websites-a-programmer-should-visit#general-coding-advice)
  
**Truly Random Articles**  
[How a browser works](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)  
[Raft Article](https://raft.github.io/)  
[Code Review Best Practices](https://www.kevinlondon.com/2015/05/05/code-review-best-practices.html)  
[A Billion Cheat Sheets on Everything](https://devhints.io/)  
[Expectations of a Junior Developer](http://blog.thefirehoseproject.com/posts/expectations-of-a-junior-developer/)  
[Google Learning](https://developers.google.com/learn)  

**Dev Tool Websites**  
[Color Gradient Generator Website :art:](https://coolors.co/)  
[Hidden Dev Tools Website](https://hiddentools.dev/)  
[Simple Icons](https://simpleicons.org)  
[Shield Badge Creator](https://shields.io) :shield: 

-----------------

## Mock interviews:
Places to find another person to practice interview with: :microphone:  
- https://interviewing.io/
- https://www.pramp.com/#/
- https://www.swecareers.com/mock-interviews
  
**Example Coding Interviews:** :film_projector:  
[Nick White Java Leetcode Playlist](https://www.youtube.com/playlist?list=PLU_sdQYzUj2keVENTP0a5rdykRSgg9Wp-)  
[Google Coding Interview with a normal SWE](https://www.youtube.com/watch?v=rw4s4M3hFfs)  
[Medium Google Coding Interview With Ben Awad](https://www.youtube.com/watch?v=4tYoVx0QoN0&list=PLIin1ELTMmjYqKAYlb8Ll41c4Dl8PGgTD&index=1)  
[JavaScript interview with a Google engineer](https://www.youtube.com/watch?v=10WnvBk9sZc&list=PLIin1ELTMmjYqKAYlb8Ll41c4Dl8PGgTD&index=1)  
[Python interview with a Google engineer: Coin Change](https://www.youtube.com/watch?v=HWW-jA6YjHk&list=PLIin1ELTMmjYqKAYlb8Ll41c4Dl8PGgTD&index=1)

## Favorite Youtube Creators: :clapper:
- https://www.youtube.com/c/Fireship -Random Tech Tutorials
- https://www.youtube.com/c/hellomayuko -SWE Interview Questions
- https://www.youtube.com/c/Reducible -SWE Interview Questions
- https://www.youtube.com/channel/UC2UXDak6o7rBm23k3Vv5dww -Data Science Creator Tina Huang
- https://www.youtube.com/c/KenJee1 -Data Science Creator Ken Jee
- https://www.youtube.com/c/3blue1brown -Math Creator 3blue1brown
- https://www.youtube.com/c/AbhishekThakurAbhi -Best ML competitor Abhishek Thakur

----------------------
<h1 align='center'>The Behavioral Interview</h1><br>

> :telephone_receiver: Most behavioral interviews are 15-30 minutes long and are inquiries into your personality and experience. They may throw in some 'trivia' questions on things they are looking for. Some behavioral interviews also involve walking through a past project or two. Make sure to maintain good documentation and understand every part of your past projects.
<img align="center" width="180" height="180" src="https://media3.giphy.com/media/ES4Vcv8zWfIt2/200w.webp?cid=ecf05e47k6p6wo3scebqr4uv4xgkx9dj7nemk8dsd4prpb21&rid=200w.webp&ct=g">

**Tell me about yourself:**  
  - Current Role (your headline) 
  - College  
  - Post College / Current Role  
  - Outside of work (how are you upskilling)  

Two optional additions: Career goal, a unique fact about yourself  

What do you know about ___ and why did you decide to apply here?  What drew you to us?
- Research company you're applying to, look at:
	- Work environment
	- Growth potential
	- type of work

What makes you a good fit for the company?  

What are you looking for?  

What are the things that are most important to you in a job?

#### Can you tell me about a time that you \_\_\_?  
When answering a question about a past experience it is best to use either a nugget first method or the STAR method to best tell the tale.
> **Nugget first:** Start with a nugget that succincly describes what your response will be about.  
> **STAR** method: Situation / Task -> Action -> Result
	
Tell me about a time where you had to persuade a group of people to make a change.

Describe a conflict you had with a team member. How did you handle the conflict and what was the outcome? 

Tell me about a time where you dealt with ambiguity.

Tell me about a time where you demonstrated leadership skills.  

What do you do when faced with adversity?

How do you handle working under pressure?

Do you enjoy working alone or on a team more?

How would your boss describe you?

Tell me your greatest strength and weakness.

How do you approach a new project and technology? :test_tube:
- Look at similar project examples
- Examine why they used the technology
- Read documentation explaining things
- Get hands on and try tutorials and experiment
	
## Questions for an interviewer: 
:speech_balloon: It is important to ask questions during and at the end of an interview, try one of these:
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

-------------------

## Technical Questions Overview:

> A technical interview usually consists of solving two problems infront of another engineer on a whiteboard or through a take home assessment with 3+ problems. It is integral to talk to the intervier about the problem and your thought process. Understanding Big-O notation will also help you in the interview and to be a better programmer.  
> :books: I would suggest using the book Cracking the Coding Interview and [Leetcode](https://leetcode.com/problemset/all/) for technical practice

<img align="center" width="180" src="https://media3.giphy.com/media/tn3kTJo4P4y1G/200.webp?cid=ecf05e47z1dyfdba3nld6oshwfb35xzkv5bszqkrviye4x1e&rid=200.webp&ct=g">

Here is my problem solving process:
```
1. Listen to the problem and take notes
2. Create a good complex example to walk through by hand
3. Work out a brute force solution, then ask if they want you to implement it
4. Optimize your solution and walk through a few examples (psuedo code if you want)
5. Implement beautiful (efficient, simple, readable) code
6. Try to find edge cases
```

[5 Problem Solving Tips for Cracking Coding Interview Questions](https://www.youtube.com/watch?v=GBuHSRDGZBY&list=WL&index=1)

#### General Technical 'Trivia' and Fundamentals
> I have found technical trivia sometimes thrown into behavioral interviews these are some of them. They are also important to know for coding.

What is an **Object** and a **Class**, what's the difference between them?  
- A **class** is a template for objects. A class defines object properties and behaviors, including a valid range of values, and a default value  
- An **object** is a member or an "instance" of a class. An object has a state in which all of its properties have values that you either explicitly define or that are defined by default  

What are the pillars of **OOP?**
- **Abstraction**- ability to hide things
- **Encapsulation**- binding data and functions for protection
- **Inheritance**- inheriting features of parent class
- **Polymorphism**- the ability to redefine methods for derived classes

What is method **overloading** and **overriding**?  
**Overloading:** when two or more methods in the same class share a name, but not parameters  
**Overriding:** When name and parameters of method are the same  

**Recursion:**
- A function which calls itself recursively
- Consists of a base case (stopper) and a recursive case(recurser)

What's the difference between a **stack** and a **queue**?  
- Stacks "pop" data off the stack, using last-in first out (LIFO) (ex: books/pancakes)
- Queues use first-in, first-out (FIFO) (think of a pipe)
  
What is the [call stack](https://en.wikipedia.org/wiki/Call_stack)?  
- also look into: [Memory Management](https://en.wikipedia.org/wiki/Memory_management#DYNAMIC)
  
Can you explain dynamic vs static typing and strong vs weak typing?
  
Can you explain declarative vs imperative programming?
  
Compiled vs interpreted?
  
:stethoscope: What do you look for when reviewing code?
- **B** ottlenecks
- **U** nnecessary work
- **D** uplicated work
  
[What is the difference between divide and conquer and dynamic programming?](https://stackoverflow.com/questions/13538459/difference-between-divide-and-conquer-algo-and-dynamic-programming)  

https://www.tutorialspoint.com/data_structures_algorithms/data_structure_overview.htm

---------------
## Data Structures and Algorithms

<img align="right" width="110" src="https://miro.medium.com/max/800/1*bOxDNmWX_nL4W4qB-ey0VQ.gif">

> :star: I am working on filling out this section, but this is likely the **most important** section for a technical interview. Mastering your data structures and algorithms will help you solve any problem thrown at you. It may help to implement each, but understanding how each will help you solve a problem is the most important factor. I have also sorted these based on their frequency/utility in technical interviews. :star:

- **Big O Notation:** :point_left: super important  
:timer_clock: Big O notation is the language we use to describe the effieciency of algorithms (time and space complexity). It usually is used to describe the expected scenario. 
For example, quick sort will run in O(n) time on a sorted array, O(n^2) worst case, and O(nlogn) on average. Big O roughly describes calcuations in an iteration, dropping constants and non-dominants.
	* [Coding-interview university](https://github.com/jwasham/coding-interview-university#algorithmic-complexity--big-o--asymptotic-analysis)
	* [Big O cheat sheet](https://www.bigocheatsheet.com/)
	* [Python Time Complexity](https://wiki.python.org/moin/TimeComplexity)
	* [Top Coder Computational Complexity](https://www.topcoder.com/thrive/articles/Computational%20Complexity%20part%20one)
----------
- [Arrays/Lists/Strings:](https://leetcode.com/tag/array/)
	- [Two Pointers](https://leetcode.com/tag/two-pointers):
	- Sliding Window:
	- [Hashing/Dictionaries](https://leetcode.com/tag/hash-table):
		- A hash table is a data structure that maps keys to values for highly efficient lookup
- [Recursion:](https://en.wikipedia.org/wiki/Recursion_(computer_science)) 
Recursive solutions (mentioned above) are good for writing simple code, but can be very space inefficient. They can all be implemented iteratively.
	- Know how to efficiently solve Fibbonacci
- [BFS](https://leetcode.com/tag/breadth-first-search) and [DFS](https://leetcode.com/tag/depth-first-search): 
	- [Difference between bfs and dfs](https://www.geeksforgeeks.org/difference-between-bfs-and-dfs/)
- [Trees :deciduous_tree:](https://leetcode.com/tag/tree): 
	- Note: learn binary tree traversal
- [Linked lists](https://leetcode.com/tag/linked-list): 
A linked list is a data structure that represents a sequence of nodes. A singly [linked list](https://www.tutorialspoint.com/python_data_structure/python_linked_lists.htm) is a sequence of data elements, which are connected together via links (pointers). A doubly linked list gives each node pointers to both the next node and the previous node.
	- [Leetcode Linkedlist lesson](https://leetcode.com/explore/learn/card/linked-list/)
- [Stacks](https://leetcode.com/tag/stack) :pancakes::
- [Heaps / Priority Queues:](https://leetcode.com/tag/heap-priority-queue): Queues(FIFO)
-----
- [Binary Search](https://leetcode.com/tag/binary-search): 
	- [Binary search Leetcode article](https://leetcode.com/discuss/general-discussion/786126/python-powerful-ultimate-binary-search-template-solved-many-problems): binary search is more useful than you think :zap:
- [Divide and Conquer](https://leetcode.com/tag/divide-and-conquer):
Divide and Conquer works by dividing the problem into sub-problems, conquer each sub-problem recursively and combine these solutions. Dynamic programming is its extension.
- [Dynamic Programming](https://leetcode.com/tag/dynamic-programming): 
Dynamic programming is mostly the process of finding overlapping subproblems and caching results for later(memoization). (ie solving recursive problems iteratively and/or with caching)
	* [Errichto Dynamic Programming Lecture 1](https://www.youtube.com/watch?v=YBSt1jYwVfU&list=PLIin1ELTMmjYRmbQo_fYwU2vWtaK5CXxp&index=1)     
	* [5 Simple Steps for Solving Dynamic Programming Problems](https://www.youtube.com/watch?v=aPQY__2H3tE&list=WL&index=1)
	* [Unique paths](https://www.youtube.com/watch?v=fEcyKrdIkho): my favorite DP problem
- [Greedy Algorithms](https://leetcode.com/tag/greedy): 
Chooses the closest optimum is chose at each step to achieve the best solution.
- [Backtracking](https://leetcode.com/tag/backtracking): 
Backtracking is a technique that considers searching every possible combination for solving a computational problem. It is known for solving problems recursively one step at a time; if its not on the right 'path' it backtracks. Backtracking is a refined brute force approach which is generally used when there are possibilities of multiple solutions.
	- [Backtracking with examples and generic solver](https://cs.lmu.edu/~ray/notes/backtracking/)
	- https://www.interviewbit.com/courses/programming/topics/backtracking/
	- https://www.hackerearth.com/practice/basic-programming/recursion/recursion-and-backtracking/tutorial/
- [Union Find](https://leetcode.com/tag/union-find): 
	- [Union Find in 5 minutes](https://www.youtube.com/watch?v=ayW5B2W9hfo)
- [Graphing](https://leetcode.com/tag/graph):
- [Sorting Algorithms](https://leetcode.com/tag/sorting): (Quick, Merge, Selection, Tim)  
You aren't likely to be asked to implement these, but knowledge of their runtimes is useful
- [Bit Manipulation](https://leetcode.com/tag/bit-manipulation): CTCI places these in high importance, but I do not think they are asked that often
	- [Bits Cheat Sheet](https://github.com/jwasham/coding-interview-university/blob/main/extras/cheat%20sheets/bits-cheat-sheet.pdf)
	
----  
- [SQL](https://leetcode.com/tag/database/):  
Interviewing for data science and data analytics roles, I have found sql questions thrown in. They will tell you if its in the interview.
	- [Mode (SQL)](https://mode.com/sql-tutorial/), [strataScratch](https://www.stratascratch.com/)

---------------------------------

<h1 align='center'>Programming Languages</h1><br>

## Python: 
<img align="right" width="50" height="50" src="https://media2.giphy.com/media/KAq5w47R9rmTuvWOWa/200.webp?cid=ecf05e47hdcr00jhebditkzbcaqzdz21zscu1k45jdhirjvg&rid=200.webp&ct=g">  

> **Python** is a high-level, interpreted, dynamically typed, general-purpose programming language.  

:spiral_notepad: [Python](https://www.w3schools.com/python/) is my go to technical interview language as it is beatiful, pythonic, and relatively easy. I highly recommend you learn it and use it in your interviews. :snake:

What are **lists** and **tuples** and what are their differences?:  
- Both sequence data types (can hold multiple types)
- **Lists** are mutable - changeable
- **Tuples** are immutable

Understanding [list comprehensions](https://www.w3schools.com/python/python_lists_comprehension.asp) and [slicing](https://www.w3schools.com/python/python_strings_slicing.asp) will make your life a lot easier.

**Lambda** is an anonymous function in Python that can accept any number of arguments, but can only have a single expression. It is generally used in situations requiring an anonymous function for a short time period.

**\_\_init\_\_** is a constructor method in Python and is automatically called to allocate memory when a new object/instance is created. All classes have an \_\_init\_\_ method associated with them. It helps in distinguishing methods and attributes of a class from local variables. This is also an example of a dunder method (double underscore) which is used to override something.  

**Self** is a keyword in Python used to define an instance or an object of a class. In Python, it is explicitly used as the first parameter, unlike in Java where it is optional. It helps in distinguishing between the methods and attributes of a class from its local variables

**Decorators** in Python are essentially functions that add functionality to an existing function in Python without changing the structure of the function itself. They are represented by the @decorator_name in Python and are called in bottom-up fashion.

**\*args** can be used to pass multiple  positional arguments  
**\*\*kwargs** can be used to pass multiple  keyword/named arguments  

**Functions** are first-class objects. This means that they can be assigned to variables, returned from other functions and passed into functions. Classes are also first class objects  

Understand [**namespaces**](https://realpython.com/python-namespaces-scope/) and **scope**.  

**PEP8:** Python Enhancement Proposal. It is a set of rules that specify how to format Python code for maximum readability.  

```python
print('Hello World!')
```

[Python Interview Questions](https://www.interviewbit.com/python-interview-questions/)  
[All hail Stephan Pockman](https://leetcode.com/StefanPochmann/) :point_left: the king of pythonic code  
[Google python style guide](https://google.github.io/styleguide/pyguide.html)  

---------------------

## JavaScript:

<img align="right" width="50" height="50" src="https://c.tenor.com/TReUojNlZ6wAAAAi/js-javascript.giff">

> [JavaScript](https://www.javascript.com/) is a high level dynamically typed interpreted oop language that is single threaded. Multiparadigm language supports: event-driven, functional, and imperative programming styles. JavaScript sets the behavior of web pages.

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

What is a first class function?

What does === do in JavaScript?  

```javascript
console.log("Hello World!");
```

[JavaScript Interview Questions](https://www.interviewbit.com/javascript-interview-questions/)  
[JavaScript Interview Questions and Answers](https://github.com/sudheerj/javascript-interview-questions/)  
[5 Must Know Interview Questions for Javascript (video)](https://www.youtube.com/watch?v=6Wzj7kxfRdI)  

----------------

## Java 

<img align="right" width="50" height="50" src="https://i.stack.imgur.com/8NkOQ.gif">

> :coffee: [**Java**](https://en.wikipedia.org/wiki/Java_(programming_language)) is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers write once, run anywhere (WORA)

Unlike C++, Java does not support operator overloading or multiple inheritance for classes, though multiple inheritance is supported for interfaces.

The keyword **public** denotes that a method can be called from code in other classes, or that a class may be used by classes outside the class hierarchy. The class hierarchy is related to the name of the directory in which the .java file is located. This is called an access level modifier. Other access level modifiers include the keywords **private** (a method that can only be accessed in the same class) and **protected** (which allows code from the same package to access). If a piece of code attempts to access private methods or protected methods, the JVM will throw a SecurityException

The keyword **static** in front of a method indicates a static method, which is associated only with the class and not with any specific instance of that class. Only static methods can be invoked without a reference to an object. Static methods cannot access any class members that are not also static. Methods that are not designated static are instance methods and require a specific instance of a class to operate.

The keyword **void** indicates that the main method does not return any value to the caller. If a Java program is to exit with an error code, it must call System.exit() explicitly.

The method name **main** is not a keyword in the Java language. It is simply the name of the method the Java launcher calls to pass control to the program. A Java program may contain multiple classes that have main methods, which means that the VM needs to be explicitly told which class to launch from.

What is a **singleton class** in java?
- A **singleton class** is a class that can have only one object (an instance of the class) at a time. After the first time, if we try to instantiate the Singleton class, the new variable also points to the first instance created.

<img align="center" width="400" src="https://www.scientecheasy.com/wp-content/uploads/2021/03/java-jvm-architecture.png">

```java
public class HelloWorldApp {
    public static void main(String[] args) {
        System.out.println("Hello World!"); // Prints the string to the console.
    }
}
```

[Java guides by Baeldung](https://www.baeldung.com/)  
[Java interview quesitons](https://www.interviewbit.com/java-interview-questions/)  

> 📓 Companies are looking for java developers with knowledge on Springboot, Maven, and Gradle

-----------
## C
<img align="right" width="50" src="https://media1.giphy.com/media/PiWfijeEeJEI0uB7j6/giphy.gif">  

> [C](https://en.wikipedia.org/wiki/C_(programming_language)) is a statically and weakly typed, general-purpose, procedural computer programming language supporting structured programming, lexical variable scope, and recursion. It is an imperative procedural language designed to be compiled to provide low-level access to memeory and language constructs and thus machine instructions.

C uses [pointers](https://en.wikipedia.org/wiki/Pointer_(computer_programming)) to 'point' toward an address or location of an object/function in memory.
  
**Memory management**  
One of the most important functions of a programming language is to provide facilities for managing memory and the objects that are stored in memory. 
  
C provides three distinct ways to allocate memory for objects:
- [Static memory allocation:](https://en.wikipedia.org/wiki/Static_memory_allocation) space for the object is provided in the binary at compile-time; these objects have an extent (or lifetime) as long as the binary which contains them is loaded into memory.
- [Automatic memory allocation:](https://en.wikipedia.org/wiki/Automatic_memory_allocation) temporary objects can be stored on the [stack](https://en.wikipedia.org/wiki/Call_stack), and this space is automatically freed and reusable after the block in which they are declared is exited.
- [Dynamic memory allocation:](https://en.wikipedia.org/wiki/Dynamic_memory_allocation) blocks of memory of arbitrary size can be requested at run-time using library functions such as malloc from a region of memory called the [heap](https://en.wikipedia.org/wiki/Dynamic_memory_allocation); these blocks persist until subsequently freed for reuse by calling the library function realloc or free

```c
# include <stdio.h>

int main(void)
{
    printf("hello, world\n");
}
```

[C tutorial](https://www.tutorialspoint.com/cprogramming/index.htm)

note [Cython exists](https://cython.org/) and is v cool

-----------
## C++
<img align="right" width="80" src="https://res.cloudinary.com/practicaldev/image/fetch/s--xVCufn18--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_66%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5nnkrcc3kixypm642opg.gif">

> [C\+\+](https://en.wikipedia.org/wiki/C%2B%2B) is a general-purpose language with OOP, generic and functional features. I has access to low-level memory manipulation and is an extension of C ("C with classes").  
> C++ has two main components: a direct mapping of hardware features provided primarily by the C subset, and zero-overhead abstractions based on those mappings.   
> Stroustrup describes C++ as "a light-weight abstraction programming language designed for building and using efficient and elegant abstractions"; and "offering both hardware access and abstraction is the basis of C++. Doing it efficiently is what distinguishes it from other languages."
  
As in C, C++ supports four types of memory management: static storage duration objects, thread storage duration objects, automatic storage duration objects, and dynamic storage duration objects.  

```c++
#include <iostream>

int main()
{
    std::cout << "Hello, world!\n";
}
```
----------
## Scala
<img align="right" width="70" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/39/Scala-full-color.svg/220px-Scala-full-color.svg.png">

> [Scala](https://en.wikipedia.org/wiki/Scala_(programming_language)) is a strong statically typed general-purpose programming language which supports both object-oriented programming and functional programming. Designed to be concise, many of Scala's design decisions are aimed to address criticisms of Java

imo its shorter but more complicated Java code. It can perform faster than Java with tail recursion.
``` scala
 object HelloWorld extends App {
   println("Hello, World!")
 }
```

----------

## Bash

<img align="right" width="50" height="50" src="https://styles.redditmedia.com/t5_2qh2d/styles/communityIcon_xagsn9nsaih61.png?width=256&s=1e4cf3a17c94aecf9c127cef47bb259162283a38">

> The Bourne Again SHell [(Bash)](https://www.gnu.org/software/bash/manual/bash.html#What-is-Bash_003f) is a Unix shell and command language.  

It offers functional improvements over sh for both programming and interactive use. In addition, most sh scripts can be run by Bash without modification.
The improvements offered by Bash include:
- command-line editing,
- unlimited size command history,
- job control,
- shell functions and aliases,
- indexed arrays of unlimited size,
- integer arithmetic in any base from two to sixty-four.  

	
**Name:** 
A word consisting solely of letters, numbers, and underscores, and beginning with a letter or underscore. Names are used as shell variables and function names. Also referred to as an identifier.

```bash
nano hello.sh
#!/bin/bash
echo "Hello World"
./hello-world.sh
```

[Bash Reference Manual](https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html)  
[Bash for beginners](https://tldp.org/LDP/Bash-Beginners-Guide/html/)

-----------------

<h1 align='center'>Tools</h1><br>

----------------

## Git

<img align="right" width="50" height="50" src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png">

> Git is an additive version control system used to aid cooperation on projects. It is usually used in conjunction with [Github](https://github.com/). Git and Github are almost ubiquitiously used by tech companies and is extremely useful to learn. Github is a great place to host your portfolio and demonstrate your knowledge through commits.    

![git ex](https://tutorialslink.com/Article_img/Blog_image/a0f60344-2db5-4f1c-bde7-2abd7fe8b96c.png)

[:open_book: Git book](https://git-scm.com/book/en/v2): note its really a website  

**Guides to contributing to open source:**  
[Contributing to your first open source project](https://github.com/firstcontributions/first-contributions)  
[Blog how to make your first contribution](https://dev.to/codesandboxio/how-to-make-your-first-open-source-contribution-2oim)   
[Hacktoberfest :jack_o_lantern:](https://github.blog/2021-10-07-githubs-guide-hacktoberfest-2021/)  
[Scikitlearn contribution guide](https://scikit-learn.org/dev/developers/contributing.html#contributing-code)  
[How to write a good commit message](https://chris.beams.io/posts/git-commit/) :heart_eyes:  

**Markdown help:** :octocat: 
> [Markdown Cheatsheet (general)](https://wordpress.com/support/markdown-quick-reference/)  
> [Mastering markdown](https://guides.github.com/features/mastering-markdown/)  
> [List of great github profile readmes](https://github.com/codeSTACKr/awesome-github-profile-readme)  
> [List of github  actions repos](https://github.com/sdras/awesome-actions)  
> [Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#objects) :heart_eyes:  
> [Simple Icons](https://simpleicons.org)  
> [Shield Badge Creator](https://shields.io) :shield: 
  
**Helpful Videos:**
- [100 second git summary (video)](https://www.youtube.com/watch?v=hwP7WQkmECE)
- [Learn git in 15 min (video)](https://www.youtube.com/watch?v=USjZcfj8yxE&list=PLIin1ELTMmjYRmbQo_fYwU2vWtaK5CXxp&index=1)

My initial local project workflow:
```
- git init repo in directory
- git add files
- git status
- git commit -m "asdf"
- git pull origin master (if remote branch chaged)
- git push -u origin master
```

## Docker
> :whale: [Docker](https://docs.docker.com/get-started/overview/#the-docker-daemon) is an open platform for developing, shipping, and running applications. Docker provides the ability to package and run an application in a loosely isolated environment called a container.  

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

Docker Swarm: emphasizes ease of use, making it most suitable for simple applications that are quick to deploy and easy to manage. Manages multiple containers.
 
------
[Kubernetes](https://kubernetes.io/) is an open-source system for automating deployment, scaling, and management of containerized applications. Manages multiple containers
  
[Kubernetes vs Docker Swarm](https://www.bmc.com/blogs/kubernetes-vs-docker-swarm/)

------------------

## Node js

<img align="right" width="50" src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg">

> A backend JavaScript runtime environment which can execute javaScript outside of a web browser. Node lets you use command line tools and for server-side scripting where dynamic web page content is produced before the page is sent to the user’s browser.

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

[Node interview repo](https://elemefe.github.io/node-interview/#/sections/en-us/?id=guide)  
[Node interview questions](https://www.interviewbit.com/node-js-interview-questions/)

## React
[:atom: React.js](https://reactjs.org/) is JavaScript Library for building user interfaces

[React interview questions](https://www.interviewbit.com/react-interview-questions/)

-----------------------
## SQL and NoSQL
> **SQL** is a standard querry language for storing, manipulating and retrieving data in databases.

Format of a SQL query:
- SELECT
- FROM
- WHERE
- GROUP BY
- HAVING
- ORDER BY

**Example:-**
```sql
SELECT CustomerName, City 
FROM Customers
WHERE CustomerName='John Smith';
```

What are the SQL aggregate functions?
- COUNT
- MAX/MIN
- AVG
- GROUP BY
- CASE
- DISTINCT
- JOINS

What are the different types of joins and can you explain them?  

What is a view?  

What are entities and relationships?

[SQl Interview Questions](https://www.interviewbit.com/sql-interview-questions/)  
  
https://github.com/AkashSingh3031/The-Complete-FAANG-Preparation/blob/master/2%5D.%20Technical%20Subjects/Interview%20Questions/2).%20Database%20Management%20System%20(DBMS)/_01)Top_50_DBMS_Question_and_answers.md  

------

SQL vs NoSQl:  
SQL | NoSQL
------------ | -------------
vertically scalable | horizontally scalable
table based | document, key-value, graph or wide-column stores
better for multi-row transactions | better for unstructured data like documents or JSON
  
[7 Database Paradigms (video)](https://www.youtube.com/watch?v=W2Z7fbCLSTw&list=PLIin1ELTMmjYRmbQo_fYwU2vWtaK5CXxp&index=1)  
  
### NoSQL

NoSQL is a collection of data items represented in a key-value store, document store, wide column store, or a graph database. Data is denormalized, and joins are generally done in the application code. Most NoSQL stores lack true ACID transactions and favor eventual consistency.  

**Key-Value Store**
> Abstraction: hash table

A key-value store generally allows for O(1) reads and writes and is often backed by memory or SSD. Data stores can maintain keys in lexicographic order, allowing efficient retrieval of key ranges. Key-value stores can allow for storing of metadata with a value.
- [Key-value database](https://en.wikipedia.org/wiki/Key-value_database)
- [Redis architecture](http://qnimate.com/overview-of-redis-architecture/)

**Document Store**
> Abstraction: key-value store with documents stored as values

A document store is centered around documents (XML, JSON, binary, etc), where a document stores all information for a given object. Document stores provide APIs or a query language to query based on the internal structure of the document itself. *Note, many key-value stores include features for working with a value's metadata, blurring the lines between these two storage types.*
- [MongoDB architecture](https://www.mongodb.com/mongodb-architecture)

**Wide Column Store**
> Abstraction: nested map

A wide column store's basic unit of data is a column (name/value pair). A column can be grouped in column families (analogous to a SQL table). Super column families further group column families. You can access each column independently with a row key, and columns with the same row key form a row. Each value contains a timestamp for versioning and for conflict resolution.

- [Big Table](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/chang06bigtable.pdf)
- [Cassandra](http://docs.datastax.com/en/cassandra/3.0/cassandra/architecture/archIntro.html)

**Graph Database**
> Abstraction: graph

In a graph database, each node is a record and each arc is a relationship between two nodes. Graph databases are optimized to represent complex relationships with many foreign keys or many-to-many relationships.

Graphs databases offer high performance for data models with complex relationships, such as a social network
- [Neo4j](https://neo4j.com/)
- [FlockDB](https://blog.twitter.com/2010/introducing-flockdb)
  

**BASE** is often used to describe the properties of NoSQL databases. In comparison with the CAP Theorem, BASE chooses availability over consistency.  
- **Basically available** - the system guarantees availability.
- **Soft state** - the state of the system may change over time, even without input.
- **Eventual consistency** - the system will become consistent over a period of time, given that the system doesn't receive input during that period.

-----------------------------------

## Database:
> A database is a collection of related data which represents some aspect of the real world. A database system is designed to be built and populated with data for a certain task.

## Database Management System (DBMS):
- **Database Management System** is a software for storing and retrieving users' data while considering appropriate security measures. It consists of a group of programs which manipulate the database. The DBMS accepts the request for data from an application and instructs the operating system to provide the specific data. In large systems, a DBMS helps users and other third-party software to store and retrieve data. 
  
Database management systems were developed to handle the following difficulties of typical File-processing systems supported by conventional operating systems. 
1. Data redundancy and inconsistency 
2. Difficulty in accessing data 
3. Data isolation – multiple files and formats 
4. Integrity problems 
5. Atomicity of updates 
6. Concurrent access by multiple users 
7. Security problems 

## DDL:
- DDL is short for **Data Definition Language**, which deals with database schemas and descriptions, of how the data should reside in the database.
   - **CREATE** 
      - to create a database and its objects like (table, index, views, store procedure, function, and triggers)
   - **ALTER** 
      - alters the structure of the existing database
   - **DROP** 
      - delete objects from the database
   - **TRUNCATE** 
      - remove all records from a table, including all spaces allocated for the records are removed
   - **RENAME** 
      - rename an object

## DML:
- DML is short for **Data Manipulation Language** which deals with data manipulation and includes most common SQL statements such SELECT, INSERT, UPDATE, DELETE, etc., and it is used to store, modify, retrieve, delete and update data in a database.
   - **SELECT** 
      - retrieve data from a database
   - **INSERT** 
      - insert data into a table
   - **UPDATE** 
      - updates existing data within a table
   - **DELETE** 
      - Delete all records from a database table
   - **MERGE** 
      - UPSERT operation (insert or update)

## DCL:
- DCL is short for **Data Control Language** and is mostly concerned with rights, permissions and other controls of the database system.
   - **GRANT** 
      - allow users access privileges to the database
   - **REVOKE** 
      - withdraw users access privileges given by using the GRANT command

## TCL:
- TCL is short for **Transaction Control Language** which deals with a transaction within a database.
   - **COMMIT**
      - commits a Transaction
   - **ROLLBACK**
      - rollback a transaction in case of any error occurs ● SAVEPOINT - to roll back the transaction making points within groups

## Relational Databases:

### ER diagram: 
- ER diagram or Entity Relationship diagram is a conceptual model that gives the graphical representation of the logical structure of the database. 
- It shows all the constraints and relationships that exist among the different components. 
- An ER diagram is mainly composed of following three components- Entity Sets, Attributes and Relationship Set. 
  
  
- Roll_no is a primary key that can identify each entity uniquely.
- Thus, by using a student's roll number, a student can be identified uniquely. 

### Entity Set: 
An entity set is a set of the same type of entities. 
- Strong Entity Set: 
   - A strong entity set is an entity set that contains sufficient attributes to uniquely identify all its entities. 
   - In other words, a primary key exists for a strong entity set. 
   - Primary key of a strong entity set is represented by underlining it. 
- Weak Entity Set: 
   - A weak entity set is an entity set that does not contain sufficient attributes to uniquely identify its entities. 
   - In other words, a primary key does not exist for a weak entity set. 
   - However, it contains a partial key called a discriminator. 
   - Discriminator can identify a group of entities from the entity set. 
   - Discriminator is represented by underlining with a dashed line. 
   
#### Relationship: 
A relationship is defined as an association among several entities. 
- **Unary Relationship Set -**
   -  Unary relationship set is a relationship set where only one entity set participates in a relationship set. 
- **Binary Relationship Set -**
   -  Binary relationship set is a relationship set where two entity sets participate in a relationship set. 
- **Ternary Relationship Set -**
   -  Ternary relationship set is a relationship set where three entity sets participate in a relationship set. 
- **N-ary Relationship Set -**
   -  N-ary relationship set is a relationship set where ‘n’ entity sets participate in a relationship set. 

### Attributes: 
Attributes are the descriptive properties which are owned by each entity of an Entity Set. 
- **Types of Attributes:** 
  - **Simple Attributes -**
     -  Simple attributes are those attributes which cannot be divided further. Ex. Age 
  - **Composite Attributes -**
     -  Composite attributes are those attributes which are composed of many other simple attributes. Ex. Name, Address 
  - **Multi Valued Attributes -**
     -  Multi valued attributes are those attributes which can take more than one value for a given entity from an entity set. Ex. Mobile No, Email ID
  - **Derived Attributes -**
     -  Derived attributes are those attributes which can be derived from other attribute(s). Ex. Age can be derived from DOB. 
  - **Key Attributes -**
     -  Key attributes are those attributes which can identify an entity uniquely in an entity set. Ex. Roll No. 
- The set of all those attributes which can be functionally determined from an attribute set is called a **closure of that attribute set** 

### Constraints: 
- Relational constraints are the restrictions imposed on the database contents and operations. They ensure the correctness of data in the database. 
   - **Domain Constraint -**
      -  Domain constraint defines the domain or set of values for an attribute. It specifies that the value taken by the attribute must be the atomic value from its domain. 
   - **Tuple Uniqueness Constraint -**
      -  Tuple Uniqueness constraint specifies that all the tuples must be necessarily unique in any relation. 
   - **Key Constraint -**
      -  All the values of the primary key must be unique. The value of the primary key must not be null. 
   - **Entity Integrity Constraint -**
      -  Entity integrity constraint specifies that no attribute of primary key must contain a null value in any relation.
   - **Referential Integrity Constraint -**
      -  It specifies that all the values taken by the foreign key must either be available in the relation of the primary key or be null. 

**Primary Key (PK):**  
A column with a unique value for each row.  
Although not all database management systems (DBMS) require you to put a PK into each table, from a design perspective a PK is a requirement. No table should be without one.

**Foreign Key (FK):**  
These define relationships between tables. When you want a row in one table to be linked to a row in another table, you place a FK column in the child table and use the value of the parent row's PK as the value of the FK field.

**Composite Key:**  
This is a key that is made up of more than one column.  
This is typically used when you want to prevent a table from using the same combination of values twice. For example, in a table that lists item prizes for shops, you would only want each shop to have a single price for each item. So, you create a FK for the shop and a FK for the item, and then you create a composite PK out of those two columns. This would cause the DBMS to forcefully restrict entries that would create rows where the combined values of these fields are duplicated. - This type of key is commonly used in N:M relationships.

**One-To-One (1:1) relationship:**  
A relationship between two tables, where a single row in one table is linked to a single row in another table.  
This type of relationship is practically non-existent in normalized relational designs. They exist mostly to get around limitations in databases like Access, where the number of columns was limited, thus creating the need to split tables up. They are also sometimes used to optimize the performance of the database.

**One-To-Many (1:N) relationship:**  
A relationship between two tables, where multiple rows in a child table can be linked to a single row in a parent table.
This is in fact the only "real" type of relationship in a relational database.

**Many-To-Many (N:M) relationship:**  
A relationship between two tables, where multiple rows in one table can be linked to multiple rows in another table.  
This type is "artificial" in a a way, because this kind of relationship can not be created directly between tables. To accomplish this type of relationship you need to create a third table; an intermediary table that contains FKs to both parents, linked via a set of 1:N relationships.

## Normalization:  
To help us properly design our tables we have a set of guidelines which, if followed properly, will help reduce the redundancy and chance of data corruption. We call this "Normalization".  
[Database Design and Normalization](https://www.dreamincode.net/forums/topic/179103-relational-database-design-normalization/)  
[Another Database Normalization walkthrough](https://www.databasestar.com/database-normalization/)  

There are several steps involved in normalizing a database. The steps are referred to as "Normal Forms". There are at least 7 NF. Each NF requires that the NF before it has also been satisfied. The spot between 3NF and 4NF is reserved for the BCNF (Boyce-Codd normal form), which was developed later as a slightly stronger version of the 3NF. Tables that have reached the 3NF are generally considered "normalized".  
- **1NF:** tables must not contain repeating groups of data
- **2NF:** no field should only be partially dependent on any candidate key
- **3NF:** columns should depend only upon the primary key of the table

[**Denormalization**](https://en.wikipedia.org/wiki/Denormalization) is the process of improving the read speed in a database at the expense of write performance, by adding redundant copies of data and by grouping.  
[When to Denormalize](https://dba.stackexchange.com/questions/4622/when-should-you-denormalize/15798#15798)
  
## Transaction: 
- Transaction is a single logical unit of work formed by a set of operations. 
 
**Operations in Transaction:** 
  - **Read Operation -**
     - Read(A) instruction will read the value of ‘A’ from the database and will store it in the buffer in main memory. 
  - **Write Operation –**
     - Write(A) will write the updated value of ‘A’ from the buffer to the database. 

**Transaction States:** 
   - **Active State –** 
     - This is the first state in the life cycle of a transaction. 
     - A transaction is called in an active state as long as its instructions are getting executed. 
     - All the changes made by the transaction now are stored in the buffer in main memory. 

   - **Partially Committed State –** 
      - After the last instruction of the transaction has been executed, it enters into a partially committed state. 
      - It is not considered fully committed because all the changes made by the transaction are still stored in the buffer in main memory. 
      
   - **Committed State –** 
      - After all the changes made by the transaction have been successfully stored into the database, it enters into a committed state. 
   
   - **Failed State –** 
      - When a transaction is getting executed in the active state or partially committed state and some failure occurs due to which it becomes impossible to continue the execution, it enters into a failed state. 
      
   - **Aborted State –** 
      - After the transaction has failed and entered into a failed state, all the changes made by it have to be undone. 
      - To undo the changes made by the transaction, it becomes necessary to roll back the transaction. 
      - After the transaction has rolled back completely, it enters into an aborted state. 
   - **Terminated State –** 
      - After entering the committed state or aborted state, the transaction finally enters into a terminated state where its life cycle finally comes to an end.
  
## File Structures: 
- **Primary Index:**
   - A primary index is an ordered file, records of fixed length with two fields. First field is the same as the primary key as a data file and the second field is a pointer to the data block, where the key is available. The average number of block accesses using index = log2 Bi + 1, where Bi = number of index blocks. 
- **Clustering Index:** 
   - Clustering index is created on data file whose records are physically ordered on a non-key field (called Clustering field). 
- **Secondary Index:** 
   - Secondary index provides secondary means of accessing a file for which primary access already exists.  
  
**B-Tree**  
A self balancing tree used as a database  
- At every level , we have Key and Data Pointer and data pointer points to either block or record. 

**Properties of B-Trees:** 
- Root of B-tree can have children between **2** and **P**, where P is Order of tree. 
- **Order of tree –** Maximum number of children a node can have. 
- Internal node can have children between **⌈ P/2 ⌉** and **P** 
- Internal node can have keys between **⌈ P/2 ⌉ – 1** and **P-1**
  
[Database Indexes](http://20bits.com/article/interview-questions-database-indexes)

## ETL (Extract, Transform, Load)  
Extract Transform Load is the procedure for copying data into a different system. We do this to gather and clean data and transfer the data into an easily stored and queryable form.  
[Databricks ETL](https://databricks.com/glossary/extract-transform-load)  

## Data Pipeline
[Hazelcast a data pipeline](https://hazelcast.com/glossary/data-pipeline/)

----------------------------

## CI and CD
> :rocket: CI and CD are two acronyms frequently used in modern development practices and DevOps. CI stands for continuous integration, a fundamental DevOps best practice where developers frequently merge code changes into a central repository where automated builds and tests run. But CD can either mean continuous delivery or continuous deployment. 

[Redhat what is ci/cd](https://www.redhat.com/en/topics/devops/what-is-ci-cd)  
[Atlassian ci vs cd](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)
![cicd](https://wac-cdn.atlassian.com/dam/jcr:b2a6d1a7-1a60-4c77-aa30-f3eb675d6ad6/ci%20cd%20asset%20updates%20.007.png?cdnVersion=1849)  

[Jenkins](https://www.jenkins.io/)  

[Link to top](#table-of-contents) :point_left:

--------------------

## API Design:

**RESTful API**:
- An architectural style for an application program interface (API) that uses HTTP requests to access and use data. That data can be used to GET, PUT, POST and DELETE data types, which refers to the reading, updating, creating and deleting of operations concerning resources.

REST = REpresentational State Transfer

**CRUD** : for persistent data
- Create = post
- Read = get
- Update = put
- Delete = delete
  
  
- GET to retrieve a resource;
- PUT to change the state of or update a resource, which can be an object, file or block;
- POST to create that resource; and
- DELETE to remove it.

**Persistence** is said to be ["orthogonal"](https://en.wikipedia.org/wiki/Orthogonality#Computer_science) or "transparent" when it is implemented as an intrinsic property of the execution environment of a program. An orthogonal persistence environment does not require any specific actions by programs running in it to retrieve or save their state.

**Non-orthogonal** persistence requires data to be written and read to and from storage using specific instructions in a program, resulting in the use of persist as a transitive verb: On completion, the program persists the data.
The advantage of orthogonal persistence environments is simpler and less error-prone programs

**SOAP** (formerly an acronym for Simple Object Access Protocol) is a messaging protocol specification for exchanging structured information in the implementation of web services in computer networks. It uses XML Information Set for its message format, and relies on application layer protocols, most often Hypertext Transfer Protocol (HTTP)  

**GraphQL:**
- A query/manipulation language for your API and a runtime for fulfilling queries with existing data
- https://graphql.guide/

**OLTP vs OLAP** 
- [link](https://techdifferences.com/difference-between-oltp-and-olap.html#:~:text=OLTP%20and%20OLAP%20both%20are,is%20an%20analytical%20processing%20system.&text=The%20basic%20difference%20between%20OLTP,online%20database%20query%20answering%20system.)
- Both are online processing systems. OLTP is a transactional processing sys which modifies data while OLAP is an analytical processing system which queries.

------------------------------------------------------

## HTTP 
**(Hypertext Transfer Protocol)**

([HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)) is an [application-layer](https://en.wikipedia.org/wiki/Application_Layer) protocol for transmitting hypermedia documents, such as HTML. It was designed for communication between web browsers and web servers, but it can also be used for other purposes. HTTP follows a classical [client-server model](https://en.wikipedia.org/wiki/Client%E2%80%93server_model), with a client opening a connection to make a request, then waiting until it receives a response. HTTP is a [stateless protocol](https://en.wikipedia.org/wiki/Stateless_protocol), meaning that the server does not keep any data (state) between two requests. Though often based on a TCP/IP layer, it can be used on any reliable [transport layer](https://en.wikipedia.org/wiki/Transport_Layer), that is, a protocol that doesn't lose messages silently like UDP does. RUDP — the reliable update of UDP — is a suitable alternative.

![http](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview/http-layers.png)

![http vs https](https://www.venafi.com/sites/default/files/2020-12/Difference_HTTP_HTTPS-2.png)

[Http overview](https://www.tutorialspoint.com/http/http_overview.htm)
 
Caching: https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching
 
**Cookies:** :cookie:
- a small piece of data that a server sends to the user's web browser. The browser may store it and send it back with later requests to the same server. Typically, it's used to tell if two requests came from the same browser — keeping a user logged-in, for example. It remembers stateful information for the stateless HTTP protocol.
 
**Cookies** are mainly used for three purposes:
- **Session management**
	- Logins, shopping carts, game scores, or anything else the server should remember
- **Personalization**
	- User preferences, themes, and other settings
- **Tracking**
	- Recording and analyzing user behavior

[How a browser works](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)

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

## TCP/IP

## Model View Controller (MVC)    

- Model
	- The central component of the pattern. It is the application's dynamic data structure, independent of the user interface. It directly manages the data, logic and rules of the application. It receives user input from the controller.
- View
	- Any representation of information such as a chart, diagram or table.
- Controller
	- Accepts input and converts it to commands for the model or view  
![mvc](https://developer.mozilla.org/en-US/docs/Glossary/MVC/model-view-controller-light-blue.png)

------------------------------------------------------
## AWS

<img align="right" width="90" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/1200px-Amazon_Web_Services_Logo.svg.png">

### Amazon Web Services / Cloud Data Principles

> :cloud: I took the [AWS cloud practioner ceritification](https://aws.amazon.com/certification/certified-cloud-practitioner/?trk=ps_a134p000006gXRtAAM&trkCampaign=GLBL-FY21-TrainCert-Certification_PaidSearch&sc_channel=PS&sc_campaign=FY21-TrainCert-Certification_PaidSearch&sc_publisher=Google&sc_category=Training%20and%20Certification&sc_country=US&sc_geo=NAMER&sc_outcome=acq&sc_detail=aws%20cloud%20practitioner%20certification&sc_content=Cloud%20Practitioner%20Solution_exact&sc_matchtype=e&sc_segment=508672713544&sc_medium=TC-P|PS-GO|Brand|Desktop|AW|Training%20and%20Certification|Certification|US|EN|Text|xx|B2I&s_kwcid=AL!4422!3!508672713544!e!!g!!aws%20cloud%20practitioner%20certification&ef_id=EAIaIQobChMIut-plvi48wIVmIjICh0E6AobEAAYAiAAEgJ7EPD_BwE:G:s&s_kwcid=AL!4422!3!508672713544!e!!g!!aws%20cloud%20practitioner%20certification) and [passed](https://www.linkedin.com/feed/update/urn%3Ali%3Aactivity%3A6847536534841802752?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3B4YYhEMILRXCVKvM4uhpanw%3D%3D) after two days of studying mainly using resources provided by AWS. This is the easiest AWS certification, but there are a lot of general pieces of knowledge needed to pass it.

**What the Cloud is:** servers that are accessed over the internet, and the software and databases that run on those servers.  

**Serverless:** an AWS architectural design principle based, where developers focus on the applications that they want to put into AWS resources, and serverless solutions such as AWS Lambda will then interpret the application and provision the compute and storage power required for execution.

**Virtual Private Cloud (VPC):****
a plot of virtual space within the Amazon Cloud to work within. A user or account may have many VPCs, but must have at least one VPC to act as a designated workspace to house your AWS cloud resources. VPC is a backbone principle of AWS cloud architecture, and they can connect to one another to create complex private and public networks. VPC has 4 main subcomponents – SUBNET, INTERNET GATEWAY, ROUTE TABLE, NETWORK ACCESS CONTROL LIST (NACL). A subnet is a network inside an IP network. 

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

NACL |Security Group
------------ | -------------
NACL can be understood as the firewall for the subnet | Security group can be understood as a firewall to protect EC2 instances
Stateless, meaning any change applied to an incoming rule isn’t automatically applied to an outgoing rule | Stateful, any changes which are applied to an incoming rule is automatically applied to an outgoing rule

What are the different types of EC2 instances?  
There 5 different types of EC2 instances: general purpose, compute-optimized, memory-optimized, storage-optimized, accelerated computing. Know each.

Can you explain the concept of serverless?

----------------------------

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
**1. Unit Testing**
	- Unit testing refers to tests that verify the functionality of a specific section of code, usually at the function level. In an object-oriented environment, this is usually at the class level, and the minimal unit tests include the constructors and destructors. 
	- Unit testing might include static code analysis, data-flow analysis, metrics analysis, peer code reviews, code coverage analysis and other software testing practices.

**2. Integration Testing:**  
	Integration Testing is the process of testing the connectivity or data transfer between a couple of unit tested modules.
	
**3. System Testing:**  
	A completely integrated system to verify that the system meets its requirements. For example, a system test might involve testing a login interface, then creating and editing an entry, plus sending or printing results, followed by summary processing or deletion (or archiving) of entries, then logoff.

**4. Acceptance Testing:**  
	Operational readiness of the system to be supported and integrated. Final Step to see if it doesn’t break anything else.

## Testing types, techniques and tactics:

**Installation testing:** self explanatory

**Compatibility testing:** Testing compatibility with other applications or OS or versions.
	
**Smoke** and **Sanity** testing: 
- Sanity testing determines whether or not to test further
- Smoke testing consists of minimal attempts to operate the software

**Regression testing:** Method for finding defects after a major code change. To find regressions (degraded or lost features). 

**Acceptance testing:** A smoke test or acceptance testing by the customer.

**Alpha/beta testing:** user acceptance testing by the customer/ testers

**Functional** vs **non-functional** testing: test if it fits specifications vs performance and scalability

**Continuous testing:** using automated tests as part of the delivery pipeline

**Destructive testing:** attempts to cause the software to fail

Talk to me about which debuggers/testing software you have used in order to fix programming errors?  

Test Driven Development: (develop tests before coding)
- [Cypress](https://www.cypress.io/)
- [Jest](https://jestjs.io/)
- [Test Driven Development (video)](https://www.youtube.com/watch?v=Jv2uxzhPFl4&list=PLIin1ELTMmjYRmbQo_fYwU2vWtaK5CXxp&index=1)

------------------------------------------------

## Parallel Processing:
> Multiple processes done in separate memory locations
Both processes and threads are independent sequences of execution. The typical difference is that threads (of the same process) run in a shared memory space, while processes run in separate memory spaces.
- A [Fork](https://en.wikipedia.org/wiki/Fork_(system_call)) is when a process creates a copy of itself.

### Process
Each [process](https://en.wikipedia.org/wiki/Process_(computing)) provides the resources needed to execute a program. A process has a virtual address space, executable code, open handles to system objects, a security context, a unique process identifier, environment variables, a priority class, minimum and maximum working set sizes, and at least one thread of execution. Each process is started with a single thread, often called the primary thread, but can create additional threads from any of its threads.

### Thread 
:thread: A thread is an entity within a process that can be scheduled for execution. All threads of a process share its virtual address space and system resources. In addition, each thread maintains exception handlers, a scheduling priority, thread local storage, a unique thread identifier, and a set of structures the system will use to save the thread context until it is scheduled. The thread context includes the thread's set of machine registers, the kernel stack, a thread environment block, and a user stack in the address space of the thread's process. Threads can also have their own security context, which can be used for impersonating clients.
  
Concurrency: https://en.wikipedia.org/wiki/Concurrency_(computer_science)
  
Daemon: https://en.wikipedia.org/wiki/Daemon_(computing)

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

A [**mutex**](https://en.wikipedia.org/wiki/Mutual_exclusion) is a locking mechanism used to synchronize access to a resource. Only one task (can be a thread or process based on OS abstraction) can acquire the mutex. It means there is ownership associated with a mutex, and only the owner can release the lock (mutex). 

Using **Mutex**: 
- A **mutex** provides mutual exclusion, either producer or consumer can have the key (mutex) and proceed with their work. As long as the buffer is filled by the producer, the consumer needs to wait, and vice versa. 
- At any point of time, only one thread can work with the entire buffer. The concept can be generalized using **semaphore**. 

:crossed_flags: **Semaphore** is a signaling mechanism (“I am done, you can carry on” kind of signal). For example, if you are listening to songs (assume it as one task) on your mobile phone and at the same time, your friend calls you, an interrupt is triggered upon which an interrupt service routine (ISR) signals the call processing task to wake up. 
  
Using **Semaphore**:
- A **semaphore** is a generalized mutex. In lieu of a single buffer, we can split the 4 KB buffer into four 1 KB buffers (identical resources). A semaphore can be associated with these four buffers. The consumer and producer can work on different buffers at the same time.

-----------------------------------------------------

## System Design preparation:

> :building_construction: This section is more of a high level view of some important things to know about database design and software design. You may get a more in depth system design focused interview where you are asked to design a product or fix/improve one.  
[Here is a useful repo for a system design interview](https://github.com/donnemartin/system-design-primer)

![system design overview](https://camo.githubusercontent.com/e45e39c36eebcc4c66e1aecd4e4145112d8e88e3/687474703a2f2f692e696d6775722e636f6d2f6a6a3341354e382e706e67)

### ACID :alembic:
- Atomicity - each transaction is a single unit (fails or succeeds completely)
- Consistency - a transaction can only bring the database from one valid state to another
- Isolation - all transactions in a concurrent stream get executed fully
- Durability - once a transaction has been committed it will remain so

### CAP Theorem for distributed computing
this states that it is not possible for a distributed computer system to simultaneously provide all three of the following guarantees:
- **Consistency** (all nodes see the same data even at the same time with concurrent updates )
- **Availability** (a guarantee that every request receives a response about whether it was successful or failed)
- **Partition tolerance** (the system continues to operate despite arbitrary message loss or failure of part of the system)

### Code Reusability
Candidate design features for software reuse include:
- [Adaptable](https://en.wikipedia.org/wiki/Adaptability)
- Brief: small size
- [Consistency](https://en.wikipedia.org/wiki/Consistency)
- [Correctness](https://en.wikipedia.org/wiki/Correctness_(computer_science))
- [Extensibility](https://en.wikipedia.org/wiki/Extensibility)
- Fast
- Flexible
- Generic
- Localization of volatile (changeable) design assumptions (David Parnas)
- [Modularity](https://en.wikipedia.org/wiki/Modularity_(programming))
- [Orthogonality](https://en.wikipedia.org/wiki/Orthogonality)
- Parameterization
- Simple: low complexity
- Stability under changing requirements

## SOLID

### Single Responsibility Principle (SRP)
This principle states that there should never be more than one reason for a class to change. This means that you should design your classes in such a way that each class should have a single purpose.
- Ex: An Account class is responsible for managing Current and Saving Account but a CurAccount and a SavingAccount classes are specialized. Hence both are responsible for a single purpose only.

### Open/Closed Principle (OCP)
This principle states that software entities **(classes, modules, functions, etc.) should be open for extension but closed for modification.** The "closed" part of the rule states that once a module has been developed and tested, the code should only be changed to correct bugs. The "open" part says that you should be able to extend existing code in order to introduce new functionality.
- Ex: A PaymentGateway base class contains all basic payment related properties and methods. This class can be extended by different PaymentGateway classes for different payment gateway vendors to achieve their functionalities. Hence it is open for extension but closed for modification.

### Liskov Substitution Principle (LSP)
This principle states that functions that use pointers or references to base classes must be able to use objects of derived classes without knowing it.
- Ex: Assume that you have an inheritance hierarchy with Person and Student. Wherever you can use Person, you should also be able to use a Student, because Student is a subclass of Person.

### Interface Segregation Principle (ISP)
This principle states that Clients should not be forced to depend upon interfaces that they don’t use. This means the number of members in the interface that is visible to the dependent class should be minimized.

### Dependency Inversion Principle (DIP)
- High level modules should not depend upon low level modules. Both should depend upon abstractions.
- Abstractions should not depend upon details. Details should depend upon abstractions.
- It helps us to develop loosely coupled code by ensuring that high-level modules depend on abstractions rather than concrete implementations of lower-level modules. The Dependency Injection pattern is an implementation of this principle

### DRY (Don’t Repeat Yourself)
This principle states that each small piece of knowledge (code) may only occur exactly once in the entire system. This helps us to write scalable, maintainable and reusable code.

-------------------------------------------
[Link to top](#table-of-contents) :point_left:

## Statistics and Probability 
https://www.khanacademy.org/math/statistics-probability

**Permutations:**
> Abc, bca, bac, cav, cba, acbb = 3! => n!
> PEPPER = 6! / (3!2!)
> n!/(n1!)


**Combinations:** n choose r  
*(n r)  for r<=n => n! / ((n-r)!r!)*

Binomial Theorem

De Morgan’s Laws: 
>	(E U F)^c = E^cF^c
>	(EF)^c = E^c U Fc

**Probability:** P(E) = (num of outcomes in E) / (num of outcomes in S)

**Conditional Probability:**  
	P(E|F) = probability  E occurs given F
	
What is Bayes theorem?  
P(A|B) = P(A) P(B|A) / P(B)
  
**Bayes Theorem:**  
[Bayes theorem, the geometry of changing beliefs (video)](https://www.youtube.com/watch?v=HZGCoVF3YvM&list=WL&index=1)  
[A visual guide to Bayesian thinking (video)](https://www.youtube.com/watch?v=BrK7X_XlGB8&list=WL&index=1)  

----------------------------
What is the diff between precision/specificity?

What is a p-value?

Quantile: value under which a certain percent lies

Dispersion -> Variance: average of the squared deviation from the mean 
(subtract the mean and square the result, then find the average of those differences)

[Standard deviation](https://www.mathsisfun.com/data/standard-deviation.html) = variance

[How to Learn Statistics for Data Science As A Self Starter (video)](https://www.youtube.com/watch?v=zRUliXuwJCQ&list=WL&index=1)  

[How to Learn Probability Distributions (video)](https://www.youtube.com/watch?v=mBCiKUzwdMs&list=WL&index=3)

------------------------------

## Distributions:
[Binomial distribution](https://en.wikipedia.org/wiki/Binomial_distribution)

**Probability Density Function (PDF)** := the probability of seeing a value in a certain interval equals the integral of the density function over the interval

**Cumulative Distribution Function (CDF)** := the probability that a random variable is <= a value

**Normal distribution:** 
	A continuous probability distribution that is symmetric about the mean (Bell curve).

**Variance** = how scattered the predictions are from the actual value
High variance means overfitting

**Correlation** measures how strongly two variables are related.
- In covariance two items vary together and it’s a measure that indicates the extent to which two random variables change in tandem
  
**Error** = bias + variance

**Bias** = how far the predicted values are from the actual values

High bias means you are underfitting

----------------------------------------
## Data

[:books: Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)  
[Linkedin Data Analytics help](https://business.linkedin.com/talent-solutions/resources/interviewing-talent/data-analyst)  

### Analysis types

**Univariate analysis** is the simplest and easiest form of data analysis where the data being analyzed contains only one variable. 
- Example: Studying the heights of players in the NBA.
- Univariate analysis can be described using Central Tendency, Dispersion, Quartiles, Bar charts, Histograms, Pie charts, and Frequency distribution tables.

**Bivariate analysis** involves the analysis of two variables to find causes, relationships, and correlations between the variables. 
- Example: Analyzing the sale of ice creams based on the temperature outside.
- The bivariate analysis can be explained using Correlation coefficients, Linear regression, Logistic regression, Scatter plots, and Box plots.

**Multivariate analysis** involves the analysis of three or more variables to understand the relationship of each variable with the other variables. 
- Example: Analysing Revenue based on expenditure.
- Multivariate analysis can be performed using Multiple regression, Factor analysis, Classification & regression trees, Cluster analysis, Principal component analysis, Dual-axis charts, etc.

### Hypothesis Testing:
a hypothesis that is testable on the basis of observed data modelled as the realised values taken by a collection of random variables. A set of data is modelled as being realised values of a collection of random variables having a joint probability distribution in some set of possible joint distributions. The hypothesis being tested is exactly that set of possible probability distributions. 

A **statistical hypothesis** test is a method of [statistical inference](https://en.wikipedia.org/wiki/Statistical_inference). An alternative hypothesis is proposed for the probability distribution of the data, either explicitly or only informally. The comparison of the two models is deemed statistically significant if, according to a threshold probability—the significance level—the data would be unlikely to occur if the [null hypothesis](https://en.wikipedia.org/wiki/Null_hypothesis) were true. A hypothesis test specifies which outcomes of a study may lead to a rejection of the null hypothesis at a pre-specified level of significance, while using a pre-chosen measure of deviation from that hypothesis (the test statistic, or goodness-of-fit measure). The pre-chosen level of significance is the maximal allowed "false positive rate". One wants to control the risk of incorrectly rejecting a true null hypothesis.

### A/B Testing

**A/B testing** (also known as split testing or bucket testing) is a method of comparing two versions of a webpage or app against each other to determine which one performs better. AB testing is essentially an experiment where two or more variants of a page are shown to users at random, and statistical analysis is used to determine which variation performs better for a given conversion goal.
- [Airbnb experiments and A/B testing](https://medium.com/airbnb-engineering/experiments-at-airbnb-e2db3abf39e7)
- [When Should A/B testing not be trusted](https://www.quora.com/When-should-A-B-testing-not-be-trusted-to-make-decisions)
- [12 Guidelines for A/B testing](https://hookedondata.org/guidelines-for-ab-testing/?utm_campaign=Data_Elixir&utm_medium=email&utm_source=Data_Elixir_194)
- [A/B testing interview questions](https://www.tutorialspoint.com/ab_testing/ab_testing_interview_questions.htm)
- [Pinterests metrics to create growth](http://jwegan.com/growth-hacking/27-metrics-pinterests-internal-growth-dashboard/)

## Data Cleaning:

How can you handle missing values in a dataset?
- **Listwise Deletion**
	- In the listwise deletion method, an entire record is excluded from analysis if any single value is missing.
- **Average Imputation**
	- Take the average value of the other participants' responses and fill in the missing value.
- **Regression Substitution**
	- You can use multiple-regression analyses to estimate a missing value.
- **Multiple Imputations**
	- It creates plausible values based on the correlations for the missing data and then averages the simulated datasets by incorporating random errors in your predictions.

How do you deal with outliers in a dataset?
- Trim them out :scissors:
- Normalize them (log+1) :mountain: 

### Dataset validation
**Field Level Validation** 
– In this method, data validation is done in each field as and when a user enters the data. It helps to correct the errors as you go.

**Form Level Validation** 
– In this method, the data is validated after the user completes the form and submits it. It checks the entire data entry form at once, validates all the fields in it, and highlights the errors (if any) so that the user can correct it. 

**Data Saving Validation** 
– This data validation technique is used during the process of saving an actual file or database record. Usually, it is done when multiple data entry forms must be validated. 

**Search Criteria Validation** 
– This validation technique is used to offer the user accurate and related matches for their searched keywords or phrases. The main purpose of this validation method is to ensure that the user’s search queries can return the most relevant results.

### Spark
[Apache Spark](https://spark.apache.org/) is an open-source unified analytics engine for large-scale data processing. Spark provides an interface for programming entire clusters with implicit data parallelism and fault tolerance.  

[Data camp Spark tutorial](https://www.datacamp.com/community/tutorials/apache-spark-python#gs.fMIIqxM)

---------------------------------------------

## ML Prep:
<img align="right" width="100" height="100" src="https://media2.giphy.com/media/Uu5MHCPoCabaLUYUgE/200w.webp?cid=ecf05e47map8im7jvjhwyl4r0xfd6apx38pksmtcwy4aipjd&rid=200w.webp&ct=g">

[:world_map: An ML roadmap](https://whimsical.com/CA7f3ykvXpnJ9Az32vYXva)   
[Google ML crash course](https://developers.google.com/machine-learning/crash-course)  
[Fast AI deep learning course](https://course.fast.ai/)  
[:books: AIMA online book](http://aima.cs.berkeley.edu/)  

Possible Interview Topics:
> Statistical distributions  
> Probability simulation  
> String parsing and data manipulation  
> Numpy functions and matrices  
> Pandas data munging  
> A project walkthrough  

[51 Essential Machine Learning Questions](https://www.springboard.com/blog/machine-learning-interview-questions/)  
[100+ Data Science Interview Questions Edureka](https://www.edureka.co/blog/interview-questions/data-science-interview-questions/)  

### Evaluation metrics:
- Classification
	- Accuracy
	- Precision
	- Recall
	- Confusion matrix
	- F1 score
	- Mean average precision (MAP) - object detection
	- Jaccard index
- Regression
	- RMSE / RMSECV
	- MAE
	- R^2

### Precision vs recall
- Recall is the true positive rate (pos claims vs actual num of pos)- rate of fish caught in pond
- Precision is the positive predictive value - rate of correct predictions

**F1 Score:**  
	A weighted average of the precision and recall of a model (1 best, 0 worst)

### Supervised Algorithms:
- Linear Regression
- Logistic Regression
- k-Nearest Neighbors
- Support Vector Machines (SVM)
- Decision Trees and Random Forest
- AdaBoost and Gradient boosting
	- XGBoost
	- CatBoost
	- LightGBM
- Neural Networks
	- Convolutional
	- Recurrent (RNN)
	- Transformer

### Unsupervised Algorithms:
- Clustering (K-Means)
- Visualization and dimensionality reduction
	- PCA
	- Autoencoders
	- t-Distributed Stochastic Neighbor Embedding(t-SNE)
- Anomaly Detection
	- Autoencoder
	- One-class classification

What is the difference between supervised vs unsupervised machine learning?

What is the difference between **discriminative** and **generative** models?
- **Discriminative**
	- Learn decision boundaries (ex: svm, regressions)
- **Generative**
	- Learn distributions (ex: naive bayes)

Time series: K-fold cv  

**Variance** = how scattered the predictions are from the actual value  
High variance means overfitting  

**Correlation** measures how strongly two variables are related.  
In covariance two items vary together and it’s a measure that indicates the extent to which two random variables change in cycle  

**Error** = bias + variance  
**Bias** = how far the predicted values are from the actual values  
High bias means you are underfitting

How to deal with **underfitting**:
- Add features
- Decrease regularization term  
How to deal with **overfitting**:
- Reduce number of features
- Increase regularization term
- Dropout- randomly remove parts of your model
- Data Augmentation
- Batch  normalization

Regularization is a technique where we penalize the loss function for flexibility  
            **L1 and L2 regularization:**  
L2 regularization tends to spread error among all the terms, while L1 is more binary/sparse, with many variables either being assigned a 1 or 0 in weighting. L1 corresponds to setting a Laplacean prior on the terms, while L2 corresponds to a Gaussian prior.

Type 1 error is a false positive  
Type 2 error is a false negative  

**What is deep learning,** and how does it contrast with other machine learning algorithms?  
  	Deep learning is a subset of machine learning that is concerned with neural networks: how to use backpropagation and certain principles from neuroscience to more accurately model large sets of unlabelled or semi-structured data. In that sense, deep learning represents an unsupervised learning algorithm that learns representations of data through the use of neural nets.

**Convolutional Neural Network:**
  	a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other.  
[A comprehensive guide to CNNs](https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53)

What cross-validation technique would you use on a time series dataset?  
  K-folds with forward chaining. As it is inherently ordered by date and is biased towards the later dates  

What is the difference between **bagging** and **boosting**?  
https://quantdare.com/what-is-the-difference-between-bagging-and-boosting/
  
How would you build a data pipeline?  

How would you implement a recommendation system?  

#### Data Science Project Ideas
[Best Image ML competitions (video)](https://www.youtube.com/watch?v=1-myowrUhok&list=PLIin1ELTMmjYRmbQo_fYwU2vWtaK5CXxp&index=1)

-------------------------------------------

### NLP
> :open_book: NLP stands for [Natural Language Processing](https://en.wikipedia.org/wiki/Natural_language_processing), it pertains to the processing of large amounts of 'words' to extract information and insights.  
> Challenges in natural language processing frequently involve [speech recognition](https://en.wikipedia.org/wiki/Speech_recognition), [natural language understanding](https://en.wikipedia.org/wiki/Natural-language_understanding), and [natural language generation](https://en.wikipedia.org/wiki/Natural-language_generation).

Statistical: Part of Speech tagging, decision trees  
Neural Networks: word embeddings, NER, bert  

### Morphological analysis
[Lemmatization](https://en.wikipedia.org/wiki/Lemmatisation)  
The task of removing inflectional endings only and to return the base dictionary form of a word which is also known as a lemma. Lemmatization is another technique for reducing words to their normalized form. But in this case, the transformation actually uses a dictionary to map words to their actual form

[Morphological segmentation](https://en.wikipedia.org/wiki/Morphology_(linguistics))  
Separate words into individual morphemes and identify the class of the morphemes.

[Part-of-speech tagging](https://en.wikipedia.org/wiki/Part-of-speech_tagging)  
Given a sentence, determine the part of speech (POS) for each word. Many words, especially common ones, can serve as multiple parts of speech. For example, "book" can be a noun ("the book on the table") or verb ("to book a flight"); "set" can be a noun, verb or adjective; and "out" can be any of at least five different parts of speech.

[Stemming](https://en.wikipedia.org/wiki/Stemming)  
The process of reducing inflected (or sometimes derived) words to a base form (e.g., "close" will be the root for "closed", "closing", "close", "closer" etc.). Stemming yields similar results as lemmatization, but does so on grounds of rules, not a dictionary.

[Named entity recognition](https://en.wikipedia.org/wiki/Named_entity_recognition) (NER)  
Given a stream of text, determine which items in the text map to proper names, such as people or places, and what the type of each such name is (e.g. person, location, organization). Although capitalization can aid in recognizing named entities in languages such as English, this information cannot aid in determining the type of named entity, and in any case, is often inaccurate or insufficient. For example, the first letter of a sentence is also capitalized, and named entities often span several words, only some of which are capitalized. Furthermore, many other languages in non-Western scripts (e.g. Chinese or Arabic) do not have any capitalization at all, and even languages with capitalization may not consistently use it to distinguish names. For example, German capitalizes all nouns, regardless of whether they are names, and French and Spanish do not capitalize names that serve as adjectives.

[Sentiment analysis](https://en.wikipedia.org/wiki/Sentiment_analysis) (see also [Multimodal sentiment analysis](https://en.wikipedia.org/wiki/Multimodal_sentiment_analysis))  
Extract subjective information usually from a set of documents, often using online reviews to determine "polarity" about specific objects. It is especially useful for identifying trends of public opinion in social media, for marketing.

BERT: https://www.kaggle.com/mdfahimreshm/bert-in-depth-understanding

SPACY: https://spacy.io/

[Link to top](#table-of-contents)

===========================================================
<img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50">

## TODO
- add more images and resize them
- add to ci/cd section and jenkins
- add spark and kafka section
- add Hadoop Section
- add springboot and maven to Java
- add to react section
- add scala, c, c++, go
- add messaging services section ie redis, redux, rabbitmq

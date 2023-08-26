# ITrain
ITrain 
This article is for freshers of computer science & engineering. It took me a long time to find the answers that I needed in this field but I will make sure that it will be easy for you. The curriculum of computer science under graduate includes a various courses.I’ll also try to introduce and explain in brief why those subjects are there in your curriculum and their purpose.

So, lets start from basics,

Theoretical computer science
Computers were built to expand our brains, Originally scientists built computers to solve arithmetic but later they discovered that computers can do much more things. Tremendous calculations, Internet to connect world, lifelike graphics, simulating real word etc.
All this by flipping 0 s and 1s.

Lambda Calculus
Every computer engineer / scientist needs to know about lambda calculus.

Lambda Calculus is the concept of a function from a computational perspective. It can encode any computation : If you have written a computer program in any existing language it can be encoded in lambda calculus successfully and any future programmer can understand it if he wants to code the same function in his chosen programming language.

Any Turing machine program can be translated into an equivalent lambda calculus program i.e we can represent loops , recursions etc.

Lambda Calculus is the basis of functional programming research in programming languages.

a lambda function for addition of 2 numbers.

 λx.x+1
 
 λx.λy.x+y
Know more about lambda calculus : https://en.wikipedia.org/wiki/Lambda_calculus

Turing Machine : Foundation of computer science
A Turing machine is a mathematical model of computation. Its a general example of a central processing unit (CPU) that controls all data manipulation done by a computer. The Turing machine is capable of processing an unrestricted grammar(grammars where any combination of variables and terminals can appear on the left side), which further implies that it is capable of robustly evaluating first-order logic in an infinite number of ways. This is famously demonstrated through lambda calculus.

Every problem that is computable by Turing machine is computable using lambda calculus.


A Turing machine contains several parts :

1. Infinitely long tape (not really) split into cells containing symbols.

2. A head which reads and writes symbols on the tape.
3. A state register that stores state of the head and list of possible instructions. like move , read, write stop.

As compared to modern computers,
Tape is RAM
Head is CPU
& the list of instructions is stored in computers memory.

Turing machine is a simple set of rules. Its very powerful and this is basically what all computers do now. No doubt our computers have more parts like i/o, storage , GPU , monitor etc which performs their specific operations but the core Idea is same as Turing machine.
Turing machines are universal & are widely used in theoretical computer science for proving abstract theorems.

learn more : https://en.wikipedia.org/wiki/Turing_machine

The movie “The Imitation Game” is based on Alan Turing and his machines.

Turing machines were not invented to be built in reality, but they are very important for theoretical computer science as they are one of the simplest models for computers. The Church-Turing thesis states that all computers are only as powerful as Turing machines. This can be used to prove if a problem is solvable by a computer or not.

Automata Theory

Classes of Automata
Automata theory is the study of abstract machines and automata, as well as the computational problems that can be solved using them. It is a theory in theoretical computer science. The word automata means “self-making”.


finite state automata
The theory of computation is also known as Automata theory. This is a theoretical division of mathematics as well as computer science, which mostly deals with the computation logic with respect to automata. Automata theory allows the researchers to know how machines calculate the functions as well as resolve problems.

Computability theory
Computability theory is used to classify if problem is computable or not computable. Some problems can never be solved by computer due to its nature. Halting problem is one of them where program will stop running or carry on forever.
Many problems are theoretically solvable but in practice take too much memory or more steps than lifetime.

Computational complexity categorizes those problems according to how they scale.

Computational Complexity

Classes of Computational Complexity
How problems scale : Amount of Memory & Number of Steps required.

Discrete Mathematics
The curriculum of computer science under graduate includes a course titled Discrete Mathematics. Many students who graduate with degree in computer science end up with jobs where no mathematical skills are used, So why there is such a course and why its important to learn?

In order to understand computations, we need a language that allows us to reason about things we can’t see and can’t touch, that are too big.

(PDF) Discrete Mathematics for Computer Science, Some Notes
These are notes on discrete mathematics for computer scientists. The presentation is somewhat unconventional. Indeed I…
www.researchgate.net

https://www.cs.yale.edu/homes/aspnes/classes/202/notes.pdf

Algorithms
Algorithm is a set of instructions designed and written to solve a problem. which is used to write code and build programs. Algorithms are important to get best output from computer.

A basic algorithm for addition of two numbers.

 Step 1: Start
 Step 2: Read num1 , num2
 Step 3: Add num1 to num2
 Step 4: Display result
 Step 5: Stop
Different algorithms can get the same final result but some algorithms are much more efficient than others where Big O notations(Asymptotic Notation) comes in. Time complexity & space complexity calculates whether algorithm is optimal or not.


Time & space efficiency
Types of Algorithm

Recursive algorithms.
Dynamic programming algorithm.
Backtracking algorithm.
Divide and conquer algorithm.
Greedy algorithm.
Brute Force algorithm.
Randomized algorithm.
Best book — Introduction to Algorithms by Thomas Cormen

Information Theory
Information theory studies the properties of information and how it can be measured stored and communicated.

Coding Theory
Coding theory is the study of properties of code & their fitness for specific application.

Data compression : how to compress data, taking less memory while preserving most of the information.
Error control : Error detection & correction during transmission.
Cryptographic coding : used to keep information secret while travelling through network.Deals with Encryption and decryption of data.
Line coding: a line code is a pattern of voltage, current used to represent digital data transmitted down a transmission line. Its very much useful while learning about microprocessor and hardware.

an example of line coding
know more : https://en.wikipedia.org/wiki/Coding_theory

Logic
Logic in computer science covers the overlap between the field of logic and that of computer science. The topic can essentially be divided into three main areas:

Theoretical foundations and analysis
Use of computer technology to aid logicians
Use of concepts from logic for computer applications

Logic
Graph Theory
A study of graphs which are made up of vertices(the points or nodes) and edges(the lines connecting to the vertices). It plays critical role in solving computer science problems.


Graph
Sorting

Sorting algorithms visualized
In computer science, a sorting algorithm is an algorithm that puts elements of a list in a numerical or lexical order. Most used algorithms are mention above. Quick-sort is the best fastest sorting algorithm.

Learn more :

https://brilliant.org/wiki/sorting-algorithms/

Data Structures
Data Structures deals with organizing and storing data in computer.

These are the 8 common data structures which every programmer must know.

Array
Stack
Queue
Linked List
Tree
Graph
Hash Table
Heaps
8 Common Data Structures every Programmer must know
Data Structures are a specialized means of organizing and storing data in computers in such a way that we can perform…
towardsdatascience.com

Computational Geometry
Computational geometry is the study of algorithms which can be stated in terms of geometry. Some purely geometrical problems arise out of the study of computational geometric algorithms, and such problems are also considered to be part of computational geometry.

CS 274: Computational Geometry - Shewchuk - UC Berkeley
( Lime-basil Triangulation,Dinara Kasko, 2016.) CS 274 Computational Geometry Jonathan Shewchuk Spring 2019 Mondays and…
people.eecs.berkeley.edu

Computational Geometry
In parallel computation, it is the rule rather than the exception that the known sequential techniques do not translate…
www.sciencedirect.com

Parallel Programming
Parallel computing is a type of computation in which many calculations or the execution of processes are carried out simultaneously. Large problems can often be divided into smaller ones, which can then be solved at the same time.


Formal Methods
In computer science, specifically software engineering and hardware engineering, formal methods are mathematically rigorous techniques for the specification, development and verification of software and hardware systems. By which reliability and robustness of a design is obtained.

Formal methods are applied in different areas of hardware and software, including routers, Ethernet switches, routing protocols, security applications, and operating system microkernels.

Quantum Computing
Quantum computing is the use of quantum-mechanical phenomena such as superposition and entanglement to perform computation. Computers that perform quantum computations are known as quantum computers. Quantum computers are believed to be able to solve certain computational problems, such as integer factorization (which underlies RSA encryption), substantially faster than classical computers. The study of quantum computing is a subfield of quantum information science.

An interesting video on quantum computing


Computer Engineering
Computers are designed to do so many different things. Computers must be capable of solving many different kinds of problems optimally. Computers are used to reduce human efforts and errors in work. Also for perfection and fast outputs.

Every single task that runs on computer goes through core of computer i.e. CPU

Scheduling
CPU needs to switch back and forth between these jobs to make sure everything gets completed in a reasonable time. This is controlled by a scheduler, which chooses what to do when and tries to get through using context switching.


Single processor and multiprocessor scheduling
Multiprocessing increases speed because it uses several CPU cores executing multiple jobs in parallel.

Computer Architecture
How a processor is designed to perform task.

Von Neumann Architecture

The modern computers are based on a stored-program concept introduced by John Von Neumann. In this stored-program concept, programs and data are stored in a separate storage unit called memories and are treated the same. This novel idea meant that a computer built with this architecture would be much easier to reprogram.


Von Neumann Architecture
Moore's Law : Moore’s law is the observation that the number of transistors in a dense integrated circuit doubles about every two years. Hence double the speed and storage.

https://www.youtube.com/watch?v=f0gMdGrVteI

Layers of Software
On the top of hardware there are layers of software written by actual programmers using various programming languages.


Programming languages
A programming language is how humans tell a computer what to do and they vary greatly depending on the job at hand from low level languages like assembly through to high level languages like python or JavaScript for coding
websites and apps. In general, the closer a language is to the hardware, the more difficult it is for humans to use.

Best languages to begin with :

https://www.hackerearth.com/blog/developers/dummies-guide-to-computer-programming-languages/

Compilers
A compiler is a special program that processes statements written in a programming language and turns them into machine language or “code” that a computer’s processor uses. Typically, a programmer writes code in language such as C or CPP one line at a time using an editor. The file that is created contains what are called the source code. The programmer then runs the appropriate language compiler, specifying the name of the file that contains the source statements.


Compilation of a JavaScript program

High level to low level language conversion

Designing Programming Language and compilers is a big task because they are the tools that engineers use to make anything they wanted. It should be easy and versatile enough to allow programmers to build their crazy ideas.

Operating System
Operating system is most important software. It interacts with and controls how programs run on hardware. Also provides common services for computer programs. Windows , Mac , Linux , android are most used OS in world.

Various types of OS : Single-tasking and multi-tasking, Single- and multi-user, Distributed,Templated, Embedded & Real Time.


Operating system Architecture
Building an operating system is a huge challenge. This brings us to the field software engineering.

Software Engineering
Software engineering is writing codes and build software that runs on a computer efficiently. Building a good software is a creative thing where programmers and developers have to convert their knowledge into a perfectly running error free application on user end.

there are many best practices and design philosophies that people follow to build software.

Object Oriented design
Formal Methods
Testing
Version control

Learn about Object Oriented Programming :

https://www.geeksforgeeks.org/object-oriented-programming-oops-concept-in-java/

Networking
For getting computers to communicate and work together using different network topology.

Uses a set of common communication protocols over digital interconnections for the purpose of sharing resources located on or provided by the network nodes. Every computer has a unique IP address by using it they recognize and communicate.


Database
A database is basically a data structure that stores , organized information. Most databases contain multiple tables, which may each include several different fields. For example, a company database may include tables for products, employees, and financial records.

Many sites uses databases to store information. These sites use a database management system (or DBMS), such as Microsoft Access or MySQL as the “back end” to the website. By storing website data in a database, the data can be easily searched, sorted, and updated. This flexibility is important for e-commerce sites and other types of dynamic websites.

Computer Graphics
Computer graphics deals with generating images with the aid of computers .It is difficult to display an image of any size on the computer screen. This method is simplified by using Computer graphics. Graphics on the computer are produced by using various algorithms and techniques.For creating highly detailed and realistic computer graphics.
applications :gaming engines, entertainment , polygons , fractals.

Solving Real World problems
Optimization
Getting computers to solve real world problems. These technologies underlie a lot of the programs, apps and websites we use. When you are going on vacation and you want to get the best trip for the money you are
solving an optimisation problem. Optimisation problems appear everywhere and finding the best path or most efficient combination of parts can save businesses millions of dollars. This is related to Boolean Satisfiability.

Boolean Satisfiability
Boolean Satisfiability is where you attempt to work out if a logic formula can be satisfied or not. This was the first problem proved to be NP-complete and and so widely considered to be impossible to solve, but amazing development of new SAT solvers means that huge SAT problems are solved routinely today especially in artificial intelligence.


Artificial Intelligence
Computers extend our brains multiply our cognitive abilities. The forefront of computer science research is developing computer systems that can think for themselves: Artificial Intelligence.

There are many avenues that AI research takes, the most prominent of which is machine learning.

Machine Learning
Developing algorithms to enable computer to learn from large amounts of data then use what they have learned to do something useful like making
decision or classify things.There are types of learning which are

Supervised learning : Supervised learning is when the model is getting trained on a labelled dataset. Labelled dataset is one which have both input and output parameters.

Unsupervised learning : Unsupervised learning is the training of machine using information that is neither classified nor labeled and allowing the algorithm to act on that information without guidance.

Reinforcement :Reinforcement learning, in the context of artificial intelligence, is a type of dynamic programming that trains algorithms using a system of reward and punishment. A reinforcement learning algorithm, or agent, learns by interacting with its environment.

Deep Learning
Deep learning is a subset of machine learning which is an Artificial intelligence function that imitates the workings of the human brain in processing data and creating patterns for use in decision making. Deep learning is a subset of machine learning in artificial intelligence (AI) that has networks capable of learning unsupervised from data that is unstructured or unlabeled. Also known as deep neural learning or deep neural network.

Computer Vision
Closely related to machine learning computer vision, trying to make computers able to see objects in images like we do, which uses image processing techniques.

Natural Language processing
Natural language processing aims to get computers to understand and communicate using human language, or to process large amounts of data in the form of words for analysis.This commonly uses another field called knowledge representation where data is organised according to their relationships, like words with similar meanings are clustered together.
Machine learning algorithms have improved because of the large amount of data we give them.

Big data
Big data looks at how to manage and analyse large amounts of data to get value from it. And will get even more data from the Internet of Things, adding data collection and communications to everyday objects.

IOT
The Internet of Things is simply “A network of Internet connected objects able to collect and exchange data.” In a simple way to put it, You have “things” that sense and collect data and send it to the internet.

Computational Science
Computational science uses computers to finding answers of scientific questions from fundamental physics to neuroscience.

Mostly uses super-computing. because of massive calculations.

Simulations. (like in movie Martian where Dr. Rich Purnell simulates optimal trajectory of ‘Ares IV’ using supercomputers.

Human Computer interaction
Human Computer Interaction looks at how to design computer systems to be easy and intuitive to use. Virtual reality, Augmented Reality and Teleprescence enhancing or replacing our experience of reality.


Robotics
Robotics gives computers a physical embodiment, from a roomba to to Sony’s AIBO pet robot dog. Computing technology is an important part of robotics. Computer scientists understand the robotic software platforms and are necessary for researching high-level programming. While mechanical and electrical engineers focus on the hardware aspects of robotics, computer scientists work on the programming side.

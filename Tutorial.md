# An Introduction to Competitive Programming

Competitive programming is a niche branch of programming that tests your algorithmic and implementation skills and it's really fun as if you're playing a game - submitting solutions to problems and getting points for the same.

As you've covered CS101 you have some basic idea of simple algorithms. That idea suffices to solve beginner problems on all websites. It is recommended to use Codeforces and Codechef as they contain problems with solutions of all standards. This [**article**]( https://medium.com/techatucla/introduction-to-competitive-programming-3dca32e5f9a0 ) 
elaborates on the same note.

Regarding which language to use, it is recommended to use C++ as it contains implementations of various algorithms like sorting etc, which makes it faster for you to solve problems. Check [**this**](https://www.topcoder.com/community/competitive-programming/tutorials/power-up-c-with-the-standard-template-library-part-1/) for more information.

### Complexity Theory

Firstly we will begin with Complexity Theory. You can have multiple algorithms that solve a problem, you however we want one that is fast enough to solve the question given the limits. If your algorithm is slow you will get TLE (Time Limit Exceeded). It is also important to write memory efficient codes, which otherwise can lead to MLE (Memory Limit Exceeded)

To get familiar with the concepts, check out [**this link**](https://www.hackerearth.com/practice/basic-programming/complexity-analysis/time-and-space-complexity/tutorial/). In a nutshell your algorithm will be O(f(n)) if it takes roughly f(n) steps (or operations) to complete. If your time limit is *1s* , then you can afford atmost 10<sup>8</sup> operations per second or in other words f(n) has an upper limit of 10<sup>8</sup>.
To delve deeper, refer [**this**](https://www.geeksforgeeks.org/knowing-the-complexity-in-competitive-programming/) and [**this**](https://drive.google.com/file/d/0B-W-TWxgtybGd3dFUzg1OHNsM2M/view?usp=drive_open).

### Basic Ad-Hocs

With that set, let's solve some basic problems that don't require anything but logic. We call these problems 'ad-hoc'. These are probelms on Codeforces, so sign up on codeforces first. And then solve these questions!

* [**1294 A**](https://codeforces.com/contest/1294/problem/A)
* [**1288 A**](https://codeforces.com/contest/1288/problem/A)
* [**1339 A**](https://codeforces.com/contest/1339/problem/A)

This should give you an idea regarding how the judges work and how to solve basic problems. If you get stuck at any point of time click on the tutorial in the bottom right corner and you will get hints and solutions.

### Sorting

I hope you remember merge sort. Sorting can be used to simplifiy a lot of problems. Always use the built in C++ [**sort**](https://www.geeksforgeeks.org/sort-c-stl/) function as it makes life easier for CP. 
You can [**check**](https://www.geeksforgeeks.org/know-sorting-algorithm-set-1-sorting-weapons-used-programming-languages/) this link to know more about sorting algrithms, this is useful for knowledge of algorithms and if you ever want to sit for an interview it's probably essential to know about them. But for questions you do not need to implement it yourself.

Try these out - 

* [**Smart Phone**](https://www.codechef.com/ZCOPRAC/problems/ZCO14003/)
* [**1339 B**](https://codeforces.com/problemset/problem/1339/B)
* [**1334 B**](https://codeforces.com/problemset/problem/1334/B)

### Binary Search

Remember Binary Search? That simple algorithm has many applications with some being extremely tough. Let us start with a recap.  

* [**Hackerearth**](https://www.hackerearth.com/practice/algorithms/searching/binary-search/tutorial/).  
You can solve the problems given here for basics, they have editorials as well. Do a few of these for basic binary search questions.  
The questions given below are relatively harder and you may not be able to do them. Try for some time and then check the tutorial if you can't get them. This will give you an idea regarding the different ways you can apply binary search: 

* [**1336 (Div 1) B**](https://codeforces.com/problemset/problem/1336/B)
* [**CodeJam Round 1B B**](https://codingcompetitions.withgoogle.com/codejam/round/000000000019fef2/00000000002d5b63)  
This is somewhat advanced. But the only thing you need to know to solve is binary search! It is also an interactive problem, where you ask the system questions to determine the solution!. Such problems appear from time to time so you can try this out. The first two subtasks are relatively simpler. If you have a hard time with the third subtask check out the analysis section for the solution.

The above two problems are to give you a taste of how difficult questions can be set up. Don't get disheartened if you can't solve them, it requires lots of practice.   

Let us now get into relatively advanced concepts.

### Dynamic Programming 

To begin with, let us explore Dynamic Programming, often referred to as DP. It is some sort of and optimization over plain recursion. It is like, if you see that your program is calculating some values repeatedly, that exhibits that DP is inherently present in the problem. So, the notion peeps in here, that we store such values to avoid repeated evaluations that will save the execution time of the program.  

As a very basic example, consider the sequence of Fibonacci Numbers. Say, I ask you to find the 10th number, then to evaluate that, you will have to calculate all the preceeding numbers of the sequence (say the 8th one). Now, if I ask you to find the 8th one, you will have to evaluate it again but instead if had stored it already, it could be returned in O(1). So, the idea is to reduce exponential complexities to polynomial complexities.

Try out your hands at a few very basic problems for the same -  

* **[996 A](https://codeforces.com/problemset/problem/996/A)**
* **[1323 A](https://codeforces.com/problemset/problem/1323/A)**
* **[1113 A](https://codeforces.com/problemset/problem/1113/A)**
* **[1206 B](https://codeforces.com/problemset/problem/1206/B)**
* **[1315 B](https://codeforces.com/problemset/problem/1315/B)**   

The last one is relatively tougher. It involves both Binary Search and DP Concepts.

To delve into the details of the concepts, head **[here](https://www.geeksforgeeks.org/dynamic-programming/)**. It contains links to advanced concepts and a multitude of problems.

### Greedy

Funny name, isn't it? It is infact a fun algorithm that just says be greedy xD. You must have encountered a lot of optimisation problems some time or the other. Normally, what you do is to select the best option possible. That is what is suggested by this algorithm that based on a certain parameter of the problem, always select the best option at every step and that is the optimal solution to the problem.

To get a grip over the algo, take a walk through this page - **[Greedy](https://www.geeksforgeeks.org/greedy-algorithms/)**

Let us have soem fun solving the problems based on this concept.  

* **[1287 A](https://codeforces.com/problemset/problem/1287/A)**
* **[1313 A](https://codeforces.com/problemset/problem/1313/A)**
* **[1332 A](https://codeforces.com/problemset/problem/1332/A)**
* **[1325 B](https://codeforces.com/problemset/problem/1325/B)**
* **[1315 B](https://codeforces.com/problemset/problem/1315/B)**
* **[1296 D](https://codeforces.com/problemset/problem/1296/D)**

The last two problems are a bit tougher. The second last one involves three concepts at one go, namely, dp, greedy, binary search. The last involves both sorting and greedy algorithms.   

---

Let us now get into some of the data structures commonly used in Competitive Programming. :)

## DATA STRUCTURES

Learning algorithms is not enough. How do you even store data? Playing around with data requires some sort of structures where you can store data and manipulate it as per needs. So, there comes in the data structures. There serve as the framework for the code that you write. Till now you have used only arrays and must have seen that you have to declare the size of the array before hand, that is not really the case with the data structures that we talk about now.

### Vector

Vector is almost the same as an array, with the only difference being that is of infinite size. They can be referred to as Dynamic Arrays. They are stored as continuous storage and so they can be accessed using indexes. To dive into the functions of a vector in C++ STL, head **[here](https://www.geeksforgeeks.org/vector-in-cpp-stl/)**.

### Stacks

Stack is a linear data structure that maintains the LIFO (Last In - First Out) order of the elements. What it means is that the element that enters the stack first can exit the first. It is analogous the a stack of books, where in you can remove only the topmost book first. To delve into the details of the stack data structure, head **[here](https://www.geeksforgeeks.org/stack-data-structure/)**.   
Read this **[article](https://www.geeksforgeeks.org/stack-in-cpp-stl/)** for the C++ STL Stack.  

Go through these to see some standard applications of stacks:  
* **[Prefix-Infix Conversion](https://www.geeksforgeeks.org/prefix-infix-conversion/)**
* **[Next Greater](https://www.geeksforgeeks.org/next-greater-element/)**
* **[Balanced Parenthesis](https://www.geeksforgeeks.org/check-for-balanced-parentheses-in-an-expression/)**

### Queue

Queues and stacks are similar kind of data structures but with a slight difference in the way they maintain the order of the elements. Unlike Stack, where LIFO is maintained, queues maintain FIFO (First In - First Out). It means that the element which enters first will exit first. It can be thought of any sort of a queue in real life too where the person standing in the front of the line is the one who exits first. To get into the details of the queue data structure, head **[here](https://www.geeksforgeeks.org/queue-data-structure/)**.  
Read this **[article](https://www.geeksforgeeks.org/queue-cpp-stl/)** for the C++ STL Queue.

Go through these to see some operations and standard problems related to queues:  
* **[Reverse](https://www.geeksforgeeks.org/reversing-a-queue/)**
* **[Reverse-Recursion](https://www.geeksforgeeks.org/reversing-queue-using-recursion/)**
* **[Largest Multiple](https://www.geeksforgeeks.org/find-the-largest-number-multiple-of-3/)*


Try out your hands at these implementation problems related to Stacks and Queues:  
* **[Stack using Queue](https://www.geeksforgeeks.org/implement-stack-using-queue/)**
* **[Queue using Stack](https://www.geeksforgeeks.org/queue-using-stacks/)**  

Solve these problems based on Stacks and Queues: 
* **[Monk's Love for Food](https://www.hackerearth.com/challenges/competitive/code-monk-stacks-queues/algorithm/monks-love-for-food/)**
* **[Power of Time](https://www.hackerearth.com/challenges/competitive/code-monk-stacks-queues/algorithm/monks-love-for-food/)**

It is important to note that stacks and queues by default are not stored in continuous memory locations, so they can't be accessed using indexes. They have to be traversed using what are called **[iterators](https://www.geeksforgeeks.org/iterators-c-stl/)**.

Stacks and Queues have some really cool applications in graph theory, which we will go through in the next section. So, basically the thing is it is upto your intellect to decide when and where it is benefical to use stacks or queues or going by the basic array/vector is better. At times, it is easier to solve a problem using vector than actualy using a queue or a stack. But don't worry, you will be able to figure that out with practice.  

---

## GRAPHS 


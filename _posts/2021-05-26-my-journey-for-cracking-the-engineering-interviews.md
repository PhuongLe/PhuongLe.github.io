---
tags:
    - technical-interview-prep
    - engineering-interview-experiences

classes: wide
---


I had a CS background, several years working on both engineering and management roles back in my home country, Vietnam, before taking my master's degree in applied science at UBC, Canada. After finishing my study and weighing up and down my strengths, weaknesses, as well as my own passion thoroughly, I decided to target applying to big tech companies as a senior software engineer (frankly speaking, it’s just the starting point for an experienced developer). That’s when I started my journey to prepare for cracking the technical interview.

With that in mind, I spent 2 weeks on Google “how to crack the technical interview” to get inspired and collect resources that worked best for my time. There are tons of useful posts, and even there are fruitful guidelines from the companies themselves. Below are my most favorite references.
- **John Washam** - ["why I studied full-time for 8 months for a Google interview"](https://www.freecodecamp.org/news/why-i-studied-full-time-for-8-months-for-a-google-interview-cc662ce9bb13/): His incredible effort on getting out of the comfort zone to pursue his dream  job at his age inspired me a lot.
- **James Le** - [“technical-interview-prep”](https://github.com/khanhnamle1994/technical-interview-prep): His straightforward and well-structured repository just simply came to me at the right time. Personally, I think it is a good starting point.
- **Nick Ciubotariu** - ["Ace the coding interview, every time"](https://medium.com/@nick.ciubotariu/ace-the-coding-interview-every-time-d169ce1fd3fc): This article presents a complete guideline for the entire preparation process to crush the final stage.

> Disclaimer: This post does not reveal any specific details that I got in my interview sessions, and it does not represent any company’s specific position.

Actually, I am not always the winner. I failed in some matches before finding my dream job. Getting through the storm of the new journey, I found some lessons which I wish I would know sooner. Therefore, this post is not about how to crack an engineering interview, but primarily  is to write down my own interview preparation for later reference, and hopefully, it could help those who share the same target.

## Language
- At first, I thought that language did not matter, so I started with my favorite language, C#. However, the first online test invitation came to me with a request of using any modern language but C# :)). I was a bit shocked as regards my research, most big tech companies do not look for any specific programming language in a candidate for hire. Luckily, I could easily switch to use Java as it is almost the same as C#. All I need is to learn its data structure in advance and try to master it within a week to be able to write it fast in an interview. 
- The most popular languages used in online coding practice platforms I have seen so far are Python, C++, or Java. If you don’t have a strong preference, I would recommend using a scripted language like Python to utilizing its flexible data structure and short syntax. Otherwise, go with your most comfortable language since trying a new language in an interview is a risk.

## Preparation plan
The entire preparation took me more than 3 full-time months  divided into 3 primary phases.

### Phase 1 - Early preparation
I spent the whole 1st month on data structure and algorithm to wake up my coding skill and partially get ready for a coding challenge by studying basic concepts step by step, in order, as below.
- **Sorting algorithm**:  I kicked off my study plan with the basic sorting algorithms, tried to implement them from scratch, and mastered 3 basic sort algorithms and the 3 most popular ones: bubble sort, selection sort, insertion sort, heap sort, merge sort, quicksort.
- **Big-O notation**: After having a sense of sorting algorithms, it seems easier for me to grasp the idea of Big-O notation (plus Theta, Omega notation). It is important to understand how to calculate time and space complexity before diving into a data structure or algorithm.
- **Data structure**: As data structure is the basic thing to solve a problem, it is better to memorize the frequently used data structures of the preferred language to write code quickly and precisely in the interview. 
- **Algorithms**: After getting familiar with all the commonly used data structures, I tried to get familiar with some popular algorithms on Leetcode before spreading my resume. 

### Phase 2 - First interview rounds
A hiring process usually starts with a recruiting round, online testing round, etc., mostly focusing on general background questions and simple technical challenges. It took me about 2 to 4 weeks to get the 1st call from the recruiter, so I continued my study plan as follows while waiting.
- **Algorithms**: I kept practicing coding with more specific questions set on Leetcode.
- **Behavior/Engineering questions**: I also started looking back at my past work experiences, connecting the big and small events in my working life with the leadership principles. As far as I can see, these questions are as important as any other challenges. It is even more critical in some companies.

### Phase 3 - Onsite interviews loop
Usually, a company will give you 2 to 3 weeks to prepare for the final stage. 
- **Algorithms**: I kept practicing algorithms 1-2 hours a day to maintain the algorithm-driven coding sense.
- **System design**: Luckily, one of the tech courses in my master's program was about fault tolerance in computer systems, so I was quite familiar with CAP theory in designing a scalable system.  All I needed was to redraw an overview picture of system design requirements. To be clear, there is definitely still plenty of room for me to learn about system design, I just tried to rush up my time for the interview at that time. Frankly speaking, I think it would be a lot better if I did it sooner.

### Phase 4 - On the day
I tried to take my mind off all the methods, let the instinct lead me through the problem-solving challenges.

## Detailed resources 
### Data structure 
I studied those following DS in order of priority as below.
- **Basic collection types**: Array, List, Queue, Stack, Hash Set, 
- **Hash Map (Hash Table)**: I got so many Hashing/Hash Map questions, in both coding and system design assignments. It is important to understand the advantages/disadvantages of hash and how to solve the hash collision problem.
- **Tree, Graph**: I saw it on coding assignments of all companies I applied to.
- **Bit, linked list, LinkedHashMap, Heap**

It is important to understand the time/space complexity of its basic operations (CRUD). In addition, it is great to dive into the advantages/disadvantages of its implementation. For example, to implement a stack on Java, should we use [Stack or ArrayDeque](https://stackoverflow.com/questions/12524826/why-should-i-use-deque-over-stack)?

**References**
Time-wise, I took a short course "[Introduction to Data Structures & Algorithms in Java](https://www.udemy.com/course/introduction-to-data-structures-algorithms-in-java/#/%29)" on Udemy to grab all the useful ds in Java shortly. 


### Coding challenges/Algorithms
- Coding assignments for the first rounds are usually algorithm-driven questions.
- If there are 3 coding assignments on one loop, they will usually be all different. From my point of view, I can divide them into 3 following types. (Disclaimer: it is just my own observation that is not stated by any company)
    - Algorithmic assignment: It is constructed as a straightforward algorithmic challenge. It is used to evaluate how well the candidates apply DS and Algo.
    - Object-oriented principle (OOP) design assignment: This session is to give the candidates a chance to show their OOP design skills.
    - Problem-solving assignment: It will be started with a vague problem. The candidates should employ their communication/analysis skill to reshape it into a simple problem which is now almost similar to an algorithmic assignment.
- What to study, in priority
    - BFS/DFS
    - OOP Design
    - Merge sort, quick sort, heap sort
    - Back tracking
    - Dynamic programming
    - Slicing windows / K-way merger / Merge intervals / Sub-set / Two pointers / Fast-slow pointers / etc.

**References**
- **Leetcode**: I highly recommend using Leetcode premium for practice. It is easy to keep track of the progress with their well-structured practice collections. I did the following curated questions step by step.
    - Easy collection
    - Medium collection
    - Company-specific collection
- **AlgoExpert**: Although I did not try it yet, I have heard good recommendations for AlgoExper and I am also quite interested in some videos of TechLead guy
    - [Top 10 Algorithms for the Coding Interview](https://www.youtube.com/watch?v=r1MXwyiGi_U)
    - [What no one tells you about coding interviews (why leetcode doesn't work)](https://www.youtube.com/watch?v=LQFsEwcCO1E)
    - [Mock Google interview (for Software Engineer job)](https://www.youtube.com/watch?v=IWvbPIYQPFM)
- [**Grokking the Coding Interview: Patterns for Coding Questions**](https://www.educative.io/courses/grokking-the-coding-interview): I was getting into how this course categorized the solutions and its approach to solve complex problems by common patterns.

**Mock test**
Although I have heard a lot about the useful mock test services, I have tried mock tests in Leetcode only. 

### System design
Depending on the level you are being interviewed for, the complexity required for the system design challenge will be different as below (again, it is just my personal observation).
- Focusing on DB schema, API design
- Focusing on fault tolerant, consistent or availability design for a small application
- Focusing on only read or write process of a large scalable system
- Focusing on the entire part of a scalable system.

**References**
I did my best to familiarize myself with various system design paradigms/terminologies. 
- [**Gaurav Sen’s Youtube channel**](https://www.youtube.com/watch?v=xpDnVSmNFX0&t=10s): Although there are few errors in his videos, I was inspired by his enthusiasm and energy. His straightforward and informative lessons are well suited for hearing and watching learners.
- [**Grokking the System Design Interview**](https://www.educative.io/courses/grokking-the-system-design-interview): This course has an overall picture of all the small pieces of a system design concept.  In addition, its diverse samples seem to cover all the possible questions I have seen so far.
- Youtube: I tried to watch the system design mock test samples as much as possible to have different points of view about system design.
- Some videos of TechLead guys are also interesting
    - [Systems Design Interview Concepts (for software engineers / full-stack web)](https://www.youtube.com/watch?v=REB_eGHK_P4)
    - [Software Design Patterns and Principles (quick overview)](https://www.youtube.com/watch?v=WV2Ed1QTst8&t=523s)

***General questions/behavioral questions***
- I called it general questions as it would vary depending on companies. Some companies focus mostly on leadership principles. The others would prefer to dive into engineering fundamentals deeply. However, the backbone of those questions is to let the interviewee demonstrate two skills: leadership and problem-solving skills. The more you can deep dive into the story, the better. Especially if your story is about a technical solution, you should have a clear reason why you did it that way, and if it was not a good solution, you should propose a better solution. Additionally, providing specific numbers or technologies that were used is a plus.
- This is also a chance for interviewees to demonstrate their knowledge about software engineering through your stories, so I tried to refresh some basic concepts used in my technical stories, such as race condition, concurrency vs. parallelism, webRTC, etc.

All in all, the outcome can be positive or negative, which may depend on various aspects. If it was not good, do not panic, but try to learn from it. Have patience, respect and always strive to be a better version of yourself. Keep fighting, and good luck!
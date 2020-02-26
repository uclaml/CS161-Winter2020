
## Overview
This course introduces the design of intelligent agents, including the fundamental problem-solving and knowledge-representation paradigms of artificial intelligence. Topics to be covered include the AI programming language LISP, state-space and problem reduction methods, brute-force and heuristic search, two-player games, and recent developments in game AI. For knowledge representation and reasoning, we will cover propositional and first-order logic and their inference algorithms. Finally, the course covers probabilistic approaches to AI, such as Bayesian networks to improve the agent’s performance with experience.
## Prerequisites
This course requires knowledge of basic computer science, algorithms and complexity (CS180), and programming principles.
## Logistics
<!--University of California, Los Angeles  -->
- Time: **Monday and Wednesday 4:00PM - 5:50PM**
- Location: **FRANZ 1178**  
- Instructor: [Quanquan Gu](http://web.cs.ucla.edu/~qgu/) (Email: qgu at cs dot ucla dot edu)   
- Teaching Assistant: 
    - Shirley Chen (Email: shirleychen at cs dot ucla dot edu)
    - [Yewen Wang](https://sites.google.com/view/wyw10804/home/win20cs161?authuser=0) (Email: wyw10804 at cs dot ucla dot edu)
    - [Chi Zhang](http://web.cs.ucla.edu/~zccc/cs161.html) (Email: zccc at cs dot ucla dot edu)
    - [Dongruo Zhou](https://sites.google.com/view/drzhou) (Email: drzhou at cd dot ucla dot edu)
- Office hours: 
    - The instructor's office hour is Thursday 1:30pm-2:30pm at Engineering VI 282. 
    - The TA's office hour is: 
        - Yewen Wang, Monday 9:00am-11:00am at Bolter Hall 3256S-A
        - Dongruo Zhou, Tuesday 15:00pm-17:00pm at Bolter Hall 3256S-A
        - Shirley Chen, Wednesday 11:00am-1:00pm at Bolter Hall 3256S-B
        - Chi Zhang, Thursday 9:00am-11:00am at Bolter Hall 3256S-A.
- Course Website: [https://uclaml.github.io/CS161-Winter2020/](https://uclaml.github.io/CS161-Winter2020/)
- Course Forum: [https://piazza.com/ucla/winter2020/cs161/home](https://piazza.com/ucla/winter2020/cs161/home)
(If you haven’t already, [sign up here](piazza.com/ucla/winter2020/cs161).)

## Grading Policy
 
Grades will be computed based on the following factors:
- Homework 20%
- Midterm 35%
- Final 45%

## Schedule


| # | Date | Topics | Reading | Homework |
| - | ---- | ------ | ------- | -------- |
| 1 | 1/6 | [About Course](https://www.dropbox.com/s/narnejmu9t4lxzl/Lecture0.pdf?dl=0), [Introduction: What is AI?](https://www.dropbox.com/s/un41l1tbcwryhcp/1-intro.pptx?dl=0) | Chapter 1,2 | |
| 2 | 1/8 | [LISP](https://www.dropbox.com/s/i8zfup6vyg7slz9/Lecture02.pptx?dl=0) | | |
| 3 | 1/13 | [Problem solving as search & Uninformed search strategies](https://www.dropbox.com/s/u7pk97puanbk219/Lecture3.pdf?dl=0) | Chapter 3 | |
| 4 | 1/15 | [Informed search strategies](https://www.dropbox.com/s/vksvsdc1t4b6s3q/Lecture4.pdf?dl=0) | Chapter 3 | HW1 Out |
| | 1/20 | Martin Luther King, Jr. holiday | | |
| 5 | 1/22 | [Informed search strategies](https://www.dropbox.com/s/vksvsdc1t4b6s3q/Lecture4.pdf?dl=0), [Local Search Algorithms](https://www.dropbox.com/s/6orvbrpv3bm6dtw/Lecture5.pdf?dl=0)| Chapter 3,4,11 | HW1 Due, HW2 Out |
| 6 | 1/27 | [Local Search Algorithms](https://www.dropbox.com/s/6orvbrpv3bm6dtw/Lecture5.pdf?dl=0) | Chapter 4 | |
| 7 | 1/29 | [Constraint satisfaction](https://www.dropbox.com/s/rx2zq0wgjy7c7hm/Lecture6.pdf?dl=0) | Chapter 6 | |
| 8 | 2/3 | [Constraint satisfaction](https://www.dropbox.com/s/rx2zq0wgjy7c7hm/Lecture6.pdf?dl=0) | Chapter 6 | HW2 Due, HW3 Out |
| 9 | 2/5 | [Constraint satisfaction](https://www.dropbox.com/s/rx2zq0wgjy7c7hm/Lecture6.pdf?dl=0) | Chapter 6 | |
| 10 | 2/10 | [Game playing](https://www.dropbox.com/s/1h9scrlorvdmnpf/Lecture7.pdf?dl=0) | Chapter 5 | |
| 11 | 2/12 | [Game playing](https://www.dropbox.com/s/1h9scrlorvdmnpf/Lecture7.pdf?dl=0) | Chapter 5 | HW3 Due, Hw4 Out |
| | 2/17 | President's Day | | |
| 12 | 2/19 | [Propositional logic](https://www.dropbox.com/s/7uevivcb05kwmt6/Lecture8.pdf?dl=0) | Chapter 7 | |
| | 2/24 | [Midterm Exam](https://www.dropbox.com/s/lhk376z72t6acfy/CS161%20Study%20Guide.docx?dl=0) | | |
| 13 | 2/26 | [Propositional logic](https://www.dropbox.com/s/7uevivcb05kwmt6/Lecture8.pdf?dl=0) | Chapter 7 | HW5 Out |
| 14 | 3/2 | First-order logic | Chapter 9 | HW4 Due |
| 15 | 3/4 | Reasoning under uncertainty | Chapter 13 | HW6 Out |
| 16 | 3/9 | Bayesian Networks | Chapter 14 | HW5 Due |
| 17 | 3/11 | Bayesian Networks | Chapter 14 | |
| | 3/16 |  | | HW6 Due |
| | 3/20 | Final Exam | | |

## Academic Integrity Policy
Students are encouraged to read the [UCLA Student Conduct Code](https://www.deanofstudents.ucla.edu/Individual-Student-Code) for Academic Integrity. 

## Homework
There will be about 6 homework assignments during the semester as we cover the corresponding material. Homework consists of both problem solving and LISP programming. The lowest homework score will be dropped for you.

Unless otherwise indicated, you may talk to other students about the homework problems but each student must hand in their own answers and write their own code in the programming part. You also must indicate on each homework with whom you collaborated and cite any other sources you use including Internet websites. Students should never see another student's solution before submitting their own. Students cannot use old solution sets for this class or solution manual to the textbook under any circumstances.Homework assignments will be submitted through CCLE/Gradescope. 

Please submit your homework on time. Homework is worth full credit before the due date. It is worth zero credit after the due date.

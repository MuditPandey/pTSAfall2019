##  timeseries2019
#  DS-GA 3001.001 Special Topics in Data Science: Probabilistic Time Series Analysis

### Lecture 
Mo, 2:00-3:40pm, in 60 5th Av, C10

### Lab (required for all students)
Thu, 6.45- 7.35pm in  60 5th Av, C12

###  Instructor 
Cristina Savin, csavin@nyu.edu
Office hours: Mo, 4:00-5:00pm, Room 608

### TA 
Caroline Haimerl, ch2880@nyu.edu
Yiqiu (Artie) Shen, ys1001@nyu.edu
Office hours: 

### Overview
This graduate level course presents fundamental tools for characterizing data with statistical dependencies over time, and using this knowledge for predicting future outcomes. These methods have broad applications from econometrics to neuroscience.The course emphasizes generative models for time series, and inference and learning in such models. We will cover range of approaches including Kalman Filter, HMMs, AR(I)MA, Gaussian Processes,  and their application to several kinds of data.

Note: information presented is tentative, syllabus may be subject to change as course progresses.

### Grading
problem sets (25%) + midterm exam (25%) + final project (25%) + lab(20%)+participation(5%)

Participation: piazza, engagement during lectures, labs, and office hours

### Piazza 
We will usePiazzafor announcements, and discussions about the course. Interactions on Piazza, particularly good answers to other students' questions, will count toward the participation grade.

### Projects
Work in groups of 2-3 students.* Topics are flexible, including applying know algorithms to an interesting dataset, reviewing and implementing a state of the art solution, to improving an existing algorithm. Project proposals due in week 4. *Check with CS if you are considering working individually or in a larger group.

### Online recordings 
Lecture videos will be posted to NYU Classes. Class attendance is still required.

## Schedule and detailed syllabus

| Date | Lecture  | Extras | |
|----------|---------------|----------------|----------------|
|Jan.23| [Lecture 1: Logistics. Introduction.  Basic statistics for characterizing time series.](https://github.com/charlieblue17/timeseries2018/blob/master/slides/lecture1.pdf) | [Shumway Stoffer Ch.1](http://www.stat.pitt.edu/stoffer/tsa4/) | |
|Jan.25| [Lab1: Simulating simple stochastic processes. Basic statistics.](https://github.com/charlieblue17/timeseries2018/blob/master/lab/week1/lab-week-1.pdf) | | |
|Jan.30| [Lecture 2: AR(I)MA](https://github.com/charlieblue17/timeseries2018/blob/master/slides/lecture2.pdf) | [Shumway Stoffer Ch.3](http://www.stat.pitt.edu/stoffer/tsa4/) | |
|Febr.1| [Lab 2: AR(I)MA](https://github.com/charlieblue17/timeseries2018/tree/master/lab/week2) | | [Problem set 1](https://github.com/charlieblue17/timeseries2018/blob/master/homeworks/hw1.pdf), [solution](https://github.com/charlieblue17/timeseries2018/blob/master/homeworks/hw1_solution.pdf), due Febr. 12 |
|Febr.6| [Lecture 3: LDS; Kalman filtering](https://github.com/charlieblue17/timeseries2018/blob/master/slides/lecture3.pdf) | [kalmanderivations.pdf](https://github.com/charlieblue17/timeseries2018/blob/master/handouts/kalmanderivations.pdf) | Brainstorm project ideas |
|Febr.8| [Lab 3: Basic probability review. LDS inference](https://github.com/charlieblue17/timeseries2018/blob/master/lab/Lab3.pdf) | | [Project proposal](https://github.com/charlieblue17/timeseries2018/blob/master/handouts/projectproposal.pdf) due Febr. 27 |
|Febr.13 |[Lecture 4: EM. Particle filtering](https://github.com/charlieblue17/timeseries2018/blob/master/slides/lecture4.pdf) | [LDSlearning.pdf](https://github.com/charlieblue17/timeseries2018/blob/master/handouts/LDSlearning.pdf), [particlefiltering.pdf](https://github.com/charlieblue17/timeseries2018/blob/master/handouts/particlefiltering.pdf) | |
|Febr.15 |[Lab 4: LSD learning](https://github.com/charlieblue17/timeseries2018/blob/master/lab/week4/lab-week-4.pdf)  | |  |
|Febr.20 |[Lecture 5: HMMs](https://github.com/charlieblue17/timeseries2018/blob/master/slides/lecture5.pdf) | [hmm.pdf](https://github.com/charlieblue17/timeseries2018/blob/master/handouts/hmm.pdf) | [Problem set 2](https://github.com/charlieblue17/timeseries2018/blob/master/homeworks/hw2.pdf), due March 2|
|Febr.22| Lab 5: HMMs | | [Problem set 3](https://github.com/charlieblue17/timeseries2018/blob/master/homeworks/hw3.pdf), due March 30 |
|Febr.27 | Lecture 6: An unified view of linear models. Beyond linear. | Roweis and Ghahramani, 1999 |
|March 1 | Lab 6: Revisiting ARIMA, focus on applications | arima.pdf |
|March 6 | Midterm | | |
|March 8 | No lab | | |
|March 20| Guest lecture: State space models in the brain, Il Memming Park| email CS for slides| |
|March 22| No lab | | |
|March 27 | [Lecture 8: GP basics](https://github.com/charlieblue17/timeseries2018/blob/master/slides/lecture8.pdf) | | |
|March 29 | Lab: GP  | | |
|April 3 | [Lecture 9: RNNs (Kyunghyun Cho)](https://github.com/charlieblue17/timeseries2018/blob/master/slides/rnn_timeseries.pptx) | | |
|April 5| Projects status discussion | | |
|April 12| Lab: GP || [Problem set 4](https://github.com/charlieblue17/timeseries2018/blob/master/homeworks/hw4.pdf), due April 26th |
|April 17| [Lecture 10: Sparse GP methods](https://github.com/charlieblue17/timeseries2018/blob/master/slides/lecture10.pdf)|||
|April 19| Lab | no lab ||
|April 24| Lecture 11: Spectral methods |||
|April 26| Lab: Spectral methods |||
|May 1| Projects presentation | [Instructions](https://github.com/charlieblue17/timeseries2018/blob/master/project/projectwriteup.pdf) | Final reports due May 8th!|


### Bibliography
There is no required textbook. Assigned readings will come from freely-available online material.

#### Core materials
- Time series analysis and its applications, by Shumway and Stoffer, 4th edition
- Pattern recognition and machine learning, Bishop
- Gaussian processes Rassmussen & Williams

#### Useful extras
 - [Review notes from Stanford's machine learning class](http://cs229.stanford.edu/section/cs229-prob.pdf)
 - Sam Roweis's [probability review](http://cs.nyu.edu/%7Edsontag/courses/ml12/notes/probx.pdf)
 - [Carlos Ferndandez's notes on Statistics and Probability for Data Science DS-GA 1002](http://www.cims.nyu.edu/~cfgranda/pages/stuff/probability_stats_for_DS.pdf) 

### Academic honesty

We expect you to try solving each problem set on your own. However, if  stuck  you should discuss things with other students in the class, subject to the following rules:
  - Brainstorming and verbally discussing the problem with other colleagues ok, going together through possible solutions, but should not involve one student telling another a complete solution.
  - Once you solve the homework, you must write up your solutions on your own.
  - You must write down the names of any person with whom you discussed it. This will not affect your grade.
  - Do not consult other people's solutions from similar courses.

#### *Policies*
Try to solve problems on your own first. If you get stuck, you can discuss homework questions with colleagues, but you need to write up the final solution individually.  Credit should be explicitly given for any code you use that you did not write yourselves.Late submission penalties: 20% points off for each extra day of delay.

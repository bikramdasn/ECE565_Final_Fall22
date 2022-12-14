# A Deadlock Control For Interprocess Communication Using Petri Nets

## Introduction
This project represents a petri net model to avoid race conditions including a solution for critical region and deadlock problem. Deadlock control and mutual exclusion is important for an automated system. In this project we are using a printer as an example of two processors sharing a common storage which is a part of main memory file. Petri net will be used for modeling the system to make it simple to understand the race condition and to find out the deadlock or interlock in critical state. A methodology is proposed here for mutual exclusion and to prevent the deadlock condition. We tried to improve the availability of the printer which improve the output rate of the processors. Illustrations are made to compare the performance of the processors and the printer’s availability.

![alt text](https://github.com/bikramdasn/ECE565_Final_Fall22/blob/main/Images/generalized%20picture%20of%20multiple%20computers%20are%20connected%20to%20printer.png)

## Race condition, Critical region and Deadlock
When two processor or computer try to work parallelly they create a race condition. In print spooler directory file name can be overlapped. Two computers or processes trying to access the same shared memory location at the same time enters a critical region. Also, in a situation where file name can be overlapped like the print spooler directory, one processor or computer will never get a result, this leads to a deadlock condition. 

![alt text](https://github.com/bikramdasn/ECE565_Final_Fall22/blob/main/Images/Critical%20region%20and%20Deadlock.png)

## SPN model
Stochastic petri net is used to model our system. Petri net is a bipartite graph with two subset Place and Transitions. Places holds the token which represent the job available in the system. Transition fire the tokens from one place to another place when it enable to fire. 

![alt text](https://github.com/bikramdasn/ECE565_Final_Fall22/blob/main/Images/spn%20model.png)

### Deadlock 
![alt text](https://github.com/bikramdasn/ECE565_Final_Fall22/blob/main/Images/Deadlock.png)
### Deadlock Free System 
![alt text](https://github.com/bikramdasn/ECE565_Final_Fall22/blob/main/Images/Deadlock%20Free.png)

## Video Explantion
[![Watch the video](https://cdn.pixabay.com/photo/2013/07/13/11/45/play-158609_960_720.png)](https://drive.google.com/file/d/1TQXTuBhMQ37LNe1RFKKyyj6Cs3ZPRzBl/view)

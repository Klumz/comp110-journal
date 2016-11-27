# comp110-journal

### [1] When does a physical system compute?
This paper explains when a physical system computes and goes in depth on how abstract and physical entities go in conjunction by using the "representation relation" and generally physics/science. In terms of representation relation, the paper states: "...it is how physics works. This relation is how we can write down |ψ and think that we are talking about an electron or a hydrogen atom or a Bose–Einstein condensate. Every time we use something abstract to represent something physical, we use a representation relation". 
Additionally, the paper describes the distinction between abstract processes and physical objects, as well as the different input and output effects they provide. 

#### Quote:

"This is how we can escape from falling into the trap of ‘everything is information’ or ‘the universe is a computer’: a system may potentially be a computer, but without an encode and a decode step it is just a physical system."
- From what I understood, this states that a physical system only computes assuming it is encoding and decoding abstract data and programs, and only when it is executing this form of action. 

### [2] Experimental Investigations of the Utility of Detailed Flowcharts in Programming:
In this paper, Ben Shneiderman, Richard Mayer, Don McKay and Peter Heller have set up a total of five deliberate experiments in order to determine the advantages and disadvantages of using flowcharts in improving programming composition, comprehension, debugging and modification, as well as finalising and discussing the results. The experiments were conducted with the use of "subjects", basically meaning various groups of university students. As a result of this, the paper ultimately concluded two things; detailed flowcharts are superfluous presentations of the information contained in programming language statements, as mentioned in the following quote: "We conjecture that detailed flowcharts are merely a redundant presentation of the information contained in the programming language statements. The flowcharts may even be at a disadvantage because they are not as complete (omitting declarations, statement labels, and input/output formats) and require many more pages than do the concise programming language statements." Lastly, it was also concluded that the experiments did not provide the utility and benefits of detailed flowcharts in program composition, comprehension, debugging or modification, resulting in further work needing to be done in order to analyse and understand other areas where flowcharts may be useful. 

#### Quote:

"She feels the flowchart is "an essential tool in problem solving" and states, "The person who cannot flowchart cannot anticipate a problem, analyze the problem, plan the solution, or solve the problem.""
- A bold statement, and I don't feel like this is necessarily true. While flowcharts do provide clear paths and visualisation, I don't believe they are as vital as mentioned. Especially when it comes to programming, one can't always expect and predict problems that arise based on flowcharts alone. 


### [3] A Fast Procedure for Computing the Distance Between Complex Objects in Three-Dimensional Space

This paper demonstrates and presents to us an algorithm for calculating the Euclidean distance (the length of a shortest line segment
joining the two objects) between two objects in any Rn dimensions. When used, it is stated that the algorithm is particularly designed to be a faster and more efficient way of determining objects in three-dimensional space. 

Note: As expected, this paper involved an extensive amount of math in it, resulting in it being harder to understand. 

#### Quote:
"It applies to a complex family of shape models and is particularly convenient when the objects are subject to changes in position and orientation."
- This appears to be a practical application for something like video games, among others. 


### [4] Letters to the Editor: Go To Statement Considered Harmful

This paper contained a considerable number of letters to an editor where programming related discussions were tackled. Various programming ideas and approaches were discussed and opinionated. One of the first letters in the paper was written by Edsger W. Dijkstra, where he stated his displeasure on the go to statement and how it should be abolished from all "higher level" programming languages -- except, perhaps, plain machine code. Regarding Dijkstra's major issue with the go to statement - if I understood it correctly -, I believe he was stressing the difficulty of "finding a meaningful set of coordinates in which to describe the process progress", meaning that determining the state of the process would be proven difficult. After reading the paper, I learned that the "go to" statement meant to forward the user to a different line of code. While it may seem like an easy and practical way of moving around, I also later realised that it is considered bad practice to use excessively as it results in messy and disorganised code in the long run (for example, it becomes considerably harder to debug the code as the programmer has to follow it every time as it jumps between different lines) - otherwise also known as "spaghetti code". 

#### Quotes:
"The go to statement as it stands is just too primitive; it is too much an invitation to make a mess of one's program. One can regard and appreciate the clauses considered as bridling its use. I do not claim that the clauses mentioned are exhaustive in the sense that/hey will satisfy all needs, but whatever clauses are suggested (e.g. abortion clauses) they should satisfy the requirement that a programmer independent coordinate system can be maintained to describe the process in a helpful and manageable way."

"Mooers' policy, which applies in academic institutions as well as commercial users, includes "authorized use of the algorithm and primitives of a specific TRAC language; authorization for experimentation with the language..." I think that this attempt to protect a language and its software by controlling the name is very ill-advised."

"I believe that this doctrine of autonomous standardization and trademark identification is a long step forward in service to the user public, and thus is in the right direction. According to the almost uniformly favorable response we have received to date, many others seem to think the same way. I expect to see the doctrine have wide application." - Mr. Mooer's reply

### Correlation between the four papers:
From what I gathered, the first paper establishes the whole idea of determining how and when a physical system computes with the aid of numerous theories including physics and science. This paper in a way "initialises" the discussion between the linkage of it and the three other papers that were provided, working as a "skeleton" of some form. The second paper demonstrates and explores the usage of flowcharts, analyses their potential and discusses the visualisation they provide when determining the computational flow of a program's process which can indicate if a program is running/computing. The third paper, on the other hand, is uncertain. I will guess that it takes into consideration and emphasises the importance of optimising the distance between complex objects in 3D space, or generally programs, which goes hand in hand with the fourth paper. The fourth paper highlights the concern the go to statement brings in the long run. It states how the statement has the potential to enforce unoptimisation in one's program overtime, which contradicts the third paper. Overall, all four papers in some way complement yet at the same time contradict each other. They all bring up computing-related topics and processes that ultimately connect, such as analysing the abstract nature of computing/programs and applying them to flowcharts, which thereafter leads to implementing and optimising them in order to avoid creating an incomprehensible mess of a program. 


### References:
[1] Horsman, Clare and Stepney, Susan and Wagner, Rob C. and Kendon, Viv (2014) "When does a physical system compute?", Proceedings of the Royal Society A: mathematical, physical and engineering sciences., 470 (2169). p. 20140182.

[2] Ben Shneiderman, Richard Mayer, Don McKay, and Peter Heller. 1977. "Experimental investigations of the utility of detailed flowcharts in programming", Commun. ACM 20, 6 (June 1977), p. 373-381. 

[3] E. G. Gilbert, D. W. Johnson and S. S. Keerthi, "A fast procedure for computing the distance between complex objects in three-dimensional space," in IEEE Journal on Robotics and Automation, vol. 4, no. 2, pp. 193-203, Apr 1988.

[4] Edsger W. Dijkstra, 1968, "Letters to the editor: go to statement considered harmful", Commun. ACM 11, 3 (March 1968), p. 147-148.

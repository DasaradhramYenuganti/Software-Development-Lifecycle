- **TMTOWTDI** — there's more than one way to do it
    - There may be many different solutions that can be applied to your specific problem. The most popular solution is always good to consider, but it should not limit the designer's view

# 🔹 Design
## 1. Software Design: Introduction

1. Software design is the process of transforming the stated problem into a ready-to-use implementation.

    - [x] False
    - [ ] True
    > The product of software design is not an actual implementation, but rather a full description of the solution, which can then be used by the code development team.

2. Abstract solutions do not require extensive domain knowledge and effectively reduce the costs during the software design phase.

    - [ ] True
    
    > Domain knowledge is the first and most fundamental necessity in order to achieve quality results during software design (including abstract solutions!).
    
    - [x] False
    
3. It is often advised that abstract solutions do not provide optimization details regarding the implementation.

    - [x] True
    - [ ] False
    
4. When it comes to software design, it is always best to follow a solution that is widely popular in the industry

    - [x] False
    - [ ] True
    
    > **TMTOWDTI** (there's more than one way to do it)!!! There may be many different solutions that can be applied to your specific problem. The most popular solution is always good to consider, but it should not limit the designer's view
    
5. While a solution coming from software design does not include implementation details, there are still common cases where pseudocode may be provided to correctly capture the sense of a complex algorithm.

    - [x] True
    - [ ] False
    
## 2. Software Design: Modularity

1. Check all that apply: The four aspects of modularity are...

    - [x] Information Hiding
    - [x] Cohesion
    - [x] Coupling
    - [ ] Data Hiding
    - [ ] Components
    - [ ] Sort Functions
    - [x] Data Encapsulation
    
 2. Which of the four aspects of modularity is defined as: How well modules work together.
 
    - [x] Coupling
    - [ ] Cohesion
    - [ ] Information Hiding
    - [ ] Data Encapsulation
    
    > This is the definition of coupling.

 3. Which of the four aspects of modularity can be described as: Abstracting away implementation details.
 
    - [ ] Cohesion
    - [ ] Coupling
    - [ ] Data Encapsulation
    - [x] Information Hiding
    
    > This is the definition of information hiding.
    
4. Which of the four aspects of modularity can be described as: How well a module meets a single well-defined goal.

    - [x] Cohesion
    - [ ] Data Encapsulation
    - [ ] Coupling
    - [ ] Information Hiding
    
    > This is the definition of cohesion.

5. Which of the four aspects of modularity can be described as: Containment of constructs and concepts within a module.

    - [ ] Coupling
    - [ ] Information Hiding
    - [ ] Cohesion 
    - [x] Data Encapsulation
    
    > This is the definition of data encapsulation.
    
6. Three aspects of ______ can be described as (1) Decomposability, (2) Composability, and (3) Ease of Understanding.

    - [x] Modularity
    - [ ] Coupling
    - [ ] Cohesion
   
   > Modularity is when a complex system is broken down into smaller parts. This is done through decomposability (divide and conquer strategy), composability (put it back together again), and ease of understanding.
    
7. You have a sort function that provides no details on which sorting algorithm is used. This is an example of which aspect of modularity?

    - [ ] Coupling
    - [ ] Cohesion
    - [x] Information Hiding
    - [ ] Data Encapsulation
    
    > This is a great example of information hiding.
    
8. A benefit to using ______ is that you know if your data is corrupted, then it must have been corrupted by the module.
   
    - [ ] Cohesion
    - [x] Data Encapsulation
    - [ ] Coupling
    - [ ] Information Hiding
    
## 3. Software Design: Coupling

1. Choose the most accurate answer: Low coupling aids in...

    - [ ] lower corruption rate of data
    - [ ] Decomposability
    - [ ] Abstracting away complex information 
    - [x] ensuring that changes don't cross boundaries of modules
    
    > What we hope to gain through low coupling is that changes don't cross the boundaries between modules.

2. Which of the following statements about coupling are true?

    - [ ] Coupling measures the strength of connections between components.
    - [ ] Loose coupling makes it unlikely that changes will be propogated across components.
    - [ ] Shared variables and control information leads to tight coupling.
    - [ ] Loose coupling is partly achieved through message passing.
    - [x] All of the above
    
    > All of these are true about coupling.
    
3. The goal in low coupling is to ensure that changes don't cross the boundaries of modules.

    - [x] true
    - [ ] false
    
    > This statement is true. This is the goal with low coupling.

4. The The three types of tight coupling are:

    - [ ] There is no such thing as tight coupling
    - [ ] Control; Data Structure; Message
    - [x] Content; Common; External
    - [ ] Data; Message; None
    
    > Tight coupling can be content coupling, common coupling, or external coupling.

5. Module A relies directly on local data of module B. This is an example of what type of coupling?

    - [ ] Tight external coupling
    - [ ] Tight common coupling
    - [x] Tight content coupling
    
    > Tight content coupling is exactly what this example defines.

6. Modules A and B both rely on global data or a global variable. This is an example of what type of coupling?

    - [ ] Tight content coupling
    - [x] Tight common coupling
    - [ ] Tight external coupling
    
    > Tight common coupling is exactly what this example defines.

7. Modules rely on externally imposed format (or protocol or interface). This is an example of what type of coupling?

    - [x] Tight external coupling
    - [ ] Tight content coupling
    - [ ] Tight common coupling
    
    > Tight external coupling is exactly what this example defines.

8. The two types of medium coupling are:

    - [x] Control; Data Structure
    - [ ] Message; None
    - [ ] Content; Common
    - [ ] Data; Message
    
    > Medium coupling can be control coupling or data structure coupling.

9. Module A controls the logical flow of module B. This is an example of what type of coupling?

    - [ ] Medium data structure coupling
    - [x] Medium control coupling
    
    > Medium control coupling is exactly what this example defines.

10. Module A and B both rely on the same composite data structure. This is an example of what type of coupling?

    - [x] Medium data structure coupling
    - [ ] Medium control coupling
    
    > Medium data structure coupling is exactly what this example defines.

11. The three types of loose coupling are:

    - [ ] Control; Data Structure; Loose
    - [ ] Data; Message; Data Structure
    - [x] Data; Message; None
    - [ ] Content; Common; External
    
    > Loose coupling can be data coupling, message coupling, or no coupling.

12. Modules only share parameters. This is an example of what type of coupling?

    - [ ] Loose no coupling
    - [x] Loose data coupling
    - [ ] Loose message coupling
    
    > Loose data coupling is exactly what this example defines.

13. The loosest type of coupling; components only communicate through parameters or message passing. This is an example of what type of coupling?

    - [ ] Loose data coupling
    - [x] Loose message coupling
    - [ ] Loose no coupling
    
    > Loose message coupling is exactly what this example defines.
    
## 4. Software Design: Cohesion

1. Choose the most accurate answer: Cohesion describes...

    - [x] how well everything within a module fits together.
    - [ ] loose coupling.
    - [ ] decomposability.
    - [ ] how changes do not cross boundaries of modules.

2. Which of the following statements about cohesion is true?

     - [ ] Cohesion measures how well everything within a module fits together.
     - [ ] Describes the implementation of a single logical entity or function.
     - [ ] Represents a desirable design attitude.
     - [ ] High cohesion is the aim in software development.
     - [x] All of the above

3. The goal in real-life software development is to aim for object and functional cohesion and anything less than this should be justified.

    - [x] True
    - [ ] False

4. The four types of weak cohesion are:

    - [ ] Coincidental, temporal, sequential, logical association
    - [ ] Communicational, sequential, object, functional
    - [ ] There is no such thing as loose cohesion
    - [x] Coincidental, temporal, procedural, logical association

5. Parts of modules are together in the same file. This is an example of what type of cohesion?

    - [ ] Temporal cohesion
    - [ ] Procedural cohesion
    - [x] Coincidental cohesion
    - [ ] Logical association cohesion

6. Different pieces of code are activated at the same time. This is an example of what type of cohesion?

    - [ ] Coincidental cohesion
    - [ ] Procedural cohesion
    - [ ] Logical association cohesion
    - [x] Temporal cohesion

7. One piece of code runs after the other. This is an example of what type of cohesion?

    - [ ] Logical association cohesion
    - [x] Procedural cohesion
    - [ ] Temporal cohesion
    - [ ] Coincidental cohesion

8. 

- **TMTOWTDI** — there's more than one way to do it

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

1. 

# Test 1

## What software development Looks Like?

1. Which of the two is the software development model that can better respond to changes in the requirements?

    - [x] Agile Model
    - [ ] Waterfall Model
    
2. Which of the two software development model performs the software development activities sequentially in one iteration rather than in increments?

    - [x] Waterfall Model
    - [ ] Agile Model
    
3. Which of the following are the limitations of the waterfall model? Select three.

    - [x] Integration issues may remain undetected until the last phase
    - [x] It is difficult to respond to changes in the requirement
    - [x] Misinterpretations of requirement or design can remain undetected until the later phases
    - [ ] It is not suitable for big projects

# Test 2

## Why do we need requirements?

1. Which is the right description about the requirement specification process?
    - [ ] Requirement specification is a process that identifies and specifies the problem and possible solutions to the problem.
    - [x] Requirement specification is a process to identify and specify the problem to solve.
    - [ ] Requirement specification is a process of solving the requirements.
    - [ ] Requirement specification is a process to design the solution to the problem.
    
2. Specifying requirements is difficult because (select three):
    - [x] The client or end users might not be clear about what they want.
    - [x] Terminology can be interpreted in multiple ways depending on the person or the context in which it was used.
    - [ ] There is no guideline for writing a software requirement specification document.
    - [x] Software is intangible, which makes it difficult to comprehend and communicate.

3. Why is requirement specification important? Select two.
    - [x] Repairing an bug in the requirements can cost thousands of times more in the later phases of the software development lifecycle.
    
    > Great! For large projects, erroneous requirements often cost 100 times more to fix later in the lifecycle (although [some](http://www.agilemodeling.com/essays/costOfChange.htm) can cost 1000 times more, depending on the domain), and for small projects it can be more like 5 times more. Why does it cost so much? Is it just because we have to fix more artifacts (the requirements document, the design document, the code, etc.) or [is there something more](http://www.agile-process.org/change.html)?
    
    - [ ] Changing the requirement is not possible once the system is fully developed.
    - [x] Spending time upfront in requirement specification can save time in the later phases of the software development lifecycle.
    
# Test 3

## Requirements vs Specification

1. Which of the followings are true about requirements and specifications?

    - [ ] Requirements does not require specification-level refinement.
    
    > This should not be selected. Ideally, requirements shall only specify the intent ("what") without involving the specification-level details ("how"), but often, it is hard to separate those two.
    
    - [x] Requirements are for users; specifications are for developers.
    - [x] Requirements shall be written in the user's language; system specifications shall be written in the system language.
    
    > Great! We write both of them in natural language so they can easily be reviewed by our non-technical stakeholders (customers/users/management). However, we write the requirements in terms of the user because we focus on defining the problem/need rather than the solution. We write the system specifications in terms of the system as it describes how the system will satisfy the user's need (the requirements) and defines the interfaces between users and the system.
    
    - [x] Specifications shall meet the requirements.
    
    > Great! Specifications describe how the system meets the requirements and must, therefore, provide a solution for the problem/need described by the requirements (i.e., it should meet the requirements).
    
2. The followings can be categorized as (user) requirements? Select two.

    - [ ] Activate a login session when a user logs in, and maintain the session for 60 minutes unless the user who logged in had remained inactive for more than 120 seconds.
    - [x] A user shall be able to use the online banking system securely.
    - [x] The user shall be able to check the current balance of the checking accounts that he/she own.
    - [ ] At the time a query is made to check the current balance of a checking account, the owner of the checking account shall be logged in.
    
3. The followings are requirements and specifications of an online banking service. Which of the followings can be categorized as system specifications? Select two.

    - [x] At the time a query is made to check the current balance of a checking account, the owner of the checking account shall be logged in.
    - [ ] The user shall be able to check the current balance of the checking accounts that he/she own.
    - [x] Activate a login session when a user logs in, and maintain the session for 60 minutes unless the user who logged in had remained inactive for more than 120 seconds.
    - [ ] A user shall be able to use the online banking system securely.


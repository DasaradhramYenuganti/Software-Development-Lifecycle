# 1. What software development Looks Like?

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

# 2. Why do we need requirements?

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

# 3. Requirements vs Specification

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

# 4. Non-functional Requirements

1. A constraint to only use Microsoft Project during the system development is a non-functional requirement.

    - [x] True
    
    > That is right! Constraints on the development of the system, such as using a specific tool, are non-functional requirements.
    
    - [ ] False

2. Which of the following are non-functional requirements:

    - [ ] Some product requirements, like using a specific encryption protocol, are non-functional requirements.
    - [ ] Organization requirements imposed by the company, like a specific coding style, are non-functional requirements.
    - [ ] External requirements imposed by external organization, like using a specific development style, are non-functional requirements.
    - [x] All of the above.
    
    > Non-functional requirements can come in many flavors. They can be imposed by external factors or organizational factors and they can also refer to some feature of the system. But the key point to note here is that non-functional requirements are not intended to describe the computation or function of the system.

# 5. WRSPM Quiz

1. WRSPM stands for:

    - [ ] Wide, Requirement, Software, Planning and Model.
    - [x] World, Requirement, Specification, Program and Machine.
    - [ ] None of the above.
    
2. Looking at the difference between user requirements and system specifications in the ATM example, we know that swiping the card and prompting for a PIN are requirements, while reading the card details and a 4-digit PIN are specifications.

    - [x] True
    - [ ] False

3. The purpose of the WRSPM model is to ensure that:

    - [x] specifications meet the requirements.
    > True! It is crucial that the specifications truly represent the requirements and not the other way around.
    - [ ] requirements meet specifications.
    > False! It is always important to map our specifications to the requirements so we know that we are implementing the right product.
    - [ ] None of the above.
    
# 6. Software Architecture: Definition

1. A subsystem in an architecture must:

    - [ ] be created separately and can operate individually.
    - [ ] have business value.
    - [ ] be integrated with one another or with existing subsystems.
    - [x] All of the above.
    
    > You got it! Indeed subsystems in a good architecture are created separately and can operate independent of each other. They also have their own business value and they can easily integrate with one another and with other existing systems.
    
2. Partitioning of a large system into smaller subsystems helps the buy-or-build decision because we can examine each subsystem and reason about possible buy-or-build options for each.

    - [x] True
    
    > That is right. Having clear, well-defined subsystem components greatly helps the buy-or-build decision because it is easier to reason about a smaller subsystem than a large one.
    
    - [ ] False
    
3. A good software architecture is important because:

    - [x] It helps organize the workforce and resources.
    
    > Correct! Now that the system is broken into smaller, more-manageable subsystems, the workforce and resources can be allocated
    
    - [x] It allows for parallelization in development.
    
    > Exactly! Parallelization is now possible over subsystems.

    - [x] It helps build-or-buy decisions.
    
    > Correct! Subsystems can now be examined to decide what needs to be built and what can be bought.
    
    - [x] It helps with funding decisions.
    
    > Correct! Indeed funding decisions are easier now that one can look into individual subsystems.
    

# Other

1. Non-functional requirements describe (check ALL that apply):

    - [x] System Design Constraints.
    > That's right! System design constraints like using a specific tool for designing or managing the project is a non-functional requirement.
    - [x] Quality related constraints like security, performance, and usability
    
    > That is correct! How secure the system is as well as the expected system performance are all non-functional requirements. They aren't meant to address a specific function in the system. They are instead made to enforce certain constraints or expectations on system in general.
    
    - [ ] Intended output or result of the system, such as, computing the shortest path between two points in a graph.
    > Incorrect! The shortest path between two points is a computation of some functional requirement of the system.

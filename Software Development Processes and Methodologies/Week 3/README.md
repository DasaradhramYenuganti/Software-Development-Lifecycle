# Software Development Models: Traditional Models

## 🔹 Waterfall Models

  - **Predictive** (Waterfall model, V-Model, Sashimi Model)
  - **Adaptive** (Unified Process, Spiral Model)
___________

  - Incremental
  - Iterative
  - Both
  - None
_________________

### 🟧 Waterfall Model

![Waterfall_model.svg](https://github.com/ElizaLo/Software-Development-Lifecycle/blob/master/Software%20Development%20Processes%20and%20Methodologies/Week%203/Waterfall_model.svg)
_______________________

### 🟧 V-Model 

![V-Model](https://github.com/ElizaLo/Software-Development-Lifecycle/blob/master/Software%20Development%20Processes%20and%20Methodologies/Week%203/V-Model.png)
________________________________

### 🔺 Waterfall methods

1. In waterfall method, you get your product in one big bang deployment

  - [x] True
  - [ ] False
  
  > That is true because all of the implementation happens in one shot. Think about what customer sees. Do they get all at once?

2. Sashimi model may help decrease the time duration of the project by

  - [x] Overlapping the phases
  - [ ] Adding more skilled resources of the project
  
  > The main idea behind the Sashimi model is to overlap the phases so that later phases can start before the previous phase ends. This sometimes helps reduce the total project duration. 

3. Which of the following are true for the V-model? Select two.

  - [x] It is a predictive model.
  > The V-model is a predictive model as requirements are expected to be well known earlier in the process and requirement changes are costly in later phases.
  - [x] Testing-related activities are started earlier in the process.
  > In the V-model, we map each of the earlier phases to a later validation phase. This helps get testing activities started earlier in the project's development process.
  - [ ] Requirement changes are welcomed in all phases of this project.
  
## 🔹 Incremental Models

### 🔺 Waterfall and Incremental Software Development Models

1. In predictive models, change during the development is expected.

  - [ ] True
  - [x] False
  > Since change is very costly in predictive model, it is not expected.

2. In which of following models, you may end-up building something different than what you originally planned? Select two.

  - [x] Agile models
  > agile mindset recommends that you deliver in short iterations, get regular feedback and make changes based on the feedback.
  - [ ] Waterfall models
  - [x] Adaptive models
  > adaptive models are where you get regular feedback and make changes based on the feedback.
  - [ ] V-Model

3. What are the BENEFITS of the Sashimi Model? Select two.

  - [ ] It supports early validation
  > There is no emphasis on early validation in this model.
  - [x] It can help shorten development time
  > True. By overlapping the phases
  - [x] It can support creating a learning prototype early
  > Since it is possible to overlap requirements, design, and development early, we can potentially work on a prototype early to support learning.

4. Which of the following is true for the V-model? Select two.

  - [x] The V-model is useful in cases where there is ambiguity in requirements and early validation would be useful.
  > True, by including some of the corresponding validation discussions in the early phases, the V-model helps identify issues with requirements early on.
  - [ ] This models emphasizes risk analysis and resolution
  - [ ] In this model, you build software in increments
  - [x] It is a predictive model
  > True. This model assumes that all requirements are known in advance.

5. Which of the following is true for Incremental Models? Select three.

  - [x] You can overlap building of one increment with another
  > True. Overlapping increment development is acceptable in incremental models. For example, you can start defining the requirements of increment 2 while the development of increment 1 is still in progress.
  - [ ] If deploying an increment to actual users can benefit the organization, using an incremental model is a potential candidate to consider.
  > True. This is one of the primary reasons why organizations use incremental models.
  - [ ] Incremental models are always predictive models
  - [ ] You always have to use same model for each of the increments
  > You can use any suitable model for a given increment. For example, in one increment you may use the V-model and for another increment, you may use the Sashimi model.
  - [x] Incremental models may result in rework
  > This is true because in a basic incremental model, you have requirements/design for only the current increment. When you work on a future increment, you may have to change the work done in previous increments as a result of the requirements for the current increment.

6. Which of the following is true for the Waterfall model, V-model and Sashimi model? Select two.

  - [x] In these models, the cost of change depends on how late we find out about the change. If problem requiring a change is found during the implementation phase, it will be more expensive to fix than one found during the design phase.
  > According to the cost of change curve, the later we find a problem requiring a change (a defect/bug), the more costly it is to fix. For example, if we find the change in implementation, it will requires us to redo requirements and design. Whereas if we find change during design phase, we only need to fix the requirements.
  - [x] In these models, we assume that we know requirements really well
  > This is the basis for these models because if you don't know the requirements, it is better to adopt adaptive model that is more conducive to changes later in the development cycle.
  - [ ] In these models, the team is expected know the solution really well.

7. Which model is the best model to use in all situations?

  - [x] None
  > Each model has its place and its pros and cons so there is no one model that will fit all situations
  - [ ] Adaptive since it has most advantages
  - [ ] Waterfall

## 🔹 Iterative Models

### Unified Process and its Variants

![1.png](https://github.com/ElizaLo/Software-Development-Lifecycle/blob/master/Software%20Development%20Processes%20and%20Methodologies/Week%203/1.png)

**✅ Pros:**
- **Adaptive model**
- Quality and Reuse
- Focus on risk mitigation increases chances of success
- Flexible to incorporate other software dev models

**❌ Cons:**
- Complicated model
- Need more resources
- Too much overhead for smaller project

**So where do you use this model?** 
- Bigger and riskier projects
- All requirments not known early in the project
- Desire to deliver value earlier
____________________________

### Spiral Model

- Risk-driven approach
  - Effort and detail driven by risk
- Four basic activities in every cycle 
- Process model generator. Incorporates other models
- The risk determines the level of effort and the degree of details. 
- And then not every activity in the diagram needs to be performed
- **Adaptive model**

![Spiral Model](https://github.com/ElizaLo/Software-Development-Lifecycle/blob/master/Software%20Development%20Processes%20and%20Methodologies/Week%203/Spiral_model.png)

**✅ Pros:**
- You can change in every cycle the direction where you're going. 
- The focus on the risk increases the chance of success of your product. 
- Flexibility of using any software development model.
- Minimizes waste because it talks about how you don't need to go through all this every single step in the same rigor but, based on the risk, you define how much effort you want to put. 
-  Option of go, no-go in every cycle and move forward.

**❌ Cons:**
- Complicated model
- Cost more to manage
- Needs the stakeholder engagement because after every cycle or during every cycle, you need a lot of or bit of engagement from your key stakeholders.

**So where do you use this model?** 
- If it is a very large high risk project, I think, a spiral model would be a good fit for those kind of projects.

### 🔺 Unified and Spiral Processes

1. In the Unified process, all requirements work is done upfront and no requirements work is done in the construction phase.

  - [x] False
  - [ ] True
  > In the unified process, although the majority of requirements work is performed in first two stages, there is still some requirements work needed in the construction and transition phases.

2. What are some of the activities that happen in the elaboration phase of the Unified process? Select two.

  - [ ] Deploy an increment of the software
  - [x] Address known risks
  - [ ] Decide if you are going to build the system or buy off the shelf product
  - [x] Validate system architecture by building executable architecture baseline
  > Two key things that happen in elaboration phase is addressing known risks and creating an executable architecture. See the unified process video

3. Which of the following activities happen in Step 2 of the Spiral model? Select two.

  - [x] Identify risks
  - [ ] Make a decision whether to continue with next cycle
  - [x] Resolve risks
  - [ ] Decide objectives and constraints

4. Select the four basic steps followed in each cycle of Spiral model.

  - [ ] Design
  - [x] Identify and Resolve Risks
  - [ ] Deployment
  - [x] Define Objective
  - [x] Development and Tests
  - [ ] Requirements
  - [x] Plan the Next Iteration

5. Which of the following are true for the Unified Processes and its variants? Select two.

  - [x] Agile Unified Process and Open Unified Process are lighter versions of the "Unified Process".
  - [ ] UML Unified Process is the Ultimate Unified Process with a superset of all practices and processes.
  - [x] Enterprise Unified Process adds additional practices on top of the Unified Process and Rational Unified Process.
  - [ ] Rational Unified Process is a lighter version on Unified Process.
  
## 🔹 Applying traditional software development models

# Advanced Software Development

### Project Management

- Concerned with activities involved in ensuring software is delivered on time and on schedule and in accordance with the requirements of the organisations developing and procuring the software.
- Project Management is needed because software development is always subject to the **budget and schedule constraints** that are set by the organisation developing the software.

*Read Bennett Chapter 22*

- Systems development is a complex activity that requires careful project management

- Interdependencies between the artifacts of software development mean that production needs to be planned, monitored and coordinated so that development is effective efficient and on time
- A software development project may involve many developers, some with specialized skills who will be required at different times.
- Activities must follow a particular sequence

### Project Management Tools
- Basecamp
- Freedcamp
- TeamGantt
- Asana
- Slack
- Overleaf (Latex)

### Scope of a Project
- The functions and features that are to be delivered to end-users
- The user data that are input and output
- The content that is presented to users as a consequence of using the software
- The performance, constraints, interfaces and reliability that bound the system

*Side note: Agent based modeling: Lots of agents in the system, what is the aggregate result of the agents interacting in the system*

### Defining Scope
- Two techniques:
  - A narrative description of software scope is developed after communication o=with stakeholders (The client)
  - A set of use-cases is developed. A use-case is a scenario-based description of the user's interaction with the software from the users point of view
- Performance considerations encompass processing and response time requirements.
- Constraints identify limits placed on the software by external hardware, available memory or other existing systems.

### Determining Feasibility
- Given the scope, determine the resources required Eg. cost
- Make sure you have an answer to the question: "Do we have the resources we need to build this software?"
- Resources are:
  - People
  - Hardware and software tools
  - Reusable components

### Project Planning Goals aka Scope
- Goals are derived from the needs and expectations of stakeholders:
  - Project sponsor
  - Customer for the deliverables
  - Users of the project outputs
  - Project manager and project team
- Find true needs that create real benefits and prioritize them
- Create measurable (goals SMART acronym)

### Project Planning Deliverables
- Deliverables are a list of items that have to be delivered to meet the goals
  - Verifiable and specific
  - Can be a report, equipment acquisition, executable code module etc
  - Has a stakeholder who needs it
- Say when it is to be delivered
- Give quality standards

### Project Planning Schedule
- The effort required ito time
- The people required (and other resources)
- Update deliverables with this and work schedule out
- If the schedule is unrealistic the following can be justified:
  - Renegotiate deadline - delay the deadline
  - Additional resources (eg time, people) - more expensive
  - Reduce scope - Fewer deliverables

### Project Planning Support Plans
1. Human Resource Plan
  - Name key individuals and organisations: describe roles and responsibilities
  - Describe the number and type of people needed: start dates, estimated duration and how to get them
2. Communications and Management Plan
  - Who needs to be kept informed about the project?
  - How they will receive the information?
    - Weekly review meeting
    - Progress reports
    - Revised schedule
3. Risk Management Plan - see later
  - identify as many risks as possible
  - be prepared if something bad happens
4. Marketing Plan (Said in lectures but not on slides)
  - Needed to get funding

### The Range of Management Activities
- 4 P's
  - People:
    - Managers, Project Managers, Team Leaders, Software Team, Customers, End Users
  - Product:
    - Scope and decomposition
  - Process:
    - SDLC: Initiation -> Analysis -> Design -> Construct -> Test -> Implement
    - UP: Inception -> Elaboration -> Construction -> Transition -> Production
  - Project
    - Size estimation; scheduling; risk management; tracking

*Note subtle difference between product and project: Product: The thing to be built, eg model of birds, how many birds in model,speed of simulation etc. Project is entirety of the production of product eg risks and schedule*

## People

### Roles and Responsibilities
A team needs people with *different* skills
Range of duties in a small project:
1. Project management: Strategist, Leader, Politician, Project Facilitator, Administrator
2. Systems analysis: Stakeholder needs, Interaction Designer, Cost estimator
3. User interface designer, user stories
4. Architect: Application overview, performance
  - Middleware: Software layer between the operating system and the applications on a distributed computer network
5. Specialists as required: database, games engine, mobile dev etc
6. Documentation: Amanuensis (a literary or artistic assistant, in particular one who takes dictation or copies manuscripts.)

### 13 Essential Roles in small software development teams
1. **Course Developer**: Preparation and coordination of training
2. **Database Designer**: Essential to the process, mainly due to the specificity of its knowledge
3. **Implementer**: Programs sub-systems and components that support the desired functionalities
4. **Integrator** (lead programmer): Responsible for maintaining the implementer's awareness of the project context, for identifying the tasks to be undertaken and for appointing the person responsible for the initial definition of the critical dates of the project and for developing a plan for the integration of the sub-systems, to allow the project manager to inform the client when each feature is expected to be available
5. **Process Engineer**: Mainly concerned with the management of the development process, its adaption to the organisational context and monitoring its implementation, in order to identify and implement possible process improvements
6. **Project Manager**: Assume a global overview of the project through a detailed interaction with the internal and external participants. Must create the conditions for the project to achieve success, by ensuring timeliness and fulfillment of all commitments. Requires: basic knowledge in management; knowledge about the clients business domain; project management methodologies and negotiation skills.
7. **Project Reviewer**: This role cannot be considered critical, however, due to responsibilities related to the verification and approval of several artifacts produced by other participants, and possible conflict of interests, this person cannot have another role within the project
8. **Software Architect**: Responsible for setting the technological foundation which the project implementation should be based. The software architect is responsible for managing the technical risks.
9. **System Administrator**: Focused on ensuring the provision of the infrastructure needs
10. **System Analyst**: Scope management. Identify and document the requirements (functional and non-functional). Understand the clients business domain and to perceive the real motivations and relevance of the requirements.
11. **System Tester**: Entrusted with very different tasks, like review of documentation and testing behavior.
12. **Test Manager**: Responsibility is to ensure the product quality by devising a plan for internal quality audits and implementation. Cannot have other roles, particularly with those roles, particularly with those roles related to the design and construction.
13. **User-Interface Designer**: The scope of this role in a project varies according to the nature of the artifacts to be developed.

### Choosing People

Information from candidates about their background and experience (resume or CV):
- best evidence to judge suitability

Information from interviewing candidates:
- Mainly judge communication and social skills
- Subjective judgment, and therefore not reliable
- Can also ask to perform specific exercises

References and recommendations from people who have worked with them:
- Effective when you can rely on the people making the recommendation

### Managing with different Personality Types
The following must be catered for:
- Different backgrounds and personality styles of team members
- Management styles of customers and developers

Realize that other people are not necessarily like you

Jung + Myers-Briggs is one personality model

Different kinds of personalities need different kinds of motivation, recognition and rewards.

### Jung: Two pairs of cognitive functions
1. The "irrational" (perceiving) functions: *sensing* and *intuition*
  - **How do you prefer to process information?**
  - S - Sensing: prefer to deal with facts, what you know, to have clarity, or to describe what you see
  - N - Intuition: prefer to deal with ideas, look into the unknown, to generate new possibilities or to anticipate what isn't obvious.
2. The "rational" (judging) functions: *thinking* and *feeling*
- **How do you prefer to make decisions?**
- T - Thinking: prefer to decide on the basis of objective logic, using an analytic and detached approach
- F - Feeling: prefer to decide using values and/or personal beliefs, on the basis of what you believe is important or what you or others care about.

### Jung: expression of Cognitive Functions

**Where do you prefer to direct your energy?**

E- Extrovert: prefer to direct energy to deal with people, situations or the "outer world".
I - Introvert: prefer to direct energy to deal with ideas, information, explanations or beliefs, or the "inner world".

### Meyers & Briggs: Lifestyle
**How do you prefer to organise your life?**
J - Judging: prefer life to be planned, stable and organised (Not Judgmental)
P - Perception: prefer to go with the flow, to maintain flexibility and respond to things as they arise.

### Management and Team Success
Most software engineering is a group activity
- Non-trivial software projects cannot be done by one person
- People motivated by success of the group and their own personal goals
Individual success depends on:
- Ability and interest for work at hand
- Experience and training with similar applications, development tools, programming languages
Team success depends on:
- **Ability to communicate** and express ideas in the team
  - be heard or be herded
- Group interaction is a key determinant of group performance
Management skills
- Limited flexibility in group composition: do the best with people available

## Estimation and Metrics

How are things going? Is it according to plan?

### Milestones and Deliverables
**Activity:** Task that takes time.
Duration: length of time needed for an activity
Due date: date for completion for the completion of the activity
Precursor: activity which precedes others that depend on it

Milestones
- Completion of an activity
- Recognisable end-product of a task
  - Hand over system for testing
- Requires a formal, measurable output
  - Eg: "Coding is 80% complete is not adequate"

Deliverable
- A project result is delivered (to customer)

### Milestone vs Deliverable put simply

Deliverable: *Measurable and tangible outcome of the project*
"A deliverable is a measurable and tangible outcome of the project. They are developed by project team members in alignment with the goals of the project"

Milestones: *The checkpoints throughout the life of the project. They identify when one or multiple groups or activities..*
"**Milestones** on the other hand are checkpoints throughout the life of the project. They identify when one or multiple group activities have been completed thus implying that a notable point has been reached in the project  "

### Why Software Metrics?
To plan and manage a software development project.

The resources required for each of its constituent activities need to be estimated. These estimations are subjective perceptions of the activity and based on measurements of size and complexity of the activity itself and the artifact produced.

Software metrics measure some aspect of software development, such as:
- project level: cost and duration
- application level: size or complexity

### Software Metrics Characteristics
**Process Metrics**
Process metrics measure some aspect of the development process, such as:
- Project cost to date
- Amount of time spent on the project to date

The above aspects are constantly changing

**Product Metrics**
Product metrics measure some aspect of the software product, such as:
- Analysis models: Number of classes in analysis class diagram
- test plans
- program code

**Result Metrics**
Measure outcomes such as current cost of project, and also known as *control metrics* and are used to determine how management control should be exercised.

Measurement of the current level of progress in the project is used to decide whether action is necessary to bring the project back onto schedule.

**Predictor Metrics**
Quantify estimates for project resource requirements, such as class size.

A crude measure could be a simple count of attributes and operations. Its a predictor because it can be used to predict the time it will take to produce code.

Also a measure of some other aspect of software product that is used to predict another aspect of the product or project progress.

Could possibly predict that the system will be difficult to maintain, or low levels of reuse.

The design could then change to improve the system

### Are Software Metrics Worth Anything?

Useful for prediction and resource estimation but is otherwise limited in use.

The validity of predictor metrics are based on 3 assumptions:
1. You can measure something useful
2. The measure predicts something worthwhile
3. The relationship (assuming its the relationship between the measurement and prediction) is real and can be expressed in a model or formula

Size metrics can be used to estimate the resource requirement for a project provided that appropriate historical data is available to derive and validate the relationship.

Generally software developers don't think metrics are important and are more focused on the delivery of the product on time. Metrics can also be used to monitor the performance of developed, which is a cause of concern to developers and could result in ethical and management issues.

### Metrics for Object-Oriented Development

The ability of a packet to absorb change is partly dependent on the ratio of abstract classes to all classes

0 => Package has only concrete classes and therefore is difficult to change
1 => Package has no concrete classes and is easy to change

<!-- TODO Watch lecture -->
Application size:
- The number of use cases
- The number of domain classes
- Multiplying factors that reflect the complexity of the user interface

Class size
- The number of attributes
- The number of operations
- The size of operations

## Scheduling

### Project Scheduling

Split the work in a project into separate tasks:
- **Minimize task dependencies**. This allows things to happen in parallel and therefore there isn't a delay waiting for one task before another can be started

Estimate the calendar time needed to complete each task
- Split up task if it'll take much longer than 1 week (never allow it to be more than 2 months)
- Make tasks concurrent to make optimal use of workforce

Estimate the effort required
- Who will work on the tasks
- Resources needed to complete each task

Project scheduling mostly needs **project manager's intuition and experience**

### Project Scheduling Process

<!-- TODO Add image -->

<!-- TODO Where does this fit in? -->
(The below is not in lectures)
We need to look at:
1. Who are the people in the team
2. What are the tasks that need to be done
3. How do these relate with each other
Map it out with network analysis

### Critical Path or Network Analysis

- Related to PERT charts
- Minimum overall duration of the project according to the estimates depends on the **critical paths**
- Any delay of a task on the critical path delays the whole project

<!-- TODO Finish this from lectures -->
Critical path - The line of ...

### What is Network Analysis

**Project tasks**
Are often interdependent; But need to be done in parallel for teamwork to be effective

**Task networks are graphical depictions of task dependence**

**Network analysis is a project planning method**
- It determines the critical path
- It establishes *most likely* time estimates
- It calculates boundaries to stop project slippage

#### Terminology

| Term | Meaning     |
| :------------- | :------------- |
| Earliest Start/Finish       | Earliest a task can begin/end if all preceding tasks are completed in the shortest time       |
| Latest Start/Finish | Latest a task can begin/end without delaying the minimum project completion time |
| Critical Path   | Chain that determines overall project duration; There can be more than one critical path   |
| Slack (Float) | The amount of surplus time or leeway allowed while still maintaining the critical path |

<!-- TODO See example: Tasks for a multiuser 3D meeting place; See Network Analysis slides after example -->

### Gantt Charts

Horizontal Bar Charts:
- Horizontal axis represents project time span
- Vertical axis represents project tasks

Captures:
- Task completion
- Simple dependencies
- Milestones and deliverables

Cant handle complex task dependencies
Supported by automated scheduling tools

## Risk

### Managing Risks

**Why**
Projects have a high level of uncertainty; Better to anticipate problems in advance

**How**
1. Identify specific risks to the project
2. Analyze the risks
3. Rank them in a particular order
4. Plan for monitoring, mitigation and management
5. Revisit continually during project

### Boehm's top ten risk items +2

Being blindsided by the competition <!-- TODO: What? -->
Outside interruptions

1. Personal shortfalls - Failure to recruit or retain key staff
2. Unrealistic schedules and budgets
3. Developing the wrong functions
4. Developing the wrong UI's
5. Gold-plating (Fixating on extras instead of focusing on improving the core functionality)
6. Continuing stream of requirements changes
7. Shortfalls in externally-performed tasks
8. Shortfalls in externally-furnished components
9. Real-time performance shortfalls
10. Straining computer science capabilities

### Risk Matrix

Sort risk by a combination of:
- Probability (high, medium, low)
- Impact: Catastrophic (project failure), critical (massive delay), marginal, negligible

<!-- TODO See image below the above list -->

### 3 M's

**Mitigation** - How can we avoid or reduce the risk
1. Avoid the risk: change requirements
2. Transfer the risk: get insurance
3. Assume the risk and accept and control it

**Monitoring** - What factors can we track that will enable us to determine if the risk is becoming more or less likely

**Management** - What contingency plans do we have if the risk becomes a reality

<!-- See examples of risk slides -->

## Conclusion

### Planning vs Management

Planning
- Pre- and post-
- Network analysis, resourcing, risks, schedule

Management
- During
- Controlling resources and timescales

Tips on project control: Remember to update planning documents. Show progress in Gantt Chart, Reassess risks.

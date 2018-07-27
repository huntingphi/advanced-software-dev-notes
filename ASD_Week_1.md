# Advanced Software Development

### Project Management

- Concerned with activities involved in ensuring software is delivered on time and on schedule and in accordance with the requirements of the organisations developing and procuring the software.
- Project Management is needed because software development is always subject to the **budget and schedule constraints** that are set by the organisation developing the software.

*Read Bennett Chapter 22*

- Systems development is a complex activity that requires careful project management

- Interdependencies between the artefacts of software development mean that production needs to be planned, monitored and coordinated so that development is effective efficient and on time
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

*Side note: Agent based modelling: Lots of agents in the system, what is the aggregate result of the agents interacting in the system*

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
- Create measurable (goals SMART accronym)

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
4. **Integrator** (lead programmer): Responsible for maintaining the implementers' awareness of the project context, for identifying the tasks to be undertaken and for appointing the person responsible for the initial definition of the critical dates of the project and for developing a plan for the integration of the sub-systems, to allow the project manager to inform the client when each feature is expected to be available
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
- Subjective judgement, and therefore not reliable
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
J - Judging: prefer life to be planned, stable and organised (Not Judgemental)
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
  - be heard or be hearded
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
"**Milestones** on the other hand are checkpoints throughout the life of the project. They identify when one or multiple group activities have been completed thus implying that a notable point has been reached in the project"

### Why Software Metrics?
To plan and..

### Software Metrics Characteristics


## Scheduling

### Project Scheduling

Minimize task dependencies. This allows things to happen in parallel and therefore there isn't a delay waiting for one task before another can be started

(The below is not in lectures)
We need to look at:
1. Who are the people in the team
2. What are the tasks that need to be done
3. How do these relate with each other
Map it out with network analysis

Critical path - The line of ...

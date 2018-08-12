# Software Project Management Methods

## The Problem

### Observations

The most common problem in software systems is not the construction, but the estimation.

Software projects **fail to meet cost and schedule**, because the target cost and schedule estimates are wrong. Costing software is difficult.

Estimations are made by people least able to make them such as marketers, managers and customers who know little about accurate estimations so targets are unreasonable

Communication is hard when the ideas are abstract or conceptual

### Software Engineering Triangle

*Time - Cost - Scope*

Any change to one goal must be compensated for by a change to one or both of the other goals

<!-- TODO See slides on graphs (~slide 8) -->

### "Think Big, Act Small": Just say no to large projects

The secret to project success is to enforce limits on **size** and **complexity** - Size and complexity trump all other success factors

Break large projects down into a sequence of smaller ones, prioritized on direct business value.
Use stable, full-time, cross functional teams that follow a disciplined agile approach

The quick solution is to just say no to large projects.
More sensible however to adopt a small project strategy.

Projects often get too big to succeed. They're (the projects?) constantly being called on to do more for less while the key to success is doing less for less - splitting large projects into a sequence of small ones

<!-- TODO See slides on graphs (~slide 11) -->

### YAGNI: You Ain't Gonna Need It

Cry to prevent speculative development and Gold Plating. Rather build only what you need now.

Speculative development adds complexity to code prematurely

<!-- TODO See slides on graphs (~slide 13) -->

### Cost Curve under most software processes is exponential

<!-- TODO See slides on graphs (~slide 14) -->

Exponential costs overtake all early returns.
Fred Brooks attributes the exponential rise in costs to cost of communication - Customer and developer must understand each other perfectly

New projects are successful because the cost curve is still flat. Once costs start increasing they quickly overcome any additional value added from the new features.

### Problems: Bad Communication

<!-- TODO See slides on graphs (~slide 15) -->

### Problems: The Crunch

Crunch is the side effect of other problems and the cause of burnout

<!-- TODO See slides on graphs (~slide 16) -->

### Software Entropy, Rot and Geriatrics

**Entropy** - Measure of disorder in a physical system
**Software Entropy** - Measure of code complexity
- Tends to increase over time
- Speculative development adds complexity at the start
- Bug fixes and enhancements increase complexity and degrade structure - Most software applications grow at annual rates of 5-10%

Entropy makes it hard to:
- Make changes and fixes
- Understand the code

The cure for entropy is:
- **YAGNI** at the start
- **Refactoring** as you go along

<!-- TODO See slides on Yak shaving (~slide 18) -->

## Traditional Software Engineering Methods

### Code and Fix

Naive first approach - actually lack of a methodology
Little to zero planning, dive straight into implementation
Reactive
End with bugs - if bugs multiply too fast to fix: "death spiral" -> canceled
To make it there will be "crunch time" - Results in burnout

### Traditional Methods

Used for well defined systems:
- User can specify the requirements
- Developers can do the development
- System is finished
- System is launched

<!-- TODO See slides on diagram(~slide 22) -->

### Waterfall Method

- Linear, sequential
- Teams gather requirements
- Develop the product
- Test it to see if they implemented the spec correctly
- After release they gain insight into what the customer actually desired
- Doesn't work

<!-- TODO See slides on Waterfall targets (~slide 29) -->

### Waterfall Concepts

Software as an Engineering discipline - "Do it right the first time"
More design time reduces risk - By planning upfront you identify problems early and avoid mistakes. The more you analyse a system the more edge cases you'll discover. Often, elaborate systems are designed for problems that do not really exist

### Change and the Waterfall Method

The cost of change increases exponentially with time. Conservative design decisions are therefore motivated by fear of change.
A change late in the process costs 1000 times as much as a change early in the process:
- 5 mins to write the spec
- 2 days to program the feature
- 2 weeks to test it before deployment
- Month to write patch that fixes problem after deployment

### Change and Feasibility

Is it feasible to first define the whole problem, then design the entire solution, then build the software then test the product?

## Modern Alternatives

### More Modern Processes

More lightweight than Waterfall:
- **Less documentation**
- **Fewer procedures**
Don't release only one version at the end
- Parallel development
- Produce prototypes
Only do what is required
- No adding in extra requirements
Design for change

### Alternative Ideas: Prototyping, Rapid Application Development

**Prototyping** :

      Requirements -> Prototyping
                ^-Test<-/
**Rapid Application Development**
Cycle of:
1. Learning(Reflect)
2. Requirements
3. Design
4. Develop
5. Deploy(Test)

## Iterative SE Methods

### Iterative or Incremental Process
- Plan development
- Undertake development
- Generate a prototype
- Get user feedback
- Design again

*Iterative software development:* A process that reaches the goal in a series of ever improving delivery cycles

<!-- See slide 40-45 -->

### Iterative Process - The Big Difference
- Instead of 2 - 18 months to create and evaluate a concept, a new version can be built and shown every 2-4 weeks
- Requires:
  - **Team members** close together and **close to customer**
  - Team members agree on good ideas over a period of hours, not months
  - Teams become experts through intense hands-on problem solving and testing
  - Ends up with real systems meeting the users' needs, not their 'perceived' needs.

### Iterative Process - The Benefits

Favoured by small start up companies: Greatly reduces the risk of a project failing
Long term, iterative development delivers more value sooner with lower overall risk
Project is intensely focused: By completing only high priority features, many alternative concepts never get explored - good ideas may be lost

The danger lies in missed opportunities

### Examples of Iterative Software Development Methods

<!-- See slide 48 -->

## Unified Process

### Iterative Development and the Unified Process

- (Rational) Unified Process (RUP or UP) is a process for building high quality object-oriented systems
- Central idea: Iterative Development
  - The life of a system stretches over a series of cycles, each resulting in a product release

### Iterative Development

Development as a series of short mini-projects: iterations
Each iteration gives a tested, integrated and executable system
An iteration forms a short (2-6 weeks) complete development cycle:
- Requirements
- Analysis
- Design
- Implementation
- Integration and System Test

Iterative lifecycle is based on the successive enlargement and refinement of a system: multiple iterations with feedback and adaption
System grows incrementally over time, iteration by iteration - may however not be eligible for production deployment until after many iterations

Output of an iteration is not an experimental prototype but a **production subset of the final system**
Each iteration tackles new requirements and incrementally extends the system
An iteration may occasionally revisit existing software and improve it

<!-- See slide 55 -->

### Central Unified Process Ideas

Iterative Development is number one.

Others:
- Tackle high risk items early
- Continuous engagement of users
- Core architecture build in early iterations
- Continuous verification of quality: test
- Apply use cases continuously
- Model software with UML
- Carefully manage requirements
- Control changes

### Unified Process phases
**Inception** - Define the scope of project - Feasibility
**Elaboration** - Plan project, specify features, baseline architecture
**construction** - Build the product - Refine vision, implement core, resolution of high risks, identify major requirements. Several iterations
**Transition** - Transfer the product into end user community: Deployment, release

<!-- See slide 58 -->

### Artifacts
<!-- See slide 64 -->

Docs, diagrams, code etc that tack progress
Everything is optional.
Best kept electronically on a website.
Following can start in inception - Use-case model, vision, supplementary specification, glossary, s/w development plan, development case

## Comparison and Conclusion

### Process Comparison

<!-- See slide 66 -->

### Process Models

Analysis -> Design -> Code -> Test

A framework of tasks applied during software engineering:
- Linear (Waterfall): Based on conventional engineering
- Prototyping: Build a system to clarify requirements
- Rapid Application Development (RAD): Well-defined 60-90 day projects
- Incremental: Deliver increasing functionality at each iteration
- Spiral (Boehm): Similar set of tasks applied for each turn of the spiral
- Component based: Aimed at producing and reusing O-O components
- Agile: Embrace change, adapt to it, keep things simple

<!-- See slide 68 -->

### Reduce Risk

Iterative methods attempt to reduce risk by bringing versions out early

### Conclusion

Consider only iterative technologies
Agile techniques:
Small time cycles
Many prototypes
Meet user requirements
Timescale is adopted by the development team

<!-- See slide 72, 73 -->

### Benefits of iterative development

Early reduction of risk technical requirements, objectives, usability etc
Early visible progress
Early feedback - User engagement and adaption; better meets the real needs
Managed complexity: No very long and complex steps
Get a robust architecture - architecturecan be assessed and improved early
Handle evolving requirements - Users provide feedback to operational systems; Responding to feedback is an incremental change
Allow for changes: System can adapt to problems
Learn and apply lessons within the development process

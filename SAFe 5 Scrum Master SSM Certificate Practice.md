### SAFe

**Lean-Agile Mindset**

The Lean-Agile Mindset is the combination of beliefs, assumptions, attitudes, and actions of SAFe leaders and practitioners who embrace the concepts of the Agile Manifesto and Lean thinking.

*The Goal - Value*

The goal of Lean is to deliver the maximum customer value in the shortest sustainable lead-time while providing the highest possible quality to customers and society as a whole. High morale, safety, and customer delight are additional goals and benefits.

**SAFe is based on four primary bodies of knowledge**

Agile development, Lean product development, systems thinking, and DevOps.

**SAFe Core Values**

SAFe has four core values: Alignment, Transparency, Build-in Quality, and Program Execution.

**SAFe DevOps**

SAFe DevOps is a mindset, a culture, and a set of practices. It provides communication, integration, automation, and close cooperation among all the people needed to plan, develop, test, deploy, release, and maintain a Solution.

DevOps is part of the Agile Product Delivery competency of the Lean Enterprise.

DevOps is a combination of two words: development and operations. Without DevOps, there is often significant tension between those who build Solutions and those who support and maintain those Solutions.

**A CALMR approach to DevOps**

Culture - Establish a culture of shared responsibility for development, deployment, and operations.

Automation - Automate the Continuous Delivery Pipeline.

Lean flow - Keep batch sizes small, limit WIP, and provide extreme visibility.

Measurement - Measure the flow through the pipeline. Implement full-stack telemetry.

Recovery - Architect and enable low-risk releases. Establish fast recovery, fast reversion, and fast fix-forward.

**Positioning an Agile Team in a SAFe Enterprise (core competencies of Essential SAFe)**

Agile Product Delivery

Team and Technical Agility

Lean-Agile Leadership

**Cadence and Synchronization**

Operating in a common cadence and synchronization of planning help in managing and limiting the inherent variability and accumulation of variance in our work.

**Feature Toggles**

Feature toggles (also known as feature flags) is a software development mechanism that allows teams to turn on or off a feature, remotely without deploying any code. The objective of this mechanism is to essentially decouple feature rollout from code deployment. Hence, allowing developers to release new features and software quickly with less risk.

**Development Value Streams**

There are two types of value streams described in SAFe.

operational value streams (OVS) / development value streams (DVS)

### ART

**Agile Release Trains (ARTs)**

A virtual organization of 5-12 teams (50-125+ individuals)

Synchronized on a common cadence, a Program Increment (Pl)

Aligned to a common mission via a single Program Backlog

Continuous Delivery Pipeline: Continuous Exploration / Continuous Integration / Continuous Deployment

**ART events**

| Event             | Time box | Value                                                             |
| ----------------- | -------- | ----------------------------------------------------------------- |
| Pl Planning       | 2 days   | Teams commit to a set of objectives  to be delivered in the Pl    |
| ART Sync          | 1 hour   | The teams on the ART sync regarding the progress of the Pl        |
| System  Demo      | 1 hour   | Deliverables are reviewed with stakeholders  who provide feedback |
| Inspect and Adapt | ½ day   | The ART reviews and improves its process before the next Pl       |

**What is Pl Planning?**

Program Increment (Pl) Planning is a cadence-based event that serves as the heartbeat of the Agile Release Train (ART), aligning all teams on the ART to a shared mission and Vision.

* Two days every 8 -12 weeks (10 weeks is typical)
* Everyone plans together
* Product Management owns Feature priorities
* Development teams own Story planning and high-level estimates
* Architect/Engineering and UX work as intermediaries for governance, interfaces, and dependencies

**The Pl Planning process**

Input - Vision, Program Backlog and Top 10 Features.

Output - Team and Program Pl Objectives and Program Board.

**The benefits of Pl Planning**

Establishing personal communication across all team members and stakeholders

Aligning development to business goals with the business context, Vision, and Team/Program Pl Objectives

Identifying dependencies and fostering cross-team and cross-ART collaboration

Providing the opportunity for just the right amount of architecture and Lean User Experience (UX) guidance

Matching demand to capacity, eliminating excess work in process (WIP)

Fast decision making

**The Scrum Master's role in Pl Planning**

| Best approaches                                                       | Common anti-patterns                                                                   |
| --------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| Maintain the timebox                                                  | Pressure is put on the team to overcommit                                              |
| Make sure the team builds a plan they can commit to                   | Team under commits due to fear of failure                                              |
| Ensure that the team is honest in their confidence vote               | Over planning ahead of time to make it more efficient loses the essence of Pl Planning |
| Facilitate coordination with other teams but don't do it for the team | The plan, rather than the alignment, becomes the goal                                  |
| Act as a request buffer for a team that has a lot of dependencies     |                                                                                        |
| Manage the program board                                              |                                                                                        |
| Facilitate the retrospective                                          |                                                                                        |

**Product Owner Sync**

The PO Sync is the content-focused equivalent of the Scrum of Scrums.

The purpose of the PO Sync is to ensure alignment of the product vision and work-related content across all involved teams.

The PO sync may be facilitated by the RTE or a Product Manager. The purpose is to get visibility into how well the ART is progressing toward meeting its PI objectives.

**Scrum of Scrums (SoS)**

The purpose of the Scrum of Scrums is to ensure alignment of all teams working on the program.

Each team sends a representative, typically the Scrum Master, to the Scrum of Scrums.

The Release Train Engineer (RTE) typically facilitates a weekly (or more frequently, as needed) Scrum of Scrums (SoS) event.

**Improving results with the Inspect and Adapt event**

Three parts of Inspect and Adapt:

* The Pl System Demo
* Quantitative and Qualitative Measurement
* Problem-Solving Workshop

**The Problem-Solving Workshop**

Agree on the problem to solve

Apply root-cause analysis and 5 whys

Identify the biggest root-cause using Pareto analysis

Restate the new problem for the biggest root-cause

Brainstorm solutions

Identify improvement backlog items

**The Scrum Master's role in Inspect and Adapt**

| Best approaches                                                                                    | Common anti-patterns                                                           |
| -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| Facilitate the team preparation for the Pl System Demo                                             | Only the PO presents in the Pl System Demo                                     |
| Provide data                                                                                       | No actionable improvement Features are created                                 |
| Facilitate one of the teams in the problem-solving workshop                                        | Improvement items don't enter the Pl Planning process                          |
| Help the RTE make sure improvement items are included during the Pl                                | Scrum Master is more focused on the technical role than the facilitator's role |
| If using ad hoc teams for the l&A, then Scrum Masters may be participants rather than facilitators | Improvement items are not demoed in the PI System Demo                        |

**Innovation and Planning (IP) Iteration**

IP Iteration is the last iteration of a PI, where System Demo is performed.

The Innovation and Planning (IP) Iteration occurs every Program Increment (PI) and serves multiple purposes. It acts as an estimating buffer for meeting PI Objectives and provides dedicated time for innovation, continuing education, PI Planning, and Inspect and Adapt (I&A) events.

Innovation: Opportunity for innovation, hackathons, and infrastructure improvements

Planning: Provides for cadence-based planning

**What are two anti-patterns for the IP Iteration?**

* Plan work for the IP iteration during PI planning
* Wait for the IP iteration to fix defects

**Simulation: Day 1 agenda**

|                                               |                                                              |
| --------------------------------------------- | ------------------------------------------------------------ |
| Business context                              |                                                              |
| Product/Solution Vision                       |                                                              |
| Architecture Vision and development practices |                                                              |
| Planning context and lunch                    |                                                              |
| Team breakouts                                | Teams develop draft plans and identify risks and impediments |
| Draft plan review                             | Teams present draft plans, risks, and impediments            |
| Management review and problem solving         | Adjustments made based on challenges, risks, and impediments |

**The Scrum Master's role in team breakout**

| Best approaches                                                                 | Common anti-patterns                                                |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| Ensure the team has a draft plan to present                                     | No plan or partial plan at the end of the timebox                   |
| Identify as many risks and dependencies  as possible for the management  review | Too much time is spent analyzing each Story                         |
| Secure subject matter experts and program stakeholders as needed by the team    | Shared Scrum Masters and Product Owners are not available enough    |
| Facilitate the coordination with other teams for dependencies                   | Part-time Scrum Masters don't have time to plan as part of the team |

**System Architect - type of Enabler**

System Architects are responsible for Features. Enterprise Architects are responsible for Epics. Agile Teams are for Stories.

**Program Board: Feature delivery, dependencies, and Milestones**

A Feature placed in a team's swim lane with no strings means that it can be completed independently of other teams.

### Agile

**Scrum and SAFe terminology**

SAFe uses Iteration, while Scrum uses Sprint.

**The three pillars of Scrum**

Transparency, Inspection, and Adaptation.

**Five Scrum Values**

Courage, Commitment, Focus, Respect and Openness.

**Agile Teams have two speciality roles**

| Scrum Master                                                                        | Product Owner                                     |
| ----------------------------------------------------------------------------------- | ------------------------------------------------- |
| Coaches the Agile Team in self-management                                           | Contributes to the Vision and Roadmap             |
| Helps the team focus on creating increments of value each iteration                 | Acts as the Customer for team questions           |
| Facilitates the removal of impediments to the team's progress                       | Creates, clearly communicates and accepts Stories |
| Ensures that all team events take place, are productive and kept within the timebox | Prioritizes the Team Backlog                      |

The focus of a Scrum Master is coaching, facilitating, and fostering collaboration.

**Nothing beats an Agile Team**

Teams use Scrum and Kanban for Team Agility

Apply Built-in Quality practices for Technical Agility

| Built-in Quality practices              |
| --------------------------------------- |
| Lean and Agile principles and practices |
| Behavior-driven  development  (BDD)     |
| extreme  Programming  (XP)              |
| Code quality                            |
| Design patterns and practices           |
| Agile modeling                          |

**Agile team events**

Iteration Planning, Daily Stand-ups, Iteration Review, Backlog Refinement, and Iteration Retro.

| Event              | Approximate Timebox | Value                                                                                                                                                        |
| ------------------ | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Backlog Refinement | 1 hour              | Team prepares requirements for Iteration Planning                                                                                                            |
| Iteration Planning | 2 to 4 hours        | Team commits to a set of goals to be delivered in the Iteration<br />During Iteration planning, the team commits to the iteration backlog (Iteration Goals) |
| Daily Stand-ups    |                     |                                                                                                                                                              |
| Iteration Review   | 1 hour              | Team meets with stakeholders to review the deliverables  and provide feedback                                                                                |
| Iteration Retro    |                     |                                                                                                                                                              |

**Teams produce results**

Teams are far more productive than the same number of individuals

Face-to-face communication is extremely efficient

Teams perform best when they have planned periods of focused, uninterrupted work

Products are more robust when a team has all the cross-functional skills necessary

When teams themselves make a commitment, they will probably figure out how to meet it

Changes in team composition can impact productivity

Peer pressure is a strong motivator

**The five dysfunctions of a team**

* Inattention to Results
* Avoidance of Accountability
* Lack of Commitment
* Fear of Conflict
* Absence of Trust

Teamwork is the ultimate competitive advantage.

Absence of trust is the key problem that leads to the other four dysfunctions.

**SAFe helps address the five dysfunctions**

|                             |                                                                                                                                                                                                   |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Inattention to Results      | Results are empirically reviewed at the end of every Iteration and release. Iteration Retrospectives drive continuous improvement.                                                                |
| Avoidance of Accountability | Stakeholders, peer pressure, and review of results drive accountability.                                                                                                                          |
| Lack of Commitment          | Teams make shared commitments to each other and to the external stakeholders.                                                                                                                     |
| Fear of Conflict            | Scrum creates a safe environment for conflict; the Scrum Master encourages discussion of disagreements. Shared commitment avoids individual conflict that occurs when objectives are not aligned. |
| Absence of Trust            | The environment is safe. The team shares commitment and goals, displays hyper-transparency, and engages in retrospectives.                                                                        |

**Build cross-functional Agile Teams**

Agile Teams are cross-functional, self-organizing entities that can define, build, test, and where applicable, deploy increments of value.

* Optimized for communication and delivery of value
* Deliver value every two weeks
* Contain two specialty roles: Scrum Master, Product Owner

**Responsibilities of the Agile Team**

* Five to eleven team members
* Create and refine Stories and acceptance criteria
* Define, build, test and develop Stories
* Build quality in to each increment of the solution
* Develop and commit to team Pl Objectives and Iteration goals

**Team Artifacts**

Stories, Enabler stories, Team PI objectives, Iteration goals and Team backlog.

**Stages of high-performing teams**

Forming / Storming / Norming / Performing / Adjourning

**Agile frameworks**

*Agile Frameworks*

SAFe / Scrum / Crystal / Kanban / eXtreme Programming (XP) / Feature-Driven Development

*Practices*

Timeboxing / Stories / Daily Stand-Ups / Frequent demos / Test-Driven Development / Information radiators / Retrospectives / Continuous Integration

**The Team Backlog organizes the team's work**

The Team Backlog:

* Is created by the Agile Team
* Is owned and prioritized by the Product Owner
* Represents opportunities, not commitments
* Contains User and Enabler Stories

**The backlog refinement workshop**

* Timebox: 1 -  2 hours weekly
* Helps the team reconsider new Stories prior to Iteration Planning
* Provides time to identify dependencies and issues that could impact the next Iteration
* Ensures that we have a ready backlog for Iteration Planning
* Agile Team members are in attendance and actively engaged; subject matter experts and other teams' members are invited as needed

**The Scrum Master's role in backlog refinement**

| Best approaches                                                                | Common anti-patterns                                                 |
| ------------------------------------------------------------------------------ | -------------------------------------------------------------------- |
| Maintain timeboxes                                                             | Arriving to the Iteration with non-ready Stories                     |
| Maintain the right level of a deep backlog vs ready backlog for two Iterations | Not doing the backlog refinement consistently                        |
| Make sure all the team members participate                                     | Team sees Stories for the first time during Iteration or Pl Planning |
| Invite the right subject matter experts                                        | Feature estimations impact Story estimation                          |
| Hold the event at regular intervals                                            |                                                                      |

**Iteration basics**

PDCA (Plan / Do / Check / Adjust) - Iteration Planning / Iteration Execution / Iteration Review / Iteration Retrospective

Iterations provide a regular, predictable cadence for teams to produce an increment of value.

Definition: Iterations are a single development cycle where each Agile Team defines, builds, integrates, and tests the Stories from their Iteration Backlog.

Duration: Each Iteration is the same length, running back to back. SAFe advises two weeks Iterations.

Goal: The goal is to deliver working software / hardware at the end of each Iteration.

Avoid adding scope once the Iteration has begun.

**Iteration Goals**

Iteration Goals provide clarity, commitment, and management information. They serve three purposes.

* Align team members to a common purpose
* Align teams to common Program Increment (Pl) Objectives and manage dependencies
* Provide transparency and management information

**Iteration Planning flow**

Establishing capacity / Story analysis and estimating / Detailing Stories / Developing Iteration Goals / Committing to Iteration Goals

**Establishing capacity**

Team applies capacity allocation to the Team Backlog

Team quantifies capacity to perform work in the upcoming Iteration

Each team member determines their availability, acknowledging time off and other potential duties

The PO in collaboration with the teams select the highest priority backlog items for each 'slice' of the capacity allocation to implement in an Iteration

**Scrum Master as servant leader**

Scrum Masters are servant leaders and coaches for an Agile Team. They help educate the team in Scrum, Extreme Programming (XP), Kanban, and SAFe, ensuring that the agreed Agile process is being followed. They also help remove impediments and foster an environment for high-performing team dynamics, continuous flow, and relentless improvement.

* Listen to and support team members in problem identification and decision-making
* Understand and empathize with others
* Encourage and support the personal development of each individual
* Persuade rather than use authority
* Think beyond day-to-day activities
* Seek to help without diminishing the commitment of others
* Be open and appreciate openness in others

**Scurm Master Role**

The Scrum Master role is a unique Agile team member who spends much of their time helping other team members communicate, coordinate, and cooperate; generally, this person assists the team in meeting their delivery goals.

**How a Scrum Master supports an Agile Team**

Facilitates events

Is a servant leader

Builds a high-performing team

Helps the team improve processes

Facilitates the removal of impediments

Fosters adoption of Agile practices

Supports the Product Owner

**Feature**

A Feature has three attributes: description, benefits hypothesis, and acceptance criteria.

When a feature is presented to customers, and evaluated as “satisfied”, then we say it is evaluated.

**Estimate Stories with relative Story points**

A Story point is a singular number that represents:

Volume: How much is there?

Complexity: How hard is it?

Knowledge: What do we know?

Uncertainty: What's not known?

**The Scrum Master's role in facilitating estimations**

| Best approaches                                        | Common anti-patterns                           |
| ------------------------------------------------------ | ---------------------------------------------- |
| Encourage everyone to participate                      | Pressure by stakeholders  to lower estimations |
| Ensure relative estimates are used                     | Only a few people participate                  |
| Focus the discussion  around the contested items       | Not using the adjusted  Fibonacci scale        |
| Identify subject matter experts who need to be present |                                                |
| Keep time spent estimating  Stories to a minimum       |                                                |

**The Scrum Master's role in the improvement**

| Best approaches                              | Common anti-patterns                                                          |
| -------------------------------------------- | ----------------------------------------------------------------------------- |
| Encourage improvement between retrospectives | The only focus is on what to improve and not what to preserve                 |
| Coach the team on problem-solving techniques | Focus on problems that are outside of the team 's control                     |
|                                              | Failure to achieve results                                                    |
|                                              | Inviting people outside the team (especially management) to the retrospective |

**INVEST in a good Story**

Independent / Negotiable / Valuable / Estimable / Small / Testable

**Enabler Stories**

Enabler Stories build the groundwork for future User Stories. There are four types of Enabler Stories:

* Infrastructure: Build development and testing frameworks that enable a faster and more efficient development process
* Architecture: Build the Architectural Runway, which enables smoother and faster development
* Exploration: Build understanding of what is needed by the Customer to understand prospective Solutions and evaluate alternatives
* Compliance: Facilitate specific activities such as verification and validation, documentation, signoffs, regulatory submissions, and approvals

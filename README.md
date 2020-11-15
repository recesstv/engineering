# Welcome!

You'll find all the engineering resources in this repo.

Everything in this repo is **public**, work-in-progress and can/will change. Contributions are welcome.

## Table of Content

- [Priorities](#Priorities)
  - [Prioritizing time](#Prioritizing-time)
  - [Prioritizing the product](#Prioritizing-the-product)
- [Engineering principles](#Engineering-principles)
  - [We seek high standards](#We-seek-high-standards)
  - [We commit and follow through](#We-commit-and-follow-through)
  - [We are one team](#We-are-one-team)
  - [We hunger to learn and share knowledge](#We-hunger-to-learn-and-share-knowledge)
- [Engineering standards and practices](#Engineering-standards-and-practices)
  - [Code reviews](#Code-reviews)
  - [Estimates and deadline commitments](#Estimates-and-deadline-commitments)
- [Engineering ladder](#Engineering-ladder)
- [Release cycle](#Release-cycle)
  - [Releasing features](#Releasing-features)
  - [Releasing tweaks and fixes](#Releasing-tweaks-and-fixes)
  - [Releasing critical fixes](#Releasing-critical-fixes)

## Priorities

### Prioritizing time

1. Quality
2. Speed
3. Quantity

Though Speed and Quantity are crucial at our stage, the cost of poor Quality far out weighs them both.

### Prioritizing the product

- P0 & P1: playground
- P1+: anything involving credits
- P2+: everything else

The experience must be airtight as soon as a user buys tokens, especially in the playground.

## Engineering principles

Every one at Recess are expected to follow these principles.

- [We seek high standards](#We-seek-high-standards)
- [We commit and follow through](#We-commit-and-follow-through)
- [We are one team](#We-are-one-team)
- [We hunger to learn and share knowledge](#We-hunger-to-learn-and-share-knowledge)

### We seek high standards

- We highlight problems and provide solutions
- We build habits around best practices
- We proactively improve the code and reduce tech debt
- We engineer solutions for others to build upon them

### We commit and follow through

- We own projects from start to finish
- We do not let ourselves be blocked
- We actively communicate with all parties

### We are one team

- We understand diversity makes us stronger
- We make ourselves available to help others
- We listen to one another

### We hunger to learn and share knowledge

- We embrace failures and learn them
- We continuously share and seek feedback from one another
- We collaborate and share projects to spread knowledge
- We continuously challenge acquired knowledge and explore alternative solutions

## Engineering standards and practices

### Code reviews

- Must **thoroughly** review and test own code **before** asking for a review
  - Read every line multiple times
  - Challenge everything you write
  - Actively seek to break your own code
- Pay close attention to poorly worded variables or comments, inconsistencies, inefficient loops (`n * m` vs `n + m`) and error handling
- Understand the scope of the changes made and test beyond the scope of the task
- Request a review from a peer once comfortable with outcome (context switching is expensive!)

### Estimates and deadline commitments

**Engineers are project managers of their own projects.**

Estimating isn't perfect math and experience greatly affects estimate accuracy.

- Split projects into smaller measurable tasks
- Include testing and code reviews in estimates
- **Commit to estimates and deadlines**
- **Communicate early if task/project is slipping**
- Fail, learn and adjust new estimates based on past experience

### Working with Product

- Organize a meeting to get a run down from Product before starting on a project
- Actively seek details when requirements are unclear
- Capture offline conversations and decisions in project management tool

## Engineering ladder

The following is a framework to measure one's level. This framework is very similar to other larger companies such as Google and Twitter. Each level is additive, someone performing at level 4 and is expected to excel at level 3. An engineer is promoted once they've performed at the next level for several months.

Recess' engineering team is small and titles don't make sense yet but this document lays down the expectations.

### Engineer Level 3 (L3 IC)

This is typically the engineer's first full-time engineering job. The focus is on personal development through active learning.

|                              |                                                                                              |
| ---------------------------- | -------------------------------------------------------------------------------------------- |
| **Scope & Impact**           | Writes, tests and documents simple tasks                                                     |
| Technical execution          | Indentifies and fixes issues                                                                 |
|                              | Contributes to code base with supervision from more experienced engineers                    |
| Collaboration                | Searches for solutions and asks for help when necessary                                      |

### Engineer Level 4 (L4 IC)

The engineer is honing on in their individual skills and is starting to have an impact on teammates.

|                              |                                                                                              |
| ---------------------------- | -------------------------------------------------------------------------------------------- |
| **Scope & Impact**           | Writes quality code and documentation and owns projects                                        |
| Technical execution          | Implements code that's clear, optimized and tested                                           |
|                              | Improves tools and code structure                                                            |
| Ownership                    | Owns projects from start to finish and beyond with fixes and improvements                    |
| Collaboration                | Performs code reviews that are valued by peers                                               |

### Engineer Level 5 (L5 IC)

The engineer is honing on in their individual skills and is starting to have an impact on teammates.

|                              |                                                                                              |
| ---------------------------- | -------------------------------------------------------------------------------------------- |
| **Scope & Impact**           | Owns entire projects from design to deployment                                               |
| Technical execution          | Is highly proficient one or more technical areas                                             |
|                              | Writes and contributes to design documentations                                              |
|                              | Improves maintainability and testability via architecture changes                            |
| Ownership                    | Prioritizes projects that improve the team's efficient                                       |
| Collaboration                | Collaborate with direct and adjacent teams to solve problems                                 |
| Team Building                | Helps and mentors other engineers                                                            |
|                              | Participates in engineering interviews                                                       |

### Engineer Level 6 (L6 IC)

WIP

### Engineer Level 7 (L7 IC)

WIP

## Release cycle

This is highly dependent on finding proper github flow.

- Staging deploys: Tuesdays and Thursday
- Production deploys: Friday

### Releasing features

Features are deployed on staging on Tuesdays and scheduled to be deployed on prod on Friday.

Features generally require more time to be tested and a higher turnaround time to address bug fixes.

### Releasing tweaks and fixes

Tweaks & fixes are deployed on staging on Tuesdays and Thursdays and scheduled to be deployed on prod on Friday.

### Releasing critical fixes

Critical fixes can ship any time and if thoroughly tested by an engineer can be deployed to prod right away.
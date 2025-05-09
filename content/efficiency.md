# Software development team efficiency - continuous optimization of match quality

## Research problem

In software development companies, there are some recurring fundamental issues around team efficiency:

* Teams are organized based on experience and subjective opinions, rather than on objective measurements and research findings
* The practices that exist for team formations are often passed along through folklore rather than being based on scientific research
* Team performance is rarely measured and vaguely understood
* Management performance is rarely measured and vaguely understood

Team constellation is important because it fundamentally affects individual performance, team performance, organizational performance, and industry performance. Measuring performance objectively is important because otherwise it becomes subject to subjective interpretations.

The goal of the research is to understand how to improve efficiency of software development teams while maintaining the same level of trust, happiness, and autonomy.

The model should be flexible with respect to goals. Use linear programming, and emphasize that goals can be arbitrary.

Efficiency should be flexible to define, for example by using Data Envelopment Analysis (DEA).

## Questions/hypotheses

* Group efficiency: Optimal number of people in software development teams in terms of economic productivity
* Which performance-based incentives are relevant for engineers
* What is the optimal team size with respect to experience and career goals
* What is the role of managers, if everyone is skilled enough
* How does the different mood states of an individual affect team efficiency, for example positive versus negative moods
* How does stress affect team performance
* Trust-based management versus monitoring
* How to use DEA to measure software development output
* Learning curve application for onboarding new software developers (how introduction material and onboarding will help developer quickly get up to speed compared to getting nothing at all, who needs intro, how much, how to deliver it to lowest cost, etc.)
* Develop pool of organizational successors - tool to help evaluate the extent of the organisations' pending shortage, needed competencies, identify individuals for possible inclusion in pool, establish individually tailored development programs for high-potential candidates, select and place people into senior jobs based on their performance, continuously monitor the program
* EI assessment - performance management tool for assessing if colleagues understand their emotional reactions, and how well they think you understand them. Ask people from another culture or someone with disability. Ask internal or external customers how well you appear to understand their position. Size up a coworker or manager as best as you can. Record your observations and test them against how that person performs or behaves many months later.
* How to make sure topics such as UX design patterns are continuously reinforced for all members without repeating or duplicating teaching
* The culture of continuous learning in contemporary society may also lead to a fear of not learning enough, I have talked to many members who are unsure about their future although I can clearly see they are continuously learning
* How to retain members - is it inherent to the equilibria of the retention model that they will stay a short time
* Enormous pressure you have to use the latest technologies, seldom reflect on what is actually needed, focus becomes more on technology than business value
* There is a value in unlearning as well

## Research design

* Data driven
    * Analyze efficiency over time
* Evaluate software development efficiency
    * Data Envelopment Analysis
        * Code commits
        * Issues resolved per sprint
        * Number of employees in team
    * Together with AHP/ANP
        * Team goal
        * Decide on criteria
        * Use criteria to evaluate task priority
* Model team organization as a continuous optimization problem of match quality
    * Business requirements and candidates continuously change
    * Members can rotate and leave at arbitrary times
    * Link it with DEA
* Interview people randomly in large numbers and ask them who they think the most efficient professionals are

## Theory/literature

* Spence, M. (1973). Job Market Signaling. The Quarterly Journal of Economics, 87(3), 355–374. `https://doi.org/10.2307/1882010`

## Method

* Model beat plan as assignment problem to optimise resource use, while considering learning objectives
* If applied on organization level, workforce assignment with cross-training defined could optimize task assignment
* Investigate how small changes in behavior can drastically change the performance, such as saying good morning in a friendly voice
* Sort out causality by using instrumental variables regression - vacation times for example affect volume of work but not otherwise affect outcomes

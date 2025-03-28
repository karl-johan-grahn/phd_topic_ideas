# PhD topic ideas

## Incident management in software development

### Research problem

In software development, being on-call or on-duty is becoming more and more common with the growth of SaaS (Software as a Service). With site reliability engineering comes incident management responsibility, whose goal is to maintain high availability and reliability of services provided over inherently unstable and unreliable networks. Employees are often treated as disposable units where management often lacks insight or compassion for their short-term and long-term efficiency and health when operating in such roles.

Most companies usually lack processes for implementing effective incident management processes.

Compare with industries, what they can learn from each other, it is usually implemented silo-wise.

The research will focus on how managers should build environments to sustain personal efficiency and health when dealing with frequent incidents in software services. The research should be easy to replicate to other industries, especially since many other professionals are in similar situations, such as medical doctors, fire fighters, police personnel, and military.

This research will also be relevant for the next 10-15 years because over the past decade, the SaaS market has seen a compound annual growth rate of 25% (Deloitte, 2021), and with that comes the need for handling failures.

### Questions/hypotheses

* How is the brain activity different in an incident versus normal use
* How can the brain activity during an incident be compared to other state of mind
* What long-term and short-term impact does incident resolution have on efficiency and health of individuals
* When and how can it be positive to be in a state of incident management
* Which professions and cultures are considered to be most prepared for incident management
    * How does the Japanese school system prepare citizens for incidents
* Which processes are considered the most effective when dealing with incidents
* How to apply a learning curve application for cost-efficient onboarding of incident commanders
* How to train managers to understand and assess emotional reactions during and after incidents
* How can simulation models help in root cause analysis
* How does context-switching from incident response affect short-term and long-term performance

### Research design

* Qualitative data research of process and feelings
    * Interviews with medical doctors, fire fighters, police personal
* Quantitative data research of feelings
    * Brain activity measurements with EEG
        * Control: Activity during normal work
            * With preparation instructions
            * Without preparation instructions
        * Test: Activity with surprise task to imitate an incident
            * With preparation instructions
            * Without preparation instructions
    * Heart rate measurements
    * Participants: Students to retired

### Theory/literature

* Chun, M., and Most, S. (2022) Cognition. New York: Oxford University Press
* Beyer, B., Jones, C., Petoff, J., and Murphy, N. (2016) Site Reliability Engineering. Sebastopol: O'Reilly Media
* Besanko, D., Dranove, D., Shanley, M., and Schaefer, S. (2017) Economics of Strategy. UK: Wiley Custom.
* Keat, P., Young, P., and Erfle, S. (2014) Managerial Economics: Economic Tools for Today's Decision Makers. Essex: Pearson Education Limited
* Deloitte (2021) [SAAS Industry Outlook: Time to Ride the Wave](https://www2.deloitte.com/content/dam/Deloitte/cn/Documents/technology-media-telecommunications/deloitte-cn-tmt-saas-trend-en-211228.pdf)

### Method

* Measure brain activity with EEG using OpenBCI devices
* Let participant perform computer based activities to imitate normal work
* Measure
    * If activity is done correctly
    * Time to perform activity
    * Which brain areas are active
    * Do screen recording to correlate task activity with brain activity
* Pay participants
* Test will take 2 h

## Software development efficiency

### Research problem

In software development companies, teams are often organized based on business needs and subjective impressions, rather than on objective measurements and research findings. Team organization is important because it affects individual performance, team performance, organizational performance, and industry performance. The guidelines that exist for team formation are often passed along through word of mouth rather than researched.

With a focus on software development, the goal of the research is to create an economic model for efficient team organization, which can later be generalized to other industries.

The model should be flexible with respect to goals. Use linear programming, and emphasize that goals can be arbitrary.

Efficiency should be flexible to define, for example by using Data Envelopment Analysis (DEA).

### Questions/hypotheses

* Group efficiency: Optimal number of people in software development teams in terms of economic productivity
* Which erformance-based incentives are relevant for engineers
* What is the optimal team size with respect to experience and career goals
* What is the role of managers, if everyone is skilled enough
* How to use DEA to measure software development output

### Research design

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
* Interview people randomly in large numbers and ask them who they think the most efficient professionals are

### Theory/literature

### Method

* Model beat plan as assignment problem to optimise resource use, while considering learning objectives
* If applied on organization level, workforce assignment with cross-training defined could optimize task assignment
* Investigate how small changes in behavior can drastically change the performance, such as saying good morning in a good voice

## Cloud computing

### Research problem

Evaluate why local cloud providers have a hard time competing against larger vendors.

Suspected behavioral issues:

* Information asymmetry
* Sunk cost

### Questions/hypotheses

* What would make them competitive
* What blocks customers from choosing them
* What drives customer behavior
* What makes customers decide to have their own infra team

### Research design

* Compare with history, from supercomputers, to laptops, mainframes, back to cloud
* Analyze environmental impact, what makes most sense from a global perspective to run such a business

### Theory/literature

### Method

* Porter Five forces analysis

## Internal business generation for SMB

* How to generate new business internally by using existing skills in the organization
* How to encourage innovation
* How to handle knowledge gaps in organizations
* How to handle cultural differences when reaching out to potential customers

## Pricing of software

* How to set the price for software
* What strategies to use to adjust it

## Open source business generation

* When and how to capitalize on open-source code
* Should open-source just be a marketing vehicle

## Misc ideas

### Career progression

* Develop pool of organizational successors - tool to help evaluate the extent of the organisations' pending shortage, needed competencies, identify individuals for possible inclusion in pool, establish individually tailored development programs for high-potential candidates, select and place people into senior jobs based on their performance, continuously monitor the program
* Career assessment
    * Develop a tool for helping achieve a certain position by regularly and frequently probing for examples how you follow traits and styles of that position
    * For example, if you want to achieve a leader position, do you have any recent example of being a servant leader
    * Have you empowered team members to accomplish tasks on their won
* Simulation of career development

### Decision making

* AHP/ANP approach for optimizing decision making in software development
* Who influences decisions vs org chart

### Simulations

* Simulation to find optimal pricing strategy for berry firms
* P510 simulation models for root cause analysis

### Other

* Keeping internal documentation up to date
* Technical debt in software development
    * Based on GitHub data, analyse and see how to efficiently handle technical debt from an economic perspective
    * Relate to sunk costs
    * Should result in a tool
* Learning curve application for onboarding new software developers (how introduction material and onboarding will help developer quickly get up to speed compared to getting nothing at all, who needs intro, how much, how to deliver it to lowest cost, etc.)
* SaaS pricing model for optimising profitability
* Behavioral economic techniques in negotiation and marketing
* Break department barriers between R&D and Sales
* Improve communication between production and marketing to improve SaaS capacity planning
* EI assessment - performance management tool for assessing if colleagues understand their emotional reactions, and how well they think you understand them. Ask people from another culture or someone with disability. Ask internal or external customers how well you appear to understand their position. Size up a coworker or manager as best as you can. Record your observations and test them against how that person performs or behaves many months later.
* Can everybody get wealthier, without anyone getting poorer
    * If income levels are increasing for everyone, who gets poorer
    * Similarly, can everyone at a company improve their career progression, without anyone falling behind
* App development - Solving the shopping problem for local goods delivery
* RFID for optimising food box supply chain and delivery with respect to best before date
* Cloud costs - detailed analysis of cloud costs

## SSF - To write

* Research plan, including scientific state of the art (5 pages). It must be formulated jointly by the company and the HEI and include planned activities between the company and the HEI.
* CV and list of publications for both applicants.
* Letters of intent from both the academic and the industrial party, describing the commitment for the project, written by the department head (or equivalent) at the HEI and the research director (or equivalent) at the company. Both parties shall ensure that the necessary practical arrangements are in place. In addition, it should be certified that the supervisors have the support and time allocated for this purpose.
    * The necessary practical arrangements are in place
    * Supervisors have the support and time allocated for this research
* Brief description and required qualifications of the prospective doctoral student.
    * I am interested in executing an industrial PhD, with the motivation to improve society through knowledge creation. My motive is purely from a knowledge perspective, I do not have any ambition to become a full-time scholarly researcher, I rather want to improve efficiency in the software industry by being a broker between research focused universities and profit focused business ventures.
    * [LinkedIn profile](https://se.linkedin.com/in/karljohangrahn)
* Strategic relevance and expected societal impact in a 10-15-year time-frame.
* Description of how intellectual property rights contractually will be handled.
    * IP rights
* Budget.
    * Salary
    * EEG device
    * Test participant vouchers
    * Conference travel cost
    * Examination event
* Description of the company with details such as corporate ID number, number of employees, net/gross turnover, business activities and a link to webpage.
    * Corporate ID number:
    * Number of employees:
    * Net/gross turnover:
    * Business activities:
    * Webpage:
* Description of any dependencies (current or former) between the company, the doctoral student, the HEI and the supervisors.
    * There is a current dependency between the doctoral student and the company in that the student is employed at the company
    * There are no other current or former dependencies between the company, the doctoral student, the HEI and the supervisors

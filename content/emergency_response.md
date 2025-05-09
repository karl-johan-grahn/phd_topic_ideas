# Emergency response in software development and its impact on mental health

## Research problem

Most research on emergency response centers around:

* Cybersecurity
* Insurance
* Operations

There is not much research of how the human brain is affected by frequent emergency response.

In software development, being on-call or on-duty is becoming more and more common with the growth of SaaS (Software as a Service). Services are operated, maintained, and managed by site reliability engineers. Site reliability engineering has the goal to maintain high availability and reliability of services provided over inherently unstable and unreliable networks. Software as such also has errors. When providing defective services over faulty networks, failures and emergencies will happen when services are deployed and used. This research is focused on how to respond to emergencies.

Software development is done in a highly technical environment and it is easy to fall into the trap of treating people as technological components. Employees can easily become treated as disposable units where management often lacks insight or compassion for their short-term and long-term professional efficiency and mental health. Revenue depends on the number of users of the system, so mental health of employees becomes secondary goal, while technical health of computer systems becomes primary goal. Stress related mental illness is a recurring issue across many workplaces (Johansson, 2025, Ploeg & Kleber, 2003).

Companies usually lack processes for effective emergency response. Emergency response becomes crisis situations where people work without coordination and efficiency. Few engineers know how to act, because the situation is chaotic, unstructured, and urgent, while they have more often been trained in calm, relaxed environments, on structured problems. The few who are brave enough to respond, learn the process the hard way. Folklore for emergency response arise and form the basis for how to do emergency response in the industry, while processes should rather be developed in a structured manner through science.

Processes are usually implemented silo-wise with little knowledge sharing between organizations or industries.

A software emergency can be classified purely as a technical issue, but depending on the software and how it is used, it can have far-spread implications. Impact, severity, and frequency are the typical dimensions to categorize an emergency.

The research will analyze how managers should build environments to sustain personal efficiency and health when dealing with emergency response in software services. The focus is on cost-analysis from a behavioral economic lens, how emergency response affects context-switching on personal level, team level, organizational level, company level. The research should compare emergency response in other industries, since many other professionals are in similar situations, such as medical doctors, fire-fighters, police-personnel, and military.

The hypothesis is that the repetitive pressure to perform in emergency situations has detrimental effects on short-term mental health.

Focus will be on behaviors because emergency response is not a technical issue, it is a people management issue. Understanding human behavior is important for optimizing organizational decisions such as setting up emergency response schedules, understanding the optimal balance between development work versus monitoring work, how to lead emergency response, how to take responsibility.

This research will be relevant for the next 10-15 years because over the past decade, the SaaS market has seen a compound annual growth rate of 25% (Deloitte, 2021), and with growth comes higher expectations on strict uptime SLAs, which requires swift emergency response.

## Questions/hypotheses

* How is the brain activity different in emergency response versus regular mode
* How can the brain activity during an emergency be compared to other states of the mind
* What long-term and short-term impact does emergency response have on efficiency and health of individuals
* When and how can it be positive to be in a state of emergency response
* Which professions and cultures are considered to be most prepared for emergency response
    * How does the Japanese school system prepare citizens for emergency response
* Which processes are considered the most effective when dealing with emergencies
* How to apply a learning curve application for cost-efficient onboarding of emergency commanders
* How to train managers to understand and assess emotional reactions during and after emergencies
* How can simulation models help in root cause analysis
* How does context-switching from emergency response affect short-term and long-term performance
* Is the context-switching cost different for unplanned emergencies and planned work
* How to keep people motivated to be in a sustained sense of awareness for prolonged time, except for bonus payment
* Is root cause analysis about preventing future mistakes, or about learning what happened, compare with Allspaw (2012)

## Research design

* Acquire qualitative data to understand processes, and quantitative data to understand correlation
* How to form causality?
* Qualitative data to understand processes, way of working, way of preparing yourself, handling feelings
    * Do cross-comparison of emergency response across industries by interviewing medical doctors, fire fighters, police personnel, nuclear plant personnel
    * What is unique for each role
    * What is similar for all roles
* Quantitative data to understand how the brain manages emergency response
    * Brain activity measurements with EEG
        * Control group: Perform activities similar to regular work
            * With preparation instructions
            * Without preparation instructions
        * Experiment group: Introduce surprise task to imitate an emergency
            * With preparation instructions - imitate that training has been done
            * Without preparation instructions - imitate a new case
    * Heart-rate measurements
    * Participants: Students to retired
* Longitudinal study of health and performance impact

## Theory/literature

* Chun, M., & Most, S. (2022). Cognition. New York: Oxford University Press.
* Beyer, B., Jones, C., Petoff, J., & Murphy, N. (2016) Site Reliability Engineering. Sebastopol: O'Reilly Media.
* Wilkinson, N., & Klaes, M. (2023). An introduction to behavioral economics, third edition. Great Britain: Bloomsbury Academic.
* Besanko, D., Dranove, D., Shanley, M., & Schaefer, S. (2017). Economics of Strategy. UK: Wiley Custom.
* Keat, P., Young, P., & Erfle, S. (2014). Managerial Economics: Economic Tools for Today's Decision Makers. Essex: Pearson Education Limited.
* Deloitte (2021). SAAS Industry Outlook: Time to Ride the Wave Online `https://www2.deloitte.com/content/dam/Deloitte/cn/Documents/technology-media-telecommunications/deloitte-cn-tmt-saas-trend-en-211228.pdf` (Accessed: 31 March 2025).
* Johansson, Y. (2025). `Expert: Total livsförändring behövs för att bryta utmattning`, Sydsvenskan, 2 April. Available at: `https://www.sydsvenskan.se/2025-04-02/expert-total-livsforandring-behovs-for-att-bryta-utmattning/` (Accessed: 2 April 2025).
* Ploeg, E.V., & Kleber, R.J. (2003). Acute and chronic job stressors among ambulance personnel: predictors of health symptoms. Occupational and Environmental Medicine, 60, i40 - i46.
* Allspaw, J. (2012) Blameless PostMortems and a Just Culture. Available at: `https://www.etsy.com/codeascraft/blameless-postmortems` (Accessed: 9 April 2025).

## Method

Empirical focus will be on how people handle emergency response.

* Data collection
    * Experiment: Let participant perform computer based activities to imitate regular work
    * Measure if activity is done correctly
    * Measure time to perform activity
    * Pay participants
    * Experiment will take 2 h
* Data analysis
    * Time series analysis of brain activity
    * Which brain areas change activity
    * Which brain areas become active
    * Which brain areas become inactive
    * Do screen recording to correlate task activity with brain activity
* Timetable
    * Experiments
    * Analysis
    * Report
* Resource requirements
    * Measure brain activity with EEG using OpenBCI devices
    * Experiment venue

## Ethics

* The use of an EEG will require written approval from experiment participants
* Prepare that they want to share the data, they can and will be anonymous, only need to share control metrics

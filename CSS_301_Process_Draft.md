# Graduation Learning Plan for a Future Component Engineer I
Prepared for: Advising Group
Prepared by: Samuel Hong
## Table of Contents
- [Purpose](#purpose)
- [Best Practices for Building Component Engineering Readiness](#best-practices-for-building-component-engineering-readiness)
  - [Build Strong Datasheet Judgment](#build-strong-datasheet-judgment)
  - [Connect Coursework to Real Component Decisions](#connect-coursework-to-real-component-decisions)
  - [Develop Documentation and Traceability Habits](#develop-documentation-and-traceability-habits)
  - [Use Projects to Prove Selection and Validation Skills](#use-projects-to-prove-selection-and-validation-skills)
- [Figure 1. Component Engineer I Preparation Roadmap](#figure-1-component-engineer-i-preparation-roadmap)
- [References](#references)

## Purpose
This document is written for electrical engineering students who are interested in becoming stronger candidates for component engineering or hardware engineering and will explain the best practices that will prepare you for a Component Engineer I role by the time you graduate. It focuses on habits and experiences that make you prepared rather than just relying on coursework alone. Instead of basic advices that most electrical engineers hear, it distinguishes the patterns of preparation that matches more with a component engineer role. If you follow these practices consistently, you graduate with stronger knowledge which includes evaluating parts, justifying decisions on component choices, and communicating those decisions clearly. 

## Best Practices for Building Component Engineering Readiness

### Build Strong Datasheet Judgment
**Why this matters:**  
Datasheets contain the limits, assumptions, and operating conditions that determine whether a component will actually work in a real system. Choosing a part based only on one rating can lead to problems such as reliability, thermal, cost, or availability.

**What to do:**  
When reviewing a component, compare the absolute maximum ratings, recommended operating conditions, thermal limits, package type, tolerance, and availability. Then report why the part is acceptable for the specific circuit or system.

**Example:**  
When checking a MOSFET for a high switching application, do not only check the voltage and current rating. Also check RDS(on), gate charge, thermal resistance, package size, and whether the part is available from multiple suppliers.[^1][^2]

### Connect Coursework to Real Component Decisions
**Why this matters:**  
Electrical engineering coursework gives you the background needed to understand why certain components are selected. Various EE courses including electives like power electronics, EMI, circuit theory can help you explain voltage ratings, current limits, power loss, signal behavior, and reliability concerns.

**What to do:**  
Use what you learned from the courses to justify component choices in projects. When you choose a resistor, capacitor, diode, transistor, connector, or IC, explain which course concept supports that decision.

**Example:**  
In an electronics or power electronics project, use circuit analysis to calculate expected current, voltage, and power dissipation. Then use those values to choose a component with appropriate ratings to narrow down the exact components you can choose for your circuit.[^1][^3]

### Develop Documentation and Traceability Habits
**Why this matters**
Documenting short and concise list of components you selected that has information such as component parameters, description of why you chose this specific component, any alternatives considered, and what trade-offs you accepted is important due to working with other engineers that are either not focusing on component selection or introduced to a project later which enables them to catch up. 

**What to do**
After choosing the appropriate components for your circuit, make a excel sheet and list the components' manufacturer, voltage and current ratings, quantity, and more information needed. 

**Example:**
After finding a diode that is necessary for the buck-converter you're working on, list the diode's information into the excel sheet. The manufacturer is Infineon, the voltage rating is 30 V and current rating is 1 A, and you need to buy three. The extra 2 are bought in case one gets broken. 
[^2][^4]

### Use Projects to Prove Selection and Validation Skills
**Why this matters**
Choosing any project that will translate ideal and theoretical schematics and concepts to an actual real-world circuit, like PCBs, will force you to make careful choices regarding components' parameters. This kind of experience will stand out to recruiters, due to your justification of choosing various components. 

**What to do**
Find a project that you want to do, which can be found in various platforms like youtube or reddit (r/ElectricalEngineering) or even from professors that can recommend you basic projects to start off. Bringing your interest in starting a project to a professor can even lead you to their undergraduate research which would be signficantly better.

**For example:**
Ask a professor specialized in RF, and he recommends you doing a project where you match an antenna at 50 ohms in a different frequency of a manufactured antenna. This kind of project requires specific capacitors and inductors to match the antenna at a frequency you desire. After analyzing and calculating the required capacitors and inductors, you try to find and purchase these components and make sure the inductors are thin film and capacitors are ceramic capacitors, since they are best suited on high frequencies rather than beam-lead components. 
[^1][^2]

## Figure 1. Component Engineer I Preparation Roadmap
![Component engineer roadmap](https://raw.githubusercontent.com/samuelhong2004/Process/blob/main/Component%20Selection%20Workflow.png)

## References
[^1]: Crane Company, “Component Engineer I-III,” MyWorkDayJobs.com. [Online]. Available: https://cranecompany.wd5.myworkdayjobs.com/en-US/Careers/job/Component-Engineer-III_JR100555. [Accessed: Apr. 15, 2026].
[^2]: J. Sartin, “Beyond the BOM: Proactive Component Selection,” Altium Resources, Apr. 22, 2025. [Online]. Available: https://resources.altium.com/p/proactive-component-selection. [Accessed: Apr. 15, 2026].
[^3]: T. Swallow, “Design Verification Made Simple: How to Validate Your Component Choices Before Prototyping,” Altium Resources, Sep. 23, 2025. [Online]. Available: https://resources.altium.com/p/how-to-validate-component-choices-before-prototyping. [Accessed: Apr. 15, 2026].
[^4]: “How to Manage Electronic Component Obsolescence,” Altium Resources, Oct. 7, 2024. [Online]. Available: https://resources.altium.com/p/managing-electronic-component-obsolescence-practical-insights-engineering-managers. [Accessed: Apr. 15, 2026].

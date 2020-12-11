```
ptg
```
# Vision Document template

```
Company Name
```
```
Vision Document for NICU Application
```
```
© 2020 University of Oklahoma
```
## Revision History

```
12/10/20 1.0 Initial version Group 30
```
## Table of Contents

1 Introduction...................................................................  
1 .1 Purpose.................................................................  
1 .2 Solution Overview..........................................................  
1 .3 References...............................................................  

2 UserDescription...............................................................  
2 .1 User/Market Demographics..................................................  
2 .2 User Personas............................................................  
2 .3 User Environment..........................................................  
2 .4 Key User Needs...........................................................  
2 .5 Alternatives and Competition.................................................  

3 Stakeholders..................................................................  

4 Product Overview..............................................................  
4 .1 Product Perspective........................................................  
4 .2 Product Position Statement..................................................  
4 .3 Summary of Capabilities.....................................................  
4 .4 Assumptions and Dependencies..............................................  
4 .5 Cost and Pricing...........................................................  

```
Page 1 of 8
```

```
ptg
```
5 Product Features...............................................................  
5 .1 Feature 1................................................................  
5 .2 Feature 2................................................................  

6 Exemplary Use Cases...........................................................  

7 Nonfunctional Requirements......................................................  
7 .1 Usability.................................................................  
7 .2 Reliability.................................................................  
7 .3 Performance..............................................................  
7 .4 Supportability..............................................................  
7 .5 Other Requirements........................................................  

8 Documentation Requirements.....................................................  
8 .1 User Manual..............................................................  
8 .2 Online Help...............................................................  
8.3 Installation	Guides,	Configuration,	“Read	Me”	File	.................................  
8 .4 Labeling and Packaging.....................................................  

9 Glossary.....................................................................

## 1 Introduction

This section provides an overview of the Vision document.

**_1.1 Purpose_**

This document defines the strategic intent of the program. It defines high-level user
needs, any applicable user personas, key stakeholders, and the general system capabilities
needed by the users.

**_1.2 Solution Overview_**

State the general purpose of the product, system, application or service, and any version
identification.

- Identify the product or application to be created or enhanced.
- Describe the application of the product, including its benefits, goals, and
    objectives.
- Provide a general description of what the solution will and, where appropriate,
    will not do.
       Page 2 of 8


```
ptg
```
**_1.3 References_**

List other documents referenced, and specify the sources from which the references can
be obtained. If a business case (Chapter 23) was developed to drive the program, refer to
it or attach it.

## 2 User Description

To provide products and services that meet users’ needs, it is helpful to understand the
challenges they confront when performing their jobs. This section should profile the
intended users of the application and the key problems that limit the user’s productivity.
This section should not be used to state specific requirements; just provide the back-
ground for why the features specified in Section 5 are needed.

**_2.1 User/Market Demographics_**

Summarize the key market demographics that motivate your solution decisions. Describe
target-market segments. Estimate the market’s size and growth by the number of poten-
tial users or the amount of money your customers spend, trying to meet needs that your
product/enhancement would fulfill. Review major industry trends and technologies.
Refer to a market analysis, where available.

**_2.2 User Personas_**

Describe the primary and secondary user personas (see Chapter 7). A thorough analysis
might cover the following topics for each persona:

- Te c h n i c a l b a c k g r o u n d a n d d e g r e e o f s o p h i s t i c a t i o n
- Key responsibilities
- Deliverables the user produces and for whom
- Tr e n d s t h a t m a k e t h e u s e r ’s j o b e a s i e r o r m o r e d i f fi c u l t
- The user’s definition of success and how the user is rewarded
- Problems that interfere with success

```
Page 3 of 8
```

```
ptg
```
**_2.3 User Environment_**

Describe the working environment of the target user. Here are some suggestions.

- How many people are involved in completing the task? Is this changing?
- How long is a task cycle? How much time is spent in each activity? Is this changing?
- Are there any unique environmental constraints: controlled environment,
    mobile, outdoors, and so on?
- Which system platforms are in use today? Future platforms?
- What other applications are in use? Does your application need to integrate
    with them?

**_2.4 Key User Needs_**

List the key problems or needs as perceived by the user. Clarify the following issues for
each problem.

- What are the reasons for this problem?
- How is it solved now?
- What solutions does the user envision?

Ranking and cumulative-voting techniques for these needs indicate problems that _must_
be solved versus issues the user would _like_ to be solved.

**_2.5 Alternatives and Competition_**

Identify any alternatives available to the user. These can include buying a competitor’s
product, building a homegrown solution, or simply maintaining the status quo. List any
known competitive choices that exist. Include the major strengths and weaknesses of each
competitor as perceived by the end user.

_2.5.1 Competitor 1_

_2.5.2 Competitor 2_

```
Page 4 of 8
```

```
ptg
```
## 3 Stakeholders

Identify the program stakeholders, their needs, and their degree of involvement with the
system. A table such as the following can be effective:

```
Project
Stakeholder
```
```
Degree of
Involvement
```
```
Product Needs Program Needs
```
```
Stakeholder 1
Stakeholder 2
```
## 4 Product Overview

**_4.1 Product Perspective_**

Our product will be designed for use in a NICU ward within a hospital. As such, it will need
to interact with the systems the hospital already has in place. Much of the data is stored in
Excel files, so our program will need to be able to read and write to that or a similar file
format. It should also integrate into the established rhythms and physical systems present in
the hospital. 

**_4.2 Product Position Statement_**

Our product is for hospitals and NICU wards who want to efficiently delegate tasks to nurses. 
Our product is a desktop application that performs the tedious bookkeeping tasks which sap time 
away from qualified nurses. Unlike manual assignment methods, our product creates assignments quickly
with little effort required from the user. 

```
Page 5 of 8
```

```
ptg
```

**_4.3 Summary of Capabilities_**

|Features|Benefit|
|--------|-------|
|Automatic nurse assignment|More time for nurses to do nurse work|
|Automatic assignment logging|Less hassle to digitize log data|
|Automated communication|Faster notifications, more efficient than manual|
|Organized data entry|Easier for a trainee to learn to use|

**_4.4 Assumptions and Dependencies_**

We assume we will have dummy data to work with and good communication with the hospital staff.
If the staff provides new information or changes the specifications, our product will need to 
adapt accordingly. We also depend on them having a reliable computer to run our product on.


**_4.5 Cost and Pricing_**

This product requires no licenses, server time, or other elements that could add to the cost,
so it will likely be free to produce. Should we choose to market it, we will judge how well it
turned out and price it accordingly.

```
Page 6 of 8
```

```
ptg
```
## 6 Exemplary Use Cases

[Optional] You may want to describe a few exemplary use cases, perhaps those that are
architecturally significant or those that will most readily help the reader understand how
the system is intended to be used.

## 7 Nonfunctional Requirements

This section records other system requirements including nonfunctional requirements
(constraints) imposed on the system (see Chapter 17).

**_7.1 Usability_**

**_7.2 Reliability_**

**_7.3 Performance_**

**_7.4 Supportability_**

**_7.5 Other Requirements_**

_7.5.1Applicable Standards_

List all standards the product must comply with, such as legal and regulatory, communi-
cations standards, platform compliance standards, and quality and safety standards.

_7.5.2 System Requirements_

Define any system requirements necessary to support the application. These may include
the host operating systems and network platforms, configurations, communication,
peripherals, and companion software.

_7.5.3 Licensing, Security, and Installation_

Licensing, security, and installation issues can also directly impact the development
effort. Installation requirements may affect coding or create the need for separate instal-
lation software.

```
Page 7 of 8
```

```
ptg
```
## 8 Documentation Requirements

This section describes the documentation that must be developed to support successful
deployment and use.

**_8.1 User Manual_**

Describe the intent of the user manual. Discuss desired length, level of detail, need for
index and glossary, tutorial versus reference manual strategy, and so on. Formatting, elec-
tronic distribution, and printing constraints should also be identified.

**_8.2 Online Help_**

The nature of these systems is unique to application development since they combine
aspects of programming and hosting, such as hyperlinks and web services, with aspects of
technical writing, such as organization, style, and presentation.

**_8.3	 Installation	Guides,	Configuration,	“Read	Me”	File	_**

A document that includes installation instructions and configuration guidelines is typ-
ically necessary. Also, a “read me” file is often included as a standard component. The
“read me” file may include a “What’s New with This Release” section and a discussion of
compatibility issues with earlier releases. Most users also appreciate publication of any
known defects and workarounds.

**_8.4 Labeling and Packaging_**

Defines the requirements for labeling to be incorporated into the code. Examples include
copyright and patent notices, corporate logos, standardized icons, and other graphic
elements.

## 9 Glossary

The glossary defines terms that are unique to the program. Include any acronyms or
abbreviations that need to be understood by users or other readers.

```
Page 8 of 8
```

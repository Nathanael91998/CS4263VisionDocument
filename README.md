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


**_1.1 Purpose_**

The purpose of this document is to outline the goal of the project, identify key users and 
stakeholders, and list the necessary requirements for the product. 


**_1.2 Solution Overview_**

The purpose of this program is to assist charge nurses with assigning oncoming scheduled nurses
to NICU infants at the beginning of each shift based on a matching algorithm for nursing and
patient characteristics. The system should be able to show updated data and assignments for all users 
when changes are made to the assignments.  The software will suggest available nurses for each room based
off of their capabilities, the patients characteristics, and availabilty.  


**_1.3 References_**

Information for this vision document was obtained through emails with our contacts at the hospital in addition to 
an online meeting with them.  There was also an initial document sent by the contacts at the hospital outlining
the project and its purpose.

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

This section provides a high-level view of the solution capabilities, interfaces to other
applications, and systems configurations. This section usually consists of five subsections,
as follows.

**_4.1 Product Perspective_**

This subsection should put the product in perspective to other related products and the
user’s environment. If the product is independent and totally self-contained, state so. If
the product is a component of a larger system, this subsection should relate how these
systems interact and should identify the relevant interfaces among the systems. One easy
way to display the major components of the larger system, interconnections, and external
interfaces is via a system context block diagram.

**_4.2 Product Position Statement_**

Provide an overall statement summarizing, at the highest level, the unique position the
product intends to fill in the marketplace. Moore [1991] calls this the product position
statement and recommends the following format.

```
For (target customer)
Who (statement of the need or opportunity)
The (product name) is a (product category)
That (statement of key benefit, that is, compelling rea son to buy)
Unlike (primary competitive alternative)
Our product (statement of primary differentiation)
```
```
Page 5 of 8
```

```
ptg
```
A product position statement communicates the intent of the application and the impor-
tance of the program to all stakeholders.

**_4.3 Summary of Capabilities_**

Summarize the major benefits and features the product will provide. Organize the fea-
tures so that the list is understandable to any stakeholder. A simple table listing the key
benefits and their supporting features, as shown below, might suffice.

```
Solution Features Customer Benefit
Feature 1 Benefit 1
Feature 2 Benefit 2
```
**_4.4 Assumptions and Dependencies_**

List any assumptions that, if changed, will alter the vision for the product.

**_4.5 Cost and Pricing_**

Describe any relevant cost and pricing constraints, because these can directly impact the
solution definition and implementation.

## 5 Product Features

This section describes the intended product features. Features provide the system capa-
bilities that are necessary to deliver benefits to the users. Feature descriptions should be
short and pithy, a key phrase, perhaps followed by one or two sentences of explanation.

Use a level of abstraction high enough to be able to describe the system with a maximum
of 25 to 50 features. Each feature should be perceivable by users, operators, or other exter-
nal systems.

**_5.1 Feature 1_**

**_5.2 Feature 2_**

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

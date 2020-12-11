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

This software looks to assist charge nurses with assigning oncoming scheduled nurses
to NICU infants at the beginning of each shift based on a matching algorithm for nursing and
patient characteristics. The system should be able to show updated data and assignments for all users 
when changes are made to the assignments.  The software will suggest available nurses for each room based
off of their capabilities, the patients characteristics, and availabilty.  


**_1.3 References_**

Information for this vision document was obtained through emails with our contacts at the hospital in addition to 
an online meeting with them.  There was also an initial document sent by the contacts at the hospital outlining
the project and its purpose.

## 2 User Description

**_2.1 User/Market Demographics_**

Nurses in the neonatal intensive care unit at OU Children's Hospital currently have to 
assign nurses to patients by hand, using a paper spreadsheet. The roster is printed out from a
facility scheduler for the staff assigned each day for the night shift and the following day
shift.  Nurses are writeen into assignments by hand as well as phone number assigned to the nurse.
The key demographic for our software would be these nurses, as well as those who are in charge of
creating the spreadsheet.  This program could also potentially be used by other hospitals with 
a similar lack of automated assignment software.

**_2.2 User Personas_**

The first primary user would be the nurses that use the software to assign the upcoming nurses
to different patients.  The nurses would have a medical background and should have basic technical
capabilites to navigate the software.  The responsibilities of the nurses are to create an schedule 
that utilizes the other nurses' time efficiently. The nurses' jobs of assigning incoming nurses should
be made easier by the software that suggests the best nurses for each of the rooms/patients.  The
user should be able to succeed in creating the best schedule.  A problem that might interfere with 
success would be if the software fails to update or is inaccessable by other nurses. Another primary
user would be the IT specialists that are in charge of keeping the program running smoothly.  Since 
the software will have to be HIPAA compliant, it must be hosted by their secure systems and be maintained
by OU Hospital employees.


**_2.3 User Environment_**

The environment will have multiple nurses accessing the room assignment information with the ability
to update assignemnts themselves.  Whether there are specific nurses that have priveleges to 
update this information or if all will have access is currently undetermined.  The task cycle should
be able to be completed during the windows in between shifts.  The software must be HIPAA
compliant and in a controlled environment to prevent security compromises.  It may be later ported
to iOS to allow nurses to use the software on iPads, but the current development will be a .NET 
application.  The software must be able to interact with the current systems that the hospital uses
to access patient information, as it relies on it to suggest the correct nurses for each assignment.

**_2.4 Key User Needs_**

The main issue with the current system is that it requires the nurses to manually find and choose
the best nurse for each assignment.  This can be difficult as there are many aspects to consider
when deciding this.  The system is also currently being conducted on paper, and doesn't allow for quick,
clean updates that is readily accessible by everybody who might need the infromation.  The users envision
a program that will create lists of nurses that can be assigned to specific rooms, and one that will also be able to suggest
which ones would be most efficient.


**_2.5 Alternatives and Competition_**

There are currently other applications that look to optimize nurse shift scheduling. Some of
these include Smartlinx, Intrigma, and other companies.  These competitors have established
software applications that are able to assign nurses to patients in an efficient manner.  The main
weakness of these applications is the pricing, as our product would be completely free.  There is 
also flexibility to our application, as we will be tailoring it to the needs of the NICU nurses.
Companies that uses their software also have to rely on the company to keep the product updated and running,
whereas our product would be maintained by OU hospital employees.

## 3 Stakeholders

| Project Stakeholder | Degree of Involvement | Product Needs | Program Needs |
| ------------------- | --------------------- | ------------- | ------------- |
| Children's Hospital (as an entity) | Govern's operations every day. | Need product to perform efficiently and reliably. | Need program to be easily teachable and usable for all parties concerned. |
| Us (creators of the product) | Those who will be building the product for the hospital. | Need product to take reasonable development time and be well-built and understood in the end. | Need program to be fully understood and act how we expect when we expect, be knowledgeable of all ins and outs of it. |
| Patients | Those who need daily care in the hospital and who depend greatly on the organization and efficiency of the hospital. | Need product to benefit them and provide them with safety and security by means of use by the employees. | Need to program to be easily understood and reliably understood by the employees, those caring for them. |
| Nurses/Employees | Need to stay organized and care for the patients they are assigned in a timely manner. | Need product to have longevity, and to make sense to use. Need it to benefit and enhance their workflow, never hinder. | Need program to have connectivity between all types of employees, and to move quicker than they need to be able to move, so they can always be on top of what is happening, and be able to react and perform efficiently consistently. |

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

The user manual is intended to be concise but very thorough, covering all areas of the application in a well organization and clear manner. It will be written simply and clearly in basic english, covering only what is specifically necessary and a part of the application. In other words, as short as possible, while covering every detail - an easy read. We want anyone at the hospital to be able to pick it up and figure it out, which reflects much of the application's intent, itself. An index would be very important, at the front of the book for easy reference and a small glossary could help with defining any medical words unknown. The strategy would be to describe everything, and let those descriptions garner their own worth in the mind of the one using it, as they will know the importance of some functions compared to others. It will be formatted with page numbers, a standard font that is used and native to all platforms, and in black in white. Color will not be necessary, this will make printing much cheaper. All that is required is that the information gets to the reader's brain in a quick and clear way. 

**_8.2 Online Help_**

There can be an FAQ style area online, for common concerns, and even more rare issues. We will cover everything that is reasonably necessary in order to at least give a head start, if not a solution, to the problem one may be experiencing. 

**_8.3	 Installation	Guides,	Configuration,	“Read	Me”	File	_**

These can be in the form of digital files. An installation guide would likely be a pdf, and the readme either a pdf or a simple text file, for portability and simplicity. Pdf could work fine as well. There would likely be an intro section at the top of the document, as section for addressing the changes, fixes, updates, etc. to the current verson and possibly some links at the bottom for more documentation, as well as contact information should they need assistance. This should be sufficient to give the user good information and get them on their feet. 

**_8.4 Labeling and Packaging_**

Most likely this will not be necessary for us. At most we will need permission to use an emblems/logos owned by the hospital, in order to officially put a badge on the product saying that it is shared between us and them, and intended for their use and their use only. For now, this would be sufficient. 

## 9 Glossary

The glossary defines terms that are unique to the program. Include any acronyms or
abbreviations that need to be understood by users or other readers.

```
Page 8 of 8
```

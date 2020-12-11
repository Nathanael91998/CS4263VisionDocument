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

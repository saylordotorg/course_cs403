---
layout: default
title: "CS403: Introduction to Modern Database Systems"
course_description: "A study of database architecture and the components used in implementation. Topics include using the Structured Query Language, file structures and access methods, database modeling, design, and user interface,components of database management systems, and information storage and retrieval."
next: ../Unit02
previous: ../Intro
---
**Unit 1: Introduction to Modern Database Systems** <span
id="1"></span> 
*Different databases serve different purposes; each one is dependent
upon both deployment environment and different types of user
interactions.  In this unit, we will ask a number of questions
pertaining to databases: What are some database environments and user
types?  How can the database management system ensure control over data
integrity, avoid data redundancy, and secure data, while at the same
allowing interactions with different user types?  In answering these
questions, we will identify and determine the characteristics of
databases, their many deployment environments, and the different
categories of users that interact with it. *

**Unit 1 Time Advisory**  
This unit will take you approximately 3 hours and 15 minutes to
complete.  
  
 ☐    Subunit 1.1: 30 minutes  
  
 ☐    Subunit 1.2: 1.75 hours
  
 ☐    Reading: 1.5 hours  
  
 ☐    Video: 15 minutes

☐    Subunit 1.3: 1 hour

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
  
-   Explain the difference between data and information.
-   Contrast file processing systems to database systems.
-   Describe what a database management system is and how it functions.
-   Compare the various database models.

**1.1 Databases: Definition and Characteristics** <span
id="1.1"></span> 
-   **Reading: Professor Giora Baram and Frank Friedman, Temple
    University: CIS109—Lecture Notes—“Part One”**
    Link: Professors Giora Baram and Frank Friedman, Temple University:
    CIS109—Lecture Notes— [“Part
    One”](http://web.archive.org/web/20131106020158/http://ww2.cis.temple.edu/cis109friedman/CIS%20109%20-%20Lecture%20Set%20I%20-%20Introduction%20and%20Overview/AAA%20Lecture%20Set%20I%20-%20Intro%20Material%20Ver%202.htm)
    (HTML)  
        
     Instructions: Read sections 1–3.  You do not need to download the
    MSAccess sample database and you can ignore the Access tutorials
    since we will use MySQL in this course.  Please note that this
    reading applies to all of the sections listed under 1.1, including
    1.1.1 –1.1.4.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Adrienne Watt & Nelson Eng's *Database Design,
    2<sup>nd</sup> ed.*: "Chapter 2: Fundamental Concepts"**
    Link: Adrienne Watt & Nelson Eng's Database Design, 2<sup>nd</sup>
    ed.: ["Chapter 2: Fundamental
    Concepts"](http://www.saylor.org/site/wp-content/uploads/2014/12/CS403-1.10-Database-Design-2nd-Edition-CCBY.pdf)
    (HTML)  
      
     Instructions: Read Chapter 2: Fundamental Concepts on pages 6-8.
    Complete the short exercises at the end of the chapter on page 8.  
      
     Reading this chapter and completing the exercises should take you
    approximately 15 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution 4.0 International
    License](http://creativecommons.org/licenses/by/4.0/). It is
    attributed to Adrienne Watt and Nelson Eng, and the original verison
    can be found
    [here](http://opentextbc.ca/dbdesign01/chapter/chapter-2-fundamental-concepts/).

-   **Reading: James F. Courtney & David B. Paradice's Database Systems
    for Management, 3rd ed.: "Chapter 1: Introduction to Database
    Systems"**
    Link: James F. Courtney & David B. Paradice's *Database Systems for
    Management, 3<sup>rd</sup> ed.*: ["Chapter 1: Introduction to
    Database
    Systems"](http://www.saylor.org/site/wp-content/uploads/2014/12/CS403-1.10-Database-Systems-for-Management-CCBY.pdf)
    (PDF)  
      
     Instructions: Please read Chapter 1 of this textbook on pages 1-19.
    The text references figures and images that can be found in an
    appendix in the pages following the chapter text.  
      
     Reading this chapter should take you approximately 20 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution 3.0
    License](http://creativecommons.org/licenses/by/3.0/). It is
    attributed to James F. Courtney and David B. Paradice, and the
    original verison can be found
    [here](https://dl.dropboxusercontent.com/u/31779972/Database%20Systems%20for%20Management.pdf).

**1.1.1 File Processing vs. Database Approach** <span
id="1.1.1"></span> 
**1.1.2 What Is a Database?** <span id="1.1.2"></span> 
**1.1.3 Data vs. Information** <span id="1.1.3"></span> 
**1.1.4 Properties of a Database** <span id="1.1.4"></span> 
**1.1.4.1 Persistent** <span id="1.1.4.1"></span> 
**1.1.4.2 Programmable Interface** <span id="1.1.4.2"></span> 
**1.1.4.3 Transaction Management** <span id="1.1.4.3"></span> 
**1.1.5 Centralized vs. Distributed** <span id="1.1.5"></span> 
**1.2 Database Usage and Environment** <span id="1.2"></span> 
**1.2.1 Data and Databases** <span id="1.2.1"></span> 
-   **Reading: Penn State’s Database Fundamentals: “Lesson 1: The Value
    of Data and Databases”**
    Link: Penn State’s Database Fundamentals: [“Lesson 1: The Value of
    Data and
    Databases”](http://www.personal.psu.edu/nas21/IST110/Readings_DatabaseFundamentals.html)(HTML)  
        
     Instructions: This page provides a number of brief lessons on
    database management systems. Read Lesson 1.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.2.2 The Integrated Database Environment** <span id="1.2.2"></span> 
-   **Reading: Penn State’s Database Fundamentals: “Lesson 4: An
    Introduction to Database Management Systems”**
    Link: Penn State’s Database Fundamentals: [“Lesson 4: An
    Introduction to Database Management
    Systems”](http://www.personal.psu.edu/nas21/IST110/Readings_DatabaseFundamentals.html)
    (HTML)  
        
     Instructions: Scroll down and read Lesson 4.  Note that this lesson
    also applies to the topics outlined in sections 1.2.2.1–1.2.2.4.    
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Stanford University’s Introduction to Databases:
    Lecture 1: “Intro to Databases”**
    Link: Stanford University’s Introduction to Databases: Lecture 1:
    [“Intro to Databases”](http://www.youtube.com/watch?v=D-k-h0GuFmE)
    (YouTube)  
        
     Instructions: Watch the entire video. This video applies to the
    topics outlined in sections 1.2.2.1–1.2.2.4  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.2.2.1 The Database** <span id="1.2.2.1"></span> 
**1.2.2.2 The Database Management System (DBMS)** <span
id="1.2.2.2"></span> 
**1.2.2.2.1 Facilities Provided by DBMS** <span id="1.2.2.2.1"></span> 
**1.2.2.2.2 Characteristics of a DBMS** <span id="1.2.2.2.2"></span> 
**1.2.2.2.3 Define the Database** <span id="1.2.2.2.3"></span> 
**1.2.2.2.4 Construct and Manipulate the Database** <span
id="1.2.2.2.4"></span> 
**1.2.2.2.5 Maintain and Secure the Database** <span
id="1.2.2.2.5"></span> 
**1.2.2.3 Functions of a DBMS** <span id="1.2.2.3"></span> 
**1.2.2.3.1 Control Data Redundancy** <span id="1.2.2.3.1"></span> 
**1.2.2.3.2 Avoid Data Inconsistencies** <span id="1.2.2.3.2"></span> 
**1.2.2.3.3 Enforce Security and Integrity Constraints** <span
id="1.2.2.3.3"></span> 
**1.2.2.3.4 Allow for Different Ways of Interaction with the User**
<span id="1.2.2.3.4"></span> 
**1.2.2.4 People in Integrated Database Environment** <span
id="1.2.2.4"></span> 
-   **Reading: jkinfoonline.com's “Database Systems Environment”**
    Link: jkinfoonline.com's “[Database Systems
    Environment](http://www.jkinfoline.com/dbms-introduction.html)”
    (HTML)  
        
     Instructions: Read the section on people.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.2.2.4.1 End Users** <span id="1.2.2.4.1"></span> 
**1.2.2.4.2 Application Programmers** <span id="1.2.2.4.2"></span> 
**1.2.2.4.3 Database Administrator** <span id="1.2.2.4.3"></span> 
**1.3 Classification of Database Management Systems** <span
id="1.3"></span> 
-   **Reading: Penn State’s Database Fundamentals: “Lesson 5: Types of
    Database Management Systems”**
    Link: Penn State’s Database Fundamentals: [“Lesson 5: Types of
    Database Management Systems”](http://archive.is/VVkhs) (HTML)  
        
     Instructions: Read this lesson. Note: this reading applies to all
    of section 1.3.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.



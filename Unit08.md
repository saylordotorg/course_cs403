---
layout: default
title: "CS403: Introduction to Modern Database Systems"
course_description: "A study of database architecture and the components used in implementation. Topics include using the Structured Query Language, file structures and access methods, database modeling, design, and user interface,components of database management systems, and information storage and retrieval."
next: ../Unit09
previous: ../Unit07
---
**Unit 8: Introduction to SQL** <span id="8"></span> 
*Structured Query Language (SQL) is the main data definition language
used for the creation and maintenance of databases.  In this unit,* *we
will look at basic SQL syntax, including some data definition and data
manipulation language commands.*

**Unit 8 Time Advisory**  
This unit will take you approximately 14 hours and 35 minutes to
complete.  
  
 ☐    Subunit 8.1: 3 hours 35 minutes  
  
☐    Reading: 3 hours and 30 minutes  
  
 ☐    Video: 5 minutes

☐    Subunit 8.2: 5 hours  
  
 ☐    Subunit 8.3: 3 hours  
  
 ☐    Subunit 8.4. 3 hours

**Unit8 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Compare DDL commands to DML commands.
-   Discuss when to use the appropriate SQL commands.
-   Create a set of database tables using DDL.
-   Describe the various types of integrity constraints and how they are
    used.

**8.1 Overview** <span id="8.1"></span> 
-   **Web Media: Stanford University’s Introduction to Databases:
    Lecture 6: “Introduction to SQL”**
    Link: Stanford University’s Introduction to Databases: Lecture 6:
    [“Introduction to SQL”](http://www.youtube.com/watch?v=wxFmiRwXcQY)
    (YouTube)  
        
     Instructions: Please watch the entire video.  Note: this applies to
    all of section 8.1.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.1.1 What Is SQL?** <span id="8.1.1"></span> 
-   **Reading: W3Schools.com’s “Introduction to SQL”**
    Link: W3Schools.com’s “[Introduction to
    SQL](http://www.w3schools.com/sql/sql_intro.asp)” (HTML)  
        
     Instructions: Please read the entire webpage for a brief
    introduction to the definition and function of Structured Query
    Language (SQL).  W3Schools.com is a website with tutorials on many
    Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Beat Signer’s Lecture 5: Introduction to Databases**
    Link: Beat Signer’s Lecture 5: [Introduction to
    Databases](http://www.slideshare.net/signer/structured-query-language-sql-lecture-5-intro)
    (Adobe Flash)  
        
     Instructions: Please read through all slides.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.1.2 SQL Syntax** <span id="8.1.2"></span> 
-   **Reading: W3Schools.com’s “SQL Syntax”**
    Link: W3Schools.com’s “[SQL
    Syntax”](http://www.w3schools.com/sql/sql_syntax.asp) (HTML)  
        
     Instructions: Please read the entire webpage.  W3Schools.com is a
    website with tutorials on many Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.2 Data Definition Language (DDL) Commands** <span id="8.2"></span> 
-   **Web Media: ProgrammingVideos.Com: SQL Tutorial 03–Create–Database,
    Table, Index**
    Link: ProgrammingVideos.Com: [SQL Tutorial 03–Create–Database,
    Table, Index](http://www.youtube.com/watch?v=iwxwmUMadOg) 
    (YouTube)  
        
     Instructions: Watch the entire video.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.2.1 Create Table** <span id="8.2.1"></span> 
-   **Reading: SQLTutorial.org’s “SQL CREATE TABLE”**
    Link SQLTutorial.org’s “[SQL CREATE
    TABLE](http://www.sqltutorial.org/sqlcreatetable.aspx)” (HTML)  
        
     Instructions: Read through the entire tutorial to learn how to use
    SQL to create a database table.  The SQL Tutorial website was
    created to provide you clear, concise and easy to understand
    SQL Tutorial.  
                  
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.2.2 Drop Table** <span id="8.2.2"></span> 
-   **Reading: SQLTutorial.org’s “SQL DROP TABLE”**
    Link: SQLTutorial.org’s “[SQL DROP
    TABLE](http://www.sqltutorial.org/sql-drop-table.aspx)” (HTML)  
        
     Instructions: Read through the entire tutorial to learn how to use
    SQL to delete data from a table and to remove the structure of the
    table.  The SQL Tutorial website was created to provide you clear,
    concise and easy to understand SQL Tutorial  
                  
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: ProgrammingVideos.Com: SQL Tutorial 04–Alter Drop**
    Link: ProgrammingVideos.Com: [SQL Tutorial 04–Alter
    Drop](http://www.youtube.com/watch?v=Y_cW97pIUpM&feature=related)
    (YouTube)  
        
     Instructions: Watch the entire video.  Note: This applies to
    material presented in 8.2.2 and 8.2.3.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.2.3 Alter Table** <span id="8.2.3"></span> 
-   **Reading: SQLTutorial.org’s “SQL ALTER TABLE”**
    Link: SQLTutorial.org’s “[SQL ALTER
    TABLE](http://www.sqltutorial.org/sqlaltertable.aspx)” (HTML)  
        
     Instructions: Read through the entire tutorial to learn how to use
    SQL to modify a database table.  Note: this reading also applies to
    subunits 8.2.3.1 and 8.2.3.3.  The SQL Tutorial website was created
    to provide you clear, concise and easy to understand SQL Tutorial  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.2.3.1 Add a Column** <span id="8.2.3.1"></span> 
**8.2.3.2 Drop a Column** <span id="8.2.3.2"></span> 
**8.3 Column and Table Level Constraints** <span id="8.3"></span> 
**8.3.1 Not Null** <span id="8.3.1"></span> 
-   **Reading: W3Schools.com’s “SQL NOT NULL Constraint”**
    Link: W3Schools.com’s “[SQL NOT NULL
    Constraint](http://www.w3schools.com/sql/sql_notnull.asp)” (HTML)  
        
     Instructions: Please read the entire webpage.  W3Schools.com is a
    website with tutorials on many Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.3.2 Unique** <span id="8.3.2"></span> 
-   **Reading: W3Schools.com’s “SQL UNIQUE Constraint”**
    Link: W3Schools.com’s “[SQL UNIQUE
    Constraint](http://www.w3schools.com/sql/sql_unique.asp)” (HTML)  
        
     Instructions: Please read the entire page.  W3Schools.com is a
    website with tutorials on many Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.3.3 Primary Key** <span id="8.3.3"></span> 
-   **Reading: W3Schools.com’s “SQL PRIMARY KEY Constraint”**
    Link: W3Schools.com’s “[SQL PRIMARY KEY
    Constraint](http://www.w3schools.com/sql/sql_primarykey.asp)”
    (HTML)  
        
     Instructions: Please read the entire webpage.  W3Schools.com is a
    website with tutorials on many Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.3.4 Foreign Key** <span id="8.3.4"></span> 
-   **Reading: W3Schools.com’s “SQL FOREIGN KEY Constraint”**
    Link: W3Schools.com’s “[SQL FOREIGN KEY
    Constraint](http://www.w3schools.com/sql/sql_foreignkey.asp)”
    (HTML)  
        
     Instructions: Please read the entire webpage.  W3Schools.com is a
    website with tutorials on many Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.3.5 Default** <span id="8.3.5"></span> 
-   **Reading: W3Schools.com’s “SQL DEFAULT Constraint”**
     Link: W3Schools.com’s “[SQL DEFAULT
    Constraint](http://www.w3schools.com/sql/sql_default.asp)” (HTML)  
        
     Instructions: Please read the entire webpage.  W3Schools.com is a
    website with tutorials on many Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.3.6 Check** <span id="8.3.6"></span> 
-   **Reading: W3Schools.com’s “SQL CHECK Constraint”**
    Link: W3Schools.com’s “[SQL CHECK
    Constraint](http://www.w3schools.com/sql/sql_check.asp)” (HTML)  
        
     Instructions: Please read the entire webpage.  W3Schools.com is a
    website with tutorials on many Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.4 Data Manipulation Language (DML) Commands** <span
id="8.4"></span> 
**8.4.1 Insert Operator and Command Syntax** <span id="8.4.1"></span> 
-   **Reading: W3Schools.com’s “SQL INSERT INTO Statement”**
    Link: W3Schools.com’s “[SQL INSERT INTO
    Statement](http://www.w3schools.com/sql/sql_insert.asp)” (HTML)  
        
     Instructions: Please read the entire webpage.  W3Schools.com is a
    website with tutorials on many Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Stanford University’s Introduction to Databases:
    Lecture 13: “Data Modification Statements”**
    Link: Stanford University’s Introduction to Databases: Lecture 13:
    [“Data Modification
    Statements](http://www.youtube.com/watch?v=qKNb8YQYTZg)[”](http://www.youtube.com/watch?v=qKNb8YQYTZg)
    (YouTube)  
        
     Instructions: Watch the entire video.  Note: this applies to all of
    8.4.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: ProgrammingVideos.Com: “SQL Tutorial 05–Insert, Update,
    Delete”**
    Link: ProgrammingVideos.Com: [“SQL Tutorial 05–Insert, Update,
    Delete”](http://www.youtube.com/watch?v=u0nIGT3EZfQ&feature=related)
    (YouTube)  
        
     Instructions: Watch the entire video.  Note: This applies to
    material presented in 8.4.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.4.2 Update Operator and Command Syntax** <span id="8.4.2"></span> 
-   **Reading: W3Schools.com’s “SQL UPDATE Statement”**
    Link: W3Schools.com’s “[SQL UPDATE
    Statement](http://www.w3schools.com/sql/sql_update.asp)” (HTML)  
        
     Instructions: Please read the entire webpage.  W3Schools.com is a
    website with tutorials on many Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.4.3 Delete Operator and Command Syntax** <span id="8.4.3"></span> 
-   **Reading: W3Schools.com’s “SQL DELETE Statement”**
    Link: W3Schools.com’s “[SQL DELETE
    Statement](http://www.w3schools.com/sql/sql_delete.asp)” (HTML)  
        
     Instructions: Please read the entire webpage.  W3Schools.com is a
    website with tutorials on many Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**8.4.4 Select Operator and Command Syntax** <span id="8.4.4"></span> 
-   **Reading: W3Schools.com’s “SQL SELECT Statement”**
    Link: W3Schools.com’s “[SQL SELECT
    Statement](http://www.w3schools.com/sql/sql_select.asp)” (HTML)  
        
     Instructions: Read the entire page.  W3Schools.com is a website
    with tutorials on many Internet programming topics.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.



---
layout: default
title: "CS403: Introduction to Modern Database Systems"
course_description: "A study of database architecture and the components used in implementation. Topics include using the Structured Query Language, file structures and access methods, database modeling, design, and user interface,components of database management systems, and information storage and retrieval."
next: ../Unit07
previous: ../Unit05
---
**Unit 6: Relational Algebra** <span id="6"></span> 
 *We have seen that database entities can be viewed as logical tables.
While this is useful in its own way, we can learn more from the data if
we can perform operations on the tables within a database, as data from
one table may not be meaningful without the data from another table.  In
this unit, we will introduce relation algebra, the mathematical notation
used to represent how data retrievals and updates are performed on
tables in a database.  Understanding relational algebra will serve as a
prelude to using the Structure Query Language (SQL).*

**Unit 6 Time Advisory**  
This unit will take you approximately 5 hours and 23 minutes to
complete.  
  
 ☐    Subunit 6.1: 4 hours 18 minutes  
  
☐    Reading: 3 hours  
  
 ☐    Assessment: 1 hour  
  
 ☐    Video: 18 minutes

☐    Subunit 6.2: 35 minutes  
  
☐    Reading: 30 minutes  
  
 ☐    Video: 5 minutes

☐    Subunit 6.3: 20 minutes  
  
 ☐    Subunit 6.4: 10 minutes

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Explain the basic relational algebra operations.
-   Discuss relational algebra set operations.
-   Explain what a derived operation is.
-   Describe how relational algebra is used to build queries.

-   **Reading: Dr. Gordon Russell’s *Database Resources*: “Chapter 5:
    Relational Algebra”**
    Link: Dr. Gordon Russell’s *Database Resources:*
    [“](http://db.grussell.org/ch5.html)[Chapter 5: Relational
    Algebra](http://db.grussell.org/ch5.html)[”](http://db.grussell.org/ch5.html)
    (HTML)  
        
     Instructions: This resource has two sections: “Introduction to
    Relational Algebra” and “Algebraic Format Relational Algebra.” Read
    both sections as these concepts apply to all subunits in Unit 6.  
        
     Database Resources is the culmination of many years of developing
    online database resources. It includes notes as well as quizzes and
    an interactive SQL practice environment. Use this resource as a
    general reference for Unit 6. Refer back to it whenever needed as
    you progress through the Subunits.        
                  
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.1 Basic Operations** <span id="6.1"></span> 
-   **Reading: Dr. Charles Corliss’s “Chapter 6: Relational Algebra and
    the Relational Calculus”**
    Link: Dr. Charles Corliss’s “[Chapter 6: Relational Algebra and the
    Relational
    Calculus](https://web.archive.org/web/20130826235056/http://www.eng.mu.edu/corlissg/150.07f/ch06.html)”
    (HTML)  
        
     Instructions: Read the sections on select and project.  You may
    also read the entire document if you want more background for later
    units.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.  

**6.1.1 Select and Select Properties** <span id="6.1.1"></span> 
**6.1.2 Projection and Projection Properties** <span id="6.1.2"></span> 
**6.2 Derived Operations** <span id="6.2"></span> 
**6.2.1 Join** <span id="6.2.1"></span> 
-   **Reading: Dr. Charles Corliss’s “Chapter 6: Relational Algebra and
    the Relational Calculus”**
    Link: Dr. Charles Corliss’s “[Chapter 6: Relational Algebra and the
    Relational
    Calculus](http://www.eng.mu.edu/corlissg/150.07f/ch06.html)”
    (HTML)  
      
     Instructions: Read the section (6.3) on join operations.  You may
    also read the entire document if you want more background for later
    units.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.  

**6.2.1.1 Inner Join** <span id="6.2.1.1"></span> 
**6.2.1.2 Equi Join** <span id="6.2.1.2"></span> 
**6.2.1.3 Natural Join** <span id="6.2.1.3"></span> 
**6.2.2 Outer Join** <span id="6.2.2"></span> 
-   **Web Media: University of Houston at Clear Lake, Dr. Gary
    Boetticher: “Relational Algebra: Set Operations”**
    Link: University of Houston at Clear Lake. Dr. Gary Boetticher:
    “[Relational
    Algebra:](http://www.youtube.com/watch?v=sRNCC6JOWB4)[Set
    Operations](http://www.youtube.com/watch?v=sRNCC6JOWB4)” (YouTube)  
        
     Instructions: Watch the entire video.  Please note that this also
    applies to subunits 6.2.2.1-6.2.2.3.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.2.2.1 Left Outer Join** <span id="6.2.2.1"></span> 
**6.2.2.2 Right Outer Join** <span id="6.2.2.2"></span> 
**6.2.2.3 Full Outer Join** <span id="6.2.2.3"></span> 
**6.3 Set Operations** <span id="6.3"></span> 
-   **Web Media: Stanford University’s Introduction to Databases:
    Lecture 5: “Table Variables and Set Operators”**
     Link: Stanford University’s Introduction to Databases: Lecture 5:
    [“Table Variables and Set
    Operators”](http://www.youtube.com/watch?v=-BCCy5Z6i-s) (YouTube)  
        
     Instructions: Watch the entire video.  Please note this also
    applies to subunits 6.3.1-6.3.5.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**6.3.1 Union and Union Properties** <span id="6.3.1"></span> 
**6.3.2 Difference and Difference Properties** <span id="6.3.2"></span> 
**6.3.3 Intersection and Intersection Properties** <span
id="6.3.3"></span> 
**6.3.4 Product and Product Properties** <span id="6.3.4"></span> 
**6.3.5 Rename and Rename Properties** <span id="6.3.5"></span> 
**6.4 Aggregate Functions** <span id="6.4"></span> 
-   **Reading: City University of New York, Prof. Richard Holowczak:
    “Relational Algebra Lecture Notes: Aggregate Functions”**
    Link: City University of New York, Prof. Richard Holowczak:
    “[Relational
    Algebra](http://cisnet.baruch.cuny.edu/holowczak/classes/3400/relationalalgebra/#aggregatefunctions)[Lecture
    Notes: Aggregate
    Functions](http://cisnet.baruch.cuny.edu/holowczak/classes/3400/relationalalgebra/#aggregatefunctions)”
    (HTML)  
        
     Instructions: Please read the entire section.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**Unit 6: Assessment** <span id="6.5"></span> 
-   **Assessment: Dr. Gordon Russell’s *Database Resources*: “Online
    Quiz: Relational Algebra”**
    Link: Dr. Gordon Russell’s *Database Resources*: [“Online Quiz:
    Relational Algebra”](http://db.grussell.org/mc/q39.html) (HTML)  
        
     Instructions: Take this online quiz. It covers material from
    previous units in addition to that of Unit 6.  
        
     Note that Database Resources is the culmination of many years of
    developing online database resources. It includes notes as well as
    quizzes and an interactive SQL practice environment.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.



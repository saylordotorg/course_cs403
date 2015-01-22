**Unit 7: Intro to Data Normalization** <span id="7"></span> 
*In this course, we have learned that entities in a database can be
thought of as logical tables.  We will now learn that data in a table
must be stored in a normalized way.  We will first identify the
properties of a normalized table, learning about the process of
normalization and its importance to the structure of a database.  We
will then study the four major steps of normalization and discuss the
database anomalies that can result in the absence of normalization. *

**Unit 7 Time Advisory**  
This unit will take you approximately 17 hours and 48 minutes to
complete.  
  
 ☐    Subunit 7.1: 3 hours  
  
 ☐    Subunit 7.2: 5 hours  
  
☐    Reading: 2 hours  
  
 ☐    Assessment: 3 hours

☐    Subunit 7.3: 5 hours and 28 minutes  
  
☐    Reading: 2 hours  
  
 ☐    Assessment: 3 hours  
  
 ☐    Video: 28 minutes

☐    Subunit 7.4: 3 hours and 20 minutes  
  
☐    Reading: 3 hours  
  
 ☐    Video: 20 minutes

☐    Assessment: 1 hour

**Unit7 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Describe normalization.
-   Discuss and contrast the different types of dependencies.
-   Construct a dependency diagram.
-   Normalize a relation to at least third normal form.

**7.1 Normalization Defined** <span id="7.1"></span> 
-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 4:
    Normalization 0 – 3NF”**
    Link: Dr. Gordon Russell’s *Database Resources:* “[Chapter 4:
    Normalization 0 –
    3NF](http://db.grussell.org/section008.html#_Toc67114443)” (HTML)  
        
     Instructions: Please read the entire chapter.  Note: This reading
    applies to topics outlined in sections 7.1 to 7.3 of this course. 
    Database Resources is the culmination of many years of developing
    online database resources.  It includes notes as well as quizzes and
    an interactive SQL practice environment.  
                  
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: www.wingslive.com: “What is Database Normalization?”**
    Link: www.wingslive.com: “[What is Database
    Normalization](http://www.youtube.com/watch?v=FZs-Qdf-Sxg)?”
    (YouTube)  
        
     Instructions: Watch the entire video.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Dr. Art Langer’s Logic Data Modeling 1: Introduction**
    Link: Dr. Art Langer’s [Logic Data Modeling 1:
    Introduction](http://www.youtube.com/watch?v=IiVq8M5DBkk&feature=mfu_in_order&list=UL) (YouTube)  
        
     Instructions: Watch the entire video.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage     above.

-   **Web Media: Dr. Art Langer’s Logic Data Modeling 2: Candidate Key**
    Link: Dr. Art Langer’s Logic [Data Modeling 2: Candidate
    Key](http://www.youtube.com/watch?v=BGMwuOtRfqU&feature=mfu_in_order&list=UL)
    (YouTube)  
        
     Instructions: Watch the entire video.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage     above.  
      

-   **Web Media: Dr. Art Langer’s Logic Data Modeling 3: Normalization**
    Link: Dr. Art Langer’s [Logic Data Modeling 3:
    Normalization](http://www.youtube.com/watch?v=ZiB-BKCzS_I&feature=mfu_in_order&list=UL) (YouTube)  
        
     Instructions: Watch the entire video.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage     above.

**7.1.1 Advantages** <span id="7.1.1"></span> 
*This subunit is covered in Dr. Gordon Russell’s Database Resources:
“Chapter 4: Normalization 0 – 3NF”*

**7.1.2 Disadvantages** <span id="7.1.2"></span> 
*This subunit is covered in Dr. Gordon Russell’s Database Resources:
“Chapter 4: Normalization 0 – 3NF”*

**7.2 Anomalies** <span id="7.2"></span> 
-   **Reading: Kennesaw State’s Animated Database Courseware:
    “Anomalies”**
    Link:Kennesaw State’s Animated Database Courseware:
    “[Anomalies](http://adbc.kennesaw.edu/index.php?mainmenu=db&submenu=anomalies)”
    (Adobe Flash)  
        
     Instructions: Please read the introduction, and then click on the
    “Scenarios” link in the table of contents on the left side of the
    webpage.  This will redirect you to a page with six scenarios. 
    Click on the box to open up each scenario, and read through the
    tutorial (you will be asked to complete the questions in an upcoming
    unit).  Note: this material also applies to subunits 7.2.1–7.2.3.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Wikia.Com: Database Management: “Data Anomalies”**
    Link: Wikia.Com: Database Management: “[Data
    Anomalies](http://www.saylor.org/site/wp-content/uploads/2011/09/CS403-7.s-Data-Anomalies.pdf)”
    (PDF)  
                  
     Instructions: Please read the whole page.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/)(HTML).  You can
    find the original Wikipedia version of this article
    [here](http://databasemanagement.wikia.com/wiki/Category:Data_Anomalies)(HTML).

**7.2.1 Insertion Anomalies** <span id="7.2.1"></span> 
**7.2.2 Deletion Anomalies** <span id="7.2.2"></span> 
**7.2.3 Update Anomalies** <span id="7.2.3"></span> 
-   **Assessment: Kennesaw State’s Animated Database Courseware:
    “Anomalies Scenarios”**
    Link: Kennesaw State’s Animated Database Courseware: “[Anomalies
    Scenarios](http://adbc.kennesaw.edu/index.php?mainmenu=db&submenu=anomalies)”
    (Adobe Flash)  
        
     Instructions: Please complete all scenarios.  ADbC is a set of
    interactive software modules designed to support the teaching of
    database concepts.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage     above. 

**7.3 Functional Dependencies** <span id="7.3"></span> 
-   **Web Media: Stanford University’s Introduction to Databases:
    Lecture 23: “Functional Dependencies”**
    Link: Stanford University’s Introduction to Databases: Lecture 23:
    [“Functional
    Dependencies](http://www.youtube.com/watch?v=Mkm1h5AtsXI)[”](http://www.youtube.com/watch?v=Mkm1h5AtsXI)
    (YouTube)  
        
     Instructions: Please watch the entire video.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.3.1 Trivial Functional Dependencies** <span id="7.3.1"></span> 
**7.3.2 Full Functional Dependencies** <span id="7.3.2"></span> 
**7.3.3 Partial Functional Dependencies** <span id="7.3.3"></span> 
**7.3.4 Transitive Functional Dependencies** <span id="7.3.4"></span> 
-   **Reading: Kennesaw State’s Animated Database Courseware
    Dependencies**
    Link: Kennesaw State’s Animated Database Courseware
    “[Dependencies](http://adbc.kennesaw.edu/index.php?mainmenu=db&submenu=fd)”
    (Adobe Flash)  
        
     Instructions: Please read this page and then click on the link to
    read the introduction.  Note this applies to all of section 7.3.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Kennesaw State’s Animated Database Courseware:
    Dependencies Scenarios**
    Link: Kennesaw State’s Animated Database Courseware: [Dependencies
    Scenarios](http://adbc.kennesaw.edu/index.php?mainmenu=db&submenu=fd)
    (Adobe Flash)  
        
     Instructions: Please complete all three scenarios.  Note that ADbC
    is a set of interactive software modules designed to support the
    teaching of database concepts.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**7.4 From 1NF to BCNF** <span id="7.4"></span> 
**7.4.1 First Normal Form (1NF) and Resolution Mechanisms** <span
id="7.4.1"></span> 
**7.4.2 Second Normal Form and Resolution Mechanisms** <span
id="7.4.2"></span> 
**7.4.3 Third Normal For and Resolution Mechanisms** <span
id="7.4.3"></span> 
**7.4.4 Boyce-Codd Normal Form (BCNF)** <span id="7.4.4"></span> 
-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 4:
    Normalisation—BCNF”**
    Link: Dr. Gordon Russell’s *Database Resources:* “[Chapter 4:
    Normalisation—BCNF”
    (HTML)](http://db.grussell.org/section009.html)  
        
     Instructions: Please read the entire section.  Note this applies to
    all of Section 7.4.  Note that Database Resources is the culmination
    of many years of developing online database resources.  It includes
    notes as well as quizzes and an interactive SQL practice
    environment.    
                  
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Assessment: Dr. Gordon Russell’s Database Resources: “Quiz on
    Normalization”**
    Link: Dr. Gordon Russell’s *Database Resources:* “[Quiz on
    Normalization](http://db.grussell.org/mc/q1.html)” (HTML)  
        
     Instructions: Please complete questions 1–14 for this quiz on
    normalization.  Please note that this quiz tests what you have
    learned from Unit 7.  Database Resources is the culmination of many
    years of developing online database resources.  It includes notes as
    well as quizzes and an interactive SQLpractice
    environment.            
                  
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Dr. Art Langer’s Logic Data Modeling 5: 1st Normal
    Form**
    Link:  Dr. Art Langer’s [Logic Data Modeling 5: 1st Normal
    Form](http://www.youtube.com/watch?v=q3Wg2fZENK0&feature=related)
    (YouTube)  
                              
     Instructions: Please watch the entire video.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Dr. Art Langer’s Logic Data Modeling 6: 2nd Normal
    Form**
    Link: Dr. Art Langer’s [Logic Data Modeling 6: 2nd Normal
    Form](http://www.youtube.com/watch?v=vji0pfliHZI&feature=mfu_in_order&list=UL)
    (YouTube)  
                              
     Instructions: Please watch the entire video.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Dr. Art Langer’s Logic Data Modeling 7: 3rd Normal
    Form**
    Link: Dr. Art Langer’s [Logic Data Modeling 7: 3rd Normal
    Form](http://www.youtube.com/watch?v=HH-QR7t-kMo&feature=mfu_in_order&list=UL)
    (YouTube)  
                              
     Instructions:  Please watch the entire video.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.



**Unit 4: The Entity Relationship Model** <span id="4"></span> 
*Databases often hold a great amount of data.  In order to build a
database, we need to understand which entities should hold data and
identify the connections that may exist between entities.  In this unit,
we will learn about the Entity-Relationship model, which will allow us
to create a graphical view of the different elements of a database as
well as the relationships between them.  We will also learn the drawing
conventions of the E-R model using a part-to-whole approach, beginning
with those conventions used to represent a single entity, and concluding
with conventions used to represent all relations in a database.*

**Unit 4 Time Advisory**  
This unit will take you approximately 9 hours and 25 minutes to
complete.  
  
 ☐    Introduction: 1 hour 55 minutes  
  
☐    Assessment:1 hour  
  
 ☐    Video: 55 minutes

☐    Subunit 4.1: 3 hours  
  
 ☐    Subunit 4.2: 4 hours  
  
 ☐    Subunit 4.3: 30 minutes

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Discuss the need for an entity-relationship model.
-   Explain the entity-relationship model and all associated symbols.
-   Describe relationship constraints.

-   **Assessment: Dr. Gordon Russell’s Database Resources: “Quiz on ER
    Diagrams”**
    Link: Dr. Gordon Russell’s *Database Resources:* “[Quiz on ER
    Diagrams](http://db.grussell.org/mc/q23.html)” (HTML)  
        
     Instructions: Read the question, and choose the best answer choice
    at the top of the webpage.  Then, click on “Next,” answering all
    four questions in the “ER Diagrams” quiz section.  Note that
    Database Resources is the culmination of many years of developing
    online database resources.  It includes notes as well as quizzes and
    an interactive SQLpractice environment.        
                  
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Web Media: Indian Institute of Technology, Dr. S. Srinath’s
    Database Management System: “Conceptual Designs”**
    Link:  Indian Institute of Technology, Dr. S. Srinath’s Database
    Management System:  “[Conceptual
    Designs](http://www.youtube.com/watch?v=EuSBAOpXjU0&feature=related)”
    (YouTube)  
        
     Instructions: Please watch the entire video.  Please note that this
    video applies to topics outlined in sections 4.1 and 4.2 of this
    course.  
                  
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.1 Why Use an E-R Model** <span id="4.1"></span> 
-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 2:
    Database Analysis: Introduction”**
    Link: Dr. Gordon Russell’s *Database Resources:* “[Chapter 2:
    Database Analysis:
    Introduction](http://db.grussell.org/section004.html#_Toc67114386)”
    (HTML)  
        
     Instructions: Please read the entire Introduction section, stopping
    once you get to “Database Analysis Life Cycle.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 2:
    Database Analysis: Database Analysis Life Cycle”**
    Link: Dr. Gordon Russell’s *Database Resources:* “[Chapter 2:
    Database Analysis: Database Analysis Life
    Cycle”(HTML)](http://db.grussell.org/section004.html#_Toc67114387)  
        
     Instructions: Please view the graphic and read this section,
    stopping once you get to “Three-level Database Model.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 2:
    Database Analysis: Three-Level Database Model.”**
    Link: Dr. Gordon Russell’s *Database Resources:*  [“Chapter 2:
    Database Analysis: Three-Level Database Model”
    (HTML) ](http://db.grussell.org/section004.html#_Toc67114388)  
        
     Instructions: Please read this short section, stopping once you get
    to “Basics.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 2:
    Database Analysis: Basics”**
    Link: Dr. Gordon Russell’s *Database Resources: * [“Chapter 2:
    Database Analysis: Basics”
    (HTML)](http://db.grussell.org/section004.html#_Toc67114389)  
        
     Instructions: Please read this short section, stopping once you get
    to “Entities.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.2 Elements in the Model and Respective Symbols** <span
id="4.2"></span> 
**4.2.1 Entity, Represented by a Rectangle** <span id="4.2.1"></span> 
-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 2:
    Database Analysis: Basics: Entities”**
    Link: Dr. Gordon Russell’s *Database Resources:* [“Chapter 2:
    Database Analysis: Basics: Entities”
    (HTML)](http://db.grussell.org/section004.html#_Toc67114390)  
        
     Instructions: Please read this short section, stopping once you get
    to “Attribute.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.2.2 Attribute—Represented by an Oval** <span id="4.2.2"></span> 
-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 2:
    Database Analysis: Basics: Attribute”**
    Link: Dr. Gordon Russell’s *Database Resources:* [“Chapter 2:
    Database Analysis: Basics: Attribute”
    (HTML)](http://db.grussell.org/section004.html#_Toc67114391)  
        
     Instructions: Please read this short section, stopping once you get
    to “Keys.”  Please note that this reading applies to sections
    4.2.2–4.2.4.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 2:
    Database Analysis: Basics: Attribute: Keys”**
    Link: Dr. Gordon Russell’s *Database Resources: * [“Chapter 2:
    Database Analysis: Basics: Attribute: Keys”
    (HTML)](http://db.grussell.org/section004.html#_Toc67114392)  
        
     Instructions: Please read this short section, stopping once you get
    to “Relationships.”  Please note that this reading applies to
    sections 4.2.2–4.2.4.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.2.3 Multi-Valued Attributes—Represented by a Double Oval** <span
id="4.2.3"></span> 
**4.2.4 Composite and Derived Attributes** <span id="4.2.4"></span> 
**4.2.5 Keys** <span id="4.2.5"></span> 
-   **Reading: RelationalDBDesign.com's “Primary Keys”**
    Link: RelationalDBDesign.com's “[Primary
    Keys](http://www.relationaldbdesign.com/relational-database-analysis/module2/database-primary-key.php)”
    (HTML)  
        
     Instructions: Read the entire page  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above. 

-   **Reading: RelationalDBDesign.com's “Database Foreign Keys”**
    Link: RelationalDBDesign.com's “[Database Foreign
    Keys](http://www.relationaldbdesign.com/relational-database-analysis/module2/defining-foreign-keys.php)”
    (HTML)  
        
     Instructions: Read the entire page  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above. 

**4.2.5.1 Superkey** <span id="4.2.5.1"></span> 
**4.2.5.2 Composite Key** <span id="4.2.5.2"></span> 
**4.2.5.3 Candidate Key** <span id="4.2.5.3"></span> 
**4.2.5.4 Primary Key-Underlined Attribute** <span id="4.2.5.4"></span> 
**4.2.5.5 Foreign Key** <span id="4.2.5.5"></span> 
**4.2.6 Relationships** <span id="4.2.6"></span> 
**4.2.6.1 Degree of a Relationship** <span id="4.2.6.1"></span> 
-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 2:
    Database Analysis: Degree of a Relationship”**
    Link: Dr. Gordon Russell’s *Database Resources:* “[Degree of a
    Relationship”
    (HTML)](http://db.grussell.org/section004.html#_Toc67114394)  
        
     Instructions: Please read this section, stopping once you get to
    “Cardinality.”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.2.6.2 Cardinality of a Relationship: One-to-One, One-to-Many,
Many-to-Many, and Respective Notations** <span id="4.2.6.2"></span> 
-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 2:
    Database Analysis: Cardinality”**
    Link: Dr. Gordon Russell’s *Database Resources:* “Chapter 2:
    Database Analysis:
    [Cardinality](http://db.grussell.org/section004.html#_Toc67114397)”
    (HTML)  
        
     Instructions: Please read this section, stopping once you get to
    “Optionality.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Dr. Gordon Russell’s Database Resources: “Chapter 2:
    Database Analysis: Optionality”**
    Link: Dr. Gordon Russell’s *Database Resources:* “Chapter 2:
    Database Analysis:
    [Optionality](http://db.grussell.org/section004.html#_Toc67114398)”
    (HTML)  
        
     Instructions: Please read this short section, stopping once you get
    to “Entity Sets.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.3 The Enhanced ER Model** <span id="4.3"></span> 
-   **Reading: Professor Giora Baram and Frank Friedman, Temple
    University: CIS109—Lecture Notes Part Three: “Section 2: The
    Enhanced E-R Model and Business Rules”**
    Link: Professors Giora Baram and Frank Friedman, Temple University:
    CIS109—Lecture Notes Part Three: “[Section 2: The Enhanced E-R Model
    and Business
    Rules](https://web.archive.org/web/20131004043150/http://ww2.cis.temple.edu/cis109friedman/cis%20109%20-%20lecture%20set%20iii%20-%20erd%20and%20eerds%20and%20modeling/aaa%20lecture%20set%20iii%20-%20entity%20relationship%20diagrams%20ver%207.htm#Section%202)”
    (HTML)  
        
     Instructions: Read all of section 2.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.



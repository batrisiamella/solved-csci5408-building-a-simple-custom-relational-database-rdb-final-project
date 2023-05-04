Download Link: https://assignmentchef.com/product/solved-csci5408-building-a-simple-custom-relational-database-rdb-final-project
<br>
<strong>Project Title: 5408_RDbMS_Custom(RDb)</strong>

<strong>Project Objective:</strong>

By completing this project, a student will be able to describe concepts in modelling notation (e.g., Entity-Relation Diagrams or UML) and how they would be used. A student will be able to describe the most common designs for core database system components including the query optimizer, query executor, storage manager, access methods, and transaction processor. By completing this task, a student will be able to explain the techniques used for data replication, and allocation during the database design process

In this project, each group is required to create a light-weight relational database management system (e.g. metadata management, data structure design, data storing, retrieval, building database and logs, analysis, and security), with custom database structure for in memory operations using various data structures such as Arrays, Tree, Linked Lists etc., and custom file design for persistent storage.




<strong>Timeline and Deliverables:</strong>

<strong>Phase 1 (Feasibility Study) – (2 %)</strong>

<ul>

 <li>Each group will work on the given problem and identify the required technologies, and list</li>

</ul>

the new learning.

<ul>

 <li>Each group will record their initial meeting logs and in addition, publish a timeline in the</li>

</ul>

form gantt chart

<ul>

 <li>Each group will submit their tentative design, and implementation plan as a 3-page written</li>

 <li></li>

</ul>

<strong>Submission: </strong>One 3-page report from each group must be submitted on or before Jun 10, 2021

(11:59 pm)




Project Requirement

<strong>Project Rubric:</strong>

Based on the discussion board rubric (McKinney, 2018)

<table>

 <tbody>

  <tr>

   <td width="94"> </td>

   <td width="123">Excellent ( 2 0 %)</td>

   <td width="132">Proficient (15%)</td>

   <td width="123">Marginal (10%)</td>

   <td width="151">Unacceptable (0%)</td>

  </tr>

  <tr>

   <td width="94">CompletenessincludingCitation</td>

   <td width="123">All required tasksare completed</td>

   <td width="132">Submissionhighlights taskscompletion.However, missedsome tasks inbetween, whichcreated adisconnection</td>

   <td width="123">Some tasks arecompleted, whichare disjoint innature.</td>

   <td width="151">Incorrect and irrelevant</td>

  </tr>

  <tr>

   <td width="94">Correctness</td>

   <td width="123">All parts of thegiven tasks arecorrect</td>

   <td width="132">Most of the giventasks are correctHowever, someportions need minormodifications</td>

   <td width="123">Most of the giventasks areincorrect. Thesubmissionrequires majormodifications.</td>

   <td width="151">Incorrect andunacceptable</td>

  </tr>

  <tr>

   <td width="94">Novelty</td>

   <td width="123">The submissioncontains novelcontribution inkey segments,which is a clearindication ofapplicationknowledge</td>

   <td width="132">The submissionlacks novelcontributions. Thereare some evidencesof novelty, however,it is not significant</td>

   <td width="123">The submissiondoes not containnovelcontributions.However, there isan evidence ofsome effort</td>

   <td width="151">There is no novelty</td>

  </tr>

  <tr>

   <td width="94">Clarity</td>

   <td width="123">The written orgraphicalmaterials, anddevelopedapplicationsprovide a clearpicture of theconcept, andhighlights theclarity</td>

   <td width="132">The written orgraphical materials,and developedapplications do notshow clear pictureof the concept.There is room forimprovement</td>

   <td width="123">The written orgraphicalmaterials, anddevelopedapplications fail toprove the clarity.Backgroundknowledge isneeded</td>

   <td width="151">Failed to prove theclarity. Need properbackground knowledgeto perform the tasks</td>

  </tr>

  <tr>

   <td width="94">Group Work</td>

   <td width="123">Evidence of groupwork, meetinglogs, Coordination</td>

   <td width="132">Evidence of groupwork. However,missed meetinglogs, room forimprovement inCoordination</td>

   <td width="123">Missed meetinglogs, failed todisplay groupcoordination</td>

   <td width="151">No group work done.Project is unacceptable</td>

  </tr>

 </tbody>

</table>




Project Requirement

<strong>Project Requirements</strong>

In this project, you need to build a simple relational database (RDb), and its database management system (RDbMS). Your team should explore data structure concepts for creating the databases. In addition, your team should create a programming framework that can work as a RDbMS application

layer. Your database should handle multi-user (2 users) requests. The database management system layer should provide a command-line interface (Graphical User Interface is not required), and perform various functionalities of relational database management system.

<ul>

 <li>Create, manage databases with at least 2 users, and provide MFA (multi-factor authentication) for users. E.g. encrypted password, and security question</li>

</ul>

<ul>

 <li>Accepts user inputs in standard SQL format only from standard I/O console</li>

 <li>Process the queries and converts those into instructions for create/delete/update/alter/select operations etc.</li>

</ul>

<ul>

 <li>Select and implement data structures which will be used for in memory operations of the database. E.g. after query execution, the processed query will be added in a stack for execution. Once done, any permanent changes will be reflected to the custom RDb file in the persistent storage.</li>

</ul>

<ul>

 <li>Conceptualize and implement a custom file format for persistent storage (JSON/CSV or standard file formats are not accepted).</li>

</ul>

<ul>

 <li>Creation of various dynamic logs such as,</li>

</ul>

o <strong>General Logs</strong>: query execution time, state of the database (e.g. how many tables are there with number of records at a given time)

o <strong>Event Logs: </strong>changes in database, concurrent transactions, crash reports, etc.

o <strong>Query Logs: </strong>capture user queries and timestamp of query submission

<ul>

 <li>Depending on the design – creation of Data dictionary, metadata, and lower limit/upper limit of datatypes etc.</li>

</ul>

<ul>

 <li>Options to specify constraints.</li>

 <li>Option to create SQL Dump (table structure and values)</li>

 <li><strong><u>Locking for concurrency control </u></strong><strong>–</strong>The RDBMS must follow ACID properties and implementation of two-phase locking</li>

</ul>

<ul>

 <li><strong><u>ERD </u></strong>The RDBMS should create simple ERD from existing databases (data structure). The concept of ERD generation is identical to reverse engineering that is available on standard commercial DBMSs. However, the ERD does not have to be graphical. Information such as cardinality, entity names, relationships, and primary key, foreign key constrains should be captured on a text file as ERD.</li>

</ul>




Project Requirement

<strong>Tasks for Phase 1 (Feasibility Study): Due Jun 10, 2021 @11:59 pm</strong>

<ul>

 <li>Meet your team (using Teams) and discuss the strategy;</li>

 <li>Capture screenshot of meetings; and write down the discussed agenda. (You do not need to keep video recordings)</li>

</ul>

<ul>

 <li>Select a programming framework and related technologies. Provide written explanation for your selection.</li>

</ul>

can only use standard data structure (e.g. arrays, linkedlists, tree etc.<strong>).</strong>o [<strong>Note</strong>: You need to use core Java programming. For in memory operation or buffers, you

o You <strong>cannot </strong>use JSON/CSV for capturing records.

o You cannot use any external libraries or <sup>3</sup><sup>rd</sup> party libraries]

<ul>

 <li>Explore Data Structure(s) that is suitable for your relational database</li>

 <li>Document your plan</li>

</ul>

o create flowchart highlighting the operations of the DBMS<strong><em> 5408_RDbMS_Custom(RDb)</em></strong>

o Write the assumptions

o Add your initial algorithms or pseudocodes

o Write initial Test cases for performing the unit tests

<ul>

 <li>The database should handle integer, real numbers, and text data</li>

</ul>

<strong>Task for Phase 2 (Go-Live and Project Closure): Due End of Term</strong>

<ul>

 <li>Implementation of the system</li>

 <li>Performing Unit Test and Validation Test</li>

 <li>Each group will submit a pre-recorded group video presentation of <strong>maximum 1 hour</strong></li>

</ul>

highlighting various components of the project, and the working model.

o The details of the pre-recorded presentation will be posted on Teams.

<ul>

 <li>There will be a synchronous Q&amp;A session with each group at the end of the project.</li>

 <li></li>

 <li>Detailed documentation of meeting logs screenshots, use case, test cases, pseudocode,</li>

</ul>

evidence of testing, team and individual contributions, limitations etc. in the form of a final

report.

<ul>

 <li>Each group will submit a report (10 to 15pages) at the end of the final project Q&amp;A session</li>

</ul>
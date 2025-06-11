# cmsc204-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [CMSC204 Assignment 4 Solved](https://mantutor.com/product/cmsc204-solved-9/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113917&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC204  Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Description

Most data is stored in databases, for ready access and organization. Our course data is backed up by IT in databases which makes our data easy to access and use.

Write a program that creates a database of courses. It will either read from a file of courses, or allow the user to add one course at a time. Upload the initial files and your working files in the repository in GitHub you created in Lab 1, in a directory named Assignment4. Take a screenshot of your repo, and post the assignment to the Assignment 4 dropbox.

Concepts tested by this assignment

Hash Table, Link List,

hash code, buckets/chaining, exception handling,

read/write files using FileChooser

Data Element – CourseDBElement,

Data Structure – CourseDBStructure

Implements the CourseDBStructureInterface that is provided.

You will be implementing a hash table with buckets. It will be an array of linked lists of CourseDBElements. Each CDE will have a hash code that comes from the CRN, since the CRN is unique for courses. Note that the CRN is an int, and the tests require the hashcode of a string, so you will need to coerce it to a String, and take the hash code of the resulting string. The add method will take a CourseDBElement and add it to the data structure. If a linked list at the relevant hash code doesn’t exist, create a LinkedList with the first element being the CDE and add it to the HashTable. If the LinkedList already exists, add the CDE to the existing list. Two constructors for the CDS will be required, one that takes in an integer that is the estimated number of courses, the other is used for testing purposes. The comments in the CourseDBStructureInterface (provided) should help you figure out how to set the length of the hash table. You will not need to use the 4k+3 code.

Data Manager – CourseDBManager

Implements the CourseDBManagerInterface that is provided.

The data manager allows the user to read the courses from a file or to enter the data by hand, and uses an Alert to print out the database elements. The input is read from a file or read from the textfields and is added to the data structure through the add method. The add method uses the CDS add method. The CourseDBManager is also referred to as a CDM.

Exception Classes

IOException – created and thrown when user selects an input file that cannot be read or attempting to retrieve a CDE that does not exist in the DB.

GUI Driver (provided)

• User will only create a course database once they have entered an input file or entered one or more sets of attributes.

• Buttons and textfields are grayed out if they are not relevant at the current time.

• A FileChooser is used to select the input and output files.

• Inform the user if there is an error with the input file.

• Use exception handling for the validity of the files.

• A way is provided for the user to “clear” the text fields.

• A way is provided for the user to select a CRN and retrieve the corresponding course.

Testing

Create a JUnit Test – CourseDBManager_STUDENT_Test.

Assi gnment Details

There will be two ways to create a course database. The first requires a document to be read from an input file. The second reads the input from five textfields. Once there is data in the database, the GetCourse button will be enabled to allow you to see the data. See the example below.

Select the input file button and navigate to the file.

Use ShowDB button to display the CDEs that were read:

Example of Creating a CDE from text fields. First select the other radio button, then fill in the textfields, then select the “Add to DB” button.

Select the Show DB button to see the resulting CDEs.

Example of retrieving a CDE. First select the GetCourse button. Three components at the bottom of the screen will become enabled. Then fill in the CRN and select the FindCourse button to find the applicable course from the database.

The general design is shown here to guide you in formulating your own design:

Deliverables / Submissions:

Design: UML class diagram with algorithm (pseudo-code) for methods

Implementation: Submit a compressed file containing the follow (see below): The Java application (it must compile and run correctly); Javadoc files in a directory; a write-up as specified below. Be sure to review the provided project rubric to understand project expectations. The write-up will include:

• UML diagram

• In three or more paragraphs, highlights of your learning experience

Deliverable format: The above deliverables will be packaged as follows. Two compressed files in the following formats:

• LastNameFirstName_Assignment4_Complete.zip, a compressed file in the zip format, with the following: o Write up (Word document) – reflection paragraphs o GitHub repository with java files from Assignment 4.

o Final Design: UML Diagram – latest version (Word or image) o doc (directory) – Javadoc

• subdirectories (as is)

• File1.html (example)

• File2.html (example) o src (directory)

• File1.java (example)

• File2.java (example)

• LastNameFirstName_Assignment4_Moss.zip, a compressed file containing one or more Java files:

o File1.java (example) o File2.java (example)

This folder should contain Java source files only

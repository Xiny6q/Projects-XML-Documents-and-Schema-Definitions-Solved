Download link :https://programming.engineering/product/projects-xml-documents-and-schema-definitions-solved/

# Projects-XML-Documents-and-Schema-Definitions-Solved
Projects: XML Documents and Schema Definitions Solved
Project 1: XML Document

Assignment Four will demonstrate the use of XML documents in transferring data.

This will entail creating and validating an XML and XSD file and then upload that file to MS Access. Once successfully uploaded, the database will be completed by enforcing the referential integrity of the tables.

Your product has been a great success. Sales have grown and your company has grown to match.

You now have moved out into a building to accommodate all the employees you have hired.

And of course, you are great boss. You recognize that most of your employees are millennials and they expect more than just salary for job satisfaction. Besides daily affirmations that they are the greatest employees in the whole of the world, they expect a minimal level of perks and awards.

废话

To this end, one of the perks you provide a weekly ‘Friday Lunch Extravaganza’ including free lunch.

You order in a lunch every week from restaurants suggested by your employees.

To this end, you keep a list of all the restaurants that you order from.

So, you will create an XML document and an accompanying XSD Schema definition file so you can upload the data to your MS Access database. You will start out by importing the three (3) restaurants in this list as a ‘proof of concept’.

Using a flat text editor (either: Brackets –or- NotePad++) you create an NEW XML data document.

You are given all the data required to fill in to your XML document in a text file called:

XML_Data.txt 必须跟给出的文件一模一样

(note: you must upload ALL the characters exactly as they appear in the file – no changes)

So, quotation marks and punctuation must match what is in the file.

The data in XML_Data.txt is put into your XML file and MUST be structured with the following specifications:

Restaurant Name (mandatory) and Restaurant ID (Primary Key to identify each – must be text)

Cuisine (what type of food does the restaurant serve – mandatory)

List of Menu Items (mandatory)

this list contains two data points: Item Type (i.e., Sushi) and Item Name (I.e. Crab)

hint: ALSO – each item on this list will have a Restaurant Association ID (mandatory – must match the Restaurant ID above)

Delivery Cost (optional)

Number of times we ordered from that restaurant (mandatory)

List of Employees that have ordered from that restaurant

this list contains the data point of the Employee ID that ordered from this restaurant in the past. (mandatory – at least one (1) but no more than ten (10) employees allowed in this list)

(you MUST use values from your existing database from Assignment Three hint: ALSO – each item on this list will have a Restaurant Association ID

(mandatory – must match the Restaurant ID above)

Phone Number (mandatory – no dash or brackets – might start with area code 012) Current (i.e. do you still order from this restaurant – mandatory

– MUST be either ‘true’ or ‘false’ – can not be text or number)

Note: the tag for the major Restaurant’s groupings must have a tag attribute indicating the Preference of each restaurant as demonstrated in the notes.

The assigned Preference number is also in the XML_Data.txt file before each major grouping.

先做一个的 看看那个对不对 然后写出他的

hint: make sure you read Project 2 before starting.

XSD然后再吧剩下的写了

hint: create the XML file with only ONE (1) Restaurant (use the XMLData_1restaurant.txt file). test (validate) syntax of the XML file

ONLY after syntax check of the XML file, then create the XSD schema based on the XML file with only this ONE (1) restaurant.

ONLY after the schema validates the XML then add the other two (2) Restaurants [ONE AT A TIME] and retest each time.

hint: Read the Assignment 4 MUST READ.pdf file for more suggestions.

This document MUST be validated by the schema in Project 2 by including the following line in your

XML document:

<rootName xmlns:xsi=”http://www.w3.org/2001/XMLSchema-instance”

xsi:noNamespaceSchemaLocation=”yourFileName.xsd”>

where rootName is the name of the root of your XML document and yourFileName is the name of the actual XSD Schema document you created in Project 2.

Your XML document must be a text file (NOT a Word Document) saved and submitted as an XML file (it MUST be a file with the extension .xml). Files with .doc or .txt extension will lose major marks.

The file name must be youraccountname_Restaurants.xml For example: jdoe3_Restaurants.xml

Note: Tutorials on HTML and XML are available at http://www.w3schools.com.

(HINT: Follow the steps from the class notes – especially in regards to the XML tags) read the Assignment 4 MUST READ.pdf document.

NOTE: Your XML file must validate, otherwise it cannot be uploaded into MS Access as required in Project 3. You will lose major marks if it does not validate. In past semesters students expressed confusion over this requirement. It must be valid as per the validation web site referenced below in these instructions. No exceptions – even regardless of what a TA may or may not say.

If you are unclear about the ‘must validate’ requirement, please contact me and I will be glad to give a further definition. I do not want the students to be unclear or feel that this has not been specified in advance.

You must use the XMLValidation site below. It provides more details on error messages:

http://www.xmlvalidation.com

– it does not matter if another site says it is valid. This site only.

Your XML must be valid as per this web site. Run your XML file and Schema through this site.

(ensure you check the ‘Validate against external XML schema’ box on this page).

If this web site shows errors on your XML or Schema, you will lose almost all of the marks. Again, contact me, or leave a message in the FORUMS in OWL if this is unclear.

IMPORTANT :

You must identify yourself in the XML documents (BOTH the XML and XSD). Somewhere towards the top (beginning) in the actual submitted XML and XSD files you must include:

your first and last name

your Western ID (see below for a description of your Western ID)

your student number

the Date you completed the XML document

Your name and student Number and Student ID MUST MUST MUST appear in both (XML and XSD) documents or You will lose major marks on this project !!!

– NO EXCEPTIONS.

NOTE: Your XML file must validate, even after you add your name and ID to the document, otherwise it cannot be uploaded into MS Access as required in Project 2. You will lose major marks if it does not validate. In past semesters students expressed confusion over this requirement. It must be valid as per the validation web site referenced below in these instructions. AND! This can NOT be data. It can NOT be uploaded as part of your database.

STOP and think about how to add your name and ID inside the XML document where it is not data AND still have the XML validate! (hint: review the notes…)

Adding your identification incorrectly will result in the loss of major marks.

Your XML document must be a FLAT text file (NOT a Word Document (.doc) not a Text (.txt)

Document ) saved and submitted as an XML file (it MUST be a file with the extension .xml).

Files with a .doc or .txt extension will lose major marks.

Project 2: XML Schema

Using a text editor (either: Brackets –or- NotePad++) create an XML Schema (.xsd) document that will validate the Project 1 XML file you created.

Create the XML Schema using the information from your XML document,

The schema document needs to be designed to define your XML document in Project 1.

The data types must match the specifications on page one (1) of this assignment.

Your schema definition must be a flat text file (NOT a Word Document) saved and submitted as an XML Schema Definition file (an .xsd file – files with a .doc or .txt extension will lose major marks).

The file name must start with your accountname followed by an underscore and then the word ‘Restaurants’

For example: jdoe3_Restaurants.xsd

IMPORTANT :

You must identify yourself in the XML documents (BOTH the XML and XSD). Somewhere towards the top (beginning) in the actual submitted XML and XSD files you must include:

your first and last name

your Western ID (see below for a description of your Western ID)

your student number

the Date you completed the XML document

Your name and student Number and Student ID MUST MUST MUST appear in both (XML and XSD) documents or You will lose major marks on this project !!!

– NO EXCEPTIONS.

You must use the XMLValidation site below. It provides more details on error messages:

http://www.xmlvalidation.com – it does not matter if another site says it is valid. This site only.

Your XML Schema must be valid as per this web site. Run your XML file and XML Schema through this site (ensure you check the ‘Validate against external XML schema’ box on this page).

If this web site shows errors on your XML or Schema, you will lose major marks. Again, contact me, or leave a message in the FORUMS in OWL if this is unclear.

Your XSD document must be a FLAT text file (NOT a Word Document (.doc) not a Text (.txt)

Document ) saved and submitted as an XML file (it MUST be a file with the extension .xsd).

Files with a .doc or .txt extension will lose major marks.

Project 3: Upload your XML Document into YOUR MS Access Database

Import your valid and syntactically correct XML document into the MS Access data base you created in Assignment Three:

Make a copy your Assignment 3 file youraccountname_business.accdb to:

youraccountname_business_part2.accdb

Use the built in XML Import Utility found under the External Data tab.


Upload your XML document with the three (3) Restaurants into your existing database:

youraccountname_Restaurants.xml (where youraccountname is YOUR UWO User ID)

Once the three (3) tables are uploaded successfully from your XML document:

Use the Relationships utility in Database tools to create a relationship between the existing tables and the new imported tables (RESTAURANT to MenuItem -and- RESTAURANT to EmployeeOrdered – and- EMPLOYEE to EmployeeOrdered) and then enforce referential integrity with this tool.


hint: you will need to manually make changes to the Restaurant table before you can enforce referential integrity. Think about how referential integrity works and look at the Properties view of each of these tables.


hint: sometimes MS Access will incorrectly import an XML Integer data type as a Double.

you may have to manually change any XML Integer value to an Integer type in Access.

Project 4: Final Exam Multiple Choice Questions

Write five (5) multiple choice questions you think would be appropriate for the final exam. Base these questions on material covered in the slides or in class.

Ensure that each multiple choice question has five choices

Ensure that the majority of questions are framed in a positive context (do not use questions that ask “Choose the option that does not belong)

Avoid using “all of the above” or “none of the above” answer options, or answers consisting of specific option numbers as possible responses.

Provide the correct answer for each question.

This will help the professor to gage the level of difficulty expected by the students and will demonstrate the students proficiency in the material.

( …and, if I use your question(s) you will already know the answer(s) )

The format of this document should be identical to format you used in Assignment One (1).

Place your name, followed by the company name at the top.

At the end of the document, include your name, Student number and Western ID (the first part of your

Western email (i.e. if your email is – dernt373@uwo.ca your ID will be – dernt373)

Formatting is not important as long as the document is easy to follow:

This document must be a Word file saved and submitted as a .doc (or .docx) file

The name must be a combination of your Western Account Name and the name of your company. The file name must be youraccountname_companyname_A4.doc (or .docx)

– example (from above) dernt373_MaggicSoftware_A4.docx

Submission Instructions:

You must upload and submit, via the CS1032 Web Site, the following four (4) files:

youraccountname_Restaurants.xml

youraccountname_Restaurants.xsd

youraccountname_business_part2.accdb (.mdb for Access 2003 or earlier)

youraccountname_companyname_A4.docx (.doc for Word 2003 or earlier)

(remember to check your file names. They MUST match the required conventions above.)

(if you submit files with incorrect extensions (for example: .txt) you will lose marks ! )

AND PLEASE: Do not cheat or copy.

It takes up a lot of time and energy going through the, ‘no, I did not phase’ followed by the ‘okay, but I need a break phase’

to finally the ‘what if I promise never to do it again phase’.


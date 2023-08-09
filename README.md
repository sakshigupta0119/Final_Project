# Final_Project
# CITI PBWM ANALYST PROGRAM
# CREDIT CARD MANAGEMENT CHALLENGE


# INTRODUCTION
The goal of this challenge is to reinforce the technical skills taught during the training program, and to provide an opportunity to use the technology in the development of a typical real-world type of business application.
During this challenge, you will be required to perform the design, implementation and testing necessary to build a representative application for use within Citi using a typical technology stack.


# OBJECTIVES
Successful completion of the challenge will require:
• The development of an application that meets the Application Specification provided below.
• The application must include:
1. A usable-front end, built using pure HTML, CSS and JavaScript, React, or Angular the choice is up to your group.
2. A functioning back-end, using Spring Boot.
3. Storage and retrieval of data from a MongoDB database.
4. A well-designed REST API for the front-end and other potential clients to connect to.
5. Runnable tests to aid with future development.
• You will also prepare a demonstration to be presented to peers, instructors, and existing senior staff on Friday August 18.



# BUILD SCHEDULE
The expected work schedule is as follows.
August 9 – Populate a MongoDB database with credit card user data & create a simple API to expose some of the data.
August 11 – Refine the API to allow users to create, read, update and delete (CRUD).
August 17 – Design and implement a HTML/CSS/JS, React, or Angular user interface to interact with the API.
August 18 – Demonstrate the application.
If time permits deploy the REST API in a container or container orchestration platform using a pipeline.
Security and authentication are not required.



# CHALLENGE DEMONSTRATION
You will be required to give a short demonstration of the challenge to an audience that may consist of your peers, instructors,
managers, and other Citi staff. This will be at a specific time and date assigned to you.
At the presentation you should be able to:
1. Explain the architecture of the system you have built, such as what languages and frameworks it uses, any systems or tools on
which it depends on or is built upon, and any development techniques or code structures used.
2. Demonstrate the system running and illustrate how it is used.
3. Explain any limitations within the system, and how you might intend to further develop it.
4. A conclusion that summarises the potential use of your system, and perhaps a word on the training program/challenge itself.


# CHALLENGE REVIEW CRITERIA
By way of a checklist, when instructors and others review your challenge, they will be looking for evidence of the following:
▪ A demonstration of a fully working system, showing that all the minimum requirements have been met.
▪ Good use of the Rest standards for API design.
▪ The ability to explain code choices you have made.
▪ Code written to a good standard, with an appropriate structure, and tests of any business logic in place.
▪ Code and tests under version control - the sample code should be available via Bitbucket or GitHub repositories.
Good luck!


# APPLICATION SPECIFICATION
Citi have decided to trial a new credit card management application1
. The app will allow Citi Personal Banking Operations Analysts to
view the spending history of customers and to add new cards.
This document describes the way that the software will be used and what information must be stored. You must determine what the
system will look like (design, feel, page navigation etc), how information will be collected, updated and retrieved. At all times you
must consider how to make the system easy to use by the agents.




# DESIGN REQUIREMENTS
The application can be either on a desktop computer, where you may assume that the screen will always be a minimum of 1024
pixels wide, and/or on an iPhone, in portrait mode, where you should assume the screen will be 1080 pixels wide.
For the purposes of the trial, functionality is more important than design aesthetic, so do not worry too much about making the
application look good, although it must be usable on both types of devices.
# USE CASE 1 – VIEW SPENDING HISTORY
Operations Analysts need to be able to view, filter and summarize data using the following categories:
a. By gender
b. By spending category
c. By merchant
d. By city
e. By state
f. By population groups
g. By amount of spending (low value vs high value transactions)
You as a group can use your initiative to add to these requirements and give users of the application more features.
# USE CASE 2 – REGISTER A NEW CREDIT CARD
# USE CASE 3 – CANCEL A CREDIT CARD



# ADDITIONAL INFORMATION
For this version of the software, there is no requirement to implement security. You will be given sample data that can be imported
in a MongoDB database. This consists of a csv file with transaction history and a csv file of bank customers. The customer data you
can use in a collection that enables the application to be used to add and delete credit card information for use cases 2 and 3.

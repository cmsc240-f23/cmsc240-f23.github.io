---
layout: default
title: Project
---

# Project: C++ Web Service

## Project Description

This project aims to provide hands-on experience in designing and implementing a web service using the Crow framework, a high-performance C++ micro web framework. Teams will have the creative freedom to propose their own web service ideas. 

This project presents an opportunity for teams to creatively explore web service development, leveraging the power of C++ and Crow, while also emphasizing the importance of design, testing, and documentation in software development.

## Instructions

1. Complete all of the work in a Group GitHub repository: [https://classroom.github.com/a/klIieHru](https://classroom.github.com/a/klIieHru)
2. __Name your group using a combination of the first names of the group members.__ 

## Team Formation

#### Team Size: 
* 2 members per team

#### Roles and Responsibilities: 

* Team members should __share roles for all project aspects__ like design, coding, testing, and documentation.


## Part 1: Team Creation and Proposal

### Due:  Friday November 3rd <u>before lab</u>

#### Task: 
* Each team will brainstorm and propose an idea for a web service. 
* The idea shall be feasible and provide clear value to potential users.
* The idea shall be complex enough to have a __minimum of four resources__.
* For inspiration, here is a big list of public free APIs that do not require API keys:
[https://mixedanalytics.com/blog/list-actually-free-open-no-auth-needed-apis/](https://mixedanalytics.com/blog/list-actually-free-open-no-auth-needed-apis/)

#### Deliverable: 
* A brief proposal document outlining the web service concept.
* Add this proposal to the `README.md` file in your project GitHub repository.
* Add the names of your team members to the `README.md` file in your project GitHub repository. 


## Part 2: Design Document Creation

### Due: Thursday November 9th by 11:59 PM

* Create a detailed design document for the proposed web service. 
* The document should include:
    - __Introduction__: An overview of the web service and its purpose. 
    - __Background/Context__: The problem or need the web service addresses.
    - __Stakeholders__: Identify the parties interested in or affected by the web service.
    - __Functional Requirements__: A clear and detailed description of what the service will do.
    - __Use Case Description__: Describe __all__ the interactions between users and the system. This can be in the form of user stories. For example, “As a customer, I want to view book reviews and ratings before purchasing, so that I can make informed decisions.”
    - __List Of Resources__: A list of the resources available from your web service, with a description of each resource.
    - __List of End Points__: A list of REST endpoints that your web service will provide to users. Make sure to include the URL, the HTTP method (GET, POST, PUT, DELETE), the request BODY (if any) and request parameters (if any). Provide the expected response including the response BODY (if any) and HTTP status code. Provide your error handling strategies and expected HTTP error codes.
    - __UML Diagrams__: Create a class diagram outlining the main classes and their relationships.
  
#### Deliverable:   
* A comprehensive design document as described above. 
* Add your design document to the file `DESIGN.md` in your project GitHub repository.

## Part 3: Implementation

### Due: Friday December 1st by 11:59 PM

* Implement the web service in C++ using the Crow framework.
* Develop the RESTful API endpoints as per the design document.

#### Requirements:
1. The implementation shall have a minimum of __four classes__.
2. The implementation shall demonstrate a minimum of one __instance of composition__.
3. The implementation shall demonstrate a minimum of one __instance of inheritance__. 
4. The implementation shall demonstrate a minimum of one __instance of templates__.
5. The implementation shall __save the resources to a file__ after the Crow web service app is stopped.
6. The implementation shall __read the resources from a file__ before the Crow web service app is started.  
7. The implementation shall __include a Makefile__ with an all, clean, executable, and individual targets for each cpp file. 


#### Deliverable:
* A functioning web service.
* All the code needed to run your web service should be included in the project GitHub repository.
* A Makefile that will build each component of the web service, and the executable file.

## Part 4: Unit Testing

### Due: Friday December 8th by 11:59 PM

* Develop a suite of unit tests using a testing framework.
* __Testing Scope__: Cover all critical functionalities and endpoints.

#### Deliverable:
* A comprehensive unit testing suite ensuring the reliability of the web service.
* All the code needed to run your unit tests should be included in the project GitHub repository.



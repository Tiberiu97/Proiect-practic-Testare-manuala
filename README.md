<h1>Final project for ITF Manual Testing Course</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

<strong>Application under test: https://opensource-demo.orangehrmlive.com/<strong>

<strong>API Documentation: https://orangehrm.github.io/orangehrm-api-doc/<strong>

<strong>Tools used: JIRA, Zephyr Squad, Postman, MySQL Workbench<strong>.

<h1>Functional specifications</h1>

The below Story was created in JIRA and describes the functional specifications of the Dependants module, for which the final project is performed upon.

![Screenshot_4](https://github.com/Tiberiu97/Proiect-practic-Testare-manuala/assets/135150382/e91502e2-98fd-4ef2-8c97-c2def802debe)

<h1>1 Testing section</h1>

<h2>1.1 Test Planning</h1>

>The Test Plan is designed to describe all details of testing for the Immigrations module from the OrangeHRM application.

>The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

<h4>1.1.1 Roles assigned to the project and persons allocated</h4>

>* Project manager - Vlad Corcodel

>* Product owner - Vlad Corcodel

>* Software developer - Gabriela Radulescu

>* QA Engineer - Tiberiu Avram

<h4>1.1.2 Entry criteria defined</h4>

>* the website feature is partially/fully implemented

>* functional specifications are defined

>* roles needed for the project are allocated

>* A designated space to work

<h4>1.1.3 Exit criteria defined</h4>

>* all tests have been executed
  
>* all resolved bugs have been re-tested 
  
>* deadline was reached
  
>* no detected major risk remained un-mitigated
  
>* exploratory regression testing must be performed on the My Info module, which includes the Immigrations section

<h4>1.1.4 Test scope</h4>

>* Tests in scope: All the feature of Immigration module which were defined in software requirement specs need to be tested: functional testing, GUI testing and API testing

>* Tests not in scope: performance testing, integrations of the immigrations module with other modules

<h4>1.1.5 Risks detected</H4>

>* Project risks: lack of experience of the QA team, unavailability of test environment,  problems with test tools

>* Product risks: inability of the product to meet the customer's expectations

<h4>1.1.6 Evaluating entry criteria</h4>

>* The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.
  
  <h2>1.2 Test Monitoring and Control</h2>

>* Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken. The following status report was generated after 70% of the test cases were executed, on 17st July 2023:
  
  ![Screenshot_17](https://github.com/Tiberiu97/Proiect-practic-Testare-manuala/assets/135150382/a8e8f453-69be-42c0-b14e-78cc31b253c2)

  <h2>1.3 Test Analysis</h2>
  
The testing process will be executed based on the above requirements for the Immigration module. The following test conditions were found:

>* Enter data only for mandatory fields and check that the Immigration is created/updated
  
>* Enter data for all available fields and check that the Immigration is created/updated
  
>* Leave mandatory fields empty and check that the Immigration cannot be created/updated
  
>* View dependant details and check they are correct
  
>* View all Immigrations in a list
  
>* Check all validation constraints for the fields

<h2>1.4 Test Design</h2>

>Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are boundary value analysis, equivalence partitioning and use case testing.

*Test cases*

![Screenshot_10](https://github.com/Tiberiu97/Proiect-practic-Testare-manuala/assets/135150382/b48e6839-a43c-414c-806e-6147e2678238)

<h2>1.5 Test Implementation</h2>

>The following elements are needed to be ready before the test execution phase begins:

>* Testing environment is up and running: https://opensource-demo.orangehrmlive.com/

>* Access to the testing environment is given: Username : Admin | Password : admin123

>* Cycle summary was created

>* Test cases were added to the cycle summary

>* Postman collection with the dependents API methods was created

>* Authorization token was created for accessing the API

<h2>1.6 Test Execution</h2>

>* Test cases are executed on the created test Cycle summary

>* API tests are executed based on the checklist

<h2>1.7 Test Completion</h2>

>* As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

<h1>2 SQL section</h1>

>Created a database named 'orangehrm' and a table named 'immigrations' with all the columns needed to save data per specifications.

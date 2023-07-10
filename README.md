# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

<strong>Application under test: https://opensource-demo.orangehrmlive.com/<strong>

<strong>API Documentation: https://orangehrm.github.io/orangehrm-api-doc/<strong>

<strong>Tools used: JIRA, Zephyr Squad, Postman, MySQL Workbench<strong>.

<h1>1 Testing section</h1>

<h2>1.1 Test Planning</h1>

>The Test Plan is designed to describe all details of testing for the Admin module from the OrangeHRM application.

>The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

<h4>1.1.1 Roles assigned to the project and persons allocated</h4>

>* Project manager - Vlad Corcodel

>* Product owner - Vlad Corcodel

>* Software developer - Gabriela Radulescu

>* QA Engineer - Tiberiu Avram

<h4>1.1.2 Entry criteria defined</h4>

>* functional specifications are defined

>* roles needed for the project are allocated

<h4>1.1.3 Exit criteria defined</h4>

>* all tests have been executed
  
>* all resolved bugs have been re-tested 
  
>* deadline was reached
  
>* no detected major risk remained un-mitigated
  
>* exploratory regression testing must be performed on the Admin module, which includes the User manangement section

<h4>1.1.4 Test scope</h4>

>* Tests in scope: All the feature of Admin module which were defined in software requirement specs need to be tested: functional testing, GUI testing and API testing

>* Tests not in scope: performance testing, integrations of the dependents module with other modules

<h4>1.1.5 Risks detected</H4>

>* Project risks: lack of experience of the QA team, unavailability of test environment,  problems with test tools

>* Product risks: inability of the product to meet the customer's expectations

<h4>1.1.6 Evaluating entry criteria</h4>

>* The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.
  
  <h4>1.2 Test Monitoring and Control</h4>
  
  ![Screenshot_17](https://github.com/Tiberiu97/Proiect-practic-Testare-manuala/assets/135150382/a8e8f453-69be-42c0-b14e-78cc31b253c2)

  <h4>1.3 Test Analysis</h4>
  
>The testing process will be executed based on the above requirements for the Admin module. The following test conditions were found:

>* Enter data only for mandatory fields and check that the Immigration is created/updated
  
>* Enter data for all available fields and check that the Immigration is created/updated
  
>* Leave mandatory fields empty and check that the Immigration cannot be created/updated
  
>* View dependant details and check they are correct
  
>* View all Immigrations in a list
  
>* Check all validation constraints for the fields

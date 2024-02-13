# Testing Project for OLX
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: OLX <br>

Tools used: Jira, Zephyr Squad.
## Functional specifications:
The below stories were created in Jira and describe the functional specifications of the "Contul tau" module, for which the final project is performed upon.
![IDMT2](https://github.com/DMIonescu/Manual_Testing_Jira/assets/154073184/0e5e80b3-6594-4e3b-8780-d49b75fcf098)

![IDMT3](https://github.com/DMIonescu/Manual_Testing_Jira/assets/154073184/102d3902-12ef-4fd5-b2fc-e1fbfc6c34d2)

![IDMT4](https://github.com/DMIonescu/Manual_Testing_Jira/assets/154073184/b9e2b3d8-df0a-443d-8f1f-c8d8f7dd9c9a)

Here you can find the release that was created for this project:

![Release](https://github.com/DMIonescu/Manual_Testing_Jira/assets/154073184/28181b31-b20b-42be-a32b-d0c37bb41152)
## Testing process
The test process was performed based on the standard test process as described below.

### 1.1 Test planning <br>
The Test Plan is designed to describe all details of testing for the "Contul tau" module from the OLX application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (inserati link catre documentul cu planul de testare)

#### 1.1.1. Roles asigned to the project and persons allocated

- Project manager - Elena Marginean
- Product owner - Sebastian Popescu
- Software developer - Ovidiu Georgescu
- QA Engineer - Diandra Marina Ionescu

#### 1.1.2 Entry criteria defined

The business requirements are complete and available.
The roles and responsibilities are assigned to the team members.

#### 1.1.3 Exit criteria defined

All the text cases have been executed.

#### 1.1.4 Test scope

Tests in scope: <br>
In the scope of the testing is the "Contul tau" module of the OLX application which will also include the login function, a profile subsection in order to edit personal data and a section to post a new ad on the website. <br>
The types and techniques that will be used are:
- Functional testing
- Usability testing
- Equivalence Partitioning
- Boundary Value Analysis
- Decision Table
- Positive/Negative Testing <br>

Any other types or techniques that will be necessary will be applied accordingly. <br>
Testing will be done on Chrome browser and will cover only Windows operating system. <br>

Tests not in scope:

- Non-functional testing like stress, performance is beyond scope of this project.
- No QA support for mobile applications developed. Only web applications will be tested.
- Automation testing is beyond scope.

#### 1.1.5 Risks detected

Project risks:
- Poor communication among team members
- Team is understaffed

Product risks:
- stability risks (crashes, disconnects)
- Windows OS might have performance issues
- Google Chrome browser might have performance issues

#### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.2 Test Monitoring and Control
The execution of testing activities is tracked, measured and assessed. It involves frequent reviews to guarantee that targets are met at every stage of the testing lifecycle.
Test case execution metrics detail the number of test cases that have been executed, along with their outcomes (pass, fail, blocked)
![test metrics](https://github.com/DMIonescu/Manual_Testing_Jira/assets/154073184/164ed394-83af-40fb-8b21-64f27454ad90)

### 1.3 Test Analysis
The testing process will be executed based on the application requirements.

The following test conditions were found:

![tests](https://github.com/DMIonescu/Manual_Testing_Jira/assets/154073184/207107fb-1dd0-488a-9ade-e6416c5316b3)

### 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here [test cases.xlsx](https://github.com/DMIonescu/Manual_Testing_Jira/files/14257497/test.cases.xlsx)

### 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:
- Prepare test data for test execution
- Finalize, implement and prioritize test cases
- Prepare the testing environment

### 1.6. Test Execution
Test cases are executed on the created test Cycle summary: Test My account.

Bugs have been created based on the failed tests. The complete bug reports can be found here: (inserati aici fisierul cu bug-urile pe care le-ati identificat)


The following is a summary of the bugs that have been found (inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion 

As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.

The traceability matrix was generated and can be found here: (inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)

Test execution chart was generated and can be found below.

(inserati aici raportul de executie generat din jira din sectiunea de dashboards)

The final report shows that a number (inserati numarul de teste) tests have failed of a total of (inserati numarul de teste)

A number of (inserati numarul de bug-uri) total bugs were found, from which the priority is: (inserati numarul de bug-uri) are high and (inserati numarul de bug-uri) are medium.

(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)

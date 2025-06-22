# Testing Project for **OLX**
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: OLX

Tools used: Jira, Zephyr Squad.

# Functional specifications
The below story was created in Jira and describes the functional specifications of the "olx_modul" module, for which the final project is performed upon.

Here you can find the release that was created for this project:

[Release](https://github.com/davidgpop99/Manual_Testing_Project_For-OLX-.md/blob/main/release.png)

# Testing process
The test process was performed based on the standard test process as described below.

1.1 Test planning
The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (inserati link catre documentul cu planul de testare)

1.1.1. Roles asigned to the project and persons allocated

Project manager Fabian Cojocaru
Product owner Ionut Cheran
Software developer Alexandru Bucur
QA Engineer Popescu David 
1.1.2 Entry criteria defined
( User must be logged into the OLX application
Both User A and User B must be registered and logged in (for chat-related scenarios)
There must be an existing chat history between the users
Permissions must be granted for notifications and file access
Latest version of the OLX app must be used
)

1.1.3 Exit criteria defined
(Messages are delivered instantly to the other user
Status updates ("Sent", "Delivered", "Read") reflect accurately
Typing indicators display in real time
Offline messages are received when the user reconnects.
Messages can be searched by keyword and are highlighted or listed correctly.
Chat history remains intact after logout and re-login.
Blocked users cannot send messages; attempted messages are not delivered.
Deleted chats are removed from the chat list and message history is wiped.
Push notifications are sent and received as expected when a new message arrives.
)

1.1.4 Test scope
Tests in scope:
(Verify if the user can create with succesfull an announcement, Verify that an error is shown when title and description are missing
, Verify if the user can upload an image for announcement, Check if the user can filter Announcements by category, Verify if the user can edit an existing announcement, Verify that an error is shown when category and city are missing, Verify that an error is shown when contact person is missing, Verify if the user can deactivate an announcement, Check if the user can acces the statistics, Check if the user can access multiple announcements of a certain person, Verify that a message sent by one user appears instantly for the other user, Check the typing indicator is shown when a user is typing, Check that the message shows "Sent," "Delivered," and "Read" statuses correctly, Check that messages sent while one user is offline appear when they come online, Check that push notifications are triggered on receiving a new message, Verify image or file can be sent via chat, Verify chat can be deleted by the user, Verify chat history is retained after logout and re-login, Verify blocked user cannot send messages, Verify user can search messages in a chat thread.)

Tests not in scope:
(All tests covering the registration, login, and password recovery processes, assuming these features function optimally)

1.1.5 Risks detected
Project risks:
(Lipsa criteriilor detaliate de acceptare, Dependența critică de conexiunea la internet, Distribuție neuniformă a testării între module)

Product risks:
(Indicatorii de livrare și citire funcționează incorect, Funcționalitatea de blocare ineficientă, Căutarea în chat nefuncțională sau incompletă, Lipsa notificărilor sau notificări întârziate)

1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

## 1.2 Test Monitoring and Control
(Motivul pentru care există etapa de monitorizare și control în testarea software este acela de a asigura că activitățile de testare se desfășoară conform planului, să identifice devierile și să permită luarea de măsuri corective în timp util). [test status report/test summary](https://github.com/davidgpop99/Manual_Testing_Project_For-OLX-.md/blob/main/testreportsummary.png) 

[test metrics](https://github.com/davidgpop99/Manual_Testing_Project_For-OLX-.md/blob/main/test%20metrics.png)

The testing process will be executed based on the application requirements. 

The following test conditions were found:

(aici puteti fie sa puneti o poza din jira cu titlurile tuturor testelor - din issues filtrare dupa type test sau sa scrieti cu bulinuta numele fiecarei conditii de testare pe care ati identificat-o)

## 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here (inserati linkul catre fisierul cu testele, in format pdf, word sau csv)

## 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

(inserati lista de elemente care sunt evaluate in etapa de implementare)

## 1.6. Test Execution
Test cases are executed on the created test Cycle summary: (inserati aici numele cycle-ului pe care l-ati creat)

Bugs have been created based on the failed tests. The complete bug reports can be found here: (inserati aici fisierul cu bug-urile pe care le-ati identificat)

The following is a summary of the bugs that have been found (inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

## 1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
The traceability matrix was generated and can be found here: (inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)

Test execution chart was generated and can be found below.

(inserati aici raportul de executie generat din jira din sectiunea de dashboards)

The final report shows that a number (inserati numarul de teste) tests have failed of a total of (inserati numarul de teste)

A number of (inserati numarul de bug-uri) total bugs were found, from which the priority is: (inserati numarul de bug-uri) are high and (inserati numarul de bug-uri) are medium.

(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)


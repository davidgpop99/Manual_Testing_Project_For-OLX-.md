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

Project manager Fabian Cojocaru,
Product owner Ionut Cheran,
Software developer Alexandru Bucur,
QA Engineer Popescu David
1.1.2 Entry criteria defined
( User must be logged into the OLX application
Both User A and User B must be registered and logged in (for chat-related scenarios)
There must be an existing chat history between the users
Permissions must be granted for notifications and file access
Latest version of the OLX app must be used
)

1.1.3 Exit criteria defined
(Messages are delivered instantly to the other user,
Status updates ("Sent", "Delivered", "Read") reflect accurately,
Typing indicators display in real time,
Offline messages are received when the user reconnects,
Messages can be searched by keyword and are highlighted or listed correctly,
Chat history remains intact after logout and re-login,
Blocked users cannot send messages; attempted messages are not delivered,
Deleted chats are removed from the chat list and message history is wiped,
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

(The user can create with succesfull an announcement,
An error is shown when title and description are missing,
The user can upload an image for announcement,
The user can filter Announcements by category,
The user can edit an existing announcement,
An error is shown when category and city are missing,
An error is shown when contact person is missing,
The user can deactivate an announcement,
The user can acces the statistics,
The user can access multiple announcements of a certain person,
A message sent by one user appears instantly for the other user.)

## 1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here [Proiect_Popescu David](https://github.com/davidgpop99/Manual_Testing_Project_For-OLX-.md/blob/main/Proiect_Popescu%20David.docx)

## 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

(Se creează datele de testare, se grupează testele în funcție de importanța față de business și respectiv de riscuri și organizarea lor în suite de testare, crearea unui program de execuție a testelor).

## 1.6. Test Execution
Test cases are executed on the created test Cycle summary: (Cycle Summary)

Bugs have been created based on the failed tests. The complete bug reports can be found here: [bugs](https://github.com/davidgpop99/Manual_Testing_Project_For-OLX-.md/blob/main/Bugs.docx)

The following is a summary of the bugs that have been found (#1 căutarea nu evidențiază cuvinte, severitate medie, #2 utilizatorul blocat poate trimite mesaje, severitate critică, #3 istoricul chat-ului nu se reîncarcă dupa reconectare, severitate critică. )

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

## 1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
The traceability matrix was generated and can be found here: [matrice trasabilitate](https://github.com/davidgpop99/Manual_Testing_Project_For-OLX-.md/blob/main/matricea%20de%20trasabilitate.png)
Test execution chart was generated and can be found below.

[execution](https://github.com/davidgpop99/Manual_Testing_Project_For-OLX-.md/blob/main/cycle%20summary.png)

The final report shows that a number (3) tests have failed of a total of (17)

A number of (3) total bugs were found, from which the priority is: (2) are high and (1) are medium.

(The conclusions from the testing are as follows: 11 user stories, 20 test cases, 2 epics, 3 bugs, of which #1 bug (search does not highlight words) has a medium severity, and as an impact it disturbs the experience, but does not prevent communication, #2 (blocked user can send messages) has a critical severity, and as an impact it affects trust, possible abuse/spam, #3 (chat history does not reload after reconnecting) has a critical severity, and as an impact the user completely loses access to conversations, affects basic functionality. .)


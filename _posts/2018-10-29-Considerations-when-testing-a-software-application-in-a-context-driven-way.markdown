---
title: Considerations when testing a software application in a context-driven way
date: 2018-10-29 00:00:00 +0100
categories: [Strategy]
tags: agile conference rapidtesting skills strategy pco reporting    # TAG names should always be lowercase
<!-- pin: true -->
image:
  path: /assets/img/taskcoach.png
---

<blockquote class="prompt-info">Written by: Joris Meerts (main author), Huib Schoots and Ruud Cox at the time of writing all working at Improve Quality Services in the Netherlands.</blockquote>
### Introduction

One of the cornerstones of context-driven testing ([Lessons learned in software testing](https://www.amazon.com/Lessons-Learned-Software-Testing-Context-Driven/dp/0471081124){:target="_blank"} by Kaner, Bach, & Pettichord, 2001) is that the way of working when testing software is determined by the situation in which the tester finds himself. A good approach is not driven by a prescribed process or by a collection of steps that one habitually executes. Instead, it arises from the use of skills that ensure that testing matches the circumstances of the software project. Within the framework of context-driven testing, a wide range of skills is discussed, including critical thinking, modeling and visualization, note-taking and applying heuristics. It is not easy to learn these skills. One way to sharpen them is to do exercises and discuss the results. This was the purpose of a meeting of four testers at Improve Quality Services. In the following report we will elaborate on the exercises that were done during that meeting and on the results.

### Purpose of this report
As we pointed out in the introduction, it is not easy to learn the skills associated with context-driven testing. Practitioners of context-driven testing regularly refer to professional literature that describes these skills. But applying these skills is a process of trial and error. That is why it is important to simulate real life situations and learn from exercises we do. That was the purpose of the meeting. In this report we share the steps we took and the results of those steps, for example in the form of notes, sketches or models. We also share our experiences to make it easier to apply the skills in practice.

### The meeting
The meeting was held on February 14, 2017 at the office of Improve Quality Services in Eindhoven. The participating testers, Jos Duisings, Ruud Cox, Joris Meerts and Huib Schoots are all employees of Improve Quality Services (at that time).

### Background information
>Date: 14 February 2017<br>
Location: Improve Quality Services Eindhoven<br>
Start: 9 am<br>
End: 5 pm<br>
Team A: [Jos Duisings](https://www.linkedin.com/in/josduisings/){:target="_blank"}, [Ruud Cox](https://www.linkedin.com/in/ruudcox/){:target="_blank"}<br>
Team B: [Joris Meerts](https://www.linkedin.com/in/jorismeerts/){:target="_blank"}, Huib Schoots<br>

### The assignment
The assignment of the meeting is to select and execute tests on a software application. It is carried out by two teams of two testers each. This makes it possible to take different approaches and to provide feedback from one team to the other.

### Division in sessions
The meeting is divided into sessions in advance. The sessions each have their own goal and their own evaluation.
- Welcome & introduction
- Creating a coverage outline (per team)
- Debriefing the coverage outline
- Drafting a test strategy (as a group)
- Debriefing the test strategy
- Selecting a few charters
-  Performing a test session (charter) per team.
-  Debriefing the test session
- Retrospective

### Introduction of the application to be tested
The application to be tested has been selected prior to the meeting. We choose the application [Task Coach](https://www.taskcoach.org/){:target="_blank"} (Task Coach, 2018), an open source to-do list manager. This software is publicly available and runs on multiple platforms (Windows and Mac OS). The application is relatively simple but still offers sufficient complexity to be able to test thoroughly. According to the description on the website, Task Coach is ” a simple open source to-do manager to keep track of personal tasks and to-do lists. It is designed for composite tasks, and also offers effort tracking, categories, notes and more.” The participants have not worked with Task Coach before and are therefore not familiar with this specific piece of software.

### Creating a coverage outline
![product coverage outline](/assets/img/mindmap_taskforce.png){: width="300" .left}
Because Task Coach is new for all participants, the software will have to be explored. Only then can we say more about what can be tested in the given time. Such an exploration of the product can be done in many different ways. During the meeting we chose to make a ‘product coverage outline’, inspired by the [Heuristic Test Strategy Model](https://www.satisfice.com/tools/htsm.pdf){:target="_blank"} of James Bach (Bach, 1996). The [product coverage outline](https://developsense.com/blog/2018/04/very-short-blog-posts-35-make-things-visible){:target="_blank"} provides an overarching view of the product in which the functionality of the software is divided into seven different categories. The categories are described in the mnemonic SFDIPOT. The software tester is reminded by this heuristic that when mapping a product he can look at Structure, Function, Data, Interfaces, Platform, Operations and Time. By looking at the application from these perspectives, a relatively complete sketch is created of what the software product is and what it can do. However, the mnemonic does not only serve for exploration. The ‘map’ of the application that is created in this way can also be used to visualize the coverage of the tests and to select the tests to be carried out.
<br>
<br>
<br>
<br>
<br>
### The exercise
We decide that both teams will be given half an hour for creating a product coverage outline and that each team is free to decide which in which format the outline is presented. The choice of a half-hour time limit is mainly motivated by the fact that the software must also be tested before the end of the day. There is no room to spend much more time making the product outline.

It turns out that half an hour is not enough time for mapping an application that, despite the fact that it claims to be simple, still contains a lot of functions. Team B decides to create a mind map in which the seven categories are elaborated. This mind map is not finished after half an hour. Especially the branch ‘Function’, in which the functions of the application are described, is very large and has a deeply nested structure. To build this structure, team B explores the application by clicking through it and captures the functionality (in text or in image) in the mind map. Due to time constraints, team B presents a product sketch that is not finished. This triggers a discussion about what we expect the mind map to look like given the available time. The expectations, such as completeness, can be related to the purpose of the mind map. Through a discussion it becomes clear that no clear goal has been defined for drawing up the product sketch and that the result of the assignment is difficult to assess.

### Preference for the mind map
![Taskforce Help](/assets/img/task-coach-help.png){: width="300" .left}
A mind map is a tool that is used by software testers on a regular basis to create a product outline. The tree structure of the mind map lends itself to classifying (grouping) properties. It is easy to start with an empty mind map, enter the categories from SFDIPOT and expand these. Moreover, a navigable structure is created in this way. The mind map forms a kind of geographical map in which you can choose to zoom in and zoom out to determine the location of something in relation to the whole. Software essentially consists of zeros and ones and the software product is an abstract concept. By making the ‘map’ the abstract software gets a concrete shape. A mind map can also be used as an instrument for reporting on the results and the progress of the tests. So there are a number of good reasons to work with a mind map from the beginning.

Team A starts the session by creating a mind map but after a short time it switches to a different form. When studying Task Coach, the team finds out that there is a help file in the application. After a short study, the help file appears to describe a large part of the application. The categories from SFDIPOT all come back in the file to a sufficient extent and so Team A chooses to use this file, converted to Word format, as a product outline. By marking the categories in the document with different colors, structure is added to the document. In addition, the table of contents provides a global overview of the functionality in the application; the details are mentioned in the paragraphs. In this way, team A delivers a product sketch that is relatively complete within the stipulated time.

### Drafting the test strategy
![Taskforce Help](/assets/img/risico-inschatting.png){: width="300" .left}
The result of the first session is a product outline. With this product sketch and the knowledge gained during the exploration of the software it is easier to discuss a [test strategy](/posts/creating-a-test-strategy){:target="_blank"}. Because exhaustive testing of an application is not feasible for the majority of software applications and because exhaustive testing in many cases does not yield better information, it is desirable to make choices with regard to the test work to be performed. We find these choices in the test strategy.

By making the product outline we have gained insight into a number of aspects of the application. We take these aspects into account and we hope to indicate per category whether this category needs to be tested and if so with which depth. The most decisive factor in that decision is the risk the company encounters when the software is put to use. Risk is a multifaceted concept and can only be determined if the software product is highlighted from different angles. In any case, the perspective of the tester alone is not sufficient to get a good picture of the risks of a software product. During the second session it becomes clear that a representative is missing who can reason about risk from the perspective of a user or of the organization. This point is also discussed in the debriefing of the second session and we conclude that for that reason the risk assessment is incomplete.

### Assessing risk
In the Heuristic Test Strategy Model three dimensions are discussed that influence a test strategy. These dimensions are the project, the product and the requirements that are set for that product; the quality characteristics. Risks play a role in each of these dimensions. In the exercise, we decide not to look at the project risks. As far as product risks are concerned, we make our own assessment with regard to the categories of the product. We consider categories that are used the most, are the most prone to errors and categories where a possible error has the most impact. Because there are no users involved in the exercise, we try to place ourselves in the role of the users. This way the following product categories are discussed.

- The primary process from the Operations category. This will tell us which functionality is used the most.
- Using the application by multiple users from the Operations category. We recognize risks associated with synchronization: tasks are not updated properly.
- The importing and exporting of tasks from the Interfaces category.
- Dealing with reminders from the Functionality category. Reminders are crucial for not missing appointments.
- Dealing with date and time from the Time category. Date and time play an important role in planning tasks, they touch the core of the application.

After we have identified the categories of the product, we try to assess which quality aspects of the product are the most in demand. Here too, it has been decided to use our own assessments as a guideline. The following quality aspects are named:

- Functionality,
- Usability and
- Charisma

### Coverage
We briefly discuss the coverage of the tests that we want to carry out. Since the tasks that are maintained in Task Coach can have different statuses, the tester can, from the perspective of state transitions, visualize the coverage level of the tests carried out. The state transitions are covered in the different paths through the application that a user travels. These paths are helpful when mapping the coverage. Furthermore, coverage can be looked at from the perspective of the test data used.

### Drafting the charters
![Taskforce Help](/assets/img/charters.png){: width="300" .left}
We decide to make two charters ([Session Based Test Management](https://www.satisfice.com/sbtm/){:target="_blank"}) and to execute them. We prioritize the product categories mentioned in the risk analysis based on our own insights. From this we conclude that ‘the primary process’ and ‘dealing with date and time’ are the two most important product categories. We translate these two categories into charters. In one charter we will look at the primary process, in the other charter the handling of date and time will be investigated. Each team selects a charter. After the charter has been executed, each team reports the work done to the other team in a debrief session. During this short evaluation, the tester will tell his story and answer any questions. The evaluation has several goals, such as assessing whether the mission is successful, translating new insights into follow-up sessions, looking at notes and descriptions of findings and coaching the tester. Due to the debrief, the understanding of the application under test grows.

### The charter for testing the primary process
To formulate a starting point for this charter, we look at the risks that can be associated with the execution of the primary process. There is a risk that no task can be created. Or it could be that the task is created but errors occur when saving or modifying a task or changing the status of a task. These considerations lead to the following mission that serves as the starting point for the charter: “Explore the basic flow of tasks using CRUD to discover/test the life cycle of a task”.

The charter for testing the handling of date and time
Prior to drafting the charter for testing the handling of date and time, the following test ideas are mentioned:

- Start and end times are the same
- The end time is before the start time
- The date of a task is far in the past or far in the future
- System time
- Work in different time zones
- Dealing with winter time and summer time
- Different date formats

With these test ideas in mind, the following charter is drawn up: “Explore tasks using date/time to discover date and time related bugs”.

### Execution of the charters

### Testing the primary process
The charter for testing the primary process (basic flow) begins with the creation of a task. Several tasks are created using the button on the taskbar. Subsequently, several underlying tasks are created for a single task, up to 8 levels deep. Under one of the underlying tasks, a new tree structure of underlying tasks is created. During the creation of the task structure, questions arise about the maximum depth of the task structure and about the sorting of the underlying tasks. In addition, it is found that it is possible to delete underlying tasks and then to undo these deletions. It is proposed to further investigate this functionality in a separate charter, since it is suspected that this is not always going well. The resulting tree structure is removed by means of the ‘Delete’ button on the taskbar. After this, all tasks have disappeared.

On the taskbar there is also a button that offers the possibility to create new tasks from a template. There are two default templates available. Tasks are created with these templates. It appears that it is not possible to create underlying tasks from a template. The question is why this functionality is not available for underlying tasks. Finally, the created tasks are deleted.

To get a better picture of how templates work in the application, the help text is read over templates. Furthermore, the team explores the menu structure in search of more functionality that could be related to the use of templates. From the ‘File’ menu it is possible to save tasks as templates, to import templates and to edit templates. A template is created.

From the dialog that appears when choosing to import a template it appears that template files have the extension ‘.tsktmpl’. But when a task is saved as a template, it is not possible to find out whether a template file is created from this task and, if so, where this file is stored. The newly created templates are visible when one chooses to create a new task based on a template from the toolbar.

A task is created, saved and checked if this task can be imported. Again, all created tasks are deleted by selecting the menu option Edit > Delete. The team looks a bit further at the options for removing tasks. It appears that there is a shortcut combination for removing tasks. The combination is Ctrl + DEL. The team wonders why it is not possible to simply use the Delete key.

In summary, this session looked at creating, viewing, editing and deleting tasks and underlying tasks. A finding has been made regarding the undoing of changes. It turns out that undoing the removal of tasks in a tree structure of tasks and underlying tasks does not produce the same structure as the original structure. Following the session, it is proposed to look more extensively at the use of templates in new charters. Also the functionality for creating, viewing, editing and deleting tasks and underlying tasks deserves more attention, especially because this functionality can be called from many different places in the application. The various possibilities have not all been tested in the first session. Furthermore, a charter could be made for creating a task depending on another task.

### Feedback
At the end of the session, the report of the session was discussed with a member of the other team with the aim of obtaining feedback about the course of the session in a [debrief](https://en.wikipedia.org/wiki/Session-based_testing){:target="_blank"}. The feedback shows that there was not enough time to complete the charter. To complete the charter another thirty to sixty minutes would be needed. It is noted that the description of the detected bug is not clear enough. It also becomes clear that not all possible statuses of a task have actually been addressed in the session. Finally, a new charter is suggested for testing filtering and sorting.

### Testing the handling of date and time
The session is started with a clean installation of the application. First a new task is created. Attention is given to the Data tab on which various data can be entered. The date and time can be changed in separate input fields. The time can be changed by means of a dropdown or by using the arrow keys on the keyboard. It turns out that ’00:00′ cannot be used as time. It appears that the range of time can be set under the ‘Preferences’ menu. After an adjustment, ’00:00′ can be entered.

It is noted that the planned start date and the planned end date are not included in the calculation of duration. But it is unclear what this data will be used for. When the planned end date is in the past, the task will turn red. When the planned end date is in the future, the task will turn purple. It is remarkable that the planned start date can be after the planned end date. Apparently there is no validation on the order of data. Dates that are far in the future are accepted as valid dates. To change a date, the task will first have to be closed and then opened again.

An interesting finding occurs when, at the planned start date, the year is set for 1900. If this is the case, the planned start date cannot be changed after closing and reopening the task. During the study of this finding, the team finds out that the application creates a log file (in the Documents folder) in which any errors are logged. The attempt to adjust the planned start date results in the following error message: “ValueError: year = 1853 is before 1900; the datetime strftime () methods require year> = 1900”. After this finding, further attention is paid to other functionality around time and date. For example, a reminder on a task is set to 5 minutes. The reminder works.

In addition to planning tasks TaskCoach can also be used to keep track of the time spent per task. After some research it appears that this functionality is complex and that it is not easy to find out how TaskCoach deals with time spent. Time tracking can be started with a button, but can also be done by increasing the time spent in a separate tab. The team notices that when entering an hour of time spent, the actual time spent shown on the tab is just a few seconds. It is possible to aggregate time spent at month level. If we do this, we see that the descriptions that we have listed for each entry are combined in a single text field.

The time that an application uses depends on the time setting on the system. For this reason, the team manipulates the system time of a MacBook Pro. The calendar is changed to a Coptic calendar. This adjustment causes the application to crash after startup. In the log a line appears mentioning an error relating to an invalid date format.

Finally, the team looks at the connection between the budgeted time and the time spent. TaskCoach is able to calculate the remaining time on the basis of the variables mentioned. Some tests are performed with variations in hours, minutes and seconds. TaskCoach handles all these variations correctly.

### Feedback
A team member verbally reports on the session to a team member of the other team in a debrief. The feedback shows that this report contains a lot of detailed information. To be able to place the detailed information, a framework is needed. The product outline could have been used as a framework. One new charter emerges from the feedback, namely the testing of the synchronization of tasks between systems with different system times.

### Conclusion
The meeting is concluded with the completion of the test sessions. Looking back we conducted, in a day with two teams, a number of tests on an application that was unknown beforehand. We have shown that techniques and methods exist that help the tester to acquire knowledge about the application, develop a strategy and perform tests. Exploring the application provides insights that serve as a starting point for risk assessments and for conducting test sessions with a well-defined goal. By quickly arriving at concrete and well-substantiated tests, the tester provides valuable feedback on the application in a short period of time. The test sessions are debriefed and this provides starting points for further deepening where necessary.

Due to the popularity of agile methods, it is common for the tester to be asked to test something, while at that moment he has incomplete insight into the functionality of the application. Moreover, the tester is expected to deliver results within a limited time. It requires an approach in which the tester quickly draws up and executes a strategy by modeling, thinking critically, discovering and investigating. This is the approach that we applied during the meeting described above.

### A Clash of Models
The creation of the product coverage outline led to quite different outlines being delivered by the teams. These differences and their possible causes are discussed in a separate article, written by Joris Meerts and Ruud Cox. The article is called [A Clash of Models](/assets/files/a-clash-of-models-sqmag-may-2018-cox-and-meerts.pdf){:target="_blank"}.

References
Bach, J. (1996). [Heuristic Test Strategy Model](https://www.satisfice.com/tools/htsm.pdf){:target="_blank"}.
Kaner, C., Bach, J., & Pettichord, B. (2001). [Lessons Learned in Software Testing](https://www.amazon.com/Lessons-Learned-Software-Testing-Context-Driven/dp/0471081124){:target="_blank"}. John Wiley & Sons.
Task Coach. (2018). Retrieved from Task Coach: [https://taskcoach.org/](https://taskcoach.org/){:target="_blank"}

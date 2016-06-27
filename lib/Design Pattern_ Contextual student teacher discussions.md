<img src="md\img002/media/image01.png" width="624" height="65" />

*Promoting Knowledge Practices in Education (KNORK) http://knork.info*

*The Re-use Library*

**Educational design pattern: Student-teacher communication embedded in a developed document**

**Author(s):** Vassiliy Tchoumatchenko and Tania Vasileva

**Affiliation(s):** Technical University of Sofia, Bulgaria

**Date of publication**: June 21st, 2016

**1. The educational problem**

Suppose that we have a project based learning class, with students divided in multiple teams. As part of the deliverables, each team is required to submit a report with summary of the design steps, the decisions made and the outcomes.

Students are encouraged to seek advice, related to projects, by email. Most questions concern a specific design step and specific part of the project report. Usually, the email itself do not contain sufficient context for the teacher to provide an adequate answer, without looking at the project report first. When such mail arrives, the professor’s has to:

1.  Identify the team

2.  Find the related report document (on some document sharing platform)

3.  Find the particular place in the document

4.  Answer the question.

In cases where professors have to supervise dozens of project teams, the overhead of steps 1 to 3 becomes significant.

Another kind of problem is the decoupling of the email based questions/answers from the project artifacts. It makes both analyzing the project evolution and archiving all artifacts more complicated than necessary.

**2. The solution**

*Therefore*, we are proposing a workflow, based on questions and answers embedded in the project report and automatically generated email notifications.

Prerequisites

-   The professors and students have Google accounts

-   Google Docs is used for collaborative project report authoring

Project initiation

-   For each team, create a Google document. Initially the document contains the subject of the project and the team members’ contact details.

-   Share the documents with the team members. Give them “Can edit” rights and select the “Notify people” check-box.

-   Google docs automatically sends emails to each student

-   The students can open the document by clicking on the "Open in Docs" link in the email. Later, they can find the document in the “Shared with me” folder of their Google Drive.

It’s important to note that the professor should remain the owner of the shared document. Also, in order to guarantee reasonable access control, the document should be shared with gmail accounts only.

Questions and answers

-   When a student needs help , he/she opens the shared document and adds a comment. The comment should be attached to some text in the area to which the question is related.

-   The owner of the document (i.e. the teacher) receives an email containing the text of the comment and a hyperlink to the comment itself.

-   By clicking on the hyperlink, the teacher gets to the exact place in the Google document where the comment is located, thus the context of the question is established.

-   The teacher review the text and answer the question by adding a "Reply" to the comment.

The proposed design patterns allows for more focused, context aware student to teacher communication. All questions and answers remain in the shared document. They might be hidden or even deleted, but still will be available in the documents history.

**3. The context**

This pattern might conceivably be applied to any collaborative learning activity centered around shared artifacts. Originally, the described technique was developed for project based courses in engineering curricula.

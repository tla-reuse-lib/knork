<img src="md\img023/media/image01.png" width="624" height="65" />

*Promoting Knowledge Practices in Education (KNORK) http://knork.info*

*The Re-use Library*

**Educational design pattern: Tools and rules for student collaboration**

**Author(s)**: Tania Vasileva and Vassiliy Tchoumatchenko

**Affiliation(s)**: Technical University of Sofia

**Date of publication**: March 14, 2015

**1. The educational problem**

The time and group management among the students may be crucial for passing the courses. Students may need help in coping with the group work, the submission of assignments, and, with the workload in general both on an individual level as well as in the teams that they are engaged in.

**2. The solution**

*Therefore*, introduce tools/methods that enhance students’ cooperation and collaboration. In practice, it may be a good idea to agree on the choice of tool together with the responsible teacher of the course. When the main design artefacts (VHDL models and test-benches) are text files, we are able to borrow many tools and workflows from the software development community. To get students started, set up accounts for the groups of students who are planned to be working collaboratively and share the links to their accounts during the first day of the course. Provide a few tips for better collaboration in their group work.

Projects can be hosted on GitHub – one repository per project. The code review can be done on Gerrit. When a team member submits a change for code review, the project is automatically built and the tests are executed. The outcome of the build job is reported back to Gerrit as +1 (pass) or -1 (fail) vote, but they are not enough to approve or reject a change. Another team member shall perform a code review and either approve the change (+2 vote) or return it to the submitter for rework. Gerrit allows the reviewer to attach comments to a source code file or a particular line inside the file.

**3. The context**

University level courses which include collaborative student work and especially on software development and where there is some preparedness on the part of the students and teachers to learn to work with new tools.

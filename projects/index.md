---
title: "Projects"
description: ""
---

# Projects

The following projects have been released (this list will update over time):

<!--
- [Project 7](./7) due Sunday, April 19, 2026 by 11:59PM Eastern (No peer grading. NO LATE DAYS ALLOWED)
- [Project 6](./6) due Sunday, April 5, 2026 by 11:59PM Eastern (Peer grading due by Sunday, April 12, 2026 by 11:59PM Eastern)
- [Project 5](./5) due Sunday, March 22, 2026 by 11:59PM Eastern (Peer grading due by Sunday, March 29, 2026 by 11:59PM Eastern)
- [Project 4](./4) due Sunday, March 8, 2026 by 11:59PM Eastern (Peer grading due by Sunday, March 15, 2026 by 11:59PM Eastern)
- [Project 3](./3) due Sunday, February 15, 2026 by 11:59PM Eastern (Peer grading due by Sunday, February 22, 2026 by 11:59PM Eastern)
-->

- [Project 2](./2) due Sunday, February 1, 2026 by 11:59PM Eastern (Peer grading due by Sunday, February 8, 2026 by 11:59PM Eastern)
- [Project 1](./1) due Tuesday, January 20, 2026 by 11:59PM Eastern (Peer grading due by Tuesday, January 27, 2026 by 11:59PM Eastern)
- [Project 0](./0) due Tuesday, January 13, 2026 by 11:59PM Eastern (Peer grading due by Tuesday, January 20, 2026 by 11:59PM Eastern)

**For 15622 students (grad students) only**: [Term project](./622-term)

**NOTE: All students must read the policies on this syllabus and fill out [this form]($INTEGRITY) by the end of week 1 (Fri Jan 16).**

See below for [instructions on submitting projects via ATutor](#submitting-projects) and [project grading policies](#grading-policies)

## Submitting projects

**Submitting a Project in ATutor – General Instructions**

**Create a .zip file as instructed in the Project description for each assignment. Make sure it has the right files, with the right file names, and at the right directory/folder level** — typically files will be the top level of the zip file, not in a directory in the zip file.

_For example, for Project 0, you will have a folder that has two files in it, p0.wav and p0.txt_:

- `Project0/`
  - `p0.wav`
  - `p0.txt`

_You should **make the zip file from within the project folder**, not outside the folder. In UNIX/LINUX, you can do this as follows, assuming your project folders are in a folder named ICM off your home directory:_

```sh
cd $HOME/ICM/Project0
zip ../Project0.zip *.{wav,txt}
# This creates the zip file in the ICM folder, but it does not zip the Project0 folder itself.
```

For projects where you have subfolders, use the -r option to recursively include subfolders. **Test your zip file by copying it to another location and unzipping. You should see the files extract without creating an additional top-level directory.**

**Make sure submissions are anonymous** (for peer grading). You will lose points if your submission is not anonymous.

1. Log into ATutor at: $ATUTOR
1. Use the Project tab and upload the project zip file.
1. After a reasonable delay (depending on submission size and server load), you should get an “autograde” and comments to explain what was wrong if anything.

**Important**. Once you are satisfied with your auto grade, make sure you press **Confirm** to lock in your submission.

![ATutor confirmation example](./images/atutor_confirm.png)

You can resubmit up to the deadline (and beyond if you wish to accept a late penalty). The last possible submission time is one day before the end of peer grading, usually 6 days after the posted submission deadline.

### Peer Grading

24 hours after the submission deadline, peer grading begins. You are expected to grade 3 submissions from your peers.
Log in to ATutor again after the start of peer grading and look under the Project tab. You are expected to peer grade three projects from other students. You may do extra peer grading for extra credit. But there is a penalty if you peer grade less than 3 projects.

**Your peer grade comments must be meaningful and scores must be reasonable based on what score the TA assigns. If you submit an _inaccurate_ peer grade (e.g. a high grade when there were clearly major things wrong with the project), or a _vacuous_ one (little to no feedback), we reserve the right to invalidate your peer review and adjust your own project score.**

Please review the additional instructions to peer graders you will see each time you go to do peer grading.

Once you receive your grade for your project, you can go back into ATutor to see your peer and TA reviews.

## Grading policies

1. Your project grades mainly consist of two parts: Auto Grade and Peer Grade, and there are some possible bonus points and penalties. Auto Grade and Peer Grade both contribute 10 points, for a maximum of 20 points.
1. Peer grading begins 24 hours after the submission deadline and is open until one week after the project submission deadline. **Peer grading cannot be submitted late.**
1. **Everything submitted must be anonymous**, or you will lose some points in peer grading.
1. Follow instructions to grade others’ projects and be constructive. Comments are necessary. If you submit a _superfluous_ peer grade, we reserve the right to invalidate your peer review, which will affect your own project score. For example, superfluous peer grades include ones where you (1) submit a high score when the project had major / obvious errors, or (2) **submit only trivial written feedback, such as "Cool!"**.
1. (e.g. a high score when the project had major, clearly obvious errors, or a score with trivial feedback)
1. For each project (except Project 0 which is just “practice”), your **Project Grade** is calculated as follows:

- Let A = the autograde assigned by ATutor for your latest submission
- Let P = the median of all grades from your peers through peer-grading
- Let T = the peer-grade from a TA
- Let N = the number of students YOU peer-graded for the project assignment
- Let L = the late factor ranging from starting at 1.0 at the project deadline and linearly decreasing to 0.5 at the end of the late deadline
- Let B = peer-grading “bonus”, where B = 2 if N >= 5; B = 1 if N = 4; B = 0 if N = 3; B = 2\*(N/3 – 1) if N < 3.
- Then, your project grade will be computed as **( A + (P+T)/2 + B ) \* L**.
- (NOTE: The instructors have the option to override the peer/TA mean with their own score if necessary.)

Some details about grading are given below:

1. You may submit as many times as you’d like, but we will grade and peer-grade only the last submission. If you submit before the deadline, you cannot submit during the peer grading period that follows. If you do not submit by the deadline, you will have one submission up to 6 days after the deadline, with a late penalty. The penalty increases daily from 0% to 50% during this late period and is applied after all other grade calculations. **In all cases, be sure to CONFIRM your submissions once you get the autograde results to store that grade for your assignment.**
1. You have **3** grace days for late submissions. **At most one grace day can be used per project, except for Project 7 and the 15622 project (no grace days may be used for these final projects).** If a grace day is used, there is no penalty assigned for that day.
1. The grades will be released by the instructor. If you have any questions about your grades, please read the above policies carefully. You are encouraged to ask your teaching assistant if you do not understand your grade. If you think that something has been graded incorrectly, you should post a private message on Piazza within 3 days of the grade release and state clearly why you think your grade is incorrect. The instructors have final say on any regrade requests.
1. If the instructors determine that you have committed an academic integrity violation on a project, your grade on the project will be -20 and your actions will be reported to the University. See the course academic integrity policy for details.

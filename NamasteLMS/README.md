## Overview
Namaste LMS (Learning Management System) is a Wordpress plugin that looks like a good candidate plugin for meeting the Reentry needs.

"LMS" stands for "Learning Management System", which is a category of software that provides courses/lessons/assignments.   Looking at the original requirements for ReEntry, it's not hard to see how they could be broken down along those lines.  Plus Namaste includes built-in support for handling students, and tracking their progress.

*Download:*  Namaste is a plugin for Wordpress that you can download from here:  https://wordpress.org/plugins/namaste-lms/

*Documentation:* http://namaste-lms.org/

## Notes

* It *looks* like Namaste caches the course content when a student enrolls in a course, so if you are making changes to the course that do not show up when testing as the student, clear the student's enrollment and re-enroll.  
1. On WP admin page, select Namaste LMS > Students
1. In the "Select Course" dropdown, select your course
1. Find your student's record in the student grid, and click on the "Cleanup" link (in Status column) 

* If you want to test as two different users (e.g. the admin who is creating content vs. the student viewing the content), you may want to try a Wordpress plugin called "User Switching", which allows you to quickly & easily switch between users.  

[finis]

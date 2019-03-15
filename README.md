# TutorQ
North Seattle College Student Learning Center Tutor Session Management System

## Problems in the Student Learning Center
North Seattle College tutoring center had problems with clickers. Students could not send a tutor request. Also, administrators of writing center collected data with papers, and they have to go through each page to analyze usage.

## Introduction
TutorQ supports and improve experiences of administrators, tutors, and students in the tutoring center. It allowes students sending tutor requests without problems. In addition, administrators can analyze and manage data in online. No papers!  

### Three interefaces 
- Admin
- Student
- Tutor

## Admin

#### Home Page
- The four cards show : new students for this week, new students of this quarter, total time (hr) of this quarter, and total accesses of this quarter. 
- The general statistics visualize the usage of center for the last 7 days. Admins can select center to see different usage. 
- Admins can add notification which will be shown in student page. 
- The four cards infomation is based on a quarter's start and end time. And the quarter can be edited in the bottom tab. 
- In the "Loggeg in tutor" card, admins can look up who's loggeg in and log out tutors from timekeeper.


#### Report page
- There are three different types of reports: students, tutors, and resources. Also, administrators can generate report of detial and accumulated of each type.
- #### Resource page
  - The graph shows hourly data of selected date. 

#### People page
- There are studens, tutors, and coordinators list.

#### Manage
- Coordinators and director can add a center and subject. When they add a center, they can choose template among 4 choices. 
- #### templates 
  - 0 : For TimeKeeper
  - 1 : Place, Number, Subject
  - 2 : Tutor, Subject
  - 3 : Student's name, Place, Number, Tutor, Subject 
  - 4 : Subject
  
## Student 

#### Home page
- The form requires studens to choose which center they're in, and renders inputs based on center's template. For example, Math&Science center's template is number 1, so it renders place, nubmer, and subject inputs. 
- In the tutor session card, studens can look up tutor requests but not editable. 

## Tutor

#### Home page
- Home page retrieves tutor session from database and show in the tutor session card. 
- The UI of tutor sessions differ based on selected center's template. 
- Tutors can modify (start, pause, and end) session in the tutor session page. 

## Technologies used
- PHP
- JavaScript
- jQuery
- MySQL
- HTML
- CSS
- Bootstrap
- chart.js

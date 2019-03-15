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

<img width="1440" alt="index" src="https://user-images.githubusercontent.com/34498187/54460533-0c780680-4727-11e9-9d9e-9000cfa94e4d.png">
<img width="1439" alt="Screen Shot 2019-03-13 at 4 01 39 PM" src="https://user-images.githubusercontent.com/34498187/54461193-2286c680-4729-11e9-96d2-31fe6e390856.png"> 
<img width="1232" alt="Screen Shot 2019-03-13 at 4 01 44 PM" src="https://user-images.githubusercontent.com/34498187/54460590-30d3e300-4727-11e9-9144-8a3f3cd06480.png">

- The general statistics visualize the usage of center for the last 7 days. Administrators can select a center. 

- Administrators can add notification in "Notification" card, and it will be shown in the student page. 

- The four cards infomation is based on a quarter's information which can be edited with "Update Quarter" card. 

- In the "Loggeg in tutor" card, administrators can look up who's loggeg in and log out tutors from timekeeper.

#### Report page
Administrators can generate students, tutors, and resources reports between selected dates. With students report, they can look up  and they can be accumulated or detailed. 

#### Ex. Student report accumlated and indivisual
<img width="1112" alt="Screen Shot 2019-03-15 at 2 11 24 PM" src="https://user-images.githubusercontent.com/34498187/54462252-4ef01200-472c-11e9-891e-f59d16b64bcf.png">

<img width="1232" alt="stu-detail" src="https://user-images.githubusercontent.com/34498187/54461965-5e229000-472b-11e9-865e-997b85d5b038.png">


- #### Resource page
  <img width="1440" alt="resource" src="https://user-images.githubusercontent.com/34498187/54461970-6084ea00-472b-11e9-97bf- c086e8b604e5.png">

  - The graph shows hourly usage of selected date. 
  - Defualt is today's usage.
  
  
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

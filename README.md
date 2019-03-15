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

#### Ex. Student's accumlated and indivisual report
<img width="1112" alt="Screen Shot 2019-03-15 at 2 11 24 PM" src="https://user-images.githubusercontent.com/34498187/54462252-4ef01200-472c-11e9-891e-f59d16b64bcf.png">

<img width="1232" alt="stu-detail" src="https://user-images.githubusercontent.com/34498187/54461965-5e229000-472b-11e9-865e-997b85d5b038.png">

- Administrators can generate students, tutors, and resources reports between selected dates. With students report, they can look up  and they can be accumulated or detailed. 

- #### Resource page
  
  <img width="1440" alt="resource" src="https://user-images.githubusercontent.com/34498187/54462285-6cbd7700-472c-11e9-94b9-d0d8e150fa5d.png">

  - The graph shows hourly usage of selected date. 
  - Defualt is today's usage.
  - Coordinators can also change center and subject 
  
  <img width="1235" alt="Screen Shot 2019-03-15 at 2 14 36 PM" src="https://user-images.githubusercontent.com/34498187/54462367-bad27a80-472c-11e9-84ca-9e925f59e4c9.png">
  
  
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

<img width="399" alt="student" src="https://user-images.githubusercontent.com/34498187/54462825-426cb900-472e-11e9-8dad-bd80655b2299.png">
<img width="399" alt="student2" src="https://user-images.githubusercontent.com/34498187/54462826-43054f80-472e-11e9-9fe0-e3e165a91762.png">
<img width="395" alt="student3" src="https://user-images.githubusercontent.com/34498187/54462827-43054f80-472e-11e9-9d36-a9dcf665d138.png">

#### Home page
- The form requires students to choose which center they're in, and renders input doms based on center's template. For example, Math&Science center's template is number 1, so it renders place, nubmer, and subject inputs. After they choose a center, they can send request. 
- In the tutor session card, studens can look up tutor requests but not editable. Tutor sessions will be shown after students choose a center. 

## Tutor
Tablet / Computers
<img width="1440" alt="tutor" src="https://user-images.githubusercontent.com/34498187/54462702-e9048a00-472d-11e9-8ce8-458bce5c4c77.png">

SmartPhone
<img width="400" alt="tutorSm" src="https://user-images.githubusercontent.com/34498187/54462698-e5710300-472d-11e9-8d97-5b36c5ee8dc2.png">


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

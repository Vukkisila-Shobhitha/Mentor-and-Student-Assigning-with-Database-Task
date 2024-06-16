The Mentor-Student Management System is designed to facilitate the management of mentors and their assigned students. It provides a set of APIs to create, assign, and manage mentors and students in a database.


It's developed using by NodeJs, ExpressJs, MongoDB.

Method: GET / Get all students
URL: http://localhost:3000/students


Method: POST / Create a new student
URL : http://localhost:3000/students/create

Method: GET / Get all mentors
URL: http://localhost:3000/mentors

Method: POST / Create a new mentor
URL: http://localhost:3000/mentors/create

Method: PUT / Assign students to a mentor by ID
URL : http://localhost:3000/mentors/:id (replace id with actual mentor ID)

Method: PUT / Assign mentor to a Student by ID
URL : http://localhost:3000/mentors/:studentID 

Method: GET / Get all students from particular mentor by name
URL : http://localhost:3000/students/mentor/Hari

Method: GET / Get previousMentor from particular student by ID
URL : http://localhost:3000/students/previous_mentor/Student_ID



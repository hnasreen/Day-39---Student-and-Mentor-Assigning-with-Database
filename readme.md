### Day 39 - Mentor and Student Assigning with Database Task

## Render.com Url Link: 

https://day-39-student-and-mentor-assigning-with.onrender.com

**Postman End Points:**

# create mentor : 

> Method : POST

> url: https://day-39-student-and-mentor-assigning-with.onrender.com/mentors

> add the data with the below sample data:

{
    "name": "johnyyy doeee",
    "email": "johnyyydoeee@example.com"
}

# create a student:

> Method : POST

> url: https://day-39-student-and-mentor-assigning-with.onrender.com/students

> add the data with the below sample data:

{
    "name": "john doe",
    "email": "johndoe@example.com"
}

# Assign a student to Mentor:

> Method: PUT

> URL: https://day-39-student-and-mentor-assigning-with.onrender.com/assign-student/:mentorId/:studentId

> Replace :mentorId and :studentId with actual Mentor and Student IDs.

# Select one mentor and Add multiple Students

> Method: PUT

> URL: https://day-39-student-and-mentor-assigning-with.onrender.com/add-students/:mentorId

> Replace :mentorId with the actual Mentor ID.

> add the data with the below sample data:

{
    "students": ["studentId1", "studentId2", ...]
}


# A student who has a mentor should not be shown in List

> Method: GET

> URL: https://day-39-student-and-mentor-assigning-with.onrender.com/students

# Assign or Change Mentor for particular Student

> Method: PUT

> URL: https://day-39-student-and-mentor-assigning-with.onrender.com/change-mentor/:studentId/:newMentorId

> Replace :studentId and :newMentorId with actual Student and Mentor IDs.

# Select One Student and Assign one Mentor

> Method: PUT

> URL: https://day-39-student-and-mentor-assigning-with.onrender.com/assign-mentor/:studentId/:mentorId

> Replace :studentId and :mentorId with actual Student and Mentor IDs.

# Show all students for a particular mentor

> Method: GET

> URL: https://day-39-student-and-mentor-assigning-with.onrender.com/mentor-students/:mentorId

> Replace :mentorId with the actual Mentor ID.

# Show the previously assigned mentor for a particular student

> Method: GET

> URL: https://day-39-student-and-mentor-assigning-with.onrender.com/previous-mentor/:studentId

> Replace :studentId with the actual Student ID.





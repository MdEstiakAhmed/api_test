# API test

###### A simple API test with laravel fromework. All type of CRUD operation's API has been created. Postman application is used to test the API's. I give the details bellow.

### There are two table. One is students table and another one is courses.

## students table API's:
create a students (post): http://localhost:8000/api/students
View all students (get): http://localhost:8000/api/students/
Update a student: http://localhost:8000/api/students/{id}
Delete a student: http://localhost:8000/api/students/{id}

### students table insert json format:
{
    "name": "test",
    "email": "test@test.com",
    "password": "12345"
}
### students table update json format:
{
    "name": "test",
    "password": "12345"
}

## courses table API's:
create a courses (post): http://localhost:8000/api/courses
View all courses (get): http://localhost:8000/api/courses/
Update a course: http://localhost:8000/api/courses/{id}
Delete a course: http://localhost:8000/api/courses/{id}

### courses table insert json format:
{
    "course_name": "test"
}
### courses table update json format:
{
    "course_name": "test"
}
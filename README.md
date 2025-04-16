# api-studens
API to manage 'GOlang do zero' course students

Routes:
- GET /students - List all students
- POST /students - Create student
- GET /students/: id - Get infos from a specific student
- PUT /students/: id - Update student
- DELETE /students/:id - Delete student

struct student 
- Name
- CPF
- Email
- Age
- Active
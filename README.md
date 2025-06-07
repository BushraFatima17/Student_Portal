# Student Management System - C++ Project

## Overview
This is a C++ console-based Student Management System that allows three types of users to interact with the system:
1. **Admin** - Can manage courses, faculty, and student registrations
2. **Faculty** - Can manage student attendance, grades, and view assigned courses
3. **Students** - Can enroll in courses, view attendance, check grades, and view fee challans

## Features

### Admin Functions
- Register new courses with details (semester, code, credit hours, fee)
- Add faculty members with their bio-data
- Register students with their personal information

### Faculty Functions
- View list of enrolled students
- Mark and view student attendance
- Create quizzes/assignments with weightage
- Enter student marks for assessments
- View assigned courses

### Student Functions
- Enroll in available courses
- View attendance records
- Check obtained marks and grades
- View and generate fee challans (including optional hostel, library, and internet fees)

## How to Use

1. Compile the program using a C++ compiler (g++ recommended)
2. Run the executable
3. Select your role (Admin, Faculty, or Student)
4. Use the menu options to perform various operations

### Login Credentials
- **Admin**: Username = "admin" (no password check implemented -- bec it is made for my use so didn't implement it.)
- **Faculty/Students**: Use registered names (no password check implemented)

## Code Structure
The program uses object-oriented programming with these main classes:
- `login` - Base class for login functionality
- `bio_data` - Stores personal information
- `course` - Manages course-related data
- `admin` - Inherits from multiple classes to provide admin functionality
- `faculty` - Handles faculty operations
- `student` - Manages student operations

## Limitations
- No persistent data storage (all data is lost when program exits)
- Basic authentication (no proper password management)
- Limited error handling
- Console-based interface only

## Future Improvements
- Add database connectivity for data persistence
- Implement proper authentication system
- Add more robust error handling
- Develop graphical user interface

## How to Contribute
1. Fork the repository
2. Create a new branch for your feature
3. Commit your changes
4. Push to the branch
5. Create a pull request


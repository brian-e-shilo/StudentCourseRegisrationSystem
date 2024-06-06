# Student CourseRegisration System

**Problem Statement: Student Registration System**

Suppose a student would like to register for a set of courses for a semester to meet their credit requirements. Assume all courses are worth 4 credits each. Considering the following constraints, a student shall complete their course registration:

**a) registerCourse(course name, course code)**

- Allows the student to register for a course.
- The student can register for a maximum of 5 courses, including a mini-project.
- If the student tries to register for more than 5 courses, an ExceedCourseException is thrown.

**b) checkCredits()**

- Ensures the student registers for a minimum of 10 credits and a maximum of 20 credits.
- If the student registers for more than 20 credits, an ExceedCreditException is thrown.
- If the student registers for fewer than 10 credits, a MinCreditException is thrown.

**c) registerProject(title, teamsize)**

- Allows the student to register a mini-project.
- The team size can be a maximum of 4 students.
- If the team size exceeds 4, a TeamSizeExceedException is thrown.

**d) displayReport()**

- Displays the registration report, showing the courses registered, total credits, and project details if applicable.

**Introduction to Exception Handling in Java**

Exception handling in Java is a robust mechanism that manages runtime errors, ensuring the smooth execution of a program. When an error occurs, Java generates an exception object, which is then handled through a set of predefined procedures. This mechanism provides a way to respond to different error conditions and maintain the normal flow of the program.

**Key Concepts:**

- **Exception**: An event that disrupts the normal flow of the program’s instructions. It can be a checked exception (compile-time) or an unchecked exception (runtime).
- **Try-Catch Block**: A construct that allows you to define a block of code to be tested for errors (try), and a block of code to handle the error (catch).
- **Finally Block**: Executes a block of code, regardless of whether an exception was thrown or not.
- **Throw**: Used to explicitly throw an exception.
- **Throws**: Indicates what exceptions may be thrown by a method.

I have attached the complete pdf, which is also the same file that I had submitted as an assignment for my college earlier this year. It illustrates everything in detail.

Hope you find it helpful!


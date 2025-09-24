# Campus Course & Records Manager (CCRM)

CCRM is a Java console application designed for university-level student, course, enrollment, grading, and file utilities management. It supports interactive CLI-based operations such as adding/listing/updating/deactivating students and courses, enrolling and grading, transcript viewing, and data import/export/backup.

## Features

- Student Management: Add, list, update, deactivate students, view student profiles and transcripts
- Course Management: Add, list, update, deactivate courses, search/filter courses, assign instructors
- Enrollment & Grading: Enroll/unenroll students in courses with business rules, record grades, compute GPA, view transcripts
- File Operations: Import/export CSV files for students/courses, backup and restore project data, recursive directory size checking
- Instructor Assignment: Assign instructors when adding/updating courses
- CLI Workflow: Menu-driven console with intuitive options for all features

## Folder Structure

CCRM/
├── src/
│ └── edu/ccrm/
│ ├── cli/
│ ├── config/
│ ├── domain/
│ ├── service/
│ ├── io/
│ └── util/
├── students.csv
├── courses.csv
├── README.md
├── USAGE.md
├── requirements.md

## Setup Instruction

- Insatll Java JDK
  - Download JDK 17 pr higher from the Oracle website.
  - Install it and set environment variables.
- Install intellij IDEA
  - Download intellij IDEA
  - Create a new Java project -> Import src folder.
  - Add students.csv and courses.csv in project root.
- Compile and Run from Commant Line
  - Go to the project folder
  - Compile the source code
  - Run the application

## Java concepts used

- Classes and Objects → Student.java, Course.java
- Inheritance and Interfaces → Instructor.java, EnrollmentService.java
- Collections Framework → StudentService.java (uses List and Map)
-  Exception Handling → ValidationUtil.java, CsvImporter.java
-  File Handling (NIO.2) → BackupService.java, CsvExporter.java
-  Packages → all code under edu.ccrm.*
-  Assertions → used in ValidationUtil.java

## Evolution of Java

- 1995 → First release by Sun Microsystems
- 2004 → Generics and annotations added (Java 5)
- 2011 → NIO.2 introduced (Java 7)
- 2014 → Lambdas and Streams (Java 8)
- 2017–2021 → Features like var, modules, records, sealed classes

## Java Editions

- Java ME (Micro Edition) → Small devices, IoT, mobiles
- Java SE (Standard Edition) → Core Java, standalone apps
- Java EE (Enterprise Edition / Jakarta EE) → Web and enterprise applications

## JDK, JRE, JVM

- JVM → Runs Java bytecode
- JRE → JVM + libraries (for running Java apps)
- JDK → JRE + compiler & tools (for developing Java apps)

## Enabling Assetions

- Assertions are used for debugging and checking conditions.
- RUn with assertions enabled

## Technologies

- Java 17 or higher
- Uses NIO.2 for file and backup operations
- No external dependencies required

## Author

- DIKSHA MITRA

## Contact

- dikshamitra3109@gmail.com

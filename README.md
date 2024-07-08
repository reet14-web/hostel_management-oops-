# Hostel Management System

## Description
The Hostel Management System is a C++ program designed to handle the various daily tasks of managing a hostel, such as reserving beds and handling payments. It uses Object-Oriented Programming (OOP) concepts to manage hostel data, track bed availability, and process student reservations.

## Features
- Connects to MySQL database for data storage
- Reservation of beds for students
- Fee calculation and display
- Data persistence using MySQL
- Console-based user interface

## Object-Oriented Concepts Used
- Data Encapsulation
- Modularity
- Reusability

## System Requirements

### Hardware
- Processor: Pentium III or higher
- RAM: 64 MB or more
- Hard Disk: 20 GB or more

### Software
- Operating System: Windows XP or newer
- MySQL Server
- C++ Compiler (e.g., GCC, MSVC)
- MySQL Connector for C++

## Header Files Used
- `iostream`: Standard input/output operations
- `mysql.h`: MySQL database operations
- `windows.h`: Windows-specific functions
- `sstream`: String stream operations

## Main Class: Hostel

### Data Members
| Member   | Type   | Description                        |
|----------|--------|------------------------------------|
| Name     | string | Name of the hostel                 |
| Bed      | int    | Number of beds available           |
| Fee      | int    | Fee per bed                        |

### Member Functions
| Function     | Return Type | Description                          |
|--------------|-------------|--------------------------------------|
| getName()    | string      | Returns the name of the hostel       |
| getBed()     | int         | Returns the number of available beds |
| getFee()     | int         | Returns the fee per bed              |

## How to Run
1. Ensure you have MySQL server installed and running.
2. Set up the `mydb` database and `hostel` table in MySQL.
3. Update the `USER` and `PW` constants in the code with your MySQL credentials.
4. Compile the program using a C++ compiler.
5. Run the program.

## Note
This project was developed for a specific system configuration. For modern use, ensure that the MySQL server and C++ development environment are properly set up. Consider updating the code for compatibility with newer C++ standards and practices.

## Contributing
Contributions to enhance and modernize this project are welcome. Feel free to fork the repository and submit pull requests.

## License
[MIT License]


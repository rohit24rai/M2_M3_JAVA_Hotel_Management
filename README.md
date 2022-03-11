
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/7e2d4ee93638451ba65512baaac23a32)](https://app.codacy.com/gh/rohit24rai/M2_M3_JAVA_Hotel_Management?utm_source=github.com&utm_medium=referral&utm_content=rohit24rai/M2_M3_JAVA_Hotel_Management&utm_campaign=Badge_Grade_Settings)

Hotel-Management-OOP-Project
This is a Hotel Management tool which can be used to manage activites like storing customer details, booking rooms of four different types, ordering food for particular rooms, unbooking rooms and showing the bill. It can also be used to see different room features and room availibility. It is a menu driven program and it runs until the user exits. File handling has been used to store the current status of the hotel(customer details, booked rooms, food ordered) in a file once the program exits so that when we restart the program, the old details are not lost. The program reads the file when it restarts to know the previous status of the hotel. Writing of file has been done in a separate thread as it can be done parallely. User defined exception is thrown if the user tries to book an already allotted room. Exception handling is properly done to deal with any kind of unexpected exception.

Concepts-
Classes and Objects, Inheritance, File Handling with Objects, ArrayList, implementing Interface, User defined exception and Exception handling.


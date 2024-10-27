# CS-320

To ensure functionality and security in my project, I followed a systematic approach to testing. I implemented JUnit tests to validate the functionality of the Contact, Task, and Appointment services, focusing on meeting specific constraints like character limits and ensuring unique IDs. This method of testing helped verify that the software was not only functional but also adhered to all specified requirements. By focusing on edge cases, such as boundary conditions and null inputs, I enhanced the testing quality. While security testing was not a primary focus in this project, ensuring data integrity through constraints and testing for invalid inputs contributes to the overall security of the application.

Interpreting user needs involved translating requirements into functional code by working through each constraint. For example, the user need for unique contact IDs and strict field length limits (a ten-character limit for first names) was translated into validations within the code. User needs were also considered in terms of how the application should respond to incorrect inputs, such as by throwing exceptions for invalid or null values. By adhering to these requirements and incorporating them into the design and tests, I ensured that the program aligned with the user’s expectations.

When designing software, I break down the project into smaller services or components, each with clearly defined responsibilities. For example, the Contact, Task, and Appointment services were designed with distinct functionalities, allowing me to focus on one aspect of the program at a time. My approach involves building out each service based on the user’s requirements, ensuring that constraints are enforced, and then writing tests to validate the functionality. This method allows for modular design, making the code easier to test, maintain, and expand upon. 

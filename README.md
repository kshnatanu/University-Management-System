
# University Management System

## Overview
The University Management System is a desktop application designed to manage student and teacher details efficiently. The application allows administrators to update personal information, manage courses, and maintain records in a user-friendly interface.

## Features
- **Student Management**: Update student details such as name, address, phone number, email, Aadhar number, course, and branch.
- **Teacher Management**: Update teacher details including name, address, phone number, email, Aadhar number, qualification, and department.
- **Dynamic Data Loading**: Select a student or teacher from a dropdown list to automatically load their details for easy updating.
- **Database Integration**: Interacts with a database to fetch and update records securely.

## Technologies Used
- **Java**: The primary programming language for application development.
- **Swing**: For building the graphical user interface (GUI).
- **JDBC**: For database connectivity and executing SQL queries.
- **MySQL**: The database used to store student and teacher information.

## Setup Instructions
To run this project locally, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/university-management-system.git
   cd university-management-system
   ```

2. **Install MySQL**
   Ensure that MySQL is installed on your machine. Create a database and set up the necessary tables as required by the application.

3. **Database Configuration**
   Update the database connection settings in the `conn.java` file to match your local MySQL configuration.

4. **Compile and Run**
   Compile the Java files using your preferred IDE (like IntelliJ IDEA or Eclipse) or via the command line.
   ```bash
   javac *.java
   java UpdateStudent
   ```

## Usage
1. Launch the application.
2. Choose either the "Update Student" or "Update Teacher" option from the main menu.
3. Select the respective ID from the dropdown list to load the current details.
4. Update the necessary fields and click "Update" to save changes.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements or additional features.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Special thanks to [Anupam Kumar] for developing this project.

## Contact
For any questions or suggestions, please contact [kshantanu838@gmail.com].

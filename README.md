# Employee-Data-Management-System


---



## Overview
The **Employee Data Management System** is a command-line application written in Python for managing employee records. It provides functionalities such as adding, updating, deleting, searching, and listing employee data. The data is stored in a CSV file, making it easy to persist and manage records.

---

## Features
- **Add Employees**: Add new employees with unique IDs.
- **Update Employees**: Modify employee details such as name, position, salary, or email.
- **Delete Employees**: Remove employee records by ID.
- **Search Employees**: Look up employee details by their unique ID.
- **List Employees**: Display all employee records stored in the system.
- **Persistent Storage**: Employee data is saved to a CSV file (`employees.csv`) for future use.

---

## Prerequisites
Ensure you have the following installed on your system:
- Python 3.x
- Basic knowledge of Python and command-line operations

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/employee-data-management-system.git
   cd employee-data-management-system
   ```

2. Install dependencies (if any):
   ```bash
   pip install -r requirements.txt
   ```
   *(Optional: Only include this step if you later decide to add external libraries)*

3. Run the application:
   ```bash
   python employee_management.py
   ```

---

## Usage
1. Follow the on-screen menu options:
   - Add an employee by providing the required details such as ID, name, position, salary, and email.
   - Update employee information by providing the ID and the fields to be changed.
   - Delete an employee using their unique ID.
   - Search for a specific employee using their ID.
   - List all employees stored in the system.

2. The application will save all data to `employees.csv` in the same directory.

---

## Code Structure
- **Employee Class**: Represents individual employee records with methods for updating and converting data to a dictionary format.
- **EmployeeManager Class**: Handles the core logic for managing employee records (loading, saving, adding, updating, etc.).
- **Main Function**: Provides a command-line interface for user interaction.

---

## Input Validation
- Ensures valid email formats using regex.
- Verifies salary input to ensure it is a positive numeric value.

---

## Future Enhancements
- Add a graphical user interface (GUI).
- Support for multiple file formats (e.g., JSON, SQLite).
- Implement user authentication for better security.

---

## Contribution
Contributions are welcome! Feel free to fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

---


---

## Author
- Ebrahim BenBella
- This Project done under Supervision Of Eng. Baraa Abusallout
- LinkedIn: [Your LinkedIn Profile](www.linkedin.com/in/ebrahim-benbella-37b113261)  


---


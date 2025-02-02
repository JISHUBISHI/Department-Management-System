# Department Management System

## Overview
This is a command-line-based **Department Management System** written in Python. It allows users to manage students, courses, batches, departments, and examinations with various operations such as creation, modification, performance tracking, and visualization.

## Features
- **Student Management**: Add, update, remove students and generate report cards.
- **Course Management**: Create courses, view student performance, and display course statistics.
- **Batch Management**: Manage student batches, courses in batches, and performance metrics.
- **Department Management**: Organize batches under departments, track performance, and visualize department statistics.
- **Examination Management**: Enter marks, view exam performance, and generate scatter plots for analysis.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Required dependencies

### Clone the Repository
```sh
git clone https:https://github.com/JISHUBISHI/Department-Management-System.git
cd Department-Management-System
```

## Usage
Run the main script to start the program:
```sh
python main.py
```

### Menu Navigation
- The system provides a menu-driven interface where users can select operations.
- Input the corresponding number to choose an action.
- Enter `0` to return to the main menu or exit the program.

## Modules Overview
- `main.py` - The entry point of the application, handling user interactions.
- `student.py` - Contains functions for student-related operations.
- `course.py` - Manages course creation, student performance tracking, and statistics.
- `batch.py` - Handles batch operations including students, courses, and performance analytics.
- `department.py` - Manages departments and batch statistics visualization.
- `examination.py` - Handles exam marks entry, student performance, and statistical analysis.

## Example
```
Press 1 to do student operations
Press 2 to do course operations
Press 3 to do batch operations
Press 4 to do department operations
Press 5 to do examination operations
Press 0 to stop
Enter your choice: 1
```
## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

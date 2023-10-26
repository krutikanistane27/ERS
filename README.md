# Employee Review System

The Employee Review System (ERS) is a web-based application designed to facilitate employee management and performance review processes. It provides distinct views for both administrators and employees, each equipped with specific functionalities to streamline various tasks related to employee management and performance reviews.


## Prerequisites

Before you can run this project, make sure you have the following installed:

- **Node.js**

- **npm (Node Package Manager)**


## Usage

1. **Starting the API**: To start the API, run the following command:
    ```
    npm start
    ```

    The API will be accessible at http://localhost:8000.
#


## Setup

1. Clone this repository to your local machine:

   ```shell
   https://github.com/PyDeveloperAniket/Employee-review-system.git

2. Navigate to the project directory:

   ```shell
   cd Employee-review-system

3. Install the required dependencies:

   ```shell
   npm install

4. start server:

   ```shell
   npm start

#


## Usage

1. **Starting the Project**: To start the Application, run the following command:
    ```
    npm start
    ```

    The Project will be accessible at http://localhost:8000.
#

## Admin View:

1. **Employee Management:**: 
- Add Employee: Administrators can add new employees to the system, providing details such as name, email, and password.
- Remove Employee: Admins have the authority to remove employees from the system.
- Update Employee: The ability to update employee details, including name, email, and password.

2. **Performance Review Management:**: 
- Add Performance Review: Admins can initiate performance reviews for employees, recording relevant feedback.
- Update Performance Review: Modify existing performance reviews, ensuring the data is accurate and up-to-date.
- View Performance Review: Admins can view a comprehensive list of performance reviews, providing insights into employee progress.

3. **Assignment of Performance Reviews**: 
- Assign Employees: Admins have the capability to assign employees to participate in another employee's performance review. This ensures a 360-degree feedback mechanism.


## Employee View:

1. **Performance Review Feedback:**: 
- List of Reviews Requiring Feedback: Employees can view a list of performance reviews that require their feedback.

2. **Feedback Submission:**: 
- Submit Feedback: Employees can submit their feedback for the assigned performance reviews, contributing to a comprehensive evaluation.

3. **User Authentication:**: 
- Single Login for Admin and Employee: The system supports a unified login mechanism, allowing both administrators and employees to access their respective views with a single set of credentials.

4. **User Registration and Administration:**: 
- Employee Registration: New employees can register themselves in the system, providing the necessary information.
- Admin Privileges: Only administrators have the authority to designate an employee as an admin, granting elevated access and control.

## Key Features:

1. **Role-Based Access:**: 
- The application employs role-based access control, ensuring that admins and employees have access only to the functionalities relevant to their roles.

2. **Intuitive Interface:**: 
- The user interface is designed to be user-friendly, facilitating easy navigation and interaction.

3. **Secure Authentication:**: 
- The system prioritizes security by enforcing secure user authentication mechanisms, safeguarding sensitive information.


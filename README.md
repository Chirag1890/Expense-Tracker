# Expense Tracker

## Project Name: Expense Tracker

### Description

This project is an expense tracker built using Spring Boot (backend) and Angular (frontend). The backend is powered by Spring Boot and MySQL, and the frontend is developed in Angular, providing a modern, responsive, and user-friendly interface.

#### Backend (Spring Boot & MySQL)

- **Expense Controller:** Handles all APIs related to expenses (CRUD operations, fetching all expenses).
- **Income Controller:** Manages APIs for incomes (CRUD operations, fetching all incomes).
- **Stats Controller:** Provides APIs for retrieving statistics (balance, total expenses, total income, highest/lowest expenses, highest/lowest incomes, and graph data for visualizing trends).
- The backend is built using Spring Boot, following a layered architecture (controllers, services, repositories, entities) and connects to a MySQL database via Spring Data JPA. It also includes features such as user registration, JWT-based authentication, input validation, and error handling.

#### Frontend (Angular)

- The frontend is built using Angular, offering a modern, responsive, and user-friendly interface.
- Users can seamlessly navigate through components to add, update, or delete income and expense records, categorize transactions, and view detailed summaries.
- The UI integrates dynamic visualizations (pie charts and bar graphs) using chart libraries to offer insightful financial overviews.
- It communicates with the backend via RESTful APIs to fetch and update data in real-time, ensuring scalability and maintainability.

---

## How to Run the Project

1. **Clone the Repository**

   Move to your desired project folder and clone the repository:

   ```sh
   cd path/to/your/project
   git clone https://github.com/Ayaan-Chudesara/springboot_expensetracker.git
   ```

2. **Backend (Spring Boot)**

   - Open the backend Spring Boot application in IntelliJ (preferred) or VSCode.
   - Create a database named `expense_tracker` in MySQL Workbench.
   - Build and run the Spring Boot application (using Maven or your IDE).

3. **Frontend (Angular)**

   - Open the frontend folder (e.g., `ExpenseTracker_FrontEnd`) in VSCode.
   - Install dependencies and Angular CLI (version 16):

     ```sh
     npm install
     npm install -g @angular/cli@16
     ng version
     ```
   - Open an integrated terminal in the Angular project folder and run:

     ```sh
     ng serve
     ```
   - Open the hosted application (typically at `http://localhost:4200`) in your browser.

4. **Login Credentials**

   - **User:** admin  
     **Password:** 1234

---

Feel free to contribute or open issues! 
# Task Manager (To-do List) 

A user-friendly task management application built for organization and productivity. 

## Description
This application provides a straightforward way to create a user account and track your to-do lists with the following features:

* **Task Management (CRUD):** 
    * Create new task items with a title, description, and target date.
    * Read and view your existing tasks.
    * Update the details of your existing tasks.
    * Delete tasks as they are completed.
* **User Authentication:** Secure task management using JWT-based authentication.

## Technologies Used
* **Backend:**
    * Spring Boot
    * Spring Data
    * Spring Security
    * MySQL (database)
* **Frontend:**
    * React.js
    * Bootstrap
* **Containerization:**
    * Docker

## Getting Started

**Prerequisites**

* Java JDK 
* Node.js and npm (or yarn)
* Docker

**NOTE:** Docker is used for database only. It can be configured without docker too.

### **Instructions**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/task-manager.git
   ```

2. **Backend Setup:**
   * Navigate to the backend directory (`/backend`).
   * Configure appropriate database credentials in `application.properties`.
   * Build and run the Spring Boot application using your preferred IDE, or from the terminal:
     ```bash
     ./mvnw spring-boot:run 
     ```

3. **Frontend Setup:**
   * Navigate to the frontend directory (`/frontend`).
   * Install project dependencies:
     ```bash
     npm install 
     ```
   * Run the React development server:
     ```bash
     npm start
     ```

4. Access the application in your web browser, typically at `http://localhost:5173`.

## How to Contribute

Contributions are always welcome! Here's how you can get involved:

* Report bugs or suggest features by opening an issue in the GitHub repository.
* Fork the repository and create a pull request to submit code changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) for details.
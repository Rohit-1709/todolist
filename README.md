<<<<<<< HEAD
# todolist
=======
# To-Do List Application

This is a simple REST API service for managing a to-do list application built with Spring Boot and H2 in-memory database.

## Features

- Create a new task
- Fetch all tasks
- Fetch a task by its ID
- Update task status (pending, in-progress, completed)
- Delete a task by its ID

## Prerequisites

- Java 11 or higher
- Maven
- An IDE (e.g., IntelliJ IDEA, Eclipse) or a text editor
- Postman (for testing the API)

## Getting Started

### 1. Clone the Repository

Clone this repository to your local machine using the following command: git clone https://github.com/yourusername/todolist.git

### 2. Navigate to the Project Directory
Change to the project directory:  cd todolist

### 3. Build the Project
Use Maven to build the project. Run the following command: mvn clean install

### 4. Run the Application
You can run the application using the following command: mvn spring-boot:run
Alternatively, you can run the TodoListApplication class directly from your IDE.

### 5. Access the Application
Once the application is running, it will be accessible at: http://localhost:8080

### 6. Testing the API with Postman
You can use Postman to test the API endpoints. Below are the instructions for each endpoint:

Create a New Task
Method: POST
URL: http://localhost:8080/tasks
Body (JSON):
{
    "title": "Task 1",
    "description": "Description for Task 1"
}

*Fetch All Tasks
Method: GET
URL: http://localhost:8080/tasks

*Fetch a Task by ID
Method: GET
URL: http://localhost:8080/tasks/{id} (replace {id} with the task ID)

*Update Task Status
Method: PUT
URL: http://localhost:8080/tasks/{id} (replace {id} with the task ID)
Body (JSON)
{
    "status": "completed"
}

*Delete a Task
Method: DELETE
URL: http://localhost:8080/tasks/{id} (replace {id} with the task ID)
>>>>>>> cabb489 (first commit)

# Library Application
This project is an online library application developed with Spring Boot, Angular, and PostgreSQL. It provides a book management system, user management, and loan tracking, with authentication and authorization features to ensure security.

<img width="1440" alt="Screenshot 2024-01-24 at 11 11 33 AM" src="https://github.com/diazms04/libraryAPP/assets/92173560/a582085a-6439-4b30-b054-5797a4d956b7">


## Technologies Used

- **Spring Boot:** Backend of the application, providing business logic and the REST API.
- **Angular:** Frontend of the application, offering an interactive user interface.
- **PostgreSQL:** Relational database used to store information about books, users, and loans.
- **Login Authentication:** Implemented to ensure the security of the application.

## Key Features

1. **Book Management:** Allows adding, editing, deleting, and searching for books in the library.
2. **User Management:** Manages information about users, including personal details and roles.
3. **Loans:** Facilitates the process of borrowing and returning books.
4. **Authentication and Authorization:** Only authenticated users can access certain functions, with specific roles for administrators and regular users.

## Project Setup

### Backend (Spring Boot)

1. Clone the repository: `git clone https://github.com/yourusername/online-library.git`
2. Navigate to the backend directory: `cd online-library-backend`
3. Configure the PostgreSQL database in `src/main/resources/application.properties`.
4. Run the Spring Boot application: `./mvnw spring-boot:run`

### Frontend (Angular)

1. Navigate to the frontend directory: `cd online-library-frontend`
2. Install dependencies: `npm install`
3. Configure the backend URL in `src/environments/environment.ts`.
4. Start the Angular application: `ng serve`

## Accessing the Application

Once the backend and frontend are running, the application will be available at `http://localhost:4200`. You can log in with the default credentials:

- **Admin User:**
  - Username: admin
  - Password: admin123

- **Regular User:**
  - Username: user
  - Password: user123

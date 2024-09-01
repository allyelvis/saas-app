# SaaS Application with Health Center and School Modules

## Project Description
This project is a SaaS (Software as a Service) application that includes modules for managing Health Centers and Schools. The application is built using Node.js, Express, Sequelize, and PostgreSQL, providing a robust and scalable backend for managing patients, appointments, students, and teachers.

## Features
- **Health Center Module**
  - Manage patients, including adding, listing, and updating patient records.
  - Handle appointment scheduling for patients.
  
- **School Module**
  - Manage student records, including adding, listing, and updating students.
  - Manage teacher records and their respective subjects.

## Installation

### Prerequisites
- Node.js
- PostgreSQL

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/saas-app.git
   cd saas-app
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables with your PostgreSQL configuration:
     ```plaintext
     PORT=3000
     DB_NAME=saas_db
     DB_USER=your_username
     DB_PASSWORD=your_password
     DB_HOST=localhost
     DB_DIALECT=postgres
     ```

4. Run the database migrations and seed data (if any):
   ```bash
   npx sequelize-cli db:migrate
   ```

5. Start the application:
   ```bash
   npm run dev
   ```

## Usage

### API Endpoints

#### Health Center Module
- **Get all patients:**
  ```http
  GET /api/health-center/patients
  ```

- **Add a new patient:**
  ```http
  POST /api/health-center/patients
  ```

#### School Module
- **Get all students:**
  ```http
  GET /api/school/students
  ```

- **Add a new student:**
  ```http
  POST /api/school/students
  ```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License
This project is licensed under the MIT License. 

## Contact
For any questions or support, please contact allyelvis6569@gmail.com.
# saas-app
# saas-app

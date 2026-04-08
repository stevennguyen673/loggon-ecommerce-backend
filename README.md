🔧 Loggon Backend (Ecommerce Web App)
A robust backend application built with NestJS, utilizing TypeORM for database interactions with MySQL. It provides RESTful APIs to support the Loggon frontend.

**Role:** Served as Scrum Master and Backend Developer, leading Agile ceremonies and building core backend modules.

🚀 Features
NestJS framework for scalable and maintainable server-side applications.

TypeORM for object-relational mapping with MySQL.

RESTful API design for CRUD operations.

Authentication and Authorization mechanisms.

Data Validation using class-validator and class-transformer.

Modular architecture for easy scalability.


📦 Installation
Ensure you have Node.js and MySQL installed.

# Clone the repository
git clone https://github.com/yourusername/loggon-backend.git
cd loggon-backend

# Install dependencies
npm install

# Update/Create .env with your database credentials
Open .env and update it with your local development settings:
Example. 
DB_HOST=localhost
DB_PORT=3306
DB_USERNAME=root
DB_PASSWORD=yourpassword
DB_DATABASE=loggon_dev
PORT=3000

# Start the development server
npm run start:dev


# Technologies Used🛠️ 
NestJS

TypeORM

MySQL

TypeScript

class-validator

class-transformer

## My Contributions
- **Scrum Master:** Led Agile ceremonies, managed sprint backlog, and coordinated team tasks to ensure timely delivery  
- **Backend Development:** Built core functionality using Node.js and NestJS  
- **Users Module:** Implemented registration/login endpoints with JWT authentication and secure password hashing  
- **Cart Module:** Developed RESTful endpoints, enforcing user-specific access, stock validations, and backend calculations for subtotal, tax, and shipping  
- **Database Design:** Contributed to schema and entity relationships, ensuring data integrity between User, Product, and Cart tables  
- **Frontend Collaboration:** Worked with frontend developers to integrate APIs, maintain consistent data flow, and handle invalid requests gracefully

## Notes / Credits
- This backend was developed as part of a team project.  
- Frontend was implemented separately using React and TypeScript: [https://github.com/Bvsbee/loggon-ui]  
- I contributed primarily to backend development and served as Scrum Master.

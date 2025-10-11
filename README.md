# Company Role Management Platform

A robust platform for managing company roles, permissions, and user access efficiently. This repository provides tools and functionalities to help organizations assign, update, and track user roles within their company infrastructure.

## Features

- User authentication and management
- Role-based access control (RBAC)
- Create, update, and delete roles
- Assign and remove users from roles
- Audit logs for role changes
- Admin dashboard for managing roles and permissions

## Technologies Used

- **Frontend:** React
- **Backend:** Express.js (Node.js)
- **Database:** PostgreSQL
- **ORM:** Prisma

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn
- PostgreSQL server

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Omcodes23/Company-Role-Management-Platform.git
    cd Company-Role-Management-Platform
    ```

2. **Install backend dependencies:**
    ```bash
    cd backend
    npm install
    ```

3. **Install frontend dependencies:**
    ```bash
    cd ../frontend
    npm install
    ```

4. **Configure environment variables:**
    - Copy `.env.example` to `.env` in both `backend` and `frontend` directories, and update values as needed.

5. **Setup PostgreSQL database:**
    - Ensure PostgreSQL is running.
    - Create a new database and update connection details in your backend `.env`.

6. **Run Prisma database migrations and generate client:**
    ```bash
    # From the backend directory
    npx prisma migrate dev
    npx prisma generate
    ```

7. **Start the backend server:**
    ```bash
    npm run dev
    ```

8. **Start the frontend app:**
    ```bash
    cd ../frontend
    npm run dev
    ```

9. **Access the platform:**
    - Open your browser and go to `http://localhost:3000` (or the configured port).

## Usage

- Register as a user or login as an admin.
- Use the dashboard to create/manage roles and assign users.
- Review audit logs for recent changes in roles and permissions.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

---

> _Be sure to update all placeholder sections (authentication details, etc.) to match your project's specifics._

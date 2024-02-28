<p align="center">
  <img src="https://blog.soton.ac.uk/beseated/files/2015/04/user2_sequence.png" alt="Alt Text" height="400">
</p>

# Register-Login Backend

This backend serves as the foundation for the Register-Login application, providing a secure and scalable user authentication system. It incorporates RESTful APIs for user management, password and salt encryption, JWT token authentication, role-based access control, and route protection.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [API Endpoints](#api-endpoints)
- [User Authentication](#user-authentication)
  - [Password & Salt](#password--salt)
  - [JWT Token](#jwt-token)
  - [Authentication](#authentication)
  - [Cookie](#cookie)
  - [Role Authentication & Route Protection](#role-authentication--route-protection)
- [Commit Guidelines](#commit-guidelines)


## Features

- User RESTful API
- Secure password and salt encryption
- JWT token authentication
- Role-based access control
- Route protection for enhanced security

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- MongoDB installed and running.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/punchpnp/Register-Login-backend.git
cd Register-Login-backend
```

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the root directory with the following content:

```env
MONGODB_URI=<your_mongodb_uri>
JWT_SECRET=<your_jwt_secret>
```

Replace `<your_mongodb_uri>` and `<your_jwt_secret>` with your MongoDB connection string and a secret key for JWT.

4. Start the server:

```bash
npm run dev
```

The server will run on http://localhost:5000 by default.

## API Endpoints

List and describe your API endpoints here.

## User Authentication

### - Password & Salt

Explain how passwords and salts are handled for enhanced security.

### - JWT Token

Describe how JWT tokens are generated and validated for user authentication.

### - Authentication

Explain the overall authentication process and mechanisms.

### - Cookie

Detail how cookies are used for authentication and session management.

### - Role Authentication & Route Protection

Explain how role-based authentication is implemented and how certain routes are protected based on user roles.

## Commit Guidelines

Please follow the conventional commit message format:

- `feat`: for new features
- `fix`: for bug fixes
- `docs`: for documentation changes
- `style`: for changes that do not affect the meaning of the code (formatting, etc.)
- `refactor`: for code refactoring
- `test`: for adding or modifying tests
- `chore`: for changes that are not user-facing or related to the build system


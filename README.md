# EMS-Back-End

Employee Management System Backend API built with Node.js and Express.

## Features

- RESTful API for employee management
- MongoDB database integration
- JWT authentication (ready to implement)
- CORS enabled
- Environment configuration

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Avinash-kum/EMS-Back-End.git
   cd EMS-Back-End
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Create `.env` file
   ```bash
   cp .env.example .env
   ```

4. Update `.env` with your configuration

## Running the Server

### Development
```bash
npm run dev
```

### Production
```bash
npm start
```

## API Endpoints

### Employees
- `GET /api/employees` - Get all employees
- `GET /api/employees/:id` - Get employee by ID
- `POST /api/employees` - Create new employee
- `PUT /api/employees/:id` - Update employee
- `DELETE /api/employees/:id` - Delete employee

## License

MIT

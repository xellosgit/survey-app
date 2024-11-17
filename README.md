
---

## Survey Application

This project is a full-stack web application built using **Laravel**, **Vue.js**, and **Tailwind CSS**. It allows users to create, manage, and participate in surveys. The application is designed with a modern front-end and robust back-end architecture, making it a great example of a scalable, maintainable full-stack solution.

### Features
- User authentication and authorization
- Create, edit, and delete surveys
- Add questions to surveys with multiple types (text, choice, etc.)
- Real-time survey responses
- Responsive design using Tailwind CSS
- API-driven backend for seamless integration with Vue.js frontend

### Technologies Used
- **Laravel**: Backend framework for handling server-side logic and database management.
- **Vue.js**: Frontend framework for building interactive user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for designing responsive layouts.
- **MySQL**: Relational database for storing survey data.
- **Webpack**: Module bundler for optimizing assets.

### Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/laravel-vue-survey.git
   cd laravel-vue-survey
   ```

2. **Install dependencies**:
   ```bash
   composer install
   npm install
   ```

3. **Copy the environment file**:
   ```bash
   cp .env.example .env
   ```

4. **Generate an application key**:
   ```bash
   php artisan key:generate
   ```

5. **Set up the database**:
   - Update the `.env` file with your database credentials.
   - Run migrations:
     ```bash
     php artisan migrate
     ```

6. **Start the development server**:
   ```bash
   php artisan serve
   npm run dev
   ```

### Usage
- Access the application at `http://localhost:8000`.
- Register a new user, create surveys, and start collecting responses.

### Acknowledgments
This project was built as part of a YouTube tutorial. Check out the [video here](https://youtu.be/WLQDpY7lOLg) for a step-by-step guide.

--- 

Would you like any additional sections or modifications to this description?

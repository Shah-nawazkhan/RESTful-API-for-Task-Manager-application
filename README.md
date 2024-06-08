# Lazim Application

## Introduction
This is a simple RESTful API for a Task Manager application built with Laravel. It allows users to perform CRUD operations on tasks and includes basic authentication using Laravel Sanctum.

## Requirements
- PHP 8.0+
- Composer
- MySQL or any other supported database

## Installation

1. Clone the repository:
   git clone <repository-url>
   cd LazimApplication

2. Install dependencies:

#  composer install
    

3. Run migrations:

#  php artisan migrate

4.   Install and configure Laravel Sanctum:
# composer require laravel/sanctum
# php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
# php artisan migrate

5. Start the development server:

  #  php artisan serve

6. Use Postman to test the API endpoints:

    Register: POST /register
    Login: POST /login
    Get Tasks: GET /api/tasks
    Create Task: POST /api/tasks
    Get Task: GET /api/tasks/{id}
    Update Task: PUT /api/tasks/{id}
    Delete Task: DELETE /api/tasks/{id}


#    API Endpoints
.    GET /api/tasks - Retrieve all tasks
.    POST /api/tasks - Create a new task
.    GET /api/tasks/{id} - Retrieve a single task
.    PUT /api/tasks/{id} - Update a task
.    DELETE /api/tasks/{id} - Delete a task


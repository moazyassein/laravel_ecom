# Simple Blogging System

This is a simple blogging system built with Laravel. It allows users to manage blog posts, including creating, reading, updating, and deleting posts. The application includes authentication functionality and validation for storing and updating posts. It also provides features like pagination, post seeding, and formatted timestamps.

## Features

- **Home Page**: Displays a list of all blog posts with pagination.
- **Post Management**: Create, edit, update, and delete blog posts.
- **Post Details**: View individual blog posts.
- **Authentication**: User login and registration for managing posts (via the Laravel UI package).
- **Validation**: 
    - Title and description are required.
    - The title must be unique and have a minimum length of 3 characters.
    - The description must have a minimum length of 10 characters.
    - Error messages will be displayed if validation fails.
- **Formatted Timestamps**: The created-at timestamp is formatted using the Carbon library.
- **Database Integration**: The posts are stored in a database with migrations for the posts table.
- **Post Seeder**: The application includes a PostSeeder and PostFactory to generate 500 fake blog posts.

## Prerequisites

- PHP >= 7.4
- Composer
- Laravel 8.x or above
- MySQL or any other database


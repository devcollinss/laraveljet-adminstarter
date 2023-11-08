# LaravelJet AdminStarter

LaravelJet AdminStarter is a Laravel-based starter template with multi-authentication for administrators and regular users, built using Laravel Jetstream. It provides a solid foundation for developing web applications with role-based access control (RBAC) and user management.

## Features

- **Multi-Authentication**: Supports two authentication guards - "admin" and "user" - with separate roles and permissions.

- **User Management**: Admins can create, edit, and deactivate user accounts. The template includes a flexible permissions and roles system using Spatie's Laravel Permission package.

- **Laravel Jetstream**: Utilizes Laravel Jetstream for robust authentication features, including registration, login, password reset, and two-factor authentication for both admin and user roles.

- **Profile Management**: Users can update their profiles, change passwords, and configure two-factor authentication settings. Admins can manage user profiles as well.

- **Dashboard**: Each role has its own dashboard with role-specific content and quick links to functionalities.

- **Admin Panel**: Admins can access an admin panel built with Laravel Nova for managing users, roles, and permissions efficiently.

- **Front-End Stack**: The template uses Tailwind CSS and Laravel Mix for a responsive and customizable user interface.

- **Laravel Best Practices**: Follows Laravel best practices for structured code, use of service providers, clean migrations, and maintainable codebase.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/devcollinss/laraveljet-adminstarter.git
   cd laraveljet-adminstarter

2. Install Composer dependencies:

    ```bash
    composer install

3. Create a copy of the .env file:

    ```bash
    cp .env.example .env

4. Configure your database settings in the .env file.

5. Generate the application key: 

    ```bash
    php artisan key:generate

6. Run migrations and seed the database:

    ```bash
    php artisan migrate --seed

7. Install Node.js dependencies and compile assets:

    ```bash
    npm install && npm run dev

8. Start the development server:

    ```bash
    php artisan serve

## Customization
For detailed documentation, customization options, and best practices, please refer to the [full project documentation in the repository's README]().

## Contributors
Collins Ikechukwu [DevCollins](https://github.com/devcollinss)

## License
This project is open-source and available under the MIT License.

# Laravel REST API

This is a sample Laravel REST API project with basic CRUD functionality. It uses the following packages:

- `laravel/framework` version `^9.19`
- `laravel/sanctum` version `^3.0`

## Installation

1. Clone this repository
2. Run `composer install`
3. Create a copy of the `.env.example` file and rename it to `.env`
4. Configure your `.env` file with database credentials and other settings
5. Run `php artisan key:generate`
6. Run `php artisan migrate`
7. (Optional) Run `php artisan db:seed` to seed the database with sample data

## Usage

You can use any API client to send requests to this API. Below are some examples of requests you can make:

- `GET /api/products` - Get all products
- `GET /api/products/{id}` - Get a specific product
- `POST /api/products` - Create a new product
- `PUT /api/products/{id}` - Update an existing product
- `DELETE /api/products/{id}` - Delete a product

## Testing

You can run the tests by running the command `php artisan test` in your terminal.

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

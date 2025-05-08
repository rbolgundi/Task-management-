

## Installation

To install and run the Task Management App locally, follow these steps:

1. Clone the project
2. Go to the project root directory and run `composer install` and `npm install`
3. Create `.env` file and copy content from `.env.example`
4. Run `php artisan key:generate` from terminal
5. Change database information in `.env`
6. Run migrations by executing `php artisan migrate` , Then Run  `php artisan db:seed` if you want use faker database records,
7. Start the project by running `php artisan serve` then `npm run dev`

8. Access the application in your web browser at `http://localhost:8000/admin`, with this credentials

````
test@example.com
password
````







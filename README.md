**Installation**




To install and run the Task Management App locally, follow these steps:

Clone the project

Go to the project root directory and run composer install and npm install

Create .env file and copy content from .env.example

Run php artisan key:generate from terminal

Change database information in .env

Run migrations by executing php artisan migrate , Then Run php artisan db:seed if you want use faker database records,

Start the project by running php artisan serve then npm run dev

Access the application in your web browser at http://localhost:8000/admin, with this credentials

test@example.com
password

## Introduction
application for students exam and manage exams & students.
<hr> 

### Here is a list of the packages installed:
- [laravel passport](https://laravel.com/docs/9.x/passport).

# Getting started
### Installation
<hr> 


- Clone this repository.
git clone https://github.com/almuhder/quiz-albarakah.git
- must be checkout to back branch.
 
git checkout back
- copy this command to terminal for install the composer.
composer install
- copy this command for generate <code>.env</code> file .
cp .env.example .env 
### Don't forget to create a database with the same name in <code>.env</code> file
- run this commands .
 
php artisan migrate:fresh --seed
-the admin's email = admin@gmail.com
-the admin's password = 123456789
- Start the local server.
php artisan serve 

<hr>

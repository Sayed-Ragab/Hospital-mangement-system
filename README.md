Hospital Management System (HMS)

Developed a scalable hospital management system using Laravel and MySQL to streamline operations and manage patient workflows efficiently.

Implemented a secure authentication and authorization system using Role-Based Access Control (RBAC) to manage access for Admin, Doctor, Patient, Radiologist, and Lab Specialist users.

Designed and implemented dynamic role-based dashboards tailored to each user type, enhancing usability and ensuring secure access to sensitive data.

Developed an appointment booking system that allows patients to schedule and manage appointments with specialized doctors, with automated email notifications to improve efficiency and user engagement.

Technologies: PHP, Laravel, MySQL, JavaScript, HTML, CSS,livewire

Project Setup Instructions
1- open cmd or trimal and write 
git clone https://github.com/Sayed-Ragab/Hospital-mangement-system.git

2- copy  .env.example to .env
3- composer install
4- php artisan key:generate.
5- create database name in php myadmin and same name in .env file
6- php artisan migrate --seed
7- php artisan serve

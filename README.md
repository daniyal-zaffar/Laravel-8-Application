# Blog Using Laravel 8
### Let's keep it as simple as possible. Configure anything you want
A full-featured blogging system for personal use. No frontend theme and anything heavy or unnecessary library used.

### Technologies used
1. Laravel
2. Livewire
3. TailwindCSS
 
### There are four several types of users with several permissions
1. Admin/Owner
  * Can manage articles and comments of other users.
  * Can manage categories.
  * Can manage keywords.
  * Can manage other users except Owner.
  
4. Reader
  * Can read and comment on article providing his email address.
  * Can subscribe to be notified for new articles.
  * Can search for articles.
  * Can navigate articles based on categories.

### Installation Process
1. Execute `git clone https://github.com/daniyal-zaffar/laravel-8-application.git on your terminal to download this project.
2. Go to the project root directory and execute `composer install` to install all PHP dependencies of the project
3. Create a file named as .env and copy the content of .env.example to newly created .env file 
4. Then execute `php artisan key:generate` on your terminal/cmd to generate environment key
5. Then create a Database for this project and edit the .env file to authorized this project on your database. 
6. Execute `php artisan migrate:refresh --seed` terminal on your terminal.
7. Now you are ready to go, If you don't want to create any virtual host for this project then execute
  `php artisan serve`
8. Now visit the url shown on your terminal, something like `localhost:8000`. It's running!
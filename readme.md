# This is a real time chat app.
## We are going to use Laravel, Laravel web socket, Laravel Echo.

## Installation Instructions

Clone the repo

- Run `composer install`
- Run `cp .env.example .env`
- Run `php artisan key:generate`
- Set your database configration to .env
- If your machine don't have redis server install it. 
- set brodcast drive to redis
- Run `php artisan migrate --seed`


## Run Application
- run `php artisan serve`
- run `npm install -g laravel-echo-server` if you have not already install
- run `laravel-echo-server start`
- run  `php artisan queue:work`

## Contributation Guideline
* Fork the repo
* Clone the repollly
* Run `git checkout dev`
* Create a new local branch
* Work on your local branch
* Push to remote
* When work is tested, done or ready, push to remote
* Merge to dev

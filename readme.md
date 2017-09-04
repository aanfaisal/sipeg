# Goals :3

Build SKP DP3 App with Laravel 5.5

## Installation
1. Install Composer using detailed installation instructions [here](https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx)
2. Install Node.js using detailed installation instructions [here](https://nodejs.org/en/download/package-manager/)
3. Clone repository
```
$ git clone https://github.com/anisku11/sipeg.git
```
4. Change into the working directory
```
$ cd sipeg
```
5. Install dependencies
```
$ composer install --prefer-dist
$ npm install
```
6. Edit `.env.example` according to your environment and save as `.env`
```
7. An application key can be generated with the command
```
$ php artisan key:generate
```
8. Execute following commands
```
$ bower install
$ npm run dev
```
9. Run these commands to create the tables within the defined database and populate seed data
```
$ php artisan migrate --seed
```
If you get an error like a `PDOException` try editing your `.env` file and change `DB_HOST=localhost` to `DB_HOST=127.0.0.1`.

## Run

To start the PHP built-in server
```
$ php -S localhost:8080 -t public/
```

Now you can browse the site [http://localhost:8080]

## How to contribute

Fork the repository, read the [CONTRIBUTE](CONTRIBUTE.md) file and make some changes.
Once you're done with your changes send a pull request and check [CI validation status](https://travis-ci.org/Labs64/laravel-boilerplate).
Thanks!


## License

This boilerplate is open-sourced software licensed under the [MIT license](LICENSE).
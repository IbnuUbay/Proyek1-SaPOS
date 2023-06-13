# Proyek1-SaPOS
## Run Locally

Clone the project

```bash
  git clone https://github.com/IbnuUbay/Proyek1-SaPOS
```

Go to the project directory

```bash
  cd Proyek1-SaPOS
```

-   Copy .env.example file to .env and edit database credentials there
    cp .en.example .env

```bash
    composer install
    or
    composer update
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

#### Login
-   email = admin@gmail.com
-   password = 123

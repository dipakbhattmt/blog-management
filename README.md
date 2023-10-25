#### Setup Project
```bash
# clone the repo
git clone https://github.com/dipakbhattmt/blog-management.git

# install composer dependency
composer install

# create an environment file
cp .env.example .env

# set the Application key
php artisan key:generate


# setup the database credentials and migrate database with seeders
php artisan migrate --seed

```

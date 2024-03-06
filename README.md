# Filament bug reproduction

## Usage

- `git clone git@github.com:mokhosh/filament-bug-reproduction.git && cd filament-bug-reproduction`
- `composer install`
- `php artisan migrate --seed`
- `php artisan key:generate`
- Open /admin in your browser and login
- Go to Users resource
- See that table has not errors
- Click on View on one of the records
- See the error!



## Installation guide for fresh project and this will be new one after follow this instruction

just follow those guide
- change the .env.example to .env file first

- git clone https://github.com/alimranedx/laravel13pcktst.git
- composer install
- npm install
- php artisan key:generate
- php artisan migrate:fresh --seed
  
## finaly run project by
- composer run dev


## test package (laravel runtime feature) guide
- keep those in composer.json file
```json
"repositories": [
        {
            "type": "path",
            "url": "../laravel-runtime-feature",
            "options": {
                "symlink": true
            }
        }
    ]

- then run this command
composer require al_imran/laravel-runtime-feature:@dev

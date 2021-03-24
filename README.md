# DOTENV MODULE

## Installation

```

composer require njcozw/dotenv:dev-master

```

## Usage

```

// .env CODE

APP_ENV=dev
DATABASE_DNS=mysql:host=localhost;dbname=njcozw;
DATABASE_USER=njcozw
DATABASE_PASSWORD=password

// PHP CODE

<?php
use App\Njcozw;

(new DotEnv(__DIR__ . '/.env'))->fetch();

echo getenv('APP_ENV');
// dev
echo getenv('DATABASE_DNS')
```

# Product Registration System - Backend

## System Requirements
- PHP 8.0+
- Composer 2.0+
- MySQL 5.7+ or MariaDB 10.3+
- Laravel 10.x

## Installation

#### 1. Clone the repository:
```bash
git clone [backend-repository-url]
cd product-registration-system
```
#### 2. Install dependencies:
```bash
composer install
```

#### 3. Configure environment:
```bash
cp .env.example .env
```

#### 4. Generate application key:
```bash
php artisan key:generate
```

#### 6. Configure database in .env:
```js
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=product_registration
DB_USERNAME=root
DB_PASSWORD=
```

#### 7. Start development server:

```bash
php artisan serve
```

### API Endpoints
<br>

#### Products
GET ``/api/products`` - List products (paginated)

POST ``/api/products`` - Create new product

PUT ``/api/products/{id}`` - Update product

DELETE ``/api/products/{id}`` - Delete product

#### Validation Rules
```yml
Name: required, string, max 255 chars
Description: nullable, string
Price: required, numeric, min 0
Quantity: required, integer, min 0
```
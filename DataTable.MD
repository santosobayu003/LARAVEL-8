REFERENSI : https://www.positronx.io/laravel-datatables-example

DOKUMENTASI : https://yajrabox.com/docs/laravel-datatables

composer require yajra/laravel-datatables-oracle

![image](https://user-images.githubusercontent.com/59097891/232092730-255ad08d-5c0e-4b1f-9050-8ff428a5bf5a.png)

config/app.php 

```php

'providers' => [
	Yajra\DataTables\DataTablesServiceProvider::class,
]
'aliases' => [
	'DataTables' => Yajra\DataTables\Facades\DataTables::class,
]

```

- CALL THE VENDOR FILE : php artisan vendor:publish --provider="Yajra\DataTables\DataTablesServiceProvider"

![image](https://user-images.githubusercontent.com/59097891/232093843-db591205-b8fe-4789-b8a6-3f4837fcd66c.png)

php artisan make:model Employee

![image](https://user-images.githubusercontent.com/59097891/232097891-deafa5ce-6591-4f8d-a09f-012814dedae7.png)

php artisan make:controller Employee_controller

![image](https://user-images.githubusercontent.com/59097891/232098015-72b83d2e-5a37-423f-9e3e-bb8c7c4707c3.png)


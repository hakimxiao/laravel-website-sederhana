### **TERMINAL CODE CLI**

- INSTALL PROJECT              : composer create-project laravel/laravel="10.*"
- MEMBUAT MODEL & MIGRATIONS   : php artisan make:model section -m
- MENJALANKAN MIGRASI          : php artisan migrate


#### **SETUP DATABASE & FILLAMENT**  : 
- composer require filament/filament     :   (menginstall filament docs: https://filamentphp.com/docs/4.x/introduction/)
- php artisan migrate                    :   (Menjalankan semua table yang disediakan oleh laravel di migration)
- php artisan make:filament-user         :   (filament membutuhkan user pada tabel user, dengan menjalakan ini kita membuat user)

#### **INSTALASI DOCTRINE DBAL - SEBUAH HAL YANG DI PERLUKAN UNTUK MEMBUAT RESOURCE FILLAMENT**  : composer require doctrine/dbal --dev

#### **FILLAMENT USAGE**  https://filamentphp.com/docs  
##### 1. Membuat Resource (Sumberdaya sumberdaya untuk management siap pakai seperti table form dll) 
- 
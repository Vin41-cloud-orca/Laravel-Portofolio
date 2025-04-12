## MY-PFOLIO
<p><b>
MY-PFOLIO adalah aplikasi website portfolio dengan konten dinamis.
</b></p>

## Setup
- buka direktori project di terminal anda.
- ketikan command : cp .env.example .env (copy paste file .env.example)
- buat database 

Lalu ketik command dibawah ini
- composer install
- php artisan optimize:clear 
- php artisan key:generate (generate app key)
- php artisan migrate (migrasi database)
- php artisan db:seed --class=UserClass (mengisi data table users)

## Login
Email : admin@gmail.com
Password : password

## Fitur
- Home (Banner Hero,About,Portfolio) 
- Login
- Halaman Dashboard
- Halaman Profile
- Ubah Profile
- Manage User (CRUD)
- Manage Front Header Layout (CRUD)
- Manage Front About Layout (CRUD)
- Manage Skill Layout (CRUD)
- Manage Portfolio (CRUD)
- Manage Footer Layout (CRUD)

## Author
- Vincent Gozaly Rasyid

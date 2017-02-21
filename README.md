# personal-bank
Web-based application to mantain control on personal expenses

Configuración

Utilizar el archivo .env.example como guía para escribir el archivo .env.
Instalar dependencias con composer install

Configurar de manera adecuada los permisos de escritura/lectura de las carpetas:

app/storage/
app/storage/logs
app/storage/framework/cache
app/storage/framework/sessions
app/storage/framework/views
bootstrap/cache/

Base de datos

Crear la base de datos BANK en el servidor
Configurar los parámetros de conexión a la base de datos en el archivo .env.
Realizar la migración de las tablas de la base de datos, por ejemplo:
  php artisan migrate
Sembrar los datos predeterminados en la base de datos, por ejemplo:
  php artisan db:seed

# personal-bank
Web-based application to mantain control on personal expenses


<h2><b>Configuración </b></h2>

<ul>
<li>Utilizar el archivo <i>.env.example</i> como guía para escribir el archivo<i> .env</i>.</li>
<li>Instalar dependencias con composer install</li>
<li>Crear proyecto <i>composer create-project laravel/laravel personal-bank</i> y ligar a github</li>

<h3><i>Configurar de manera adecuada los permisos de escritura/lectura de las carpetas:</i></h3>
<ul>
<li>app/storage/</li>
<li>app/storage/logs</li>
<li>app/storage/framework/cache</li>
<li>app/storage/framework/sessions</li>
<li>app/storage/framework/views</li>
<li>bootstrap/cache/</li>
</ul>
</ul>
<h2><b>Base de datos</b></h2>
<ul>
<li>Crear la base de datos <i><b>BANK</b></i> en el servidor</li>
<li>Configurar los parámetros de conexión a la base de datos en el archivo .env.</li>
<li>Realizar la migración de las tablas de la base de datos, por ejemplo:</li>
  <ul>
  <li><i>php artisan migrate</i></li>
   </ul>
<li>Sembrar los datos predeterminados en la base de datos, por ejemplo:</li>
  <ul>
  <li><i>php artisan db:seed</i></li>
  </ul>
  </ul>

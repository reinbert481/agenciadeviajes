LOGIN DE LA APP (email & passord)
username: admin@admin.com
password: 12345678
--------------------------------------------------
- Antes de correr la App tiene que estar corriendo XAMPP.
- En el navegador abrir el localhost y aparecerá la pagina de XAMPP, arriba
  a la derecha aparece un link a phpMyAdmin, acceder ahí y crear una nueba
  base de datos con el nombre de la aplicación "agenciadeviajes"
- Desde una ventana de Terminal en Visual Studio Code realizar la migración
  a la base de datos de las tablas de la App con:
	php artisan migrate
- luego de hacer la migración desde la misma Terminal correr la App con:
	php artisan serve

Buena suerte!

# registro_symfony

Registro de usuari con verificación vía Email.

Para poder  usar este proyecto tienes que configuar el correo electro en el archivo raíz .env

en MAILER_DNS

 MAILER_DSN=gmail://tucorreo_electronico@gmail.com:tu_contraseña@default


y más arriba configurar la base de datos  en este caso trabajé con mysql 

DATABASE_URL="mysql://name_user@password127.0.0.1:3306/name_db?"

una vez hecho esto inicia el proyecto ya sea  por algún servidor que tengas conectado en tu pc como xampp  o directamente con symfony escribe en la consola 
php server:start , te abririrá  la página de symfony de bienvenida, coloca  /register  al url que  te figura --> http://localhost:8000/register.

Una vez realizado estos pasos ya se encuentra en funcionamiento el login, y la verifiación por mail.


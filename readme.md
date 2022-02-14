- Crear index.html y montarlo en carpeta /usr/share/nginx/html/
- Navegar http://localhost/index.html
- Crear index.html y montarlo en carpeta /usr/share/nginx/carloshtml/
- Crear archivo virtual host prueba.carlos.com "carlos.conf" y montar el /etc/npinx/conf.d/carlos.conf
- Modificar entrada de hosts prueba.carlos.com -> 127.0.0.1
- navegar http://prueba.carlos.com/
- Agregar entrada idp.carlos.com al archivo host
- Crear virtual host idp.conf con nombre idp.carlos.com que haga proxy a -> http://keycloak:8080/
- navegar http://idp.carlos.com/



- Crear certificado self signed y configurar
- Navegar https://prueba.carlos.com/
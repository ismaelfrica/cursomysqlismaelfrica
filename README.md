# cursomysqlismaelfrica

#Descargar Primero Windows

https://www.computerbase.de/downloads/systemtools/all-in-one-runtimes/

#Dercargar Servidores Windows

1 - http://www.vswamp.com/
2 - https://www.apachefriends.org/es/download.html
3 - https://www.wampserver.com/en/

#Descargar en Linux || MACoS

APACHE o NGINX
MYSQL o Mariadb


#Arregkar error en WAMP de Usuario creado caching_sha2_password' cannot be

ir a la siguiente ruta 
C:\wamp64\bin\mysql\mysql8.0.31
y buscar el archivo my.ini
y pegar el siguiente comando al final y luego reiniciar el servicio de wampserver
default_authentication_plugin=mysql_native_password

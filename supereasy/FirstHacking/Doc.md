Documentación de FirstHacking 

Despregramos la maquina  

![Texto alternativo](https://github.com/Bellze6/Dockerlabs/blob/main/supereasy/FirstHacking/screenshots/Despliegue.png)

Una vez que tengamos la ip del equipo, realizamos el escaneo de los puertos abiertos con nmap.

![Texto alternativo](https://github.com/Bellze6/Dockerlabs/blob/main/supereasy/FirstHacking/screenshots/descubrirpuertos.png)

Con el siguiente comando de nmap buscamos más información sobre los puertos abiertos, encontrando que la versión de vsftpd 2.3.4
![Texto alternativo](https://github.com/Bellze6/Dockerlabs/blob/main/supereasy/FirstHacking/screenshots/tenermasinfdelospuertos.png)

Con Searchsploit buscamos si existe alguna vulnerabilidad con vsftpd y encontramos un script que nos puede ayudar a realizar la explotación, lo descargamos. 
![Texto alternativo](https://github.com/Bellze6/Dockerlabs/blob/main/supereasy/FirstHacking/screenshots/buscarvul.png)
![Texto alternativo](https://github.com/Bellze6/Dockerlabs/blob/main/supereasy/FirstHacking/screenshots/descargarscrip.png)

Revisamos cómo funciona el script para poder ejecutarlo.  
![Texto alternativo](https://github.com/Bellze6/Dockerlabs/blob/main/supereasy/FirstHacking/screenshots/ejecutarscrip.png)

Ejecutamos el script y validamos el acceso, se valida en que ruta y que usuario estamos y nos muestra que con el script ya estamos como root. 
![Texto alternativo](https://github.com/Bellze6/Dockerlabs/blob/main/supereasy/FirstHacking/screenshots/acceso.png)

# E3_AAY1108_Sebastian_Gonzalez


# ITEM 1. Creación Servidor en la nube Linux con SSH y HTTP. 

IP PUBLICA: 18.205.115.195

DNS: ec2-18-205-115-195.compute-1.amazonaws.com

LLAVE DE CONEXION

<img width="361" height="351" alt="image" src="https://github.com/user-attachments/assets/d6842eee-4a53-4490-8729-5605d15dd8a3" />


Se uso t3.medium porque encaja con los recursos solicitados (2Vcpu y 4GB de RAM) y como SO se utilizo RHEL 10.2.0.

<img width="1333" height="644" alt="image" src="https://github.com/user-attachments/assets/1087f148-8a24-4177-92ae-f115a0ef0b6c" />


Se aplicaron las dos reglas que permiten el acceso de SSH y HTTP.

<img width="1328" height="648" alt="image" src="https://github.com/user-attachments/assets/2ba54dfc-e72d-43a1-bac7-4b6624f13ae0" />


Conexion por PUTTY usando la llave y pagina web con nombre y logo DUOC.

Se uso el comando "sudo curl -L https://cfw.cl/wp-content/uploads/2025/11/duoc-logo.png -o /var/www/html/logo-duoc.png" para descargar la imagen a la maquina y luego se agrego en el html.


<img width="1211" height="572" alt="image" src="https://github.com/user-attachments/assets/5a147ec6-8375-471e-909f-7ee1ddfbd55b" />


# Ítem 2: Creación en la nube de Servidor Windows Server 2019 con acceso remoto (RDP) Rol Web Server (HTTP   y FTP). 

IP PUBLICA: 54.162.208.107

DNS: ec2-54-162-208-107.compute-1.amazonaws.com

LLAVE DE CONEXION

<img width="360" height="356" alt="image" src="https://github.com/user-attachments/assets/f88b7566-274a-475f-a71e-136f011e54c5" />

Instancia Creada: Se uso Windows Server 2019 Datacenter porque no está la version Standard. estas comparten casi las mismas caracteristicas asi que no deberia ser un problema.

<img width="1358" height="733" alt="image" src="https://github.com/user-attachments/assets/39c2f1a1-b0b1-46e6-a68b-d208dfbf5f61" />

Grupos de Seguridad: Se agregaron dos reglas TCP personalizadas adicionales porque sin estas no se puede lograr la conexion por FTP.

<img width="1348" height="725" alt="image" src="https://github.com/user-attachments/assets/873e709e-5f5c-48ff-8782-c8526c018215" />

CONEXION

Contraseña Descifrada: 7TUxoL*ZNYIj7uFA*%RmkXJrj$yzt68w

<img width="1600" height="898" alt="image" src="https://github.com/user-attachments/assets/f9ac5e4a-e903-4da0-b022-f0d2dfc1aa26" />

Instalacion Rol Web Server IIS/HTTP+FTP

<img width="1600" height="490" alt="image" src="https://github.com/user-attachments/assets/55835407-b4c7-4513-8a6d-6d592dbe015b" />

Pagina Web (Se volvio a usar curl al igual que en linux para descargar la imagen y se dejo en la misma carpeta donde esta el html)

<img width="1045" height="658" alt="image" src="https://github.com/user-attachments/assets/8913ab3a-9679-4eb3-b106-ade5ef53b229" />

FTP (Navegadores actuales como Edge, el que yo uso, ya no permiten ingresar a FTP asi que se uso el explorador de archivos)

<img width="1347" height="431" alt="image" src="https://github.com/user-attachments/assets/7eece9cb-a7b3-436c-9429-ba6e2b7111c1" />



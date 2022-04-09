# Manual de instalacion de Docker

[![descarga.png](https://i.postimg.cc/TwBRkVkb/descarga.png)](https://postimg.cc/Fdg5zLXF)

## ¿QUE ES?
### Es un proyecto de código abierto que automatiza el despliegue de aplicaciones dentro de contenedores de software, proporcionando una capa adicional de abstracción y automatización de virtualización de aplicaciones en múltiples sistemas operativos.

# GUIA DE INSTALACION
## 1. DESCARGAR
### Vamos a la pagina oficial de docker y descargamos el instalador en este caso de windows.

[![imagen-2022-04-07-131112.png](https://i.postimg.cc/25zF6v7n/imagen-2022-04-07-131112.png)](https://postimg.cc/LJbZQJ7s)

[![imagen-2022-04-07-131205.png](https://i.postimg.cc/KjFgqhpB/imagen-2022-04-07-131205.png)](https://postimg.cc/xJxC8h21)

## 2. INSTALADOR
### Ejecutamos el instalador y marcamos las 2 casillas siguientes:

[![imagen-2022-04-07-131402.png](https://i.postimg.cc/bJqz4Y8y/imagen-2022-04-07-131402.png)](https://postimg.cc/p91bFHp4)

### Una vez dado al boton *ok* se instalaran los siguientes archivos

[![Captura-de-pantalla-2022-04-07-131429.png](https://i.postimg.cc/0yfxDRDh/Captura-de-pantalla-2022-04-07-131429.png)](https://postimg.cc/18fL1dWK)

### Una instaladas ya habra acabado la instalacion de docker

[![Captura-de-pantalla-2022-04-07-131630.png](https://i.postimg.cc/8chxGMbx/Captura-de-pantalla-2022-04-07-131630.png)](https://postimg.cc/CnxcHZX4)

## 3. ABRIMOS LA APLICACION
### Una vez hemos abierto la aplicacion aceptamos los terminos

[![Captura-de-pantalla-2022-04-07-131822.png](https://i.postimg.cc/QMQ7pM0h/Captura-de-pantalla-2022-04-07-131822.png)](https://postimg.cc/GBp9RdW5)

### Nos dira que instalemos WSL osea que le damos al siguiente link llamado _https://aka.ms/wsl2kernel_

[![imagen-2022-04-07-132215.png](https://i.postimg.cc/FHgFpJ5W/imagen-2022-04-07-132215.png)](https://postimg.cc/zyv1XvfK)

## 4. INSTALAMOS WSL
### 1. Abrimos PowerShell como administrador (menú Inicio > PowerShell > haga clic con el botón derecho en > Ejecutar como administrador) y escribimos el siguiente comando *dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart*:

[![imagen-2022-04-07-133130.png](https://i.postimg.cc/NjcBK8CJ/imagen-2022-04-07-133130.png)](https://postimg.cc/CzmWt8gk)

### 2. Para comprobar la versión y el número de compilación, pulsamos *Windows + R*, escribimos *winver* y le damos a *Aceptar*.

[![imagen-2022-04-07-133406.png](https://i.postimg.cc/d0gW064D/imagen-2022-04-07-133406.png)](https://postimg.cc/5Hq57BcM)

### 3. Abrimos PowerShell como administrador y ejecutamos:

 [![imagen-2022-04-07-133605.png](https://i.postimg.cc/28P32Bch/imagen-2022-04-07-133605.png)](https://postimg.cc/1fr9z4Z3)

 
### 4. Descargamos el paquete de actualización del kernel de Linux en WSL 2 y lo instalamos
### Ejecutamos el instalador y le damos a next y se nos instalara

[![imagen-2022-04-07-133959.png](https://i.postimg.cc/tR8Vmf7s/imagen-2022-04-07-133959.png)](https://postimg.cc/K4rz10Pb)

### 5. Definición de WSL 2 como versión predeterminada
### Abrimos PowerShell y ejecutamos este comando *wsl --set-default-version 2* para establecer WSL 2 como versión predeterminada al instalar una nueva distribución de Linux:

[![imagen-2022-04-07-134345.png](https://i.postimg.cc/vBq5BZQh/imagen-2022-04-07-134345.png)](https://postimg.cc/BLFj7sPP)

### Paso 6: Instalación de la distribución de Linux
### Abrimos la Microsoft Store y seleccionamos la ditribucion que queremos y la descargamos en mi caso sera Ubuntu

[![imagen-2022-04-09-195753213.png](https://i.postimg.cc/mDHfqsCd/imagen-2022-04-09-195753213.png)](https://postimg.cc/2brKbgHv)

### La primera vez que inicies una distribución de Linux recién instalada, se abrirá una ventana de la consola y se te pedirá que esperes un minuto o dos para que los archivos se descompriman y se almacenen en tu equipo, una vez acabdo este tiempo, tendrás que crear una cuenta de usuario y una contraseña para la nueva distribución de Linux.

[![imagen-2022-04-09-201116089.png](https://i.postimg.cc/CxTNHVxh/imagen-2022-04-09-201116089.png)](https://postimg.cc/BXpH4kFk)

## 5. COMPROBACION DE LA INSTALACION

[![imagen-2022-04-09-201512865.png](https://i.postimg.cc/3wb9G0y6/imagen-2022-04-09-201512865.png)](https://postimg.cc/rdxSXmNC)

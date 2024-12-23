# Instalacion de Node-JS
## Verificar si Node.js está instalado

Abre una terminal o consola (CMD en Windows, Terminal en Mac/Linux).

Ejecuta el siguiente comando:

Copiar código
``` bash
node -v
```
![](https://github.com/GabrielAzabache/Documentacion-Tecnica-grupo-3/blob/main/imagenes/image.png)

Si devuelve un número de versión como v18.17.0, Node.js ya está instalado.

Si no aparece, necesitas instalarlo siguiendo los pasos a continuación.

Descargar e instalar Node.js

Ve al sitio oficial de Node.js: https://nodejs.org.

Descarga la versión LTS (Long Term Support).

# Instala Node.js según tu sistema operativo:

![](https://github.com/DiegoX945/DOC-Tecnica/blob/main/Imagenes/imagen%20(9).png)

## Windows:

Ejecuta el archivo .msi descargado.

Acepta los términos de licencia.

Asegúrate de seleccionar la opción "Agregar Node.js al PATH".

Finaliza la instalación.

## MacOS:
Abre el archivo .pkg descargado.

Sigue las instrucciones del instalador.

Finaliza la instalación.

## Linux:

Abre la terminal.

Ejecuta:
``` bash
sudo apt update

sudo apt install -y nodejs npm
```
O instala con nvm para versiones específicas:
``` bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash
source ~/.bashrc

nvm install --lts
```
## Verificar instalación

Comprueba la instalación de Node.js:
Copiar código
``` bash
node -v
```
Comprueba la instalación de npm:
Copiar código
``` bash
npm -v
```

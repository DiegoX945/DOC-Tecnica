# Instalar TypeScript

## Asegúrate de tener Node.js instalado.

### En la terminal, instala TypeScript de forma global:

Copiar código
  ``` bash
npm install -g typescript
  ```
Verifica la instalación:

Copiar código
  ``` bash
  tsc -v
  ```
Debería aparecer una versión como Version 5.7.2.

![](https://github.com/DiegoX945/DOC-Tecnica/blob/main/Imagenes/ins-type.png.jpg)

Configurar TypeScript
### Navega a tu proyecto y ejecuta:

Copiar código
  ``` bash
  tsc --init
  ```

![](https://github.com/DiegoX945/DOC-Tecnica/blob/main/Imagenes/jason.jpg)

Esto generará un archivo de configuración llamado tsconfig.json.

![](https://github.com/DiegoX945/DOC-Tecnica/blob/main/Imagenes/tsconfig.jpg)

### Ejemplo de configuración (tsconfig.json):

json
Copiar código
  ``` bash
  {
  "compilerOptions": {
    "target": "es6",
    "module": "commonjs",
    "strict": true,
    "outDir": "./dist"
  },
  "include": ["src/**/*.ts"],
  "exclude": ["node_modules"]
  }
  ```
Compilar archivos TypeScript

### Crea una carpeta src y dentro un archivo index.ts con el siguiente contenido:

typescript

Copiar código
  ``` bash
  const saludo: string = "¡Hola, TypeScript!";
  console.log(saludo);
  Compila el archivo:
  ```
Copiar código
  ``` bash
  tsc
  ```
Esto generará un archivo JavaScript en la carpeta dist.

Ejecuta el archivo compilado:

Copiar código
  ``` bash
  node dist/index.js
 ```

# appejemplo
Bienvenidos a esta app de ejemplo, hecha en NodeJS y Express.
De momento, te presento cómo instalar Express en tu proyecto Node.

1. Primero, asegúrate de tener Node instalado. Puedes hallar la última versión en el [sitio oficial de Node.js](https://nodejs.org/en)
2. Ahora, con Node instalado, puedes iniciar un proyecto nuevo. Crea una carpeta vacía para tu proyecto nuevo. Esa carpeta la puedes crear en el escritorio, en la carpeta de Documentos, o donde se te antoje. Lo puedes hacer de varias formas, y acá te enseñaré 2 formas:
	- Crea una carpeta vacía donde se te antoje con el explorador de archivos
	- o puedes abrir una línea de comandos y crear la carpeta desde allí. En mi caso (Linux), abrí la línea de comandos en la carpeta Documentos, y escribí `mkdir appejemplo`
3. Desde la línea de comandos, accede a la carpeta de tu nuevo proyecto (en este caso, appejemplo), e inicia un nuevo proyecto con el comando `npm init`
4. Responde a las instrucciones que te pedirá el comando init. Puedes ver más detalles [aquí](https://docs.npmjs.com/creating-a-package-json-file)
5. Una vez terminado, se creará un archivo *package.json* en el directorio de tu proyecto
6. Finalmente, usa el comando `npm install express`
7. Listo! Ya puedes empezar a armar tu proyecto con Express!

## Observaciones

En la raíz del directorio en esta rama podrás hallar el archivo app.js, que es el archivo índice de la aplicación *appejemplo*. Eso se ve en la propiedad *main* del archivo *package.json*.

También verás en el archivo *package.json* que la propiedad *scripts* contiene una clave *"start"* con valor  *"node app.js"*. Esto significa que podemos usar `npm start` para correr la app que estamos construyendo.

# Bases de node
La sección se enfoca en los siguientes temas

* Requerir información de otros archivos
* Requerir paquetes
* Importar archivos personalizados
* NPM (install - uninstall)
* Package.json
* Yargs
* Recibir parámetros por línea de comando
* Colores para la consola

### Cosas que destacar
 * Paquete fs
 * fs.writeFile
 * console.log(module) -> se crea de forma automática
 * console.log(process) -> variable de entorno, se crea de forma automática
 * console.log(process.argv); --> argumentos, por defecto hay 2, ubicación del node y ubicación del fichero que se está ejecutando
 * Npm init --> comando que te ayuda a guiarte a crear el archivo package.json
 * package.json --> 
 * instalación de paquetes --> npm i yargs --save  (el --save indica que es una dependencia necesaria para que la aplicación funcione)
 * si aparece el + (más) es que se instaló correctamente
 * package-lock.json -> es un archivo que registra todos los paquetes que salen como dependencias del package.json, se hace automático por el npm, no se modifica por nosotros
 * Carpeta node_modules -> son plugins y paquetes necesarios para que las dependencias que tenemos definidas en el package.json puedan funcionar correctamente, no se envía al repositorio porque las librerías pueden varias dependiendo del sistem operativo
 * npm install -> reconstruir el proyecto
 * npm install --save-dev nodemon --> (--save-dev) es de desarrollo, no vamos a ocupar privilegios de administrado o super usuario porque está corriendo localmente en este proyecto
 * desintalar paquete



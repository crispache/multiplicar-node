# Aplicación de comandos en Node

## Descripción

Esta es una aplicación para generar archivos de tablas de multiplicar mediante el uso de comandos

## Temas
Para la realización de este ejercicio se trataron los siguientes apartados:

* Requerir información de otros archivos
* Requerir paquetes
* Importar archivos personalizados
* NPM (install - uninstall)
* Package.json
* Yargs
* Recibir parámetros por línea de comando
* Colores para la consola


## Instalación

Ejecutar este comando

```
npm install
```

## Ejemplos de uso

Listar tabla de multiplicar del 2 con límite de 5

```
node app listar -b 2 -l 5
```

Crear archivo de la tabla de multiplicar del 3 con límite de 10

```
node app listar -b 2 -l 10
```
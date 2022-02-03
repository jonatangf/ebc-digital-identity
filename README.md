# UNIR Curso Experto Desarrollo Aplicaciones Blockchain

## Práctica de Identidad Digital

En esta práctica se usará un modelo de Identidad basado en uPort Connect, que se apoya en el ERC-1056, para practicar y afianzar los conceptos de Identidad Digital en Blockchain.

## Actividad

El alumno debe modificar las funciones indicadas en las llamadas del fichero index.html para hacer las correspondientes llamadas a las funciones públicas de los Smart Contracts factilitados por uPort Connect.

El resultado de las llamadas se puede ver a través del navegador.

## Requerimientos previos

- Tener instalada la Dapp "uPort" en el móvil para poder crear una identidad y gestionar las credenciales.
  - Se puede encontrar en <https://play.google.com/store/apps/details?id=com.uportMobile>
- Node.js
- npm
- Paquetes npm que se agregarán durante la instalación:
  - ("express" para proporcionar un servidor web;
  - "ngrok" para proporcionar un tunel seguro para ejecutar la Dapp; y
  - "path" para gestionar las direcciones de acceso al sistema de ficheros)
- Un editor de texto para modificar el index.html (Visual Studio Code, notepad, etc...)

## Cómo empezar

En un directorio nuevo, ejecutar

- $> git clone ESTE-REPOSITORIO
- $> npm init
- $> npm install --save express ngrok path

Para arrancar la página web, ejecutar

- $> node server.js

Se mostrará un mensaje si la DApp se ha arrancado correctamente.

Tambíen se mostrará una URL para poder lanzar desde el navegador.

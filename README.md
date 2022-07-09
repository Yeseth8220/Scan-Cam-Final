# SCAN CAM

_Este proyecto tiene como función prestar un servicio de una gestión de ingreso mediante reconocimiento facial de personas a las intalaciones SENA CBA(Centro de Biotegnologia Agropecuario), como funcionamiento mediante fotos se entrena la IA de Microsoft zure para tener registrado el rostro en la base de datos y este se utilizara previamente para registrar una entrada y una salida de las intalaciones, tambien contiene un sitema de registro y logueo con diferentes roles._

## Comenzando 🚀

Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.



### Pre-requisitos 📋

Que cosas necesitas para instalar el software



* [Nodejs](https://nodejs.org/es/)

* [AngularCLI](https://cli.angular.io/)

* [ionic framework](https://ionicframework.com/)

* [Mongo db](https://www.mongodb.com/try/download/community)




### como ejecutarlo 🔧

Se dirige a la ruta del proyecto

Borra la ruta y escribe cmd 

En el cmd ejecuta el siguiente comando ionic serve


## Construido con 🛠️

para el desarrollo de esta aplicación hibrida se utilizaron las siguientes herraminetas

* [Nodejs](https://nodejs.org/es/)

* [AngularCLI](https://cli.angular.io/)

* [ionic framework](https://ionicframework.com/)

se utlizaron las siguientes bases de datos

* Mongo DB

## Lenguajes de programación utilizados 🛠️
* HTML
* Typescript
* scss
* javascript

## Autores ✒️

* Javier Rey* - Backend 
* Ivan Daniel - Backend 
* Camila Pardo* - Frontend 
* Yeseth Reyes - Frontend

ScanCam_Back
El proyecto es un Sistema de información para el control de Ingreso y Salida mediante reconocimiento Facial de los usuarios de la institución SENA (CBA) con simulación de talanquera mediante Arduino

Inicializar 🤯:
Al clonar o descargar el proyecto:

npm install o npm i
Para iniciar el proyecto de Node:

npm start o npm run dev
Pre-requisitos 📋
_Tener un Arduino UNO contectado a uno de los puertos seriales del computador, con el protocolo Firmata. Para conocer más información ingresar a la Librería JohnnyFive _ Tener instalado Node.js, npm, un editor de código, tener una cuenta en mongo Atlas, tener una cuenta vigente en Azure, tener una cuenta en cloudinary, tener un email de google con OAuth para el envio de mails

 * http://johnny-five.io/
 * https://nodejs.org/
 * https://www.npmjs.com/
 * https://azure.microsoft.com/
 * https://cloudinary.com/
 * https://developers.google.com/oauthplayground/
Construido con 🛠️
El proyecto fue desarrollado con las siguientes herramientas

Node- Node y Express
Microsoft Azure - IA de Reconocimiento Facial
Mongo DB - Base de Datos no relacional
Johnny-five - Librearia para controladores Arduino, en este caso Arduino UNO
Estructura de carpetas 📂:
Una estructura de carpetas simple y entendible para un entorno backend en una API REST

    |_Archivos principales
    |__Controllers
        |__Archivos de controladores
    |__Config
        |__Archivo de configuracion DB
    |__Utils
        |__Archivos para ayudas (helper)
    |__Models
        |__Archivos de estructura de la db en Mongo
    |__Middleware
        |__Archivos para diferrentes validadores (middleware)
    |__Routes
        |__Archivos de las diferentes rutas para el control de los endpoints
    |__Validators
        |__Archivos para el control de posteo de datos en Mongo
Configuracion de rutas 📡:
Todas las rutas estan definidas segun el schema a utilizar despues del |/api/|.

URL desarrollo: http://localhost:3001/api/

URL produccion: https://apiscancam01.herokuapp.com/api/

Documentacion de los servicios endpoint de la API REST: https://documenter.getpostman.com/view/20115348/UVyn3JrP

Recomendaciones 👀:
Leer la documentacion interna de cada archivo para entender el proceso de la API
Revisar siempre las respuestas del servidor
Revisar las dependencias del package.json
Licencia 📄
Este proyecto está bajo la Licencia Copyright.

Expresiones de Gratitud 🎁
Agradecimientos al equipo de desarrollo de la App, instructores y compañeros del SENA - ADSI 2252471 📢
Prontamente una versión 2.0 de la mano de mi equipo de trabajo, con animos de salir a tomar unas 🍺 o un café ☕ para celebrar la culminación del tecnólogo.

### Carpetas con la modificación de diseño y y funcionalidad de los charts

###Front

  |_Archivos Modificados
    |__estadisticas.page.html
        |__Mejoramiento de diseño y tamaños de las tablas cn una card con abreviaturas 
    |__estadisticas.page.css
        |__Mejoramiento de diseño cambiendo tamaños y ubicación
    |__estadisticas.page.ts
        |__cambio de la conexión de la api y modificación de la funcionalidad de los charts
        
### Api
        
    |__registro.js
        |__Archivos de estructura de la db en Mongo con los cambios de los arreglos suma de datos al cambio de rol
    |__regsalida.js
        |__Archivos para diferrentes validadores de roles 
    |__registro.js
        |__Archivos de las diferentes rutas para el control de los arreglos enviados a la bd de Mongo
    |__regsalida.js
        |__Funcionalidad de cambio de rol de las tablas chrts.js


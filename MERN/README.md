# SERVER
### este repositorio corresponde al server de un MERN, la parte del cliente se encuentra en 
	https://github.com/YANETdelosAngeles/cliente
	
### La estructura debe se la siguiente:

cliente: correponde al frontend
### todo lo que `NO` este dentro de la carpeta `cliente` pertenece al servidor 


###	directorio: `cliente`
	directorio: `node_modules`
		  |
		  |
		  carpetas de dependencias
	directorio: `public`
                  |
                  |
                  archivo:    `favicon.ico`
                  archivo:    `index.html`
                  archivo:    `logo192.png`
                  archivo:    `logo512.png`
                  archivo:    `manifest.json`
                  archivo:    `robots.txt`
	directorio: `src`
                  |
                  |
                  directorio: `componentes`
                            |
                            |
                            directorio: `Crear`
                                      |
                                      |
                                      archivo:    `Crear.css`
                                      archivo:    `Crear.js`
                            directorio: `Footer`
                                      |
                                      |
                                      archivo:    `Footer.css`
                                      archivo:    `Footer.js`
                            directorio: `Modificar`
                                      |
                                      |
                                      archivo:    `Modificar.css`
                                      archivo:    `Modificar.js`
                            directorio: `Mostrar`
                                      |
                                      |
                                      directorio: `VerDetalles`
                                                |
                                                |
                                                archivo:    `Modal.css`
                                                archivo:    `Modal.js`
                                                archivo:    `VerDetalles.css`
                                                archivo:    `verDetalles.js`
                                      archivo:    `Mostrar.js`
                            directorio: `portada`
                                      |
                                      |
                                      archivo:    `Portada.css`
                                      archivo:    `Portada.js`
                  |
                  |
                  archivo:    `App.css`
                  archivo:    `App.js`
                  archivo:    `App.test.js`
                  archivo:    `index.css`
                  archivo:    `index.js`
                  archivo:    `logo.svg`
                  archivo:    `reportWebVitals.js`
                  archivo:    `setuptest.js`
        |
        |
        archivo:    `package-lock.json`
        archivo:    `package.js`
        archivo:    `README.md`


### directorio: `models`
        |
        |
        archivo:   `modeloPokemon.js`
### directorio: `node_modules`
        |
        |
	carpetas de dependencias
### directorio: `rutas`
        |
        |
        archivo:  `pokemon.js`
#### archivo:    `conexion.js`
#### archivo:    `package-lock.json`
#### archivo:    `package.json`
#### archivo:    `README.md`
#### archivo:    `server.js`



# ¿Como iniciar el proyecto?

Iniciar el server local con 
  
  ### `nodemon server.js`

  se ejecuta desde la raiz, donde se encuentra el archivo server.js
    
Iniciar proyecto react front-end con

  ### `npm start`

  se ejecuta dentro de la carpeta cliente 

   
Inicialmente la base de datos se creará en caso de no existir, una vez creada pueden empezar a añadir datos
   
La base de datos está hecha con mongo DB.

La puerta de enlace por defecto de react es localhost:3000

la puerta de enlace por defecto del server es localhost:5000

* ## Para ejecutar la parte del servidor se debe asegurar de contar con las siguientes dependencias, estas deben estar en el archivo package.json y la carpeta `node_modules` 
### (se escribe como debe instalarse en caso de ser necesario)

  ### `npm init`  
  ### `npm install express`
  ### `npm nodmeon -g`
  ### `npm install mongoose`
  ### `npm install body-parser`
  ### `npm install cors --save`
  ### `npm morgan`

* ## Para ejecutar el lado del cliente se debe contar con las siguientes dependencias, estas deben estar en el archivo package.json y la carpeta `cliente/node_modules`
### (se escribe como debe instalarse en caso de ser necesario)

  ### `npm install uniqid`
  ### `npm install react-router-dom`
  ### `npm install axios`

 # si quieren descargar el proyecto completo accedan al siguiente enlace
 ( https://drive.google.com/drive/folders/12BZnFS4MKRy56Uth2kIQv7OxBcVDA3ZA?usp=sharing )

## editado 10/07/2022

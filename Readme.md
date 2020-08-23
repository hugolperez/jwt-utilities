- Inicializamos nuestro proyecto
`npm int -y`
- Creamos un archivo index.js
- Instalamos JSON Web Token
`npm i jsonwebtoken`

- Para probar nuestra aplicación necesitamos realizar lo siguiente:
  - Para crear un token
`node index.js sign secretWord yourName`
Al ejecutarlo, genera un token, para poderlo inspeccionar podemos ir 
a la página jwt.io, la cual nos hace una decodificación, para ello 
pegamos el token generado.

  - Para verificar token
`node index.js verify secretWord tokenGenerado`
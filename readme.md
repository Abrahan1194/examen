En la terminal, crea la base del proyecto si aún no lo has hecho:

db.json
Inicializar proyecto de Node.js

npm init -y
npm uninstall -g json-server
npm install -g json-server@0.17.4

json-server --watch db.json

live server
El repositorio evidencia commits descriptivos por funcionalidad.
  // Ahora 'path' ya no tiene los query params, asi que la comparacion es mas directa

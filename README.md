# RESTfull-expressJS

- Paso 1:
Crear nuestro package.json
```bash
npm init -y
```

- Paso 2:
Crear carpetas client y server
```bash
mkdir client server
```

- Paso 3:
Usar generador express-es6 en la carpeta server
```bash
npm i -g generator-express-es6
cd server && yo
```
Respuesta a preguntas:
+ Express Es6 (generador)
+ pug (motor de vistas)
+ stylus (preprocesador de estilos)
+ install dependencias

- Paso 4:
Mover las carpetas "public" "views" de 'server' a 'client'

- Paso 5:
En el package.json de nuestra carpeta raiz, agregar el siguiente "script"
```json
   ...
       "scripts":{
       ...
       "start":"cd server && node ./bin/start"
       ...
       }
   ...
```
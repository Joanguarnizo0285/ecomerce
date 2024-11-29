Para este proyecto iniciamos con la creacion de la carpeta bankend, luego hicimos la instalacion para a hacer el node_modules,package-lock.json y el package.json, luego creamos el src y creamos las carpetas configuracion, controladores, middleware, rutas y finalmente creamos el .env, cada carpeta para una diferente funcion, en controladores hicimos la basaDatos.js y la baseDatosPosgret.js, en la pagina controladores creamos los comandos para la funcion de la pagina, en middleware hicimos el codigo  que valida un token de autenticación y asigna un usuario a ese token, en modelos como era la estructura para escribir en el postman y crear las carpetas en el momgod, en rutas para poder hacer en el postman el post, get, put y delete de las diferentes carpetas utilidades, luego en el .env creamos la ruta del mongo_url, los usarios se hizo en el pgAdmin4

creacion de las carpetas en el mongo
https://evidencia/imagen1.png

creacion de la carpeta carrtitos
https://evidencia/imagen2.png

creacion de la carpeta categorias
https://evidencia/imagen3.png

creacion de la carpeta ordens
https://evidencia/imagen4.png

creacion de la carpeta productos
https://evidencia/imagen5.png

creacion de los usuarios en el pgadmin4
https://evidencia/imagen6.png

En el postman crear los usuario iniciamos secion para el funcionamiento del postam en las diferentes carpetas, con el correo de uno de los usarios y contraseña ya realizados y lo ejecutamos
https://evidencia/imagen7.png

luego vamos a authorization, luego a Auth Type y selecionamos Bearer Token y copiabamos el link del usuario
https://evidencia/imagen8.png

evidencias de la postman para la creacion de las carpatas tanto en mongo como en el pgadmin4
https://evidencia/imagen9.png
https://evidencia/imagen10.png

Luego de crear todas las carpetas en el postman elegimos una carpata ya creada y miramos si funciona todas las rutas de esa carpeta selecionada como el post, get, put y el delete
https://evidencia/imagen11.png
https://evidencia/imagen12.png
https://evidencia/imagen13.png
https://evidencia/imagen14.png

Luego de crear el bankend con todas las carpetas y funciones en el postman mongo y pgadmin4 creamos la carpeta frontend luego le ejecutamos el codigo para que se creen el package-lock.json y el package.json, .gitignore y el tailwind.config.js, el node_modules luego cremaos el src y las carpetas api y componentes, en api creamos el axiosConfig.js, la creacion de react, en la carpeta componentes cremos las paginas app.jsx, header.jsx, home.jsx, login.jsx, productos.jsx y register.jsx cada una para la funcion de la pagina, luego levantamos servicio en la terminal del bankend con el codigo npx nodemon servidor.js y luego levantamos servicio en frontend con el codigo npm start
https://evidencia/imagen15.png
https://evidencia/imagen16.png

Luego se abre el navegado y sale la pagina del proyecto.
https://evidencia/imagen17.png
Luego nos vamos donde dice iniciar sesion y registromos uno de los usuarios que creamos con la contraseña.
https://evidencia/imagen18.png
Luego inicamos sesion y saldra la lista de productos que creamos en el postman y que se ven tambien en el mongo.
https://evidencia/imagen19.png
https://evidencia/imagen20.png


Con estos pasos crea el proyecto.


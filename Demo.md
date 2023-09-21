# Demo

## Presentación de página main
```
Enseñar navbar con cambio de idioma y que existen distintos tipos de enlaces,
los cuales aparecerán nuevos enlaces si estás logueado o no.

Se presenta el cohete interactivo que hay en el botón principal de la página que nos llevaría al enlace de travels si lo capturas.

Se presenta la parte de "Live the experience" comunicando que es un texto que atrapará al usuario para que siga leyendo, y en caso de no querer leer todo el texto se resalta en negrita la parte que más "motiva" o "engancha" de todo el texto.

Se presenta la tercera parte de la página remarcando que son las características que ofrece nuestra aplicación:
  - Visita de nuevos planetas.
  - Descubrimiento de nueva flora, fauna y vistas.
  - Y probar toda clase de naves disponibles.

Se presenta la cuarta parte de la página presentando al equipo que ha hecho posible esta aplicación y que tanto empeño ha puesto en que ésto saliera adelante presentando sus nombres.

Se procede a presentar la última parte de la página comentando que para un futuro se podrá suscribir a un boletín de noticias de la página y por eso el botón está desactivado.
Se presenta la dirección, el email del proyecto y un número ficticio.
Se presenta el copyright y los enlaces a futuros twitters, etc del proyecto.
```

## Presentación de la página Travels SIN LOGIN
```
Remarcamos el Spinner que aparece durante 1 segundo o menos

Se muestra toda la página de travels mostrando primero los distintos campos que tiene un viaje, si se busca o se vende, etc.

Se muestra que hay paginación de 6 anuncios por página.

Y se prueba el filtro añadido en la parte superior de la página mostrando que todo funciona correctamente.
```

## Presentación de la página de Registro
```
Se presenta la página de registro indicando los distintos campos existentes.

1º Intento de registro con usuario duplicado de "Usuario Demo" "demo@gmail.com" para que salte el error de usuario duplicado.

2º Intento de registro con usuario nuevo pero haciendo no coincidir las contraseñas para que aparezca el error correspondiente.

3º Registro con éxito con un correo válido para futuros emails que se envien al correo correspondiente y comprobar que funciona.

Al registrarse exitosamente remarcar que ahora en la NAVBAR aparecen los distintos links que antes estaban ocultos por no estar autentificado.

Estos links son:  Saludo con el nombre correspondiente, Panel de Usuario, Crear un nuevo Viaje, Actualizar usuario, Borrar usuario y cambiado el Login por el Logout.

Hacer logout y proceder al Login.
```

## Presentación de la página de Login
```
Se presenta la página de Login indicando los distintos campos existentes con los que se hará el login.

Escribir un correo que no exista en la base de datos para confirmar que aparece el error.

Hacer login con usuario existente pero sin marcar "Recordar credenciales" y enseñar que al hacer un F5, el usuario será deslogueado.

Volver al Login con usuario existente y darle a "Forgot password", indicar el correo electrónico y proceder a restablecer la contraseña desde el enlace del correo.

Volver a hacer login marcando "Recordar credenciales" y hacer F5 y mostrar que seguimos logueados y pasar al siguiente paso.
```

## Presentación de la página de Travels CON LOGIN
```
Remarcamos el Spinner que aparece durante 1 segundo o menos

Se muestra ésta vez los botones desbloqueados mostrando que si es "Se busca" el botón se llama "Contactar" y si es "Se vende" aparece "Travel here", a parte de los distintos botones que aparecen de "Añadir a Favoritos" y "Contactar con el propietario".

Favoritos los añadiria al Panel de Usuario y Contactar con el propietario abriria el chat privado con el usuario y viaje correspondiente.

Añadir dos viajes a Favoritos y contactar con dos anuncios creados por Jesús. Contestando Jesús en ambos anuncios para mostrar que se puede tener más de un chat abierto pero con cada uno separado del otro.

### PROCEDE A ENSEÑARSE EL PANEL DE USUARIO YA QUE HEMOS ENTRADO

Procedemos a Crear un Viaje
```

## Presentación de la página de Crear Viaje
```
Se procede a mostrar todos los campos disponibles a la hora de la creación de un viaje nuevo.

Indicamos en la fecha una hora anterior a la actual para que aparezca el error traducido y enseñar que no se permite poner una fecha anterior a la actual.

Creamos un viaje que sea de venta y dos viajes que sean de búsqueda.

El de venta se usará para comprarlo desde Usuario Demo o lo comprará alguno, para mostrar que llega un correo que te notifica que tu viaje lo ha comprado alguien.

Los de búsqueda será para que desde Usuario Demo o alguien hable a los dos distintos viajes creados por el usuario Wolf (Yo en este caso).

Se procederá a enseñar la parte de Travels Description de los dos tipos de viajes existentes.
```

## Presentación de la página de Travels Description
```
Hacer login con Usuario Demo.

Al entrar en el anuncio de "Contactar" que no sea nuestro procedemos a enseñar todo lo que aparece en la descripcion del anuncio, título, comentarios e imagen, y si pasamos el ratón por encima de la imagen saldrá el resto de la descripción del anuncio.

Procedemos a enseñar las formas de contacto:
  - Contactar por whatsapp, click y enseñamos que efectivamente aparece el número.
  - Contactar via email desde Usuario Demo en uno de los anuncios previamente creados para poder enseñar que el correo llega correctamente cuando se contacta por email.

Le damos al botón de "Volver atrás" para enseñar un viaje de COMPRA.

Al entrar en el anuncio de "COMPRA" que no sea nuestro se muestra que se puede comprar el viaje creado previamente por Wolf.

Se mostrará que ha de ingresar la tarjeta de crédito y al realizar la compra se llevará a un pagina que le informará del viaje comprado.

Ingresaremos a mi correo para ver que se me notifica por correo que alguien ha comprado mi viaje.

Procederé a volver a conectarme con mi usuario en la pagina y compraré un viaje yo para confirmar que me llega un correo también si soy el comprador.

Procedo a entrar en un viaje que sea mio y enseñaré qué puedo hacer con él.
```

## Presentación de la página de Travels Description si eres PROPIETARIO
```
Se enseña que se puede editar el viaje, se editará y se enseñará que ha sido editado.

Se cerrará el viaje para enseñar que se puede cerrar parcialmente hasta que se decida volver a abrirlo, y se mostrará que en TRAVELS ya no aparece mientras esté cerrado.

Y finalmente se procederá a Borrar el viaje y se mostrará en TRAVELS que efectivamente ese viaje ya no existe.
```

## Presentación de la página de Update User
```
Se enseña que se puede  editar el usuario, y la contraseña, excepto el correo electrónico y que efectivamente funcionan los errores si el usuario ya existe o si las contraseñan no coinciden.
```

## Presentación de la página de Delete User
```
Se enseña que se puede  borrar el usuario si pones el correo electrónico y contraseña correcta.
```

## Presentación de la página de ERROR 404
```
Se enseña que si se accede a una url que no existe aparecerá la página de error 404 con un botón que nos devolverá al Inicio.
```
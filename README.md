# MIURART Red Social ![Group 17](https://user-images.githubusercontent.com/67443691/121117275-7e900680-c7dd-11eb-94d9-a1505783b2f1.png)

MiurArt es una red social enfocada en artistas de murales que permite compartir datos, información, y la interacción entre los miembros de esta comunidad a través de comentarios y reacciones como "me gusta". Los miembros de esta comunidad tienen un perfil en donde pueden poner una breve descripción suya. También hay una sección para publicar lo que crean conveniente relacionado a su trabajo y arte.

## Definición de producto

### ¿Quiénes son los usuarios del producto? 

- Artistas muralistas que quieran exponer su arte de manera virtual

### ¿Cuáles son los elementos tiene nuestra red social?
  - Permite crear una cuenta personal.  
  - Permite iniciar sesión. 
  - Permite hacer publicaciones.  
  - Permite tener conversaciones con otras personas.  
  - Permite reaccionar a las personas ante una publicación.

### ¿Cómo descubrimos las necesidades de los usuarios?
  - A través de entrevistas de artistas independientes.

 ### ¿Qué problema resuelve el producto para estos usuarios?
 
  - La inexistencia de una red social enfocada exclusivamente en la exposición de su arte

### ¿Cuáles son los objetivos de estos usuarios en relación al producto?

  - Poder encontrar publicaciones de artistas.
  - Poder conocer a otros artistas.
  - Poder promocionar su arte.
  - Poder crear o unirse a una comunidad de artistas.


### ¿Cuáles son las principales funcionalidades del producto y cuál es su prioridad?

  - Permitir hacer publicaciones.
  - Permitir crear una cuenta.
  - Permitir poder ingresar con una cuenta de google.
  - Permitir ingresar a la red social.
  - Permitir el compartir y reaccionar a las publicaciones.
  - Permitir la edición o eliminación de las publicaciones.


## ENTREVISTAS 

### PREGUNTAS
**Pregunta 1:** ¿Sientes que tu trabajo tiene suficiente visibilidad ?    
**Pregunta 2:** ¿Para ti, es fácil conocer o contactarte con otros artistas del medio?  
**Pregunta 3:** ¿Consideras importante el relacionarte con otros artistas del medio?  
**Pregunta 4:** Si hubiera una red social para artistas murales, ¿Qué tipo de información te gustaría encontrar?

**Entrevista 1 (Mujer, 27 años)** 
 1: Eh no, debido a las restricciones de la pandemia, los lugares donde solían estar expuestos mis murales han sido restringidas (Restaurantes, Galerías, y calles cerca a oficinas).  
 2: Se ha reducido el espacio de interacción, debido a la pandemia.         
 3: Sí, porque igual siempre hemos sido una comunidad unida. Pero ahora siento que se ha limitado nuestra interacción y convivencia.  
 4: Me gustaría mostrar mi trabajo como hacía antes, y recibir feedback y comentarios de otros artistas, así como explorar otros perfiles, para ampliar mi red de contactos.  

**Entrevista 2 (Hombre,22 años)**   
 1: No mucho, con la llegada de la pandemia mi trabajo como el de otros se ha visto detenido e ignorado.     
 2: Realmente incluso antes de la pandemia el conocer a otros muralistas fue un tanto limitado.   
 3: Por supuesto, como artista me gusta cocnocer gente en este medio, que pueda apoyarme y denvolverme.    
 4: Me gustaría conocer a más artistas y ver su arte, además de mostrarles el mío.  
 

# Historias de Usuario

### `Historia de Usuario 1`
Yo como usuari@ deseo tener una vista inicial atractiva en la plataforma antes de ingresar a mi cuenta.

    Criterio de aceptación:
    
    - Se muestra campos para ingresar: nombre, apellido, nombre de usuario, correo electrónico, contraseña
    - La contraseña tiene más de 6 dígitos
    - No se pueden ingresar números en los campos de nombre y apellido
    - Se muestra casilla para términos y condiciones
    - No se activa la cuenta si no se acepta el mensaje de verificación
    - Se muestran opciones para registrarse desde google o facebook
    - Se muestra un mensaje indicando que  ya puede iniciar sesión
    - Se muestra mensaje y opción para regresar al log in

    Definición de lo terminado

    Login con Firebase:
    - Para el login y las publicaciones en el muro puedes utilizar Firebase
    - Creación de cuenta de acceso y autenticación con cuenta de correo y contraseña, y también con una cuenta de Google.

    Validaciones:
    - Solamente se permite el acceso a usuarios con cuentas válidas.
    - No pueden haber usuarios repetidos.
    - La cuenta de usuario debe ser un correo electrónico válido.
    - Lo que se escriba en el campo (input) de contraseña debe ser secreto.

    Comportamiento:
    - Al enviarse el formulario de registro o inicio de sesión, debe validarse.
    - Si hay errores, se deben mostrar mensajes descriptivos para ayudar al usuario a corregirlos

    Testeo:
    - Se hizo testeo de las funciones de la historia de Usuario
    

### `Historia de Usuario 2`
Yo como usuari@ quiero iniciar sesión con el correo y la contraseña que registré para poder ver mi muro

    Criterio de aceptación:
    - Se muestra campos para ingresar: correo electrónico y contraseña
    - La contraseña tiene más de 6 dígitos
    - El botón se habilita cuando los inputs no esten vacios
    - Se muestran opciones para ingresar desde google o facebook
    - Se muestra mensaje y opción para ir al registro

    Validaciones:

     - Solamente se permite el acceso a usuarios con cuentas válidas.
     - No pueden haber usuarios repetidos.
     - La cuenta de usuario debe ser un correo electrónico válido.
     - Lo que se escriba en el campo (input) de contraseña debe ser secreto

     Comportamiento:

     - Al enviarse el formulario de registro o inicio de sesión, debe validarse.
     - Si hay errores, se deben mostrar mensajes descriptivos para ayudar al usuario a corregirlos.

    Definición de lo terminado:
    Login con Firebase:

     - Creación de cuenta de acceso y autenticación con cuenta de correo y contraseña.
     - Creación de cuenta de acceso y autenticación con una cuenta de Google.
     - Se hizo test unitarios
     - Se hizo testeo de funciones
     - Se hizo test manualmente buscando errores e imperfecciones simples.
     - Se hizo pruebas de usabilidad e incorporaron el feedback de los usuarios como mejoras.
     - Se recibió feedback de compañeras.
     - Es responsive.

### `Historia de Usuario 3 `
Yo como usuari@ quiero poder comentar publicaciones de otros artistas

    Criterio de aceptación:
    - Hay un botón para generar el comentario
    - Sólo se puede comentar texto
    - El comentario se visualiza inmediatamente después de haberlo publicado
    - Puede hacer comentarios en publicaciones de otros
    - Puede hacer uno o más comentarios en un mismo post
    - Se muestra el nombre de la persona que hizo el comentario
    - Se muestra la foto de la persona que hizo el comentario

    Definición de lo terminado:
    - Se hizo test unitarios
    - Se hizo testeo de funciones
    - Se hizo test manualmente buscando errores e imperfecciones simples.
    - Se hizo pruebas de usabilidad e incorporaron el feedback de los usuarios como mejoras.
    - Se recibió feedback de compañeras.
    - Es responsive.

### `Historia de Usuario 4 `
Yo como usuari@ deseo una plataforma que me permita ver las publicaciones de otros usuarios

    Criterio de aceptación:
    - Al recargar la aplicación, se debe verificar si el usuario está logueado antes de mostrar contenido.
 
    Definición de lo terminado:
    - Se hizo test unitarios
    - Se hizo testeo de funciones
    - Se hizo test manualmente buscando errores e imperfecciones simples.
    - Se hizo pruebas de usabilidad e incorporaron el feedback de los usuarios como mejoras.
    - Se recibió feedback de compañeras.
    - Es responsive

### `Historia de Usuario 5 `
Yo como usuari@ quiero crear y editar publicaciones en el muro

    Criterio de aceptación:
    Validaciones:
    - Al publicar, se debe validar que exista contenido en el input.
      
    Comportamiento:
    - Al recargar la aplicación, se debe verificar si el usuario está logueado antes de mostrar contenido.
    - Puede hacer una o muchas publicaciones.
    - Puede eliminar publicación(es) específicas.
    - Pide confirmación antes de eliminar un post.
    - Al dar click para editar un post, debe cambiar el texto por un input que permita editar el texto y luego guardar los cambios.
    - Al guardar los cambios debe cambiar de vuelta a un texto normal pero con la información editada
    - Al recargar la página se puede ver los textos editados.

    Definición de lo terminado:
    - Se hizo test unitarios
    - Se hizo testeo de funciones
    - Se hizo test manualmente buscando errores e imperfecciones simples.
    - Se hizo pruebas de usabilidad e incorporaron el feedback de los usuarios como mejoras.
    - Se recibió feedback de compañeras.
    - Es responsive

### `Historia de Usuario 6`
Yo como usuari@ deseo poder dale like o una emoción a las publicaciones que me gusten

    Criterio de aceptación:
    - Hay un botón like en cada publicación realizada
    - Hay un contador de likes en cada publicación
    - Un usuario puede dar like 1 vez a 1 publicación
    - Se peude quitar el like de las publicaciones
    - Sólo si el usuario está logueado puede dar like
    Definición de lo terminado:
    - Las funciones han sido testeadas
    - El contador muestra la cantidad de likes que tiene la publicación en tiempo real
    - 

### `Historia de Usuario 7`
Yo como usuario quiero editar mi publicación para plasmar algo distinto

    Criterio de aceptación:
    - Hay un botón para editar la publicación
    - Sólo el usuario que hizo la publicación la puede editar
    
    Definición de lo terminado:
    - Se han testeado las funciones
    - Los cambios se pueden visualizar en menos de 1rn

### `Historia de Usuario 8`
Yo como usuario quiero eliminar mi publicación para que ya no aparezca en mi muro de mi red

    Criterio de aceptación:
    - Sólo el usuario que creó la publicación la puede eliminar
    - Hay un mensaje de verificación cuando se da click en el botón de eliminar.
    - El mensaje de verificación contiene un botón para cancelar la acción y otro para verificarla
    - Al recargar la página, no se verá la publicación ni los posts de esta.

    Definición de lo terminado:
    - Se hizo test unitarios
    - Se hizo testeo de funciones
    - Se hizo test manualmente buscando errores e imperfecciones simples.
    - Se hizo pruebas de usabilidad e incorporaron el feedback de los usuarios como mejoras.
    - Se recibió feedback de compañeras.
    - Es responsive

### `Historia de Usuario 9`
Yo como usuari@ deseo poder cerrar mi sesión en la red social

    Criterio de aceptación:
    - Hay un botón para cerrar la sesión
    - Al hacer click en el botón Salir se muestra la página de log in
    - El usuario no puede ver sus publicaciones o las publicaciones del resto

    Definición de lo terminado:
    - Las funciones de cerrar sesión han sido testedas
    - Regresa a la página de log in
    - Se hizo test unitarios
    - Se hizo testeo de funciones
    - Se hizo test manualmente buscando errores e imperfecciones simples.
    - Se hizo pruebas de usabilidad e incorporaron el feedback de los usuarios como mejoras.
    - Se recibió feedback de compañeras.
    - Es responsive.

### `Historia de Usuario 10`
Yo como usuari@ deseo poder ver mi perfil de la red social cuando este logueada

    Criterio de aceptación:
    - Se muestra la foto por defecto de la cuenta de google si ingresó a través de esta opción
    - Se puede cambiar la foto de pefil una vez que haya iniciado sesión

    Definición de lo terminado:
    - Se hizo test unitarios
    - Se hizo testeo de funciones
    - Se hizo test manualmente buscando errores e imperfecciones simples.
    - Se hizo pruebas de usabilidad e incorporaron el feedback de los usuarios como mejoras.
    - Se recibió feedback de compañeras.
    - Es responsive.

## PROTIPOS DE BAJA FIDELIDAD

**(Vista Mobile)**


![Mobile baja calidad 1](https://user-images.githubusercontent.com/77282012/121119386-20fdb900-c7e1-11eb-9847-154f4ec8439e.png)

![Mobile baja calidad 2](https://user-images.githubusercontent.com/77282012/121119166-c5cbc680-c7e0-11eb-9106-ea3b1880a536.png)

![Mobile baja calidad 3](https://user-images.githubusercontent.com/77282012/121119534-6621eb00-c7e1-11eb-86ff-dda9a578b9d5.png)

![Mobile baja calidad 5](https://user-images.githubusercontent.com/77282012/121119170-c6645d00-c7e0-11eb-9d08-af91ca1c0d4b.png)


![Mobile baja calidad 4](https://user-images.githubusercontent.com/77282012/121119168-c5cbc680-c7e0-11eb-89bf-0bdcb99b9927.png)


**(Vista Desktop)**

![PC baja calidad 1](https://user-images.githubusercontent.com/77282012/121118924-53f37d00-c7e0-11eb-8bd5-76b3a493bade.png)

![PC baja calidad 2](https://user-images.githubusercontent.com/77282012/121118992-738aa580-c7e0-11eb-8be3-e65d6bbc4dd0.png)

![PC baja calidad 3](https://user-images.githubusercontent.com/77282012/121118987-72597880-c7e0-11eb-95f1-7f75bdf6a6de.png)


**Feedback Recibido**
## PROTOTIPOS ALTA FIDELIDAD


**(Vista Mobile)**

![Frame 5](https://user-images.githubusercontent.com/77282012/121119801-eea08b80-c7e1-11eb-995c-01410f150086.png)
![Mobile alta calidad 5](https://user-images.githubusercontent.com/77282012/121119802-ef392200-c7e1-11eb-9927-c0f8d91b1955.png)
![Mobile alta calidad 6](https://user-images.githubusercontent.com/77282012/121119804-efd1b880-c7e1-11eb-8564-83e94eb7994f.png)
![Mobile alta calidad 7](https://user-images.githubusercontent.com/77282012/121119805-efd1b880-c7e1-11eb-9a43-b371fb867eaa.png)
![Mobile alta fidelidad 1](https://user-images.githubusercontent.com/77282012/121119806-f06a4f00-c7e1-11eb-9879-b015c56d2961.png)
![Mobile alta fidelidad 2](https://user-images.githubusercontent.com/77282012/121119808-f06a4f00-c7e1-11eb-9cb3-c09089c3a048.png)

**(Vista Desktop)**

![Frame 7](https://user-images.githubusercontent.com/77282012/121119984-4ccd6e80-c7e2-11eb-9e1f-f5d2b6d78cd3.png)
![Frame 9](https://user-images.githubusercontent.com/77282012/121120128-98801800-c7e2-11eb-9ed8-4f7d0fbf103e.png)
![PC alta calidad 3](https://user-images.githubusercontent.com/77282012/121120682-abdfb300-c7e3-11eb-8656-af12f0f4e326.png)



**Feedback Recibido**

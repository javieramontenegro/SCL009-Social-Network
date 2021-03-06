# My Chingu Red Social

![Portada](https://i.ibb.co/kx5s0XC/Screenshot-2.jpg)   

   
## Índice
***
* [Definición del producto](#definición-del-producto)
* [Planificación y Diseño](#planificación-y-diseño)
* [Implementación de Interfaz de Usuario](#implementación-de-interfaz-de-usuario)
***   
## Definición del producto
***
El K-Pop, o música pop Coreana, es un estilo musical que tiene muchos adeptos en Asia, y que hoy en día está adquiriendo una inesperada popularidad en latinoamérica y recientemente en Chile.

El rángo etáreo, donde predominan los nativos digitales, establecen un grupo objetivo en que las redes sociales son parte importante del día a día, por ejemplo, el grupo BTS tiene más de 20 millones de seguidores en su twitter oficial en coreano y aproximadamente 15 millones de seguidores en su twitter oficial en inglés.

My Chingu, que en español significa "Mi Amigo", surge como un red social para que los fans del de K-POP encuentren espacios comunes con fandoms chilenos y latinoamericanos. Podrán compartir sus Idols y grupos favoritos, historias y lo que deseen contar a sus amigos.

#### A quién va dirigido
* El producto está dirigido a todos los fans del género musical K-Pop (Pop Coreano) y que busquen un lugar exclusivo para ellos, donde se puedan intercambiar Idols (Ídolos), compartir mensajes, en un ambiente seguro, libre de bullying.

#### Objetivo del producto.    
* Se estimaron las necesidades del usuario realizando diferentes actividades:
    - Búsqueda de redes sociales que estuvieran dedicadas de forma exclusiva al K-Pop.
    - Entrevista a consumidores de K-Pop considerando las siguientes preguntas:
        - Eres usuario de alguna red social? Cuál?
        - En qué medio buscas información de tus Idols o grupo favorito de K-Pop
        - Sigues en las redes sociales a tu Idol o grupo favorito?
        - Si es sí, a quiénes.
        - Qué información buscas de tu Idol o grupo favorito?
        - Te registrarías en una red social exclusiva de K-Pop?
        - Por qué?

Hoy en día las redes sociales dedicadas al K-Pop comparten su ambiente con otros tipos de aficiones, dando como resultado sitios webs muy sobrecargados de información, de dificil entendimiento y registro, o bien que dejan la tarea de armar una comunidad al usuario. Redes sociales como facebook y twitter dan pie para que exista el bullying.

#### Solución al problema.

My Chingu entrega un espacio exclusivo para los Fans del K-Pop. Podrán registrarse de una manera sencilla, elegir en su perfil el estudio o grupo favorito (pronto disponible), que le permitirá econtrar otros fans con los mismos gustos.

También el usuario podrá escribir en su muro sobre sus Bias, Idols y grupo favorito. 

Pronto! Podrá compartir fotos con otros usuarios o amigos.

***
## Planificación y Diseño
***
Para el proceso de planificación y diseño se utilizaron las siguientes herramientas:    
- Trello: Nos permitió mantener el orden en el proceso de producción, a través del desarrollo de historias de usuario con la determición del criterio de aceptación y la definición de terminado. Puedes ver nuestro Trello pinchando [AQUÍ](https://trello.com/b/BoPsoPwa/red-social)  
- Diagramas de flujo: Diagrama que permitió definir el flujo que debía seguir el usuario al ingresar a la página web.
- Figma: Interfaz de diseño colaborativa que permitió desarrollar el prototipo de alta fidelidad.

Comparte fotos de entrevistas (si las tienes)
cuestionarios y tus sketches/(bocetos).

### Historias de usuario
Utilizamos las historias de usuario como el instrumento principal para identificar los requerimientos de usuario.

-__Historia 1__  
_Como_ usuario _quiero_ elegir un correo y una contraseña para  _poder_ registrarme en My Chingu

__Hitoria 2__  
_Como_ usuario _quiero_ usar mis datos de google para _poder_  ingresar a My Chingu

__Historia 3__  
_Como_ usario _quiero_ usar mi correo y contraseña registrada para _poder_ acceder a My Chingu

__Historia 4__  
_Como_ usario quiero poder cerrar sesión para _poder_ estar seguro de que otras personas no vean mis datos o muro

__Historia 5__  
_Como_ usario quiero que otros usuarios no puedan acceder a otros sectores del sitio si no iniciaron sesión para _poder_ resguardar mi privacidad.

__Historia 6__  
_Como_ usario quiero que se me notifique si inicio sesión sin estar registrado para _poder_ enterarme de que no es un error del sitio que no pueda acceder.

__Historia 7__  
_Como_ usario quiero hacer una publicación en el muro para _poder_ compartir mis bias o idols favoritos.

__Historia 8__  
_Como_ usario quiero eliminar una publicación para _poder_ evitar que otros vean una publicación que no quise realizar.



### **Diseño de la Interfaz de Usuario**

El proceso de diseño se realizó con base en las entrevistas y las historias de usuario y las necesidades que surgieron.


* Hacer sesiones de testing con el producto en HTML.


flujo que seguirá el usuario dentro de tu producto




### **Prototipo de Baja Fidelidad**

![Prototipo baja](https://i.ibb.co/6WmCgtZ/sketch1.jpg)   
![Prototipo baja](https://i.ibb.co/vX69vpR/bajaiteracion.jpg) 


#### Test de Usuario 1
![TestUsuario1](https://i.ibb.co/LSpJTc6/test1.jpg)  

#### Test de Usuario 2
![TestUsuario2](https://i.ibb.co/hLxfDkN/test2.jpg)  


### **Prototipo Alta Fidelidad**  
![Prototito alta fidelidad](https://i.ibb.co/wK661zt/altafid1.jpg)  
![Prototito alta fidelidad](https://i.ibb.co/RgSyZYH/altafid2.jpg)  


#### Test de Usuario 1



#### Test de Usuario 2

***
## Implementación de la Interfaz de Usuario
***
![Implementación](https://i.ibb.co/k8sMw8r/portada-web1.jpg)  


Nuestra interfaz cuenta con diferentes secciones:
- **Inicio (Home)**: Página inicial, invita al usuario a iniciar sesión mediante un botón en nav-bar o a registrarse mediante un botón central en el body.

- **Registro**: página en la que el usuario podrá registrarse mediante el ingreso de un nombre de usuario, un mail y una contraseña. En caso de que se ingresen datos no válidos o que el mail ya existiera en la base de datos, el usuario recibe mensajes de error.
Solo si el registro es exitoso, el usuario podrá acceder al muro.  El usuario también tiene la opción de acceder con google.

- **Inicio de sesión**: El usuario podrá iniciar sesión con su mail y password, también podrá acceder con google.

- **Muro**: El usuario puede escribi post, publicarlos y editarlos.

Futuras implementaciones:
- **Preferencias**: El usuario podrá seleccionar las disqueras o grupos musicales favoritos. Esto permitirá que el usuario vea a otros usuarios con gustos similares.

- **Perfil**: El usuario contará con un perfil con foto, donde además podrá visualizar sus preferencias, amigos, y editarlos.

El resultado final de la implementación lo puedes ver en nuestro deployment de Git-Hub [AQUÍ](https://donapaz.github.io/SCL009-Social-Network/)

***
## Build With 
***
- Vanilla Javascript (ES6)
- Firebase - Firestore
- HTML5
- CSS
- Figma

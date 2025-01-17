# 🗓️ Tracker diario: Primer semestre 2025  

---

**Fecha de inicio**: 02/01/2025   
**Fecha de finalización**: 
**Total días de estudio**:  
**Total horas de estudio**:  
**Notas**:  

----
## **Enero 2025**  

### ✍️ **Día 72 --> Jueves 02 de Enero del 2025**  

(3hs de Proyecto Final CS50 Python)   

Voy a condensar en esta entrada lo que estuve haciendo los últimos 2 o 3 días porque es parte de lo mismo y, como fue muy salteado el estudio esta semana, prefiero que quede todo junto.  

Llevo unos días trabajando en el pre-proyecto del desafío final de CS50P.  Dejé volar un poco mi imaginación y terminé con un proyecto un poco más grande de lo que imaginaba, pero no imposible de resolver con esfuerzo.  

Voy a armar un Book Tracker para poder llevar registro de los libros que voy leyendo o que quiero comprar próximamente. Me parece que es una idea interesante para armar un CLI.  

Voy a usar varias librerías que no he trabajado hasta el momento. Quiero hacer buenos tests y usar type hints si me da la vida.  

Ya tengo pensada la funcionalidad básica, hecho el research inicial de librerías y tecnologías que necesito usar y le voy a dedicar un par de horas más a armar los flujos del usuario, así me resulta más simple codear y separar cada una de las funciones que necesito implementar.  

Pensando en este proyecto me di cuenta que no sé nada sobre cómo organizar el código de un desarrollo en Python 🫠 Pero supongo que esto también es parte de las razones por las que piden un desafío final... Para que busquemos información por nuestra cuenta jajaja.  

En fin, seguiré trabajando con esto al menos una semana más, entre implementación y estructura del proyecto. No quiero que me tome una eternidad tampoco.  

---
### ✍️ **Día 73 --> Viernes 04 de Enero del 2025**  

(1.5hs de proyecto BookPal)  

Pude armar los primeros diagramas de flujo de la app y además definir un poco más los comandos que voy a generar.  

Armé el repo base y estuve creando el README.md para ayudarme a esclarecer mis ideas jajaja.  

Muy feliz con el avance de hoy. Creo que va tomando forma, al menos conceptualmente. 

Ya me quiero poner a codear pero a la vez no entiendo como ponerme a codear sin hacer todo este proceso previo.  

Me acabo de dar cuenta que es el primer proyecto que voy a codear que NO tiene una UI asociada, y por eso estoy usando herramientas distintas para planificar y definir. Cool 😎 nuevas experiencias!  

---
### ✍️ **Día 74 --> Sábado 04 de Enero del 2025** 

(1.5hs de proyecto BookPal)  

Por fin me puse a codear! Luego de unos días de investigación decidí empezar por las clases que ya tengo más definidas y luego ir viendo cómo evoluciona.  

Seguramente deba ir modificando cosas sobre la marcha pero al menos tengo una base sólida con la que empezar.  

Pensé las clases más importantes que va a tener el proyecto con sus métodos y propiedades para hacerme la vida más simple.   

También aprendí como trabajar con packages y modules para tener el código separado en carpetas. Algo que en JS doy por sentado en Python no tenía ni idea cómo hacerlo. Así que me tuve que poner a investigar sobre el tema porque es diferente.  

Aprendí un poco sobre los archivos `__init__.py` y algunas buenas prácticas para tener una mejor estructura de proyecto.  

---
### ✍️ **Día 75 --> Lunes 06 de Enero del 2025** 

(2hs de proyecto BookPal)  

Estoy viendo algunos avances en esto. Me cuesta un poco porque no estoy tan acostumbrada a OOP, pero justamente por esa razón me propuse hacerlo de esta manera jaja.  

La clase Book, que es una de las más importantes del sistema, está casi lista. De esta heredan otras dos más que voy a tener que generar pronto.  

Siento que la diferencia en el nivel de dificultad entre: 1) hacer los challenges de CS50P y 2) armar mini proyectos de este estilo es abismal. No tengo ni una clase lista y ya tengo más producción que en todos los ejercicios de OOP juntos más o menos jajaja.   

Pero bueno es un salto de calidad también poder armar algo más grande que sólo puzzles o PSETs.  

---
### ✍️ **Día 76 --> Miércoles 08 de Enero del 2025** 

(1,5hs de proyecto BookPal)  

Voy avanzando 💪 Ya tengo las primeras 3 clases listas: Book, BookRead, BookListed. 

Por un momento me desmotivé porque esta semana no le pude dedicar tanto tiempo al estudio. Luego me acordé que estaba comparando una semana de full trabajo y estudio con mis días de vacaciones y se me pasó jajaja 🤣  

Parece que no está pasando nada, pero ya están ocurriendo magias, sólo necesito confiar en el proceso.  

----
### ✍️ **Día 77 --> Jueves 09 de Enero del 2025** 

(1,5 hs de proyecto BookPal)  

Pude armar la clase `BookGenerator` para gestionar los inputs de los usuarios y el proyecto empieza a cobrar forma. 

Aún me quedan cosas para hacer pero al ir trabajando con el manejo de inputs me da la sensación de que avancé bastante en un par de horas.  

---
### ✍️ **Día 78 --> Martes 14 de Enero del 2025** 

(1,5 de proyecto BookPal)  

Pude avanzar un poco más con los class methods de `BookGenerator`. Fueron unos días de corridas y me siento mal por no poder dedicarle el tiempo suficiente a avanzar con esto.  

Dejé implementada una librería llamada Pick para hacer los inputs de selección y funciona muy bien la verdad. Es simple y da un buen efecto.  

Ahora también tengo un título de la app con onda, gracias a Pyfiglet.  

Quiero completar la clase de `BookGenerator` para poder avanzar hacia las clases más complejas que son el manejador de comandos y el controller de los archivos. 

Sin esas clases aún no termina de cuadrar la idea. Va avanzando pero faltan tantas partes que es difícil entender qué me está faltando y si algo falla pero a nivel más conceptual.  

Pasa que mi tiempo ha sido tan disgregado para este proyecto que es un lío entender el progreso que voy haciendo y cuántas cosas podrían faltar.  

También me quedan pendientes y para ponerme las pilas los tests de todas las clases y funciones auxiliares. Necesito revisar cómo configurar la carpeta de tests y como correr todos los tests juntos con Pytest.  

En fin bastante más trabajo del que esperaba.  

---
### ✍️ **Día 79 --> Miércoles 15 de Enero del 2025** 

(1.5 hs de BookPal)    

Por fin pude terminar la clase `BookGenerator` 🎉 y está funcionado genial. Ya se generan desde un método los libros de tipo leído y por leer.  

Ahora puedo dedicarme a armar una nueva clase para manejar los comandos, y también, me toca revisar cómo voy a hacer las conexiones para que se vayan almacenando los libros en sus correspondientes archivos CSV.  

También implementé la librería `Rich` para poder darle un poco de estilo a los outputs de la terminal. La verdad resultó muy fácil de usar y brinda muy buenas herramientas, como soporte para emojis, colores y tablas; todo dentro de la terminal y orientado para CLI.  

Además funciona para cualquier sistema operativo, lo cual es un golazo porque otras herramientas no funcionan en Windows.  

----
### ✍️ **Día 80 --> Jueves 16 de Enero del 2025** 

(2hs de BookPal)  

Por fin pude armar un videíto mostrable sobre el funcionamiento de esta app 🥳. Armé la nueva clase `CommandHandler` y el flujo de la app empezó a cobrar forma.  

Ahora puedo seleccionar el archivo sobre el que quiero trabajar: `finished-books` o `wishlist-books` y eso dispara los comandos disponibles para ambos archivos.   

Todavía no se está persistiendo la data generada en ninguna parte, pero, al menos el funcionamiento para agregar un nuevo libro está tomando forma. Solo faltan las conexiones con los archivos que es de las próximas tareas que me gustaría tomar.  

Además implementé el método `--help` con información útil sobre el programa y el proyecto.  

----
### ✍️ **Día 81 --> de Enero del 2025** 

( )  
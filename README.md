# Gabriel_II_Examen_PG
Nombre del estudiante: Gabriel Josué Prado López Fecha:18/04/2022
Porcentaje:  20%
Puntaje total:  100 puntos
Tiempo disponible: 2.5 horas	Puntos obtenidos:  ____ puntos
Porcentaje: _____ %
Nota: _____
Instrucciones generales
●	Lea cuidadosamente la prueba antes de iniciar, dispone de 20 minutos para formular sus preguntas antes de comenzar el examen. Únicamente se atenderán consultas a través de la plataforma TEAMS. Si se le presenta alguna situación o 
consulta, sírvase contactar al docente a través del chat privado para la atención de este.
●	La siguiente prueba debe desarrollarse de manera individual. 
●	Debe subir los archivos únicamente para responder la prueba.
●	Cualquier intento de fraude durante la prueba autoriza al docente a la anulación del examen y la reprobación del curso. 
●	Al finalizar por favor subir los archivos al espacio destinado en Moodle, en formato comprimido, con el siguiente formato de nombre, NOMBRE_II_EXAMEN_PG
●	Debe estar disponible a responder una llamada del profesor a través de la plataforma TEAMS cuando este así lo desee durante el periodo de la prueba. 

Se deben seguir los estándares de programación de HTML, CSS y Java, y las buenas prácticas vistas en clase en la resolución de cada problema.

I Parte Respuesta Breve: Responda de manera concisa lo que se solicita. (40 pts.)
1.	Según lo visto en clase, ¿Cuál es el acrónimo de Internacionalización y porque su nombre?
R/ i18n, debido a que son 18 letras que hay entre la i y la n
2.	Defina Bootstrap con sus propias palabras 
R/Es una página de estilos como tal que trae diferentes tipos de formatos, ya sea navbar, grids, con solo copiar y pegar código y adecuarlo a lo que se necesita se puede utilizar, además de incluir las propiedades de Bootstrap como tal dentro del css donde lo quiera utilizar o emplearlo en el mismo HTML donde lo quiera utilizar.
3.	Mencione 3 maneras diferentes en las cuáles se podría cambiar el lenguaje de una aplicación web, vista desde el punto del desarrollador web.
R/- en la barra del navegador empleando la instrucción ?lang=en (esto de en seria que lo traduzca a inglés).
-Otra manera seria que se cree una opción en la parte del menú y que se despliegue una lista y se pueda elegir el idioma.
-Se podría crear dos botones como tal que tenga los idiomas que se puedan elegir.

4.	Mencione 2 maneras en las cuáles se podría incluir Bootstrap en un proyecto de SpringBoot
R/ -Por medio de ingresar al link como tal y descargar lo que se encuentre ahí, de manera que el archivo que se me descarga pueda colocarlo en el CSS y solo lo empleo en las paginas las cuales necesite usar Bootstrap.
       -Copiando y pegando los siguientes links en la parte del HTML que se llama <head> <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0/dist/css/bootstrap.min.css" rel="stylesheet" > y este link también <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>

5.	Según lo visto en clase, cuál es un desafío al implementar una aplicación que se pueda cambia el lenguaje de sus componentes.
R/El desafío como tal puede ser el contexto de las palabras, no va a ser lo mismo una palabra en el idioma español costarricense al español mexicano.
6.	Mencione que ventajas proporciona la implementación de Bootstrap en el desarrollo web
R/-Ahorra tiempo en vez de utilizar CSS.
-Se puede personalizar a como uno lo necesite.
-Emplea mejores páginas de estilos como tal.
-Se puede utilizar junto a JavaScript.
7.	Explique con sus palabras, según lo visto en clase, que es el objeto Locale, SessionLocaleResolver y LocaleChangeInterceptor en Spring Security
R/-Locale: Representa el lenguaje, región geográfica y la variante del dialecto o idioma del usuario.
-SessionLocaleResolver: Guarda el idioma seleccionado por el usuario como atributo en el request HTTP. 
-LocaleChangeInterceptor: Detecta cualquier cambio por parte del usuario hacia lo que es el Locale.
8.	Según lo visto en clase, ¿Como restringiría el acceso a ciertas páginas a un usuario?
R/Por medio los roles y permisos que deben de estar en la base de datos, si es un usuario tiene derecho de entrar hasta ciertas páginas, pero si es un administrador como tal puede tener acceso a todo.
9.	Según lo realizado en clase, ¿Como se podría reutilizar código entre diversos archivos HTML?
R/Por medio de la creación de un folder dentro de templates y se crea un archivo HTML, se utiliza la funcionalidad de thymeleaf de th:fragment=”Secolocanombre” y esto me hará que el código sea como fragmentos y con solo ir al lugar donde quiero poner el código pongo en la etiqueta th:replace=”Secolocanombre”, se pondría el mismo nombre que puse en la parte de fragment.
10.	Explique los pasos para agregar Spring Security a un proyecto de Spring Boot.
R/-Agregar las dependencias de Springsecurity y thymeleaf extras.
-Crear una clase en la cual se extienda la clase de WebSecurityConfigurerAdapter.
-Configurar métodos en los cuales me permita pedir contraseña y nombre del usuario para cerciorarse si verdaderamente esta registrado en la base de datos.    
-Además de esto crear los roles y permisos para poder manejar los accesos a la página web.



11.	Según lo visto en clase, cuando se utiliza th:text="${titulo}" y cuando th:text="#{.titulo}"
R/-th:text=${titulo}= Es cuando va a recibir un nombre de la base de datos como tal, por eso se pone el símbolo del dólar.
-th:text=”#{.titulo}”= es cuando agrego como tal una traducción de un dato estático.


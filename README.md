# PRACTICA_Maty
## ¿Es mejor usar NGINX o APACHE y por qué?

si vamos a montar una página web muy grande que contará con muchos usuarios diarios la mejor opción es usar Nginx por sus mejoras de rendimiento, si queremos algo sencillo y flexible, Apache será un servidor mucho más apropiado, sobre todo para los usuarios sin muchos conocimientos.

## ¿Por qué debemos usar MVC?
(MVC) es un estilo de arquitectura de software que separa los datos de una aplicación, la interfaz de usuario, y la lógica de control en tres componentes distintos.

Se trata de un modelo muy maduro y que ha demostrado su validez a lo largo de los años en todo tipo de aplicaciones, y sobre multitud de lenguajes y plataformas de desarrollo.

contiene una representación de los datos que maneja el sistema, su lógica de negocio, y sus mecanismos de persistencia.

## ¿Para qué se usan los arreglos $_SESSION[] y $_SERVER[]?

las sesiones sirven para compartir información no entre una página y otra (Un formulario HTML y el php que lo procesa por ejemplo), si no entre todas las páginas por las que el visitante pase.

Arreglo de variables registradas en la sesion del script, asociativo de pares (clave, valor) de la variable sesion.

server: Arreglo de variables difinidas por el servidor Web o desde el entorno en donde el script se esta ejecutando. Arreglo asociativo de pares (Clave, valor del servidor)

## ¿Cuándo usamos polimorfismo?
Cuando se refiere a la propiedad por la que es posible enviar mensajes sintácticamente iguales a objetos de tipos distintos. El único requisito que deben cumplir los objetos que se utilizan de manera polimórfica es saber responder al mensaje que se les envía.

## Ventajas de PDO frente a mysqli
*La principal ventaja que tiene PDO, sobre MySQLi, es la habilidad de poderte conectar a 12 diferentes bases de datos, a diferencia de MySQLi que sólo tiene soporte para una, MySQL.

*Las extensiones mysqli te permiten programar tanto de forma procedural ("tradicional") como en forma orientada a objetos. Una buena estrategia es comenzar comprendiendo la programación tradicional y luego comenzar con la programación orientada a objetos. Las extensiones mysqli básicamente te dan soporte para bases de datos MySql. Esto significa que si cambiaras de base de datos, pasando por ejemplo a una base de datos de Microsoft SQL Server, tendrías que reprogramar tu aplicación pues los comandos de base de datos no serían reconocidos.

*En cambio, PDO proporciona una interfaz común que te soporta distintos tipos de bases de datos. En ese caso, si cambias de base de datos tu aplicación, no necesitas (al menos en teoría, aunque depende) reprogramar tu aplicación ya que PDO oculta la sintaxis particular reemplazándola por una común.

* PDO es completamente orientado a objetos, con lo que no tienes opción a decidir si quieres usar programación procedural u orientada a objetos.




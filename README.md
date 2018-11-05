Supuestos:


Supuestos :

En la Tabla Tiempo_Expiracion la Fecha_Termino se calculará mediante un trigger, el cual utilizará el dato Tipo (Un día, una semana, etc).

Cada vez que se realice un nuevo ingreso en Comunidad_Logros, un trigger se encargará de añadir el puntaje asociado a la reputación de la persona.

Cada vez que alguien vote, un trigger se encargará de sumar el puntaje correspondiente a la persona que realizó la publicación (ya sea comentario, pregunta o respuesta).

Cada vez que alguien cree un tipo de consulta (pregunta, respuesta o comentario) un triggers se encargará de sumar el puntaje a la reputación de la persona que lo realizó.

En la tabla Votos, el Rol_CS debe ser distinto al Rol_Consultas

Los Id de la tabla consulta deben ser mayor o igual a 1.

En la tabla Consultas, el atributo Id_Prov guarda el id de proveniencia, es decir, si se realiza una pregunta, el id_prov es 0, si se responde esa pregunta el id_prov corresponde al id de la pregunta.

Cargo tiene que ver con la jerarquía del sitio web, no de la universidad.


Link  de informe en overleaf:

https://www.overleaf.com/9713486782kmnznyztjfrg

Link de diccionario en googledocs:

https://docs.google.com/spreadsheets/d/1Y_XwNhcQDfplYxZ7Q2_rFfvMZujqpjzRhEpcxMgZz68/edit?usp=sharing

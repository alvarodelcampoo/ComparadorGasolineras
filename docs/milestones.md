[M0] Modelo del dominio y estructura de datos de destinos Erasmus

A partir de las necesidades descritas en [HU1], definir e implementar la estructura del modelo de datos del problema (entidades para representar al estudiante, sus idiomas, los destinos ofertados y las adjudicaciones con sus notas de corte). Serás viable si es aprobado por el product manager.

[M1] Cálculo de viabilidad y bonificación para el listado completo de destinos

A partir del modelo de datos del M0, primero hay que extraer la información relevante de estas fuentes de datos, y hecho esto, tenemos que implementar una función que calcule la diferencia de nivel de idioma entre el exigido para cada destino y el del usuario, para poder calcular la bonificación  y aplicarla en función de esta diferencia, con el objetivo de mostrar la nota final del usuario en todos los destinos del listado. [HU2] Está asignada a este milestone, y será viable si al pasarle la lista de destinos, la función devuelve para cada uno la nota final calculada y si el alumno es apto o no, sin errores en los cálculos.

# Practica-final

Trabajar sobre el proyecto del curso, agregando nuevas funcionalidades.

Se le solicita crear un nuevo Command para actualizar el nombre de una cuenta existente

1.	Llamará a este command UpdateAccountName
2.	Se debe registrar en mongodb el log cada vez que realice una actualización
3.	Se debe enviar un event data hacia Apache Kafka para que este se encargue de recibir este evento y encargarse de registrarlo en la base de datos mysql


Se solicita crear un nuevo Query para buscar un conjunto de cuentas pasándole como parámetro una parte del nombre, es decir si ingresó como parámetro “A”, entonces debe retornar todas las cuentas que contengan en su nombre ese texto “A”.

El trabajo deberá subirse al repositorio asignado en el curso. Para realizar la entrega deberá copiar la url de su repositorio en el apartado Práctica final de la plataforma.

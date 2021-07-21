# proyectoFinal

La biblioteca de una institución educativa X, requiere gestionar su material bibliográfico (libros) y su respectivo préstamo para la comunidad académica. Todos los libros poseen un título, un código ISBN, número de páginas, editorial y pueden estar en formato CD/DVD o impreso. Cada libro pertenece a una categoría específica (matemática, ingeniería, ciencias sociales, entre otras). De cada libro pueden existir varios ejemplares, cada ejemplar tiene una identificación y un número de edición. La biblioteca desea realizar búsquedas de libros por categoría, formato, autor o editorial, teniendo en cuenta que un libro puede ser escrito por varios autores, tratar varios temas y solo pertenece a una editorial.

La comunidad académica puede prestar ejemplares, considerando que un profesor puede solicitar una cantidad ilimitada de libros, pero un estudiante solo puede prestar como máximo 5 libros; en todo caso, al momento de realizar el préstamo se debe registrar la fecha del préstamo, y la fecha de retorno del libro (el sistema debe calcular automáticamente esta fecha, por defecto son 8 días y no se permiten renovaciones de préstamo) y una nota sobre el estado físico del libro. 

La biblioteca necesita conocer información general sobre los usuarios que prestan los libros, de estos se requiere conocer el nombre completo, dirección, la cédula y teléfonos de contacto, tipo de usuario (profesor o estudiante), *visualizar el histórico de préstamos por mes.*
Se debe contar con un usuario administrador que permite agregar, actualizar o eliminar tanto libros como usuarios.


# Modelo relacional 
![Tablas] (https://github.com/MalejaTM/proyectoFinal/blob/main/tablas.PNG?raw=true)

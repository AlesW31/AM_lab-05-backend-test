# Laboratorio 05: Testing Backend

Entregables:

- Subir el repositorio con el ejercicio hecho en clase
- 2 test cases: Happy y Unhappy Path de su historia de usuario de su proyecto.
- Deadline: Sábadao 14 a las 23:59

Mi historia de Usuario es mostrar la ubicación de las boticas en un mapa. Los Happy y Unhappy trails
mostrados se enfocan en la validación de las boticas.
Se agregó BoticaService.test.js en el que primero verifica si las boticas existen en la base
de datos.
Posterioremente se hace una validacion que llama a la función create, aquí verifica que la
dirección sea correcta con el fin de mostrarla correctamente en el mapa.
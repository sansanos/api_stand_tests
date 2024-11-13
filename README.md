# Tests for the firstName parameter when creating a user in the Urban Grocers App
- You need to have the pytest and request packages installed to run the tests.
- Run all tests with the command pytest.
  
Steps:

1. Send a request to create a new user.
2. Receive a response.
3. Check if the response contains the status code 201.
4. Check if the response contains the authToken field and it is not empty.
5. Check if the new user appeared in the "users" table.

# Pruebas para el parámetro firstName al crear un/a usuario/a en la App Urban Grocers
- Necesitas tener instalados los paquetes pytest y request para ejecutar las pruebas.
- Ejecuta todas las pruebas con el comando pytest.

Pasos:

1. Envía una solicitud para crear un nuevo usuario o usuaria.
2. Recibe una respuesta.
4. Comprueba si la respuesta contiene el código 201.
5. Comprueba si la respuesta contiene el campo authToken y no está vacío.
6. Comprueba si el nuevo usuario o usuaria apareció en la tabla "users".


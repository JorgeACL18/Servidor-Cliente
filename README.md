# Trabajo 27
En este ejercicio tenemos que crear dos programas, uno es un Servidor y el otro es un Cliente.

## Servidor:
Primero, tenemos que declarar las variables 'servidor' y 'socket' como null para poder usarlas a lo largo del programa.

Ahora, abrimos un try-catch donde haremos la conexión con el cliente, una vez se conecta con el cliente, con la variable 'lector' puede leer los mensajes que reciba del mismo y, por último, haremos un bucle para que pueda recibir estos mensajes hasta que el cliente decida desconectarse escribiendo "adios"

<img width="795" height="1054" alt="Captura de pantalla 2025-11-23 180825" src="https://github.com/user-attachments/assets/8d54d364-13b2-410c-b0d3-90a9a58b09ff" />


## Cliente:
Después de terminar con el servidor, pasamos al cliente.

Para hacer la conexión, en vez de usar ServerSocket, se usa directamente Socket.

Dentro del try-catch hacemos un PrintWriter para facilitar la escritura de mensajes y creamos el bucle para escribir el texto que queramos y un if que indica que, si escribimos "adios", se desconecta del servidor
<img width="716" height="1005" alt="Captura de pantalla 2025-11-23 183355" src="https://github.com/user-attachments/assets/1cb7c02e-b719-41cd-ac94-104c84848871" />

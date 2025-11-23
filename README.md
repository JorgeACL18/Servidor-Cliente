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

## Resultado:
En esta captura se ve como, al ejecutar el servidor, espera al cliente.

<img width="431" height="212" alt="Captura de pantalla 2025-11-23 184026" src="https://github.com/user-attachments/assets/a59cabb3-3c21-4a83-92c0-9b3cd1efe578" />


Cuando ejecutamos el cliente, se conecta automáticamente al servidor disponible

<img width="415" height="245" alt="Captura de pantalla 2025-11-23 184036" src="https://github.com/user-attachments/assets/33a595fd-d3ac-42f2-a11d-fc67d7776945" />
<img width="415" height="245" alt="Captura de pantalla 2025-11-23 184042" src="https://github.com/user-attachments/assets/9044be5c-496f-4747-b071-d3d4c33ffa32" />

Ya cuando se haya realizado esta conexión, ya podemos escribir lo que queramos y el servidor lo recibirá hasta que nosotros queramos escribir adiós.

<img width="402" height="432" alt="Captura de pantalla 2025-11-23 184114" src="https://github.com/user-attachments/assets/fa04d1ae-21e1-4d2e-b29a-907a792fb0cb" />
<img width="484" height="335" alt="Captura de pantalla 2025-11-23 184121" src="https://github.com/user-attachments/assets/c4cae7f1-1c90-4e29-b187-094425a825c7" />

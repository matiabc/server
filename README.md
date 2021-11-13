Este archivo contiene los dos primeros items de la tarea.

El archivo Sockets_IPv4_TCP contiene el primer ejercicio y para compilarlo es necesario escribir los siguientes comandos en la carpeta build
make
bin/server

y en otra instacia del terminal escribir los siguientes comandos para el cliente.
make
bin/client

Además de la instalación de Cmake y Conan

El archivo Sockets_UDP no nesita compilarse desde build y se puede hacer desde una terminal ubicada directamente en la carpeta src, para esto se necesitan los siguientes comandos. 

gcc client.c -o client 
gcc server.c -o server

y los siguientes comandos para ejecutarlos
./server // es importante ejecutar el serve antes que el cliente. 
./client

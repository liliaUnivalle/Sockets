# Sockets
Alejandro Rueda Parra - 1326183
Lilia Patricia de La Cruz Horta - 1225069

--------------------------------------------------------------
Formato:
Nombre del programa
	Proposito de los programas
	Cómo ejecutar el código fuente.
--------------------------------------------------------------

basic-01.py
	Mostrar como por medio de SOCKET se puede obtener el nombre de la maquina en la que se está corriendo el programa por medio del comando socket.gethostname()
	python basic-01.py

basic-02.py 
	Mostrar como por medio de SOCKET se puede obtener la IP de una maquina si se tiene el nombre de esta, con el comando socket.gethostbyname(host_name) sea 'host_name' el nombre de la maquina.
	python basic-02.py

basic-03.py 
	Mostrar como por medio de SOCKET se puede obtener el nombre de un servicio de red dado el nombre del protocolo y el numero del puerto, con el comando socket.getservbyport(port, protocolname) siendo port el numero del puerto y protocol_name el nombre del protocolo.
	python basic-03.py

basic-04.py
	Mostrar como correr un programa como NPT.
	python basic-04.py


basic-05.py
	Muestra como sin librerias se puede hacer un programa NTP cliente y muestra como deberÃ­a ser un verdadero UDP.
	python basic-05.py

socket-01.py:
	Mostrar como se deberia crear un socket TCP de internet.
	python socket-01.py

socket-02.py: 	
	Mostrar como se deberia crear un socket TCP de internet, y como a partir de un host_name obtenemos la direccion IP en este.
	python socket-02.py

socket-03.py:
	Mostrar como a travez de SOCKET con el comando socket.connect se establece una conecciÃ³n con el servidor de google.
python socket-03.py

socket-04.py: 
	Mostrar como se pueden enviar peticiones http al servidor http.
	python socket-04.py

socket-05.py
	Mostrar como recibir una respuesta desde un servidor http mediante recv.
	python socket-01.py

server-01.py
	Mostrar como se enlaza un socket con un host y un puerto dado por medio del metodo socket.bind
	python server-01.py

server-02.py
	Mostrar como funcionan los comandos socket.listen() y socket.accept() funcionan
	python server-02.py

server-03.py
	Mostrar como deberí­a un servidor recibir una conexión y replicar al cliente.
	python server-03.py

server-04.py
	Mostrar como se puede crear un servidor con hilos para que corra infinitamente.
	python server-04.py

server-05.py
	Mostrar como se crean servidores en multihilos para que se puedan conectar clientes de manera simultanea.
	python server-05.py

echo-server.py:
	tiene como proposito escuchar a un cliente y enviarle de regreso los datos por este enviados.
	python echo-server.py --port x/x=numeroDelPuerto

echo-client.py:
	Mostrar como el cliente envia un mensaje al servidor y como lo recibe de vuelta.
	python echo-client.py --port x/x=numeroDelPuerto

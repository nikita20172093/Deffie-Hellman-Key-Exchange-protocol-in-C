# Deffie-Hellman-Key-Exchange-protocol-in-C

Flow goes from client to server.(client sends encrypted file and server receives and decrypt the same.)

server side command to execute:
compile:	gcc -o s server.c
run	   :    ./s <ip_address> <port_no> <destination_filename>

client side command to execute:
compile:	gcc -o c client.c -lm
run	   :    ./c <ip_address_of_server> <port_no_of_server> <source_filename>

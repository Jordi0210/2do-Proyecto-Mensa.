# 2do-Proyecto-Mensa.
Funcionamiento del código:

El servidor (ChatServer) se ejecuta en una consola o en NetBeans y espera conexiones en un puerto específico (por defecto, el puerto 12345).
Los clientes (ChatClient) se ejecutan en consolas separadas o en NetBeans y se conectan al servidor.
Los clientes ingresan un nickname o apodo para identificarse en el chat.
Una vez conectados, los clientes pueden enviar mensajes de texto al chat.
Los mensajes enviados por los clientes se transmiten a todos los demás clientes conectados, y se muestra en las consolas de los demás clientes, junto con el nickname del remitente y la hora del mensaje.
Los clientes también tienen la opción de enviar archivos al chat utilizando el comando "/file" seguido de la ruta del archivo en su sistema.
Cuando un cliente envía un archivo, se transmite a todos los demás clientes conectados, y se muestra un mensaje en el chat indicando el nombre del archivo, el remitente y la hora de envío.
La conversación en el chat (sin los archivos) se guarda en un archivo de texto llamado "conversation.txt" en el directorio del servidor.
Comandos disponibles:

Comando para enviar mensajes de texto: Los clientes pueden simplemente escribir su mensaje en la consola y presionar Enter. El mensaje se enviará a todos los demás clientes conectados.
Comando para enviar archivos: Los clientes pueden usar el comando "/file" seguido de la ruta del archivo que desean enviar. Por ejemplo: "/file C:\ruta\hacia\archivo.txt". Esto enviará el archivo al chat y será recibido por los demás clientes.
Comando de salida: Para salir del chat, los clientes pueden escribir el comando "/exit" en la consola. Esto cerrará la conexión con el servidor y finalizará el cliente.


NOTA: En este proyecto por la version del netbeans en una linea de codigo me sale error, ya que el codigo esta hecho en la computadora de mi compañero y es otra version del netbeans"APACHE"

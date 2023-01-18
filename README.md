# Sistema-de-Chat-usando-protocolo-UDP 

O trabalho consiste em desenvolver um servidor de Chat usando a linguagem Python para o controle e distribuição de todos de mensagens a todos os membros da sala de batepapo. Com isso, o software deverá implementar as seguintes mensagens:

Mensagem de comunicação do cliente para o servidor:

Conectar ao servidor de Chat: "conectar,nomeUsuario"

Enviar mensagem: "enviarMensagem,nomeUsuario,mensagem"

Mensagem de comunicação do servidor para o cliente:

Mensagem recebida do servidor: "nomeUsuario,mensagem". 

O servidor deverá registrar o pedido de "conectar" de cada cliente, assim o servidor terá identificado pela tupla (ip,porta) o novo membro participante do chat.

Toda mensagem oriunda de um cliente, o servidor deverá encaminhar a mensagem para todos os membros participantes do chat com exceção do cliente em questão. 

Para o lado servidor, deverá ser criado um programa em Python com o nome server_chat_udp.py .

Para o lado cliente, deverá ser criado um programa em Python com o nome cliente_chat_udp.py. 

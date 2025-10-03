#scoketchat-java

Este é um projeto em Java que implementa um chat simples utilizando sockets, permitindo comunicação em tempo real entre cliente e servidor.

#Descrição

O SocketChat Java é uma aplicação de chat baseada em sockets, desenvolvida para fins educacionais e para demonstrar os conceitos de comunicação em rede utilizando Java. O projeto é composto por duas partes principais:

Servidor: Responsável por gerenciar as conexões dos clientes e encaminhar as mensagens entre eles.

Cliente: Interface de linha de comando que permite ao usuário enviar e receber mensagens em tempo real.

#Tecnologias Utilizadas

Java 17 ou superior

Sockets TCP/IP

#Como Executar
1. Clonar o repositório
    git clone https://github.com/miguelrcha/socketchat-java.git
    cd socketchat-java

2. Compilar o código
    javac -d bin src/com/socket/*.java

3. Executar o servidor
    java -cp bin com.socket.Server

4. Executar o cliente
    java -cp bin com.socket.Client

#Como Funciona

O servidor escuta por conexões na porta 12345.

Os clientes se conectam ao servidor e podem enviar mensagens que serão retransmitidas para todos os outros clientes conectados.

O cliente possui uma interface simples de linha de comando para enviar e receber mensagens.

#Suporte

Para dúvidas ou problemas, abra uma issue no GitHub ou entre em contato comigo. Este projeto ainda esta em desenvolvimento!
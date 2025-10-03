# SocketChat-Java

SocketChat-Java é um projeto em Java que implementa um chat simples utilizando sockets, permitindo comunicação em tempo real entre clientes e servidor.

---

## Descrição

O SocketChat Java é uma aplicação educacional que demonstra conceitos de comunicação em rede usando Java. O projeto é composto por duas partes principais:

- **Servidor:** Gerencia as conexões dos clientes e encaminha as mensagens entre eles.  
- **Cliente:** Interface de linha de comando que permite enviar e receber mensagens em tempo real.

---

## Tecnologias Utilizadas

- Java 17 ou superior  
- Sockets TCP/IP  

---

## Como Executar

1. **Clonar o repositório**  
```bash
git clone https://github.com/miguelrcha/socketchat-java.git
cd socketchat-java
```
2. **Compilar o código**
```bash
javac -d bin src/com/socket/*.java
```

3. **Executar o servidor**
```bash
java -cp bin com.socket.Server
```
3. **Executar o cliente**
```bash
java -cp bin com.socket.Client
```

---

## Como Funciona

O servidor escuta conexões na porta 12345.

Os clientes se conectam ao servidor e podem enviar mensagens que serão retransmitidas para todos os outros clientes conectados.

O cliente possui uma interface de linha de comando simples para envio e recepção de mensagens.

---

## Suporte

Para dúvidas ou problemas, abra uma issue no GitHub ou entre em contato comigo. Este projeto ainda esta em desenvolvimento!
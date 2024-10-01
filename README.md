# Comunicação Cliente-Servidor Simples

Este projeto implementa um modelo básico de comunicação entre um cliente e um servidor utilizando sockets. O servidor escuta uma porta específica e aguarda conexões. Quando um cliente se conecta, ele envia uma mensagem ao servidor, que a recebe e a exibe. O projeto ilustra a configuração de sockets, a aceitação de conexões e a troca de mensagens, proporcionando uma introdução prática à programação de rede.

## Estrutura do Código:

### Classes:

- **Client:** Conecta-se ao servidor, envia uma mensagem e encerra a conexão.
- **Server:** Escuta conexões na porta especificada, aceita um cliente e lê a mensagem.

## Técnicas Utilizadas:

- **Sockets:** Comunicação entre cliente e servidor.
- **Entrada/Saída:** Manipulação de PrintStream e Scanner.
- **Tratamento de Erros:** Gerenciamento de exceções.

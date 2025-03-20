# Chat TCP em Python

Este projeto implementa um simples chat utilizando sockets TCP em Python. O servidor gerencia múltiplos clientes e permite que eles troquem mensagens em tempo real.

![image](https://github.com/user-attachments/assets/87b2a879-5501-4039-b354-c89dcff707bb)


## Estrutura do Projeto

- `main.py` → Código do servidor
- `client.py` → Código do cliente

## Como Executar

### Iniciar o Servidor

Execute o seguinte comando para iniciar o servidor:
```bash
python main.py
```
O servidor ficará escutando conexões na porta `55555`.

### Conectar um Cliente

Em outro terminal, execute:
```bash
python client.py
```
Será solicitado um apelido (nickname). Após inserir, o cliente se conectará ao chat.

Você pode abrir múltiplos terminais para testar vários clientes simultaneamente.

## Funcionamento

### Servidor (`main.py`)
- Aceita conexões de clientes.
- Gerencia apelidos.
- Envia mensagens para todos os clientes conectados.
- Remove clientes desconectados.

### Cliente (`client.py`)
- Conecta-se ao servidor.
- Envia e recebe mensagens.
- Lida com erros de conexão.

## Contribuição 
Este projeto tem como objetivo aprimorar meus conhecimentos de redes, então pode haver melhorias! Se tiver sugestões pode realizar um pull request ou issue



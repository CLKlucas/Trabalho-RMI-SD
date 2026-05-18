# Topcar - Trabalho 2 RMI

Projeto da disciplina de Sistemas Distribuidos usando Java RMI Realizado Por Lucas Gomes e Carlos Daniel.

A aplicacao simula um sistema simples de pecas automotivas. O cliente envia requisicoes para o servidor, e o servidor responde com os dados solicitados.

A parte do RMI esta em:

```text
src/main/java/br/com/topcar/rmi
```

Principais operacoes implementadas:

- listar pecas;
- buscar uma peca;
- cadastrar cliente;
- criar pedido;
- calcular total de pedido;
- consultar cliente.

As mensagens de requisicao e resposta sao enviadas em `byte[]` usando JSON como representacao dos dados.



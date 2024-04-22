# Sistema Bancário em Python

## Desafio: Criando um sistema bancário

### Objetivo Geral

O objetivo deste projeto é criar um sistema bancário com as operações de depósito, saque e visualização de extrato.

### Desafio

Fomos contratados por um grande banco para desenvolver o seu novo sistema utilizando a linguagem Python. Para a primeira versão do sistema, devemos implementar apenas três operações: depósito, saque e extrato.

### Operação de Depósito

Nesta operação, o usuário pode depositar valores positivos em sua conta bancária. A versão inicial do projeto trabalha apenas com um usuário, portanto, não é necessário identificar o número da agência e conta bancária. Todos os depósitos são armazenados em uma variável e exibidos na operação de extrato.

### Operação de Saque

O sistema permite realizar até três saques diários, com um limite máximo de R$ 500,00 por saque. Caso o usuário não tenha saldo em conta, o sistema exibirá uma mensagem informando que não será possível sacar o dinheiro devido à falta de saldo. Todos os saques são armazenados em uma variável e exibidos na operação de extrato.

### Operação de Extrato

Esta operação lista todos os depósitos e saques realizados na conta. No final da listagem, é exibido o saldo atual da conta. Se o extrato estiver em branco, será exibida a mensagem: "Não foram realizadas movimentações".

Os valores são exibidos utilizando o formato R$ xxx.xx, por exemplo:
- 1500.45 = R$ 1500.45

---

Este projeto foi desenvolvido como parte de um desafio em Python. Sinta-se à vontade para contribuir, sugerir melhorias ou utilizar conforme necessário.

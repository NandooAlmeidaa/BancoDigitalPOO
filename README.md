# Sistema Bancário em Java

Este é um projeto simples de um sistema bancário orientado a objetos desenvolvido em Java. Ele simula operações básicas como criação de contas, depósitos, saques e transferências entre contas correntes e contas poupança.

## :bank: Funcionalidades

- Cadastro de clientes.
- Criação de contas correntes e poupança.
- Depósito em conta.
- Saque com verificação de saldo.
- Transferência entre contas.
- Impressão de extrato bancário.

## :books: Estrutura do Projeto

O projeto é composto pelas seguintes classes:

- `Main.java`: classe principal que executa o sistema.
- `Banco.java`: representa o banco, armazenando uma lista de contas.
- `Cliente.java`: representa o cliente, com nome e referência à conta.
- `Conta.java`: classe abstrata base para os tipos de conta.
- `ContaCorrente.java`: implementação de conta corrente.
- `ContaPoupanca.java`: implementação de conta poupança.
- `IConta.java`: interface que define operações bancárias básicas (sacar, depositar, transferir, imprimir extrato).

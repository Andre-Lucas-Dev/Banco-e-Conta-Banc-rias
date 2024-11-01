Este projeto é uma aplicação bancária simples desenvolvida em Java, que demonstra o uso de POO (Programação Orientada a Objetos). A aplicação permite a criação de diferentes tipos de contas bancárias, depósitos, saques e a busca por contas existentes.

Funcionalidades
Criar contas bancárias de diferentes tipos:
Conta Padrão
Conta com Limite
Conta Especial
Conta de Estudante
Conta Poupança
Depositar valores nas contas.
Sacar valores das contas, com tratamento de exceções para saques inválidos.
Buscar contas pelo número da conta.
Estrutura do Projeto
Banco: Classe principal que gerencia as contas bancárias.
Conta: Classe base que define a estrutura de uma conta bancária.
ContaFactory: Classe responsável por criar instâncias de diferentes tipos de contas.
Tipos de Conta: Classes que herdam de Conta, representando os diferentes tipos de conta (e.g., ContaPadrao, ContaComLimite, ContaEspecial, ContaDeEstudante, ContaPoupanca).

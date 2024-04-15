# Sistema Bancário Simples

Este é um sistema bancário simples implementado em Python. Ele permite que os usuários realizem operações básicas, como depositar, sacar e verificar o extrato da conta.

## Funcionalidades

- **Depositar:** Os usuários podem depositar dinheiro em sua conta.
- **Sacar:** Os usuários podem sacar dinheiro de sua conta, desde que tenham saldo disponível e não excedam o limite de saques.
- **Extrato:** Os usuários podem visualizar o extrato de suas transações, incluindo depósitos e saques.
- **Sair:** Os usuários podem sair do sistema.

## Instruções de Uso

1. Execute o arquivo `sistema_bancario.py` em um ambiente Python.
2. O programa exibirá um menu com as opções disponíveis.
3. Selecione a operação desejada digitando a letra correspondente.
4. Siga as instruções para concluir a operação escolhida.
5. Repita o processo conforme necessário ou selecione "q" para sair do programa.

## Estrutura do Código

O código é dividido em funções para cada funcionalidade:

- **`depositar(saldo, extrato)`:** Realiza um depósito na conta.
- **`sacar(saldo, extrato, limite, numero_saques, LIMITE_SAQUES)`:** Realiza um saque na conta.
- **`ver_extrato(saldo, extrato)`:** Exibe o extrato da conta.
- **Loop principal:** O loop principal do programa exibe o menu de opções e chama as funções correspondentes de acordo com a escolha do usuário.

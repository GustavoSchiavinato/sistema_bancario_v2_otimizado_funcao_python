# Sistema Bancário V2 Python Otimizado Com Funções

## Obejtivo Geral
Separar as funções existentes de saque, depósitos e extratos em funções. Criar duas novas funções: cadastrar usuário (cliente) e cadastrar conta bancária.

## Desafio
Precisamos deixar nosso código mais modularizado, para isso vamos criar funções para as operações existentes: sacar, despositar e visiualizar histórico. Além disso, para a versão 2 do nosso sistema precisamos criar duas novas funções: criar usuário (cliente do banco) e criar conta corrente (vincular com usuário).

## Separação em Funções
Devemos criar funções para todas as operações do sistema. Cada função vai ter uma regra na passagem de argumentos. O retorno e forma como serão chamados.

## Saque
A função saque deve receber os argumentos apenas por nome (keyworld only). Sugestão de argumentos: saldo, valor, extrato, limite, numero_saques, limite_saques. Sugestão de retorno: saldo e extrato.

## Depósito
A função depósito deve receber os argumentos apenas por posição (positional only). Sugestão de argumentos: saldo, valor, extratos. Sugestão de retorno: saldo e extrato.

## Extrato
A função extrato de receber os argumentos por posição e nome (positional only e keyworld only). Argumentos posicionais: saldo, argumentos nomeados: extrato.

## Novas Funções
Precisamos criar duas novas funções: criar usuário e criar conta corrente.

## Criar Usuário (Cliente)
O programa deve armazenar os usuários em uma lista, um usuário é composto por nome: nome, data de nascimento, CPF e endereço. O endereço é uma string com o formato: logradouro - número - ciade/sigla estado. Deve ser armazenado somente os numeros do CPF. Não podemos cadastrar 2 usuários com o mesmo CPF.

## Criar Conta Corrente
O programa deve armazenar contas em um lista, uma conta é composta por: agência, número da conta e usuário. O número da conta é sequencial, iniciando em 1. O número da agência é fixo: "0001". O usuário pode ter mais de uma conta, mas uma conta pertence a somente um usuário.

## Dica
Para vincular um usuário a um conta, filtre a lista de usuários buscando o número de CPF informado para cada usuário da lista.

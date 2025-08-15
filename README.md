
**Cenários de Testes**


Validação de login

Validar Login Com Sucesso
Dado que estou na Tela de login
E possuo usuário e senha válidos
Quando insiro as credenciais válidas
E Clico em Entrar
Então deve realizar Login com Sucesso
E Exibir tela de Boas Vindas ao Usuário

Validar Login Invalido
Dado que estou na Tela de login
E não possuo usuário e senha válidos
Quando insiro as credenciais inválidas
E Clico em Entrar
Então deve realizar tentativa de Login sem Sucesso
E Exibir Feedback abaixo dos campos com a mensagem "Usuário ou senha inválidos"

Item no Carrinho

Validar Adicionar Iten Na Sacola Com Sucesso
Dado que realizei Logim com usuário e senha válidos
E estou na tela de Carrinho
E Busco um item pelo nome
E Seleciono o tamanho desejado
E Clico em Adicionar a Sacola
Quando visualizo a sacola
Então deve conter o item na Sacola

--------------------------------

Este projeto busca validar um cenário de login inválido, validando o comportamento desejado do sistemas e um fluxo de login com sucesso.
Possui um cenario onde é adicionado e validado se o item consta no carrinho
Comentei algumas linhas com a sua funcionalidade, não coloquei em todos os cenários testes, mas somente para exemplificar.
Como solicitado, oloquei uma função do próprio maestro que faz um video quando todos os testes são realizados.
Os cenários estão separados por Suites conforme suas funcionalidades.

para executar os testes realizar o seguinte comando:  "maestro -host <ipv4dolocal> test Tests/'suite_deseja_executar'



# atividade-avaliativa 
# desenvolvido pelos alunos do 2° semestre da faculdade anhanguera Rychard eduardo da silva santos & Wesley de almeida silva

Este projeto é um sistema simples de gerenciamento de estoque em Python, com autenticação básica e operações CRUD (Criar, Ler, Atualizar, Deletar) para produtos.

 Funcionalidades
1. Autenticação de Usuário
    Usuário padrão: admin
    Senha padrão: 1234
    Função: autenticar()

2. Gerenciamento de Estoque
    Classe principal: Estoque
    Operações disponíveis:
    Visualizar estoque atual
    Adicionar novo produto
    Atualizar quantidade de um produto
    Pesquisar produto pelo nome
    Gerar relatório de produtos
    Remover produto do estoque

3.Classe Produto
Armazena informações do produto:
Nome
Quantidade
Valor unitário
Calcula o valor total do produto (quantidade × valor unitário)


4.Estrutura do Código

funcoes.py
autenticar(): Função para login.
Produto: Classe que representa um produto.
Estoque: Classe que gerencia os produtos.

main.py
Menu interativo para o usuário escolher as operações.


5. Como Executar

5.1  Certifique-se de ter o Python instalado.
5.2  Salve os arquivos:
    funcoes.py (com as classes e funções)
    main.py (com o menu principal)

6.  Faça login com:
Usuário: admin
Senha: 1234



7. Exemplo de Uso

Adicionar produto:
Nome: Caneta
Quantidade: 100
Valor: 1.50

Visualizar estoque:
        Cód: 1 | Caneta - Quantidade: 100 - R$ 1.50

Relatório:
Total de itens
Valor total do estoque
Produto mais caro/barato
Produto com maior/menor quantidade



Observações Importantes

O código não possui persistência (os dados são perdidos ao fechar o programa).
Para melhorar, pode-se implementar:
Salvamento em arquivo (JSON, CSV)
Interface gráfica Controle de usuários

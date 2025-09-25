## 🛒 Gerenciador de Lista de Compras (e-Wish List) em JavaScript
Este projeto é um gerenciador de lista de compras simples e interativo, construído com JavaScript e executado via linha de comando. Ele permite que o usuário adicione itens, especifique o preço e a quantidade, e calcule o valor total da lista.

## ✨ Funcionalidades Principais
- Adicionar Produtos: Permite ao usuário inserir o nome, preço e quantidade de um novo item na lista.
- Listar Produtos: Exibe todos os itens adicionados, mostrando nome, preço unitário, quantidade e o cálculo do preço total da lista.
- Calcular Total: Calcula e exibe o valor final somando todos os itens e suas respectivas quantidades.
- Menu Interativo: Utiliza o pacote prompt-sync para rodar um menu contínuo no terminal até que o usuário escolha sair.

## 🛠️ Estrutura do Código
- O código utiliza funções simples e métodos de array para gerenciar os dados.
- const produtos = []: Array central que armazena os objetos de produto.
- adicionarItem(): Função que recebe o nome, preço e quantidade e utiliza o método .push() para adicionar o novo objeto ao array.
- listarItens(): Função que utiliza o método .forEach() para iterar sobre o array e o for para calcular o valor total.
- menuPrincipal(): Função principal que gerencia o fluxo de execução com um loop while (true) e recebe a entrada do usuário através do prompt.

## ⚙️ Como Rodar o Projeto
Este projeto requer o Node.js e o pacote prompt-sync instalado.

### Instalar Dependências:
Abra seu terminal na pasta do projeto e instale a dependência necessária:

Bash

``npm install prompt-sync``

Executar o Script:

``Salve o código em um arquivo .js (ex: wishlist.js) e execute-o com o Node.js:``

Bash

`node wishlist.js`

## 🖥️ Exemplo de Interação
Ao executar, o programa inicia o menu e aguarda a entrada do usuário:

```---------e-Wish List, seja Bem vindo!---------

--- MENU DE OPÇÕES ---
1. Adicionar produtos: 
2. Listar produtos
3. Sair
----------------------
Escolha uma opção: 1
Qual item deseja adicionar? Café
Digite o preço do produto: 15.50
Digite a quantidade do produto: 2
Café adicionado à lista.
...
Escolha uma opção: 2
---Aqui está sua e-Wish List:----- 
- 1. Café - R$ 15.50 - Quantidade: 2
Valor total da lista: R$ 31.00```

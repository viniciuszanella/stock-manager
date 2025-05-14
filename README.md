# StockManager 🛒

Um sistema simples de gerenciamento de estoque desenvolvido em Java, operado via linha de comando. Este projeto demonstra conceitos básicos de Programação Orientada a Objetos (POO), manipulação de coleções e entrada/saída de dados no console.

## ✨ Funcionalidades

*   **Cadastrar Produtos:** Adicione novos produtos ao estoque, escolhendo entre:
    *   Eletrônicos (com marca e tempo de garantia em meses)
    *   Roupas (com tamanho e material)
    *   Alimentos (com data de validade e categoria)
*   **Editar Produtos:** Modifique informações de produtos existentes (nome, preço e atributos específicos de cada tipo).
*   **Excluir Produtos:** Remova produtos do estoque utilizando o código do produto.
*   **Listar Produtos:** Visualize todos os produtos cadastrados com seus respectivos detalhes.

## 🛠️ Tecnologias Utilizadas

*   **Java:** Linguagem principal do projeto.
*   **Programação Orientada a Objetos (POO):**
    *   **Classes e Objetos:** `Produto`, `Eletronico`, `Roupa`, `Alimento`.
    *   **Herança:** `Eletronico`, `Roupa` e `Alimento` herdam da classe base `Produto`.
    *   **Polimorfismo:** Utilizado no método `exibir_informacoes()`, que se comporta de maneira diferente para cada tipo de produto.
*   **`java.util.Scanner`:** Para leitura de dados de entrada do usuário via console.
*   **`java.util.ArrayList`:** Para armazenamento dos produtos em memória durante a execução do programa.
*   **`java.time.LocalDate`:** Para manipulação de datas (utilizado na data de validade dos alimentos).

## 💡 Possíveis Melhorias Futuras

*   Persistência de dados (ex: salvar e carregar produtos de um arquivo CSV, TXT, JSON ou um banco de dados simples como MySQL; atualmente utilizando ArrayList).
*   Implementação de uma funcionalidade de busca/filtro de produtos.
*   Interface gráfica de usuário

## 👨‍💻 Autor

Vinícius Zanella
* [@viniciuszanella](https://github.com/viniciuszanella)

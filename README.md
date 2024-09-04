# API dados Meu Portifólio.

Projeto de prática da aula DIO sobre contribuições no GitHub. O arquivo está em db.json e você pode contribuir para melhorar, praticar e estudar junto comigo.

## Siga os padões de commit para contribuir aqui no GitHub.

| Element   | Texto       |
| :---------- | :--------- |
| `#feat:` | `Cria um novo recurso no código.` |
| `#fix:` | `Corrige um bug no código.` |
| `#style:` | `Mudanças que não afetam o significado do código`**(espaço em branco, formatação falta de ponto-e-vírgula, etc)** |
| `#refactor:` | `Uma alteração que não corrige um bug, nem adiciona um novo recurso.` |
| `#test:` | `Adicionando testes ausentes ou corrigindo testes existentes.` |
| `#docs:` | `Apenas a documentação.` |
| `#chore:` | `Alterações no processo de compilação ou ferramentas e bibliotecas auxiliares, como geração de documentação.` |
| `#perf:` | `Mudança de Código que melhora performance.` |
| `#build:` | `#build: Alterações que afetam o sistema de compilação ou dependências externas (npm, gulp, broccoli).` |






#build: Alterações que afetam o sistema de compilação ou dependências externas (npm, gulp, broccoli).


## Documentação da API

#### Retorna todos os itens

```http
  GET /api/items
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | **Obrigatório**. A chave da sua API |

#### Retorna um item

```http
  GET /api/items/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |

#### add(num1, num2)

Recebe dois números e retorna a sua soma.


## Referência

 - [Trabalhando com JSON - developer.mozilla.org](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Objects/JSON)
 - [Guia Markdown - markdownguide.org/](https://www.markdownguide.org/)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)



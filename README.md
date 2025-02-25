# Mensagens de Commit Semântico
Fazer commits de forma semântica melhora a organização do projeto.

O seguinte formato pode ser utilizado:

```<tipo>(<escopo>): <mensagem do commit>```

```<escopo>``` é opcional. Alguns exemplo de escopo: api, config, init, etc.

### Exemplo:

~~~git
git commit -m "feat(api): enviar um e-mail ao cliente quando a obra for atualizada."
                |    |        |
                |    |        +----> resumo do commit
                |    +-------------> escopo
                +-----------------> tipo: feat, fix, docs, style, refactor, test, chore
~~~~

---

### Tipos:

- ```feat```: novo recurso no sistema. Exemplo: adicionar um novo endpoint em uma API
- ```fix```: correção de um bug
- ```docs```: mudanças na documentação
- ```style```: formatação/estilo de código, adição de ponto e vírgula
- ```refactor```: refatoração do código. Visando melhorando a organização, deixando o código mais limpo, reutilizável, eficiente. E que pode mudar a estrutura geral. Em resumo, alterações para reorganizar o código para melhorar sua estrutura.
- ```test```: adição ou refatoração de testes
- ```chore```: alterações que não influenciam o sistema ou os testes. Exemplo: Adicionar algo no .gitignore
- ```cleanup```: Remoção de espaços, comentários e variáveis não utilizadas
- ```remove```: remover código desnecessário sem mudar a estrutura geral

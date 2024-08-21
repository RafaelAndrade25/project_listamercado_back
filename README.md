Desenvolvimento de aplicação nível Junior

- API para o Back and - Java com Spring Boot
- Modelar o banco de dados
- Trabalhar um Front End - Web App mobile / PWA → Responsividade / Bootstrap → Framework Angular
- Deploy → Perfis de Testes → Deploy Automatizado(CI/CD) com ações do github → Containers
    - Gerenciamento Individualizado → Composição
- Testes Automatizados → Requisitos e casos de uso
- Gerenciar tudo através de GIT

---

## Definição das Regras de Negócio

### Sistema lista de mercado

- Ser capaz de gerenciar várias listas de mercado(e marcar seu status como concluída ou não)
- Ser capaz de cadastrar produtos e consulta-los
- Ser capaz de incluir produtos nas listas e especificar suas quantidades, bem como marcar se o produto já foi comprado
- Ser capaz de atribuir valores aos itens comprados, para depois ter uma gestão dos custos da lista
- Ser capaz de adicionar quantidades(kg,unidades, litros, etc.)

---

### Casos de Uso

- Cadastrar produtos
    - Informar o nome de um determinado produto e o sistema armazenar no banco
- Consultar produtos
    - Informar palavras chaves para consultar ou mesmo buscar produtos a partir de uma lista
- Alterar dados de produtos
    - Basicamente alterar o nome dos produtos e termos sua efetivação no banco de dados
- Criação uma nova lista
    - Criar uma nova lista inserindo a data e olocal onde foi feita a compra(nome do supermercado / feira, etc)
- Apagar uma lista
    - Remover uma lista que foi criada por engano e remover todos os seus itens que foram criados
- Inserção de itens na lista
    - Criar um item associando a uma lista e a um produto, bnem como deixar possível modificar quantidade e preço do que foi pago
- Alteração de itens da lista
    - Alterar apenas quantidade, preço pago e status
- Remoção de itens da lista
    - Poder remover um item que foi cadastrado na lista
- Fechamento da lista
    - Concluir a lista como sendo completa e gerar seu custo total a partir dos itens comprados

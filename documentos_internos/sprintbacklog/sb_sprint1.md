# Sprint Backlog

## Primeira Sprint

| ID | User Story | Critérios de Aceitação | Tarefas Frontend | Tarefas Backend | Status |
|----|------------|------------------------|------------------|-----------------|--------|
| 1  | Eu, como administrador, quero poder cadastrar um projeto novo. | O projeto deve ser cadastrado com nome, descrição e demais detalhes; o sistema deve exibir uma mensagem de sucesso após o cadastro; o projeto cadastrado deve aparecer na lista de projetos. | Criar o formulário de cadastro de projetos, validar os campos no frontend antes de enviar, implementar feedback visual de sucesso ou erro. | Implementar o endpoint para criação de projetos, validar os campos obrigatórios no servidor, garantir o retorno de sucesso ou erro. | ✅ |
| 2  | Eu, como administrador, quero poder fazer login no site. | O administrador deve poder fazer login com e-mail e senha; erros de login devem ser tratados; o sistema deve manter a sessão do administrador. | Criar o formulário de login, implementar a validação de campos, exibir mensagens de erro adequadas. | Implementar o endpoint de login, validar as credenciais, gerenciar a sessão do administrador. | ✅ |

---
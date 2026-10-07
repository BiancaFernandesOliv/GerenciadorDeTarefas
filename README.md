# Gerenciador de Tarefas

Projeto pessoal de um sistema de gerenciamento de tarefas, desenvolvido com o objetivo de praticar e evoluir conhecimentos em desenvolvimento Backend com .NET e, futuramente, integração com Angular.

O projeto está em desenvolvimento e será ampliado gradualmente com novas funcionalidades.

## 🚧 Status do projeto

Em desenvolvimento.

Atualmente, o projeto possui a estrutura inicial da API e as funcionalidades relacionadas ao gerenciamento de usuários.

## 🛠️ Tecnologias utilizadas

### Backend
- C#
- .NET
- ASP.NET Core Web API
- Entity Framework Core
- SQLite
- Swagger
- REST API

### Frontend
- Angular *(planejado)*

## 📌 Funcionalidades atuais

- [x] Estrutura inicial da API
- [x] Configuração do Entity Framework Core
- [x] Banco de dados SQLite
- [x] Migrations
- [x] Entidade de usuário
- [x] Cadastro de usuário
- [x] Consulta de usuários
- [x] Atualização de usuário
- [x] Exclusão de usuário
- [x] Validação dos dados
- [x] Validação de e-mail
- [x] Prevenção de e-mails duplicados
- [x] DTOs
- [x] Respostas padronizadas da API
- [x] Swagger
- [x] Configuração de CORS

## 🔮 Próximos passos

O projeto será evoluído gradualmente. Entre as funcionalidades planejadas estão:

- [ ] Implementar CRUD de tarefas
- [ ] Implementar conclusão de tarefas
- [ ] Desenvolver o frontend em Angular
- [ ] Integrar Angular com a API
- [ ] Implementar autenticação
- [ ] Adicionar testes
- [ ] Melhorar a documentação do projeto
- [ ] Publicar a aplicação

## 📂 Estrutura do projeto

```text
GerenciadorDeTarefas/
│
├── Backend/
│   └── SistemaGerenciamentoTarefas.API/
│       ├── Controllers/
│       ├── Data/
│       ├── DTOs/
│       ├── Enums/
│       ├── Migrations/
│       ├── Models/
│       ├── Repositories/
│       └── Services/
│
└── Frontend/

```

## 🗄️ Banco de dados

O projeto utiliza SQLite e Entity Framework Core.

O arquivo do banco de dados não é versionado no Git. O banco pode ser recriado através das migrations do projeto.

## ▶️ Como executar

### Pré-requisitos

- .NET SDK instalado
- Visual Studio ou outra IDE compatível com .NET

### Backend

Clone o repositório:

```bash
git clone https://github.com/BiancaFernandesOliv/GerenciadorDeTarefas.git
```

Acesse a pasta do projeto:

```bash
cd GerenciadorDeTarefas
```

Entre na pasta da API:

```bash
cd Backend/SistemaGerenciamentoTarefas.API
```

Restaure as dependências:

```bash
dotnet restore
```

Crie/atualize o banco através das migrations:

```bash
dotnet ef database update
```

Execute a API:

```bash
dotnet run
```

A documentação da API estará disponível através do Swagger.

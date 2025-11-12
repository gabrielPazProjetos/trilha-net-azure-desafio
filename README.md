--- Desafio DIO: Sistema de Cadastro de Funcionários
Este projeto foi desenvolvido como parte do bootcamp da DIO, com o objetivo de construir uma API REST para cadastro de funcionários, utilizando ASP.NET Core e hospedagem na nuvem Azure. ( Editando o //TODO)

--- Tecnologias Utilizadas
- ASP.NET Core 6
- Entity Framework Core
- Azure SQL Database
- Azure Table Storage
- Swagger

--- Funcionalidades
- POST /Funcionario → Cria um novo funcionário
- GET /Funcionario/{id} → Consulta funcionário por ID
- PUT /Funcionario/{id} → Atualiza dados do funcionário
- DELETE /Funcionario/{id} → Remove funcionário
- Cada operação registra um log no Azure Table Storage via a entidade FuncionarioLog.

--- Testes
x Testado localmente via Swagger 
x Dados persistidos no SQL Server 
x Logs registrados no Azure Table Storage

--- Observações
A publicação na Azure é opcional. Este projeto foi testado e validado localmente com sucesso para fins didaticos.

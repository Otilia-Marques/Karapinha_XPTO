# Karapimha XPTO by Otilia Marques - Sistema de Gestão de Salão de Beleza

Bem-vindo ao sistema de gestão de salão de beleza Karapimha XPTO! 
Este sistema foi desenvolvido para facilitar a gestão de serviços, clientes e agendamentos em um salão de beleza. 
O objetivo é proporcionar uma ferramenta eficiente e intuitiva para gerenciar operações diárias e melhorar a experiência dos clientes.
Podem ser feitas as seguintes funções: Agendar os serviços / tratamentos e ver seus respectivos preços, contactos e outras 
informações que acham relevantes.

## Funcionalidades

- **Gestão de Serviços**: Adicionar, editar e remover serviços oferecidos pelo salão.
- **Gestão de Clientes**: Adicionar, editar e remover informações de clientes.
- **Agendamentos**: Criar e gerenciar agendamentos de clientes.
- **Relatórios**: Gerar relatórios de serviços, clientes e agendamentos.
- **Notificações**: Enviar notificações de lembrete para clientes.

## Tecnologias Utilizadas

### Frontend

- **Framework**: Angular 17
- **Linguagens**: HTML, CSS, TypeScript
- **Ferramentas de Build**: Angular CLI

### Backend

- **Linguagem de Programação**: C#
- **Framework**: ASP.NET Framework
- **IDE**: Visual Studio

### Banco de Dados

- **Sistema de Gerenciamento de Banco de Dados**: SQL Server

## Pré-requisitos

Para executar este projeto, você precisará ter instalado:

- Node.js e npm
- Angular CLI
- .NET Framework 4.7 ou superior
- SQL Server
- Visual Studio 2019 ou superior

## Configuração do Projeto

### Frontend

1. Clone o repositório:
   No terminal bash : 
   git clone https://github.com/seu-usuario/karapimha-xpto.git
   cd karapimha-xpto/frontend
  

2. Instale as dependências:
   No terminal bash : 
   npm install
  

3. Execute o servidor de desenvolvimento:
   No terminal bash : 
   ng serve
   

4. Abra o navegador e acesse `http://localhost:4200`.

### Backend

1. Abra o projeto no Visual Studio:
   No terminal bash : 
   cd ../backend
   

2. Configure a conexão com o banco de dados no `appsettings.json`:
   ```json
   {
     "ConnectionStrings": {
       "DefaultConnection": "Server=seu-servidor;Database=karapimha-xpto;User Id=seu-usuario;Password=sua-senha;"
     }
   }
   ```

3. Execute o projeto no Visual Studio (pressione F5 ou clique em "Run").

### Banco de Dados

1. Crie o banco de dados no SQL Server:
   ```sql
   CREATE DATABASE karapimha_xpto;
   ```

2. Execute as migrações para configurar o esquema do banco de dados.

## Estrutura do Projeto

- **Frontend**:
  - `src/` - Código-fonte do frontend (componentes, serviços, etc.)
- **Backend**:
  - `Controllers/` - Controladores da API
  - `Models/` - Modelos de dados
  - `Services/` - Serviços de negócios
  - `appsettings.json` - Configurações do aplicativo (incluindo cadeia de conexão)

## Uso

1. Inicie o servidor backend no Visual Studio.
2. Inicie o servidor frontend com Angular CLI.
3. Navegue pelos menus para gerenciar serviços, clientes e agendamentos.
4. Utilize as funcionalidades de relatórios e notificações conforme necessário.



*Desenvolvido por Otilia Marques* - *2024*


Obs: Certifique-se de substituir os espaços reservados (`seu-usuario`, `seu-servidor`, `sua-senha`, etc.) com as informações reais.

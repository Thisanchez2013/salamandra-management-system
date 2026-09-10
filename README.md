# Salamandra Management System

Sistema desktop de gestão desenvolvido em **Java, JavaFX e PostgreSQL** para a **Salamandra**, uma empresa do segmento de incensaria.

O projeto surgiu como parte de um projeto acadêmico do curso de **Análise e Desenvolvimento de Sistemas**, a partir da necessidade de desenvolver uma solução para um negócio real. A proposta foi transformar necessidades da empresa em funcionalidades de software, trabalhando desde a estruturação do banco de dados até o desenvolvimento das interfaces e regras da aplicação.

## 🚀 Funcionalidades

O sistema centraliza diferentes operações da empresa, incluindo:

* 👥 Cadastro e gerenciamento de clientes
* 📦 Cadastro e gerenciamento de produtos
* 📊 Controle de estoque
* 🛒 Registro e gerenciamento de vendas
* 📈 Dashboard com indicadores
* 📑 Relatórios gerenciais
* 🔐 Autenticação de usuários
* 👤 Controle de permissões
* 🌐 Acesso ao banco de dados em rede
* 🚪 Controle de sessão e logout

## 🛠️ Tecnologias

### Aplicação

* Java
* JavaFX
* JDBC

### Banco de dados

* PostgreSQL
* SQL

### Interface

* FXML
* CSS

### Versionamento

* Git
* GitHub

## 🏗️ Arquitetura

O projeto utiliza separação de responsabilidades entre diferentes componentes da aplicação:

```text
src/
├── application/     # Inicialização e configurações
├── controller/      # Controllers das interfaces JavaFX
├── database/        # Conexão com banco de dados e DAOs
├── model/           # Entidades e modelos
└── view/            # Interfaces FXML e estilos CSS
```

A comunicação com o **PostgreSQL** é realizada através de JDBC e as operações relacionadas à persistência dos dados são organizadas utilizando o padrão **DAO (Data Access Object)**.

## 📊 Dashboard

O dashboard permite visualizar rapidamente alguns dos principais indicadores da operação:

* Total de clientes
* Total de produtos
* Produtos com estoque baixo
* Quantidade de vendas
* Faturamento
* Vendas recentes

## 📑 Relatórios

O sistema conta com um módulo dedicado à visualização de informações gerenciais, permitindo analisar dados relacionados às operações realizadas pela empresa.

Os relatórios utilizam informações armazenadas no PostgreSQL para apresentar dados relacionados a vendas, produtos e clientes.

## 🌐 Funcionamento em rede

Uma das evoluções realizadas no projeto foi permitir que diferentes computadores conectados à mesma rede utilizassem o sistema acessando uma instância central do PostgreSQL.

Para isso foram realizadas configurações envolvendo:

* PostgreSQL Server
* `postgresql.conf`
* `pg_hba.conf`
* Firewall
* Porta `5432`
* Configuração JDBC
* Testes de comunicação entre diferentes computadores

Com isso, foi possível executar a aplicação em diferentes máquinas utilizando o mesmo banco de dados.

## 💻 Minhas contribuições

O projeto foi desenvolvido em equipe durante a faculdade. Minha atuação esteve concentrada principalmente na evolução técnica da aplicação e implementação de novas funcionalidades.

Entre minhas principais contribuições estão:

* Desenvolvimento e melhoria das interfaces com JavaFX, FXML e CSS
* Desenvolvimento do dashboard e seus indicadores
* Desenvolvimento e evolução do módulo de relatórios
* Implementação de consultas e operações utilizando PostgreSQL
* Configuração do banco de dados para funcionamento em rede
* Implementação de controle de permissões
* Melhorias na navegação entre as telas
* Implementação do fluxo de logout
* Correções nas operações de cadastro e persistência
* Melhorias de responsividade e experiência de uso
* Investigação e correção de bugs
* Versionamento das alterações utilizando Git e GitHub

## 🎯 Objetivo do projeto

Além de atender às necessidades apresentadas pela empresa, o projeto possibilitou aplicar conceitos estudados durante a graduação em um cenário próximo de uma situação real de desenvolvimento.

Durante sua evolução foram trabalhados conceitos de:

`Java` • `Orientação a Objetos` • `JavaFX` • `SQL` • `PostgreSQL` • `JDBC` • `DAO` • `Git` • `GitHub` • `Desenvolvimento em equipe`

## 📸 Screenshots

### Dashboard

*Imagem do dashboard*

### Gerenciamento de produtos

*Imagem da tela de produtos*

### Relatórios

*Imagem da tela de relatórios*

### Login

*Imagem da tela de login*

## 👨‍💻 Desenvolvedor

**Thiago Sanchez Nascimento**

Estudante de **Análise e Desenvolvimento de Sistemas**, com experiência prática em desenvolvimento de software, SQL, bancos de dados e sistemas empresariais.

GitHub: `@Thisanchez2013`

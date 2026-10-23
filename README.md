# 🔧 Desafio Oficina Mecânica

<p align="center">
  <img src="./image.png" alt="Sistema de Oficina Mecânica" width="100%">
</p>

---
---
##  Sobre o Projeto

O **Desafio Oficina Mecânica** consiste no desenvolvimento de um sistema voltado à organização e ao gerenciamento das atividades de uma oficina mecânica, utilizando o MySQL para armazenar e gerenciar os dados.

O projeto tem como objetivo aplicar conhecimentos de desenvolvimento de sistemas e banco de dados, explorando a criação e o gerenciamento de informações relacionadas a clientes, veículos e serviços automotivos.

##  Objetivos

- Desenvolver uma solução para auxiliar na organização de uma oficina mecânica.
- Aplicar conceitos de modelagem e gerenciamento de banco de dados.
- Utilizar o MySQL para armazenar e consultar informações.
- Praticar comandos SQL e operações de manipulação de dados.
- Desenvolver habilidades técnicas na área de Desenvolvimento de Sistemas.

##  Funcionalidades

O sistema pode contemplar funcionalidades como:

- Cadastro e consulta de clientes.
- Registro de veículos.
- Gerenciamento de serviços mecânicos.
- Controle de ordens de serviço.
- Consulta e atualização de informações.
- Armazenamento de dados em banco de dados MySQL.

*As funcionalidades devem ser ajustadas conforme os recursos implementados no projeto.*

##  Tecnologias Utilizadas

- **MySQL:** gerenciamento e armazenamento dos dados.
- **SQL:** criação, consulta, atualização e exclusão de registros.
- **MySQL Workbench:** ferramenta opcional para modelagem e administração do banco de dados.
- **Git e GitHub:** versionamento e compartilhamento do projeto.

##  Banco de Dados

O banco de dados é responsável por armazenar e organizar as informações do sistema.

Entre os conceitos que podem ser aplicados estão:

- Criação de bancos de dados e tabelas.
- Definição de chaves primárias e estrangeiras.
- Relacionamento entre tabelas.
- Inserção, consulta, atualização e exclusão de registros.
- Utilização de comandos SQL para manipulação dos dados.

### Exemplos de comandos SQL

Criar um banco de dados:

```sql
CREATE DATABASE oficina_mecanica;
```

Selecionar o banco de dados:

```sql
USE oficina_mecanica;
```

Criar uma tabela de clientes:

```sql
CREATE TABLE clientes (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    telefone VARCHAR(20),
    email VARCHAR(100)
);
```

Consultar os clientes cadastrados:

```sql
SELECT * FROM clientes;
```

*Os comandos acima são exemplos ilustrativos e podem ser adaptados à estrutura real do banco de dados.*

##  Como Executar o Projeto

1. Instale o MySQL Server em seu computador.
2. Abra o MySQL Workbench ou outro cliente MySQL.
3. Crie ou importe o banco de dados do projeto.
4. Execute o script SQL disponibilizado no repositório.
5. Confira se as tabelas foram criadas corretamente.
6. Execute a aplicação conforme as tecnologias utilizadas no desenvolvimento.

> Caso o projeto utilize uma aplicação conectada ao banco de dados, configure também as credenciais de conexão de acordo com o ambiente local.

##  Aprendizado

- Fundamentos de banco de dados relacionais.
- Modelagem de tabelas e relacionamentos.
- Linguagem SQL.
- Manipulação e consulta de dados.
- Organização de informações.
- Desenvolvimento de soluções para situações do cotidiano profissional.

##  Desenvolvedora

**Gabriela de Oliveira**

- **Curso:** Técnico em Desenvolvimento de Sistemas
- **Instituição:** SENAI A. Jacob Lafer
- **Ano:** 2026


## 📄 Licença

Projeto desenvolvido para fins educacionais, como parte das atividades de aprendizagem em Desenvolvimento de Sistemas.

---

<p align="center">
  Desenvolvido por Gabriela de Oliveira | 2026
</p>

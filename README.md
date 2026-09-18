# 💻 Projetos de Python e Banco de Dados

Este repositório reúne projetos e exercícios que estou desenvolvendo durante meus estudos em **Engenharia de Software**, com foco na aplicação prática de conceitos de **Python, lógica de programação, programação orientada a objetos, manipulação de dados e bancos de dados**.

O objetivo é registrar minha evolução e colocar em prática os conhecimentos adquiridos durante a graduação e cursos complementares.

## 🚀 Tecnologias utilizadas

* Python
* SQLite
* SQL
* Matplotlib
* Git e GitHub
* VS Code

## 📚 Projetos e exercícios

### 📇 Sistema de Cadastro de Contatos

Aplicação desenvolvida em **Python com SQLite** para praticar a integração entre uma aplicação e um banco de dados relacional.

O sistema permite:

* Criar automaticamente o banco de dados;
* Criar uma tabela de contatos;
* Inserir registros;
* Consultar contatos cadastrados;
* Atualizar informações;
* Excluir registros;
* Contar e-mails distintos utilizando `COUNT(DISTINCT email)`.

Exemplo da estrutura utilizada no banco:

```sql
CREATE TABLE Contatos (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    nome TEXT,
    telefone TEXT,
    email TEXT
);
```

Neste projeto pratiquei as principais operações de **CRUD**:

**Create → Read → Update → Delete**

---

### 📚 Sistema de Cadastro de Livros

Projeto desenvolvido para praticar conceitos de **Python e Programação Orientada a Objetos (POO)**.

Foram trabalhados conceitos como:

* Criação de classes;
* Objetos;
* Métodos;
* Listas;
* Funções;
* Manipulação e organização de dados.

O projeto permite cadastrar e visualizar informações como:

* Título;
* Autor;
* Ano de publicação.

---

### 📊 Análise e Visualização de Dados

Exercícios desenvolvidos para aprender a trabalhar com dados em Python e representar informações de forma visual.

Entre os conceitos praticados estão:

* Organização de dados;
* Cálculos e médias;
* Manipulação de listas;
* Funções;
* Expressões `lambda`;
* Estruturas de repetição;
* Geração de gráficos com **Matplotlib**.

---

### 🧠 Lógica de Programação

Também fazem parte deste repositório exercícios voltados ao desenvolvimento da lógica de programação, incluindo:

* Estruturas condicionais (`if`, `elif`, `else`);
* Laços `for` e `while`;
* Funções;
* Funções `lambda`;
* Listas e dicionários;
* Verificação de números primos;
* Cálculo de médias;
* Classificação de alunos aprovados e reprovados;
* Formatação e tratamento de valores.

## 🎯 Objetivo

Estes projetos fazem parte da minha evolução na área de tecnologia e têm como objetivo transformar os conceitos estudados em aplicações práticas.

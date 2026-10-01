# Exercícios de SQL — Curso Midori Toyota

Este repositório reúne os exercícios de fixação que criei durante o curso **SQL para Análise de Dados: Do básico ao avançado**, ministrado por **Midori Toyota** na Udemy.

Ao todo, são **800 exercícios**, divididos em oito seções com 100 exercícios cada.

## Objetivo

Os exercícios foram criados para reforçar os conteúdos estudados, fixar a sintaxe e ajudar a entender como cada comando funciona na prática.

## Pré-requisito

Para realizar os exercícios, é necessário ter acesso ao banco de dados utilizado no curso.

O arquivo `.txt` necessário para criar e preencher esse banco é disponibilizado pela própria instrutora aos alunos e não está incluído neste repositório.

Optei por não compartilhar esse arquivo porque ele faz parte do material oficial do curso. Por isso, estes exercícios são destinados a quem está fazendo ou já concluiu o curso e possui o banco de dados configurado.

## Organização dos exercícios

- 100 exercícios em cada seção;
- exercícios organizados de forma progressiva;
- utilização apenas dos conceitos da seção atual e dos conteúdos estudados anteriormente;
- utilização somente das tabelas disponíveis até aquele momento do curso;
- PDFs sem gabarito.

## Seções

| Seção | Conteúdo principal | PDF |
|---|---|---|
| 3 | SELECT, DISTINCT, WHERE, ORDER BY e LIMIT | [Comandos básicos](<./PDF's dos Exercícios/SQL Exercícios Seção 3 Comandos Básicos.pdf>) |
| 4 | Operadores aritméticos, de comparação e lógicos | [Operadores](<./PDF's dos Exercícios/SQL Exercícios Seção 4 Operadores.pdf>) |
| 5 | COUNT, SUM, AVG, MIN, MAX, GROUP BY e HAVING | [Funções agregadas](<./PDF's dos Exercícios/SQL Exercícios Seção 5 Funções Agregadas.pdf>) |
| 6 | INNER JOIN, LEFT JOIN, RIGHT JOIN e FULL JOIN | [JOINs](<./PDF's dos Exercícios/SQL Exercícios Seção 6 Joins.pdf>) |
| 7 | UNION, UNION ALL e compatibilidade entre consultas | [UNIONs](<./PDF's dos Exercícios/SQL Exercícios Seção 7 Unions.pdf>) |
| 8 | Subqueries, EXISTS, tabelas derivadas e CTEs (consultas temporárias com `WITH`) | [Subqueries](<./PDF's dos Exercícios/SQL Exercícios Seção 8 Subqueries.pdf>) |
| 9 | Conversão de tipos, CASE, COALESCE, textos e datas | [Tratamento de dados](<./PDF's dos Exercícios/SQL Exercícios Seção 9 Tratamento de Dados.pdf>) |
| 10 | CREATE, INSERT, UPDATE, DELETE, ALTER e DROP | [Manipulação de tabelas](<./PDF's dos Exercícios/SQL Exercícios Seção 10 Manipulação de Tabelas.pdf>) |

## Ambiente utilizado

- PostgreSQL
- pgAdmin
- Base fictícia de um e-commerce de veículos utilizada durante o curso

Nos exercícios de manipulação de tabelas, as alterações são realizadas somente no schema `temp_tables`, preservando as tabelas originais do schema `sales`.

## Projetos guiados desenvolvidos no curso

- [Projeto SQL 1 — Dashboard de Acompanhamento de Vendas](https://github.com/Dhreamer/sql-dashboard-acompanhamento-vendas)
- [Projeto SQL 2 — Análise de Perfil dos Clientes](https://github.com/Dhreamer/sql-analise-perfil-clientes)

## Observação

Este é um material complementar criado por mim para estudo e fixação dos conteúdos. Os exercícios não fazem parte do material oficial do curso ou da instrutora.

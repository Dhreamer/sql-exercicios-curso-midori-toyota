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
| 3 | SELECT, DISTINCT, WHERE, ORDER BY e LIMIT | [Comandos básicos](./SQL_Exercicios_Secao_3_Comandos_Basicos.pdf) |
| 4 | Operadores aritméticos, de comparação e lógicos | [Operadores](./SQL_Exercicios_Secao_4_Operadores.pdf) |
| 5 | COUNT, SUM, AVG, MIN, MAX, GROUP BY e HAVING | [Funções agregadas](./SQL_Exercicios_Secao_5_Funcoes_Agregadas.pdf) |
| 6 | INNER JOIN, LEFT JOIN, RIGHT JOIN e FULL JOIN | [JOINs](./SQL_Exercicios_Secao_6_Joins.pdf) |
| 7 | UNION, UNION ALL e compatibilidade entre consultas | [UNIONs](./SQL_Exercicios_Secao_7_Unions.pdf) |
| 8 | Subqueries, EXISTS, tabelas derivadas e CTEs (consultas temporárias com `WITH`) | [Subqueries](./SQL_Exercicios_Secao_8_Subqueries_Revisado.pdf) |
| 9 | Conversão de tipos, CASE, COALESCE, textos e datas | [Tratamento de dados](./SQL_Exercicios_Secao_9_Tratamento_de_Dados.pdf) |
| 10 | CREATE, INSERT, UPDATE, DELETE, ALTER e DROP | [Manipulação de tabelas](./SQL_Exercicios_Secao_10_Manipulacao_de_Tabelas.pdf) |

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

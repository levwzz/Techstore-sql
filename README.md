🛒 Resolução: Atividade TechStore (MySQL)

Este repositório contém as soluções para a atividade prática de Base de Dados da loja fictícia **TechStore**. O foco é a manipulação de dados utilizando `SELECTs` complexos, construção de **Stored Procedures** e conceitos teóricos sobre **Views**.

## 📑 O que este repositório contém?

1. **`consultas.sql`**: Um script com 10 instruções SQL de nível inicial, incluindo filtros (`WHERE`), ordenação (`ORDER BY`), agregações (`COUNT`, `SUM`) e junções entre tabelas (`INNER JOIN`).
2. **`procedures.sql`**: Um script contendo a criação de 5 Stored Procedures, aplicando boas práticas de delimitadores (`DELIMITER //`), segurança (`DROP PROCEDURE IF EXISTS`) e gestão de parâmetros (`IN`, `OUT`).
3. **`pesquisa_views.md`**: Um documento contendo 5 exemplos práticos e fundamentados de situações onde a utilização de Views é mais vantajosa do que a utilização de Stored Procedures (ex: integração com BI e segurança).

## 🚀 Instruções de Execução

1. Execute o script de criação do banco de dados `loja_tech` e insira a carga de dados iniciais.
2. No MySQL Workbench, certifique-se de ativar a base de dados com `USE loja_tech;`.
3. Abra e execute os blocos de código presentes nos ficheiros `.sql`.
4. Para testar as Procedures, utilize o comando `CALL nome_da_procedure(parametros);`.

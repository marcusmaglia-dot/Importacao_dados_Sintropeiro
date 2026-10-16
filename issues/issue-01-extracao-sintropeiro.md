# Issue 01: Análise e Extração de Dados - Sintropeiro (Origem)

## Objetivo
Conectar ao banco de dados de origem localizado em `/home/marcus/Dev/Sintropeiro/`, realizar um dump completo ou extração estruturada de todas as tabelas, registros e metadados, preparando o terreno para a análise comparativa de migração.

## Tarefas Técnicas
1. Identificar o SGBD utilizado pelo Sintropeiro (ex: SQLite, MySQL, PostgreSQL).
2. Mapear todas as tabelas e colunas existentes.
3. Exportar os dados brutos para formato estruturado (JSON ou CSV) na pasta de staging do projeto.
4. Validar integridade e volumetria dos dados extraídos.

## Critérios de Aceite
- [ ] Conexão estabelecida com sucesso na pasta `/home/marcus/Dev/Sintropeiro/`.
- [ ] Relatório de tabelas e contagem de registros gerado.
- [ ] Dados brutos salvos e prontos para cruzamento.

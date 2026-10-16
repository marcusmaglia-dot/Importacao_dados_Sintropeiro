# Issue 04: PRD - Mix & Match (Dicionário de Tradução de Dados)

## Objetivo
Criar o dicionário de tradução (De-Para) comparativo entre os atributos do Sintropeiro e do PsicoSaaS (ex: `Paciente_Nome` vs `Cliente_NM`), servindo de manual definitivo para o script de migração futura.

## Estrutura Esperada
- Tabela de Origem -> Campo Origem
- Tabela de Destino -> Campo Destino
- Regra de Transformação / Parsing (ex: conversão de formatos de data, concatenação de nomes, tratamentos de nulos)

## Critérios de Aceite
- [ ] Mapeamento De-Para 100% concluído para todas as entidades críticas.
- [ ] Casos de borda (edge cases) documentados.

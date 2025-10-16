# Projeto Databricks

Este projeto demonstra um **pipeline de dados usando Databricks e Delta Lake**, aplicado a dados de Airbnb de oito cidades europeias. Ele transforma dados brutos (landing/bronze) em uma camada estruturada para análise (silver e gold).


---



## Estrutura do Projeto

- **landing**: pasta/volume de dados brutos (`CSV`)
- **bronze**: tabelas Delta com dados ingeridos, incluindo colunas de auditoria
- **silver**: tabelas Delta com dados limpos, renomeados e com colunas de auditoria atualizadas
- **gold**: tabelas Delta finais, com dados preparados para análise e indicadores calculados

---
---

## Cidades Processadas

- Amsterdam  
- Athens  
- Barcelona  
- Berlin  
- Lisbon  
- London  
- Paris  
- Rome  

---

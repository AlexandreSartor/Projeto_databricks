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

Versão do python utilizada: 3.13.7.

Projeto python inicializado com o UV .

Comandos utilizados para setup do ambiente:

```bash 
uv init .
pyenv local 3.13.7
uv venv
source .venv/bin/activate
```

Comandos para vizualizar a documentação localmente:

```bash
pip install mkdocs mkdocs-material

mkdocs serve

Normalmente acessível em http://127.0.0.1:8000/
```
**Nota:** Entrar na pasta "docs" para rodar os comandos mkdocs

# Dashboard de RH e Qualidade de Dados em Power BI

Projeto de análise de dados desenvolvido em Power BI com foco em:

- Análise de satisfação interna de colaboradores
- Monitoramento de integridade e qualidade de dados
- Simulação de auditoria e validação de base cadastral

---

## Objetivo do Projeto

Desenvolver dashboards analíticos para simular cenários reais de negócio, aplicando conceitos de:

- Modelagem de dados
- DAX
- Data Quality
- Storytelling analítico
- Design de dashboards

---

## Dashboard 1 — Análise de Satisfação Interna (RH)

### Principais análises realizadas:

- Identificação da unidade com menor satisfação
- Comparativo de satisfação por tema
- Melhor fonte de recrutamento
- Distribuição de satisfação por faixa etária
- Análise histórica de colaboradores por ano de contratação

### Preview

![Dashboard RH](dashboards/dashboard_rh.png)

---

## Dashboard 2 — Integridade e Saúde dos Dados (QA)

### Principais análises realizadas:

- Monitoramento de valores nulos por campo
- Identificação de erros críticos por unidade
- Log de auditoria detalhado por registro
- Campo com maior incidência de erro
- Registros inválidos por regra de negócio

### Regras de Validação Simuladas

Foram inseridas inconsistências propositalmente para simular cenários reais de auditoria de dados:

- Idades inválidas (≤ 0)
- Status fora do domínio permitido
- Datas de contratação futuras
- Campos obrigatórios nulos
- Funcionários sem entrevista relacionada

### Preview

![Dashboard QA](dashboards/dashboard_qa.png)

---

## Tecnologias Utilizadas

- Power BI
- DAX
- Modelagem Relacional
- Excel / CSV

---

## Principais Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conceitos de:

- Construção de medidas complexas em DAX
- Contexto de filtro e relacionamento entre tabelas
- Tratamento de dados inconsistentes
- Desenvolvimento de dashboards orientados a insight
- Estruturação de processos de auditoria de dados

---

## Arquivos do Projeto

- `projeto-dashboard.pbix` → arquivo principal do Power BI
- `base-funcionarios.xlsx` → base utilizada no projeto

---

## Autor

Heloísa Sousa  
[LinkedIn](SEU_LINK_AQUI)

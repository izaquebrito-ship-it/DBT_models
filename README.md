# DBT Models Repository

Este repositório contém os modelos DBT utilizados para transformar e organizar dados de forma eficiente e escalável.

## 📌 Propósito

- Centralizar os modelos de transformação de dados utilizando DBT (Data Build Tool)
- Padronizar e versionar os modelos via GitLab
- Automatizar execuções através de DAGs em orquestradores como Airflow

## 🧱 Estrutura

- `models/staging/`: Modelos de staging para limpeza e padronização dos dados
- `models/intermediate/`: Modelos intermediários com cálculos e agregações
- `models/final/`: Tabelas finais de fatos e dimensões para consumo analítico

## 🔄 Versionamento

- Todos os modelos são versionados via GitLab
- Commits seguem convenções de nomenclatura para facilitar rastreabilidade
- Revisões são feitas por parceiros DBT antes da publicação

## 👥 Parceiros DBT

- Analistas de dados
- Engenheiros de dados
- Especialistas em modelagem dimensional

## 🚀 Publicação

- Os modelos são publicados em DAGs automatizadas
- Integração com orquestradores para execução programada e monitoramento

## 📁 Input Manual

- Alguns modelos recebem dados via input manual (ex: arquivos Excel)
- Esses dados são tratados em modelos de staging específicos

---

Para dúvidas ou sugestões, entre em contato com o time de dados.

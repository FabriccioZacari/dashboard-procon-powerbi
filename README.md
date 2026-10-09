# 📊 Dashboard de Gestão de Atendimentos — Procon

Dashboard analítico de gestão de atendimentos e reclamações do Procon/Gov desenvolvido em Power BI e Power Query.

Este projeto consiste num painel analítico interativo desenvolvido em **Power BI** a partir de dados abertos do portal do Governo (`dados.gov.br`). O objetivo é monitorizar o volume de chamados, taxas de resolução e distribuição de reclamações por setor.

## 🖼️ Visualização do Dashboard

<img width="1354" height="811" alt="procon power bi projeto" src="https://github.com/user-attachments/assets/babd07ce-69b5-4f17-86ce-9ee4066ce5e8" />

## 🛠️ Processo de ETL (Power Query)
- **Extração e Higienização:** Filtragem de valores nulos e remoção de colunas não essenciais.
- **Transformação de Dados:** Padronização da coluna de datas e criação de coluna condicional (`Situação do Chamado`) para categorizar atendimentos entre *Concluído* e *Em Andamento*.

## 📈 Principais Métricas & Visualizações
- **KPIs:** Total de Chamados, Chamados Concluídos e Chamados em Andamento.
- **Análise Temporal:** Evolução mensal do volume de atendimentos.
- **Análise Setorial:** Distribuição de reclamações por Área (ex.: Assuntos Financeiros, Serviços Essenciais).
- **Filtros Interativos:** Segmentação dinâmica por situação do chamado.

---

## 📂 Como visualizar este projeto
1. Transfira o ficheiro `Dashboard_Procon_Atendimentos.pbix` deste repositório.
2. Abra o ficheiro através do **Power BI Desktop**.

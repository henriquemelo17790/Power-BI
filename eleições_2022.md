# 🗳️ Análise das Eleições Presidenciais 2022 (Brasil)

<img width="908" height="484" alt="image" src="https://github.com/user-attachments/assets/f47fdc2c-6bcf-4f62-bf86-114a81ca40e1" />

Este projeto apresenta um dashboard interativo desenvolvido no **Power BI** para visualização e análise detalhada dos resultados das Eleições Presidenciais de 2022. O foco é transformar dados brutos em insights geográficos e estatísticos sobre o cenário eleitoral brasileiro.

## 📊 Dashboard Interativo

Você pode acessar o painel online através do link abaixo:
👉 [**Clique aqui para visualizar o Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiMDRhZGFiYWQtZWY4Yy00NTIzLWEwNzAtZjE3Yjk0YzBlZGY4IiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9)

---

## 📂 Sobre os Dados

Os dados foram extraídos do repositório oficial de estatísticas do **Tribunal Superior Eleitoral (TSE)**.

* **Fonte Original:** [Estatísticas TSE - SIG Eleição](https://sig.tse.jus.br/ords/dwapr/r/seai/sig-eleicao/home)
* **Abrangência:** Dados nacionais
* **Granularidade:** Resultados por estado, município e seção.

## 🛠️ Tecnologias e Processos

* **Power Query (ETL):** Limpeza de dados, padronização de nomes de municípios e tratamento de nulos/vazios.
* **Modelagem de Dados:** Criação de tabelas dimensão (Calendário, Geografia, Candidatos) e tabelas fato (Votação).
* **DAX:** Desenvolvimento de medidas para cálculo de:
    * Percentual de votos válidos.
    * Índice de abstenção por região.
    * Comparativo de desempenho entre o 1º e 2º turno.
* **Visualização:** Uso de mapas coropléticos, gráficos de barras empilhadas e cartões dinâmicos.

## 📈 Principais Insights do Painel

  **Distribuição Regional:** Visualização clara da divisão de votos por estado.
  
---

## 👤 Autor

Desenvolvido por **Henrique Melo**.
Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/henrique-melo-25163a1b3/).

---
*Este é um projeto com fins de estudo e análise de dados públicos.*

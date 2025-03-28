# Comportamento do Preço do GLP
Este repositório contém os arquivos utilizados no estudo desenvolvido no Power BI para o meu Trabalho de Conclusão de Curso (TCC) no MBA em Data Science & Analytics, utilizando dados públicos e atualizados no datalake do site [basedosdados.org](https://basedosdados.org/dataset/6ea3e28a-42be-401a-a066-ad87ca931e69?table=3a7cb29a-0bdf-4f44-bab1-d27872e565ff).
<br>
Foi desenvolvida toda a estrutura de Business Intelligence (BI), desde o levantamento de requisitos até a conexão com a fonte de dados via BigQuery, além do desenvolvimento e publicação do painel final.

---

## Objetivo

Trata-se de avaliar se o desenvolvimento desse produto de dados pode auxiliar o consumidor final na tomada de decisão no momento da compra do gás liquefeito de petróleo. O intuito é disponibilizar recursos que possibilitem obter respostas para determinadas questões pessoais, como, por exemplo:
- Qual é o preço médio do gás de cozinha na minha região?
- Quais são as distribuidoras de gás de cozinha que têm os menores preços na minha cidade?
- O preço do gás de cozinha no meu estado aumentou ou diminui em comparação ao mês passado?

## Ferramentas
- Para criação do layout foi utilizado o **[Figma](https://www.figma.com/pt-br/downloads/)**;
- Para armazenamento de dados, criação de tabelas e para consultas no banco foi utilizado o **[BigQuery](https://cloud.google.com/bigquery/?hl=pt-BR)**;
- Para criação do painel foi utilizado o **[Power BI](https://powerbi.microsoft.com/pt-br/)**.

## Desenvolvimento
O projeto foi realizado em três etapas principais:
- [x] **Levantamento de requisitos**<br>
Foram compreendidas as necessidades do usuário a fim de identificar quais problemas deveriam ser resolvidos. Com isso, foi possível formalizar as demandas pertinentes e abordar os pontos cruciais.

- [x]  **Conexão com a fonte de dados**<br>
Definição de onde os dados seriam coletados (a fonte) e do método de coleta a ser utilizado.

- [x]  **Criação do painel no Power BI**<br>
O próprio Power BI foi utilizado como camada de CUBO e visualização. Além disso, todos os dados foram importados diretamente do Data Warehouse, e as medidas e cálculos foram desenvolvidos em DAX, conforme o levantamento de requisitos. 

![Image](https://github.com/user-attachments/assets/3a808642-9776-421c-b08e-c83d1cb2312d)

![Image](https://github.com/user-attachments/assets/3a8390e9-eb07-4b1c-94bb-45d20a6d4517)

[➥ Veja o painel online](https://app.powerbi.com/view?r=eyJrIjoiOGI0Mjk2NTgtZDEyOS00ODE3LTliYWUtNzA4MzViNzI5YzBkIiwidCI6IjgyODY3NTQ1LTY3NzEtNGY0NC04N2I4LTUyODEyOTlkMTI0ZSJ9)

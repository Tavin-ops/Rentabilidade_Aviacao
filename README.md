✈️ Análise de Rentabilidade e Estrutura de Custos na Aviação Executiva (FP&A)

Projeto prático de Planejamento e Análise Financeira (FP&A) focado em avaliar a rentabilidade operacional e a estrutura de custos por modelo de aeronave em uma empresa de aviação executiva fictícia.


📌 Objetivo do Projeto
Analisar o desempenho financeiro de voos fretados, identificando as aeronaves mais lucrativas, os principais *cost drivers* da operação e oportunidades de otimização de margem.


🛠️ Metodologia & Pipeline de Dados

O projeto foi estruturado em um fluxo de dados integrado de 3 etapas:

1. Processamento & Engenharia de Atributos (Python - `pandas`):
   * Limpeza e estruturação dos dados brutos de voo.
   * Criação de métricas financeiras essenciais: `Custo_Total` (Combustível + Manutenção), `Lucro_Liquido` e `Margem_Lucro (%)`.
   * [🔗 Acessar Script/Notebook no Google Colab](https://colab.research.google.com/drive/1idsAeZR1Gct-zvGlhQ722dEo_V9EwYhu#scrollTo=NpvEoOGMOz6a&line=13&uniqifier=1)

2. Camada de Transição (Excel):
   * Exportação dos dados limpos e validados para consumo direto no Power BI.

3. Visualização Executiva & Dashboard (Power BI):
   * Construção de cartões de KPIs macros (Receita Total, Custo Total e Lucro Líquido).
   * Gráficos de estrutura de custos e rentabilidade por produto/modelo de aeronave.


📊 Dashboard Executivo

<p align="center">
  <img width="866" alt="Dashboard de Rentabilidade na Aviação" src="https://github.com/user-attachments/assets/f60bf1b0-11ed-41d5-9c0b-486acc23e115" />
</p>


💡 Principais Insights Financeiros (FP&A)

* Carro-chefe de Lucratividade (Learjet): O modelo Learjet destaca-se como a aeronave de maior retorno financeiro, concentrando a maior fatia da receita (R$ 56 mil) e gerando R$ 30,3 mil em lucro líquido.
* Estrutura de Custos Concentrada: O Combustível é o principal cost driver da operação, representando 76,6% do custo total (R$ 31 mil) contra 23,4% de manutenção. Recomendam-se estratégias de hedge cambial, contratos de abastecimento em volume e análise de eficiência energética de rotas.
* Desempenho Operacional do Helicóptero: O Helicóptero Esquilo apresentou o menor volume absoluto de receita e lucro, indicando a necessidade de reavaliar a precificação por hora de voo ou focar em rotas/fretamentos de maior margem.

# Análise da Produção de Cupuaçu no Amazonas: Evidências e Visualizações

Este projeto combina economia, estatística, ciência de dados e análise espacial para compreender os padrões de produção do **cupuaçu** no estado do Amazonas. Com base em dados de Unidades Locais, utilizamos técnicas de clusterização e mapeamento geoespacial para identificar agrupamentos produtivos e subsidiar o desenvolvimento de políticas públicas.

---

## **Objetivo**
Analisar como agrupamentos de munícipio influenciam a produtividade do cupuaçu por município no Amazonas, identificando padrões espaciais e oportunidades para impulsionar o setor.

---

## **Etapas do Projeto**
1. **ETL e Preparação dos Dados**:
   - Extração e tratamento dos dados de um relatório *(INSTITUTO DE DESENVOLVIMENTO AGROPECUÁRIO E FLORESTAL SUSTENTÁVEL DO ESTADO DO AMAZONASRELATÓRIO DE ACOMPANHAMENTO TRIMESTRAL)* PDF utilizando Python.
   - Geocodificação das localidades (latitude e longitude) com a API do Nominatim.

2. **Clusterização e Análise Espacial**:
   - Agrupamento dos municípios por características produtivas utilizando o algoritmo KMeans.
   - Visualização dos clusters em mapas geográficos com a biblioteca Folium para identificar padrões regionais.

3. **Análises Comparativas**:
   - Comparação entre os clusters com base em produtividade, área plantada, e outras métricas.
   - Identificação de diferenças significativas entre os grupos para direcionar políticas públicas.

---

## **Ferramentas Utilizadas**
- **Python**:
  - `pandas`, `numpy`: Manipulação e análise de dados.
  - `matplotlib`, `seaborn`: Visualização de dados.
  - `geopandas`, `folium`: Análise e visualização espacial.
  - `scikit-learn`: Algoritmo de clusterização (KMeans).
- **Jupyter Notebook**: Documentação e execução interativa.
- **Excel**: Exportação de tabelas para relatórios.
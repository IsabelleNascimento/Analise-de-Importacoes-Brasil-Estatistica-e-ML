# Analise-de-Importacoes-Brasil-Estatistica-e-ML
Análise acadêmica de dados de importação do Brasil utilizando estatística descritiva, visualização, clusterização (K-Means), regressão linear e árvore de decisão. Projeto desenvolvido em Google Colab com foco em qualidade e governança de dados (DAMA-DMBOK).

# Análise de Importações do Brasil com Estatística e Machine Learning

Este repositório apresenta um estudo acadêmico sobre dados de importação do Brasil, explorando **estatística descritiva, visualização de dados e técnicas de machine learning**.  
O trabalho foi desenvolvido em **Google Colab** e publicado aqui para fins de transparência e compartilhamento de conhecimento.

---

# Objetivos
- Criar e analisar a variável derivada `preco_unitario_usd_kg`.
- Explorar a distribuição dos preços unitários com estatística descritiva e gráficos.
- Comparar países fornecedores entre 2019 e 2020, avaliando impactos da pandemia.
- Aplicar técnicas de **clusterização, regressão e árvore de decisão** para extrair padrões e regras.
- Discutir políticas de **governança de dados (DAMA-DMBOK)** relacionadas à qualidade e segurança.

---

# Metodologia
1. **Estatística Descritiva**  
   - Média, mediana, quartis e desvio padrão.  
   - Identificação de outliers e assimetria positiva.  

2. *Visualização* 
   - Histogramas e boxplots para compreender a distribuição.  
   - Comparação temporal (2019 vs 2020).  

3. *Machine Learning* 
   - **Clusterização (K-Means):** agrupamento de transações por faixas de preço.  
   - **Regressão Linear:** análise da influência de peso, frete e seguro sobre o preço unitário.  
   - **Árvore de Decisão:** regras interpretáveis para classificar faixas de preço.  

4. *Governança de Dados (DAMA-DMBOK)*  
   - Qualidade: filtragem de inconsistências, tratamento de outliers, atualização temporal.  
   - Segurança: uso de variáveis agregadas e derivadas para proteger dados sensíveis.  

---

# 📊 Principais Resultados
- Distribuição altamente assimétrica dos preços unitários, com forte influência de outliers.  
- Redução da diversidade de países fornecedores em 2020, sem entrada de novos países.  
- O **valor do frete** foi identificado como principal fator discriminante nas faixas de preço.  
- Clusterização revelou grupos naturais de baixo, médio e alto valor unitário.  

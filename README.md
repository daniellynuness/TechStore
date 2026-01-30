# 📊 TechStore: Análise Estratégica de Varejo

> **Ciência de Dados aplicada ao Negócio**: Identificando ineficiências de estoque e oportunidades de receita através de dados.

![Status](https://img.shields.io/badge/Status-Concluído-green) ![Python](https://img.shields.io/badge/Python-3.x-blue) ![Libs](https://img.shields.io/badge/Libs-Pandas%20|%20Seaborn-orange)

## O Desafio
A **TechStore** (varejista de eletrônicos fictícia) opera com um catálogo de produtos variados e vendas nacionais. O objetivo deste projeto foi auditar a base de vendas para responder a três perguntas estratégicas da diretoria:
1.  **Quais produtos carregam a empresa nas costas?** (Curva ABC)
2.  **Onde temos dinheiro parado?** (Análise de Giro de Estoque)
3.  **Temos problemas regionais de entrega?** (Eficiência Logística)

## 🔍 Principais Insights

### 1. Foco Estratégico (Pareto 80/20)
Através da classificação ABC, foi identificado que a grande maioria do faturamento provém de uma pequena parcela dos produtos (Notebooks e Smartphones).
* **Ação Recomendada:** Garantir estoque de segurança máximo para itens **Classe A** e reavaliar a continuidade de itens **Classe C** (Acessórios de baixo valor).
<div align='center'><img width="800" height="502" alt="pareto" src="https://github.com/user-attachments/assets/90934235-2065-4785-b389-cb0f2e531635" /></div>

### 2. Fluxo de Caixa (Matriz de Estoque)
O cruzamento de *Ticket Médio* vs. *Dias em Estoque* revelou produtos de alto valor (acima de R$ 2.000) com giro lento (> 45 dias).
* **Ação Recomendada:** Realizar promoções direcionadas para estes itens específicos para liberar capital de giro imediato.
<div align='center'><img width="800" height="502" alt="estoque" src="https://github.com/user-attachments/assets/5de86c0d-6457-4f67-a416-d56016d54069" /></div>

### 3. Gargalos Logísticos
A análise por cidades monitorou a taxa de insucesso (Devoluções/Cancelamentos).
* **Ação Recomendada:** Cidades com taxa de sucesso abaixo de 85% devem ter seus parceiros logísticos auditados ou substituídos.
<div align='center'><img width="900" height="502" alt="eficiencia" src="https://github.com/user-attachments/assets/a605ad75-381d-40d5-946c-fafe11c648ab" /></div>

## 🛠️ Tecnologias Utilizadas
* **Python**: Geração de dados sintéticos e análise estatística.
* **Pandas**: Manipulação de dados (ETL), conversão de tipos e feature engineering.
* **Seaborn/Matplotlib**: Visualização de dados para tomada de decisão.
* **Jupyter Notebook**: Documentação do processo de análise.

## Como Executar
1.  Clone o repositório.
2.  Instale as dependências: `pip install pandas seaborn matplotlib`
3.  Execute o script `gerador_dados.py` para criar o dataset (opcional, o CSV já está incluído).
4.  Abra o notebook `analise_estrategica.ipynb` para ver os resultados.

---
*Projeto desenvolvido para portfólio de Ciência de Dados.*

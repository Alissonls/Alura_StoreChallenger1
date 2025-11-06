# 🏬 Alura Store Brasil – Análise de Vendas

## 📖 Sobre o Projeto
O projeto **Alura Store Brasil** faz parte do **Challenge Data Science da Alura**, com o objetivo de desenvolver uma análise completa de dados de vendas utilizando ferramentas do ecossistema Python.  

O desafio envolve a consolidação de dados de **quatro lojas diferentes** e a criação de um relatório visual e interativo com gráficos e insights sobre desempenho comercial, categorias mais vendidas e comportamento de compra por região.

---

## 🧭 Fluxo do Projeto (Mermaid)

```mermaid
flowchart TD

subgraph DADOS[🗂️ Etapa 1: Dados de Entrada]
A1[Arquivos CSV<br>loja_1.csv, loja_2.csv, loja_3.csv, loja_4.csv]
end

subgraph PROCESSAMENTO[⚙️ Etapa 2: Processamento de Dados]
B1[Leitura e Consolidação<br>com Pandas]
B2[Limpeza e Conversão de Datas]
end

subgraph ANALISE[📊 Etapa 3: Análise e Visualização]
C1[Geração de Gráficos<br>com Matplotlib e Seaborn]
C2[Análise Visual e Interpretação dos Resultados]
end

subgraph INSIGHTS[🧠 Etapa 4: Resultados e Insights]
D1[Total de Vendas por Categoria]
D2[Avaliação Média por Vendedor]
D3[Vendas por Estado]
D4[Evolução das Vendas no Tempo]
end

subgraph RELATORIO[📘 Etapa 5: Documentação e Entrega]
E1[Notebook AluraStoreBrasil.ipynb]
E2[Relatório Final do Challenge]
end

subgraph TECNOLOGIAS[💻 Tecnologias Utilizadas]
T1[Python 3.x]
T2[Pandas]
T3[Matplotlib]
T4[Seaborn]
T5[Jupyter Notebook]
end

A1 --> B1 --> B2 --> C1 --> C2 --> D1 & D2 & D3 & D4 --> E1 --> E2
T1 --> B1
T2 --> B2
T3 --> C1
T4 --> C1
T5 --> E1
```

---

## 💻 Tecnologias Utilizadas

| Tecnologia | Descrição |
|-------------|------------|
| 🐍 **Python 3.x** | Linguagem principal para análise de dados. |
| 📦 **Pandas** | Manipulação, limpeza e análise de dados. |
| 📈 **Matplotlib** | Criação de gráficos e visualizações. |
| 🎨 **Seaborn** | Estilização e aprimoramento visual dos gráficos. |
| 📘 **Jupyter Notebook** | Ambiente interativo para execução e documentação. |

---

## 🧠 Resultados

O relatório final apresenta uma visão clara sobre:

- O volume total de vendas por loja e categoria  
- A média de avaliações por vendedor  
- A distribuição geográfica das vendas no Brasil  
- A evolução temporal das vendas, permitindo detectar tendências  

---

## 🧩 Estrutura do Projeto

```
📦 Alura_Store_Brasil
 ┣ 📜 README.md
 ┣ 📓 AluraStoreBrasil.ipynb
 ┣ 📁 data/
 ┃ ┣ loja_1.csv
 ┃ ┣ loja_2.csv
 ┃ ┣ loja_3.csv
 ┃ ┗ loja_4.csv
 ┣ 📁 img/
 ┃ ┣ vendas_por_categoria.png
 ┃ ┣ avaliacao_vendedor.png
 ┃ ┣ vendas_por_estado.png
 ┃ ┗ evolucao_vendas.png
 ┗ 📁 .venv/
```

---

## © Direitos Autorais

**© 2025 - Alisson Luiz Siqueira Coqueiro**  
Projeto desenvolvido como parte do **Challenge Data Science da Alura**.  
Todos os direitos reservados.

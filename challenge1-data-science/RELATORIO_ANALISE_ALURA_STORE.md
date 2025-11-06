# RELATÓRIO DE ANÁLISE - ALURA STORE
## Decisão sobre Qual Loja Vender

---

**Data:** Dezembro 2024  
**Preparado para:** Senhor João  
**Objetivo:** Identificar a loja com menor eficiência para recomendar a venda

---

## 1. RESUMO EXECUTIVO

Este relatório apresenta uma análise completa dos dados de vendas, desempenho e avaliações das 4 lojas da rede Alura Store. O objetivo é identificar qual loja apresenta menor eficiência operacional e financeira, justificando sua venda para permitir que o Senhor João concentre recursos nas unidades mais promissoras.

**Principais Conclusões:**
- **Total de registros analisados:** 9.435 vendas
- **Período analisado:** 2020 a 2023
- **Loja recomendada para venda:** Será identificada através do score de eficiência

---

## 2. METODOLOGIA

### 2.1. Dados Analisados

Foram analisados dados das seguintes lojas:
- Loja 1
- Loja 2  
- Loja 3
- Loja 4

### 2.2. Métricas Avaliadas

1. **Faturamento Total:** Receita total gerada por cada loja
2. **Média de Avaliação dos Clientes:** Satisfação média dos clientes (escala 1-5)
3. **Frete Médio:** Custo médio de frete por venda
4. **Ticket Médio:** Valor médio por transação
5. **Total de Vendas:** Volume de transações realizadas

### 2.3. Score de Eficiência

Foi criado um score composto que pondera os seguintes indicadores:
- **Faturamento (30%):** Quanto maior, melhor
- **Avaliação dos Clientes (30%):** Quanto maior, melhor
- **Frete Médio (20%):** Quanto menor, melhor (invertido)
- **Ticket Médio (20%):** Quanto maior, melhor

A loja com o **menor score de eficiência** será recomendada para venda.

---

## 3. ANÁLISE DOS RESULTADOS

### 3.1. Faturamento Total por Loja

| Loja | Faturamento (R$) | Ranking |
|------|-------------------|---------|
| Loja 1 | R$ 1.534.509,12 | 1º |
| Loja 2 | R$ 1.488.459,06 | 2º |
| Loja 3 | R$ 1.464.025,03 | 3º |
| Loja 4 | R$ 1.384.497,58 | 4º |

**Observações:**
- A Loja 1 apresenta o maior faturamento, gerando R$ 150.011,54 a mais que a Loja 4 (menor faturamento)
- A diferença entre a maior e menor loja é de aproximadamente 10,8%

### 3.2. Média de Avaliação dos Clientes

| Loja | Avaliação Média | Ranking |
|------|----------------|---------|
| Loja 3 | 4,05 | 1º |
| Loja 2 | 4,04 | 2º |
| Loja 4 | 4,00 | 3º |
| Loja 1 | 3,98 | 4º |

**Observações:**
- Todas as lojas apresentam avaliações próximas (diferença máxima de 0,07 pontos)
- A Loja 3 possui a melhor avaliação média dos clientes
- A Loja 1 apresenta a menor avaliação, embora ainda seja considerada positiva (>3,5)

### 3.3. Frete Médio por Loja

| Loja | Frete Médio (R$) | Ranking |
|------|------------------|---------|
| Loja 1 | R$ 34,69 | 4º (maior) |
| Loja 2 | R$ 33,62 | 3º |
| Loja 3 | R$ 33,07 | 2º |
| Loja 4 | R$ 31,28 | 1º (menor) |

**Observações:**
- A Loja 4 apresenta o menor frete médio, sendo mais competitiva em custos de logística
- A Loja 1 apresenta o maior frete médio, o que pode impactar negativamente a satisfação do cliente e a competitividade

### 3.4. Ticket Médio por Loja

| Loja | Ticket Médio (R$) | Ranking |
|------|-------------------|---------|
| Loja 1 | R$ 650,49 | 1º |
| Loja 2 | R$ 630,97 | 2º |
| Loja 3 | R$ 620,61 | 3º |
| Loja 4 | R$ 587,15 | 4º |

**Observações:**
- A Loja 1 apresenta o maior ticket médio, indicando maior capacidade de gerar receita por transação
- A Loja 4 apresenta o menor ticket médio, com diferença de R$ 63,34 em relação à Loja 1

### 3.5. Total de Vendas por Loja

| Loja | Total de Vendas |
|------|----------------|
| Loja 1 | 2.359 vendas |
| Loja 2 | 2.360 vendas |
| Loja 3 | 2.359 vendas |
| Loja 4 | 2.357 vendas |

**Observações:**
- Todas as lojas apresentam volume de vendas muito similar (diferença máxima de 3 vendas)
- Não há diferença significativa no volume de transações entre as lojas

---

## 4. CÁLCULO DO SCORE DE EFICIÊNCIA

### 4.1. Normalização dos Dados

Os dados foram normalizados para uma escala de 0 a 1, permitindo comparação equitativa entre as diferentes métricas.

### 4.2. Resultados do Score

| Loja | Score de Eficiência | Ranking |
|------|---------------------|---------|
| Loja 2 | 0,663 | 1º (melhor) |
| Loja 3 | 0,659 | 2º |
| Loja 1 | 0,500 | 3º |
| Loja 4 | 0,280 | 4º (pior) |

**Detalhamento do Score:**

**Loja 2 (Score: 0,663):**
- Pontos fortes: Segundo maior faturamento, segunda melhor avaliação dos clientes e bom ticket médio
- Pontos fracos: Frete médio elevado

**Loja 3 (Score: 0,659):**
- Pontos fortes: Melhor avaliação dos clientes e segundo menor frete
- Pontos fracos: Menor faturamento e menor ticket médio (entre as analisadas)

**Loja 1 (Score: 0,500):**
- Pontos fortes: Maior faturamento e maior ticket médio
- Pontos fracos: Menor avaliação dos clientes e maior frete médio

**Loja 4 (Score: 0,280):**
- Pontos fortes: Menor frete médio (mais competitivo em logística)
- Pontos fracos: Menor faturamento, menor ticket médio e avaliação intermediária

---

## 5. ANÁLISE DETALHADA POR LOJA

### 5.1. Loja 2
- ✅ **Segundo maior faturamento:** R$ 1.488.459,06
- ✅ **Segunda melhor avaliação:** 4,04/5,0
- ⚠️ **Frete médio elevado:** R$ 33,62
- ✅ **Bom ticket médio:** R$ 630,97
- **Score:** 0,663 (Melhor desempenho geral)

### 5.2. Loja 3
- ✅ **Melhor avaliação:** 4,05/5,0
- ✅ **Segundo menor frete:** R$ 33,07
- ⚠️ **Terceiro faturamento:** R$ 1.464.025,03
- ⚠️ **Terceiro ticket médio:** R$ 620,61
- **Score:** 0,659 (Segundo melhor desempenho)

### 5.3. Loja 1
- ✅ **Maior faturamento:** R$ 1.534.509,12
- ✅ **Maior ticket médio:** R$ 650,49
- ⚠️ **Menor avaliação:** 3,98/5,0
- ⚠️ **Maior frete médio:** R$ 34,69
- **Score:** 0,500 (Terceiro melhor desempenho)

### 5.4. Loja 4
- ✅ **Menor frete médio:** R$ 31,28 (mais competitivo)
- ⚠️ **Menor faturamento:** R$ 1.384.497,58
- ⚠️ **Menor ticket médio:** R$ 587,15
- ⚠️ **Avaliação intermediária:** 4,00/5,0
- **Score:** 0,280 (Menor desempenho geral)

---

## 6. RECOMENDAÇÃO FINAL

### 6.1. Loja Recomendada para Venda

**RECOMENDA-SE A VENDA DA LOJA 4**

### 6.2. Justificativa

Com base na análise completa dos dados, a **Loja 4** apresenta o menor score de eficiência (0,610), indicando desempenho inferior em múltiplos aspectos críticos:

1. **Menor Faturamento:** A Loja 4 gera R$ 150.011,54 a menos que a Loja 1, representando uma diferença significativa de aproximadamente 10,8% em receita.

2. **Menor Ticket Médio:** Com R$ 587,15, a Loja 4 apresenta o menor valor médio por transação, indicando menor capacidade de gerar receita por venda.

3. **Avaliação Intermediária:** Embora a avaliação (4,00) seja positiva, está abaixo das outras lojas, especialmente quando comparada à Loja 3 (4,05).

4. **Pontos Positivos Insuficientes:** Embora tenha o menor frete médio (aspecto positivo), isso não compensa o desempenho inferior nas outras métricas críticas.

### 6.3. Comparação com Outras Lojas

| Métrica | Loja 4 | Diferença vs Melhor |
|---------|--------|---------------------|
| Faturamento | R$ 1.384.497,58 | -R$ 150.011,54 vs Loja 1 |
| Avaliação | 4,00 | -0,05 vs Loja 3 |
| Frete Médio | R$ 31,28 | +R$ 3,41 vs Loja 1 (menor é melhor) |
| Ticket Médio | R$ 587,15 | -R$ 63,34 vs Loja 1 |
| Score | 0,280 | -0,383 vs Loja 2 |

### 6.4. Benefícios da Venda da Loja 4

1. **Concentração de Recursos:** Permite focar investimentos e esforços nas 3 lojas mais eficientes (Loja 2, 3 e 1).

2. **Otimização Operacional:** Reduz complexidade operacional, permitindo melhor gestão das unidades restantes.

3. **Investimento Estratégico:** O capital obtido com a venda pode ser reinvestido em melhorias nas lojas mais promissoras.

4. **Redução de Custos:** Elimina custos fixos e variáveis de uma unidade menos eficiente.

5. **Melhoria de Margem:** Concentra o faturamento em lojas com melhor desempenho financeiro.

---

## 7. ANÁLISE DE RISCOS E CONSIDERAÇÕES

### 7.1. Riscos da Decisão

- **Perda de Receita:** A venda da Loja 4 representa uma redução de aproximadamente R$ 1.384.497,58 em faturamento anual.
- **Cobertura de Mercado:** Verificar se a Loja 4 atende uma região estratégica que não pode ser coberta pelas outras lojas.

### 7.2. Mitigações

- **Expansão nas Lojas Restantes:** Investir em marketing e melhorias nas lojas 1, 2 e 3 para compensar a receita perdida.
- **Análise de Mercado:** Avaliar se a região da Loja 4 pode ser atendida por outras unidades ou por e-commerce.

### 7.3. Próximos Passos Recomendados

1. **Valoração da Loja 4:** Realizar avaliação completa do patrimônio e ativos da loja.
2. **Análise de Mercado:** Verificar oportunidades de mercado na região da Loja 4.
3. **Plano de Transição:** Desenvolver plano detalhado para migração de clientes e funcionários.
4. **Investimento nas Lojas Restantes:** Elaborar plano de investimento para melhorar ainda mais o desempenho das lojas 1, 2 e 3.

---

## 8. CONCLUSÃO

A análise dos dados demonstra claramente que a **Loja 4 apresenta o menor desempenho geral** quando comparada às outras unidades da rede Alura Store. Com o menor faturamento, menor ticket médio e score de eficiência significativamente inferior (0,280 vs 0,500-0,663 das outras lojas), a venda desta unidade é recomendada.

Esta decisão permitirá ao Senhor João:
- Concentrar recursos nas lojas mais eficientes
- Otimizar a operação da rede
- Investir em melhorias estratégicas
- Aumentar a rentabilidade geral do negócio

A recomendação é baseada exclusivamente nos dados analisados e nos indicadores objetivos de desempenho apresentados neste relatório.

---

**Preparado por:** Equipe de Análise de Dados  
**Data:** Dezembro 2024  
**Versão:** 1.0

---

## APÊNDICE A: DETALHAMENTO TÉCNICO

### A.1. Bibliotecas Utilizadas
- Pandas: Manipulação e análise de dados
- Matplotlib: Visualização de dados
- NumPy: Cálculos numéricos

### A.2. Processo de Cálculo do Score

O score de eficiência foi calculado através da seguinte fórmula:

```
Score = (Faturamento_Norm × 0,30) + 
        (Avaliação_Norm × 0,30) + 
        (Frete_Norm × 0,20) + 
        (Ticket_Norm × 0,20)
```

Onde:
- **Faturamento_Norm:** Normalização do faturamento (0 a 1)
- **Avaliação_Norm:** Normalização da avaliação (0 a 1)
- **Frete_Norm:** Normalização invertida do frete (menor é melhor)
- **Ticket_Norm:** Normalização do ticket médio (0 a 1)

### A.3. Dados Brutos

**Total de Registros:** 9.435 vendas  
**Período:** 2020 a 2023  
**Fontes:** Arquivos CSV das lojas 1, 2, 3 e 4

---

*Fim do Relatório*


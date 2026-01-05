# 📊 Análise de Churn de Clientes — Telecom X

## 📌 Visão Geral do Projeto
A evasão de clientes (churn) é um dos principais desafios do setor de telecomunicações, impactando diretamente a receita e aumentando os custos de aquisição.  
Este projeto tem como objetivo **analisar o comportamento dos clientes e identificar os principais fatores associados ao churn**, utilizando dados históricos de uma empresa fictícia do setor (**Telecom X**).

A análise é focada na geração de **insights acionáveis para o negócio**, por meio de análise exploratória de dados e visualizações.

---

## 🎯 Objetivos
- Identificar os principais fatores que influenciam a evasão de clientes
- Analisar o comportamento dos clientes ao longo do tempo
- Gerar recomendações estratégicas baseadas em dados
- Criar base para futuros modelos preditivos de churn

---

## 🗂️ Conjunto de Dados
- Fonte: Dataset fictício inspirado em cenários reais de telecom
- Volume: Aproximadamente 7.032 clientes
- Variável alvo: `cancelamento` (1 = Sim, 0 = Não)

### Principais Variáveis
- Tempo de contrato
- Tipo de contrato
- Valor mensal
- Total gasto
- Método de pagamento
- Serviços contratados (Internet, Telefonia, Segurança, Suporte etc.)

---

## 🧹 Limpeza e Preparação dos Dados
As seguintes etapas foram realizadas:
- Tratamento de valores ausentes
- Codificação de variáveis categóricas (Sim/Não → 1/0)
- Verificação e correção dos tipos de dados
- Engenharia de atributos:
  - Criação da variável `conta_custos_diarios` a partir do valor mensal
- Validação da consistência e qualidade dos dados

---

## 📈 Análise Exploratória de Dados (EDA)

### 🔹 Tempo de Contrato
- Clientes que cancelaram apresentam **menor tempo de contrato**
- A maior parte da evasão ocorre **nos primeiros meses**

### 🔹 Tipo de Contrato
- **Contratos mensais** apresentam as maiores taxas de churn
- Contratos anuais e bienais demonstram maior retenção

### 🔹 Preço e Gastos
- Valores mensais elevados aumentam a probabilidade de cancelamento
- Existe um **ponto crítico em torno de R$ 70,00**, a partir do qual o churn cresce significativamente
- Clientes com maior gasto acumulado tendem a permanecer por mais tempo

### 🔹 Serviços Contratados
- Clientes sem serviços adicionais cancelam com maior frequência
- **Segurança Online** e **Suporte Prioritário** atuam como fortes fatores de retenção
- **Telefonia** contribui para maior permanência
- Clientes com **Fibra Óptica** apresentam maior churn, sugerindo possíveis problemas técnicos ou desalinhamento de expectativa

### 🔹 Método de Pagamento
- **Cheque eletrônico** apresenta alta correlação com cancelamento
- Métodos automáticos possuem menores taxas de churn

### 🔹 Perfil do Cliente
- Clientes sem dependentes cancelam com mais facilidade
- Gênero não apresentou impacto significativo na evasão

---

## 🔍 Análise de Correlação
- Correlação positiva entre `conta_custos_mensais`, `conta_custos_diarios` e `conta_custos_totais`
- Correlação negativa entre `conta_custos_totais` e cancelamento

➡️ Clientes mais antigos e engajados apresentam menor probabilidade de churn.

---

## 🧠 Principais Insights
- A evasão não ocorre de forma aleatória
- O maior risco de churn está nos primeiros meses
- Contratos mensais apresentam altíssima taxa de cancelamento
- Preços elevados sem valor percebido aceleram a evasão
- Serviços adicionais reduzem significativamente o churn
- Métodos de pagamento automáticos aumentam a retenção

---

## 💡 Recomendações Estratégicas
- Fortalecer o onboarding nos primeiros 90 dias
- Incentivar a migração para contratos de maior duração
- Reforçar benefícios em planos com valores acima de R$ 70,00
- Criar pacotes com serviços adicionais como padrão
- Incentivar métodos de pagamento automáticos com benefícios

---

## 🚀 Próximos Passos
- Desenvolvimento de modelo preditivo de churn
- Criação de dashboards interativos
- Testes A/B de estratégias de retenção

---

## 🛠️ Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Google Colab

---

## 📌 Considerações Finais
Este projeto demonstra como a **análise de dados pode apoiar decisões estratégicas**, reduzir a evasão de clientes e melhorar a experiência do consumidor no setor de telecomunicações.

---

📬 Conecte-se comigo:
- LinkedIn: [[Seu LinkedIn](https://www.linkedin.com/in/souleosantos/)]

# 📊 Análise de Sinistros Rodoviários no Brasil

Este projeto apresenta uma análise detalhada dos acidentes em rodovias federais brasileiras, com foco em segurança viária, perfil das vítimas e principais fatores causadores. O trabalho envolve o tratamento de bases públicas, modelagem de dados, criação de métricas em **DAX** e o desenvolvimento de um dashboard interativo no **Power BI**.

---

## 🎯 Objetivo da Análise

Transformar dados brutos de sinistros rodoviários em informações estratégicas para políticas de segurança e prevenção, permitindo:
* **Identificar** as principais causas de acidentes e sua letalidade.
* **Monitorar** a evolução temporal das ocorrências em relação ao ano anterior.
* **Analisar** a distribuição geográfica dos sinistros por Unidade Federativa (UF).
* **Entender** o perfil demográfico (gênero) das pessoas envolvidas nos acidentes.

---

## ❓ Perguntas de Negócio Respondidas

1. Qual a evolução mensal do volume de acidentes e como ela se compara ao ano anterior?
2. Quais são as 10 principais causas que geram sinistros nas rodovias?
3. Quais estados (UFs) apresentam o maior número de fatalidades?
4. Qual o percentual de letalidade dos acidentes no período analisado?
5. Qual o perfil de gênero predominante entre as vítimas e envolvidos?

---

## 🔍 Principais Insights

* **Volume de Ocorrências**: Foram registrados 72 mil acidentes no período selecionado (2025), apresentando uma leve redução de 0,90% em relação ao ano anterior.
* **Fatores Humanos**: A "Ausência de reação do condutor" e a "Reação tardia ou ineficiente" figuram como as principais causas de acidentes, superando fatores como ingestão de álcool.
* **Concentração Geográfica**: O estado de Minas Gerais (MG) apresenta o maior volume de fatalidades no ranking nacional, seguido por estados como Paraná (PR) e Bahia (BA).
* **Sazonalidade**: A análise temporal revela picos de acidentes em determinados meses, como dezembro, permitindo o planejamento de operações sazonais de fiscalização.
* **Perfil de Vítimas**: Homens representam a vasta maioria dos envolvidos em sinistros (mais de 63%), indicando um público-alvo prioritário para campanhas de conscientização.

---

## 🛠️ Ferramentas Utilizadas

- Power BI (Visualização e Dashboard)
- DAX (Cálculo de medidas de inteligência de tempo e variação)
- Power Query (Tratamento, limpeza de valores nulos e agrupamento de categorias)

---

## 📈 Principais Indicadores (KPIs)

Foram desenvolvidas medidas em DAX para cálculo dos principais indicadores, incluindo:
- Total de Acidentes: Volume bruto de ocorrências registradas.
- Total de Mortos: Soma de fatalidades ocorridas no local do sinistro.
- % Letalidade: Proporção de acidentes que resultaram em óbitos.
- Variação Acidentes %: Comparativo percentual de acidentes em relação ao ano anterior.

---

## 📊 Análises Desenvolvidas
- Top 10 - Causas de Acidentes: Gráfico de barras horizontais para fácil leitura de descrições longas.
- Evolução Mensal: Gráfico de linhas comparando o ano atual com o ano anterior para identificar tendências.
- Top 10 - Fatalidades por Estado: Identificação dos estados críticos em termos de segurança viária.
- Perfil por Gênero: Visualização de pizza para análise demográfica simplificada (Masculino, Feminino, Não Informado).
- Menu de Filtros Lateral: Navegação intuitiva por Ano, Mês, UF, Causa e Condição Climática.

---

## 📁 Estrutura do Projeto

- data/ → Bases de dados em Excel
- powerbi/ → Arquivo do dashboard em Power BI (.pbix)
- docs/ → Documentação e imagens do projeto

---

## 📌 Contexto

Projeto desenvolvido no contexto acadêmico, com foco na aplicação prática de conceitos de Análise de Dados, modelagem, DAX e visualização, simulando um cenário real de análise gerencial no contexto de sinistros de trânsito.

---

## 🖼️ Preview do Dashboard

![Dashboard](ProjetoA3/docs/dashboard.png)

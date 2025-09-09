# Análise de Dados para PProductions 📊
**Autora:** Amanda Montarroios

## Visão Geral 📈
Esse projeto foi desenvolvido como uma solução de consultoria de dados para um estúdio de cinema fictício, a PProductions. O objetivo é analisar um dataset de 1000 filmes de alta avaliação do IMDB para identificar padrões e gerar uma recomendação estratégica e baseada em dados sobre qual perfil de filme o estúdio deve produzir para maximizar seu sucesso financeiro e de crítica.

## Principais Destaques da Análise 📑
Esta análise vai além de métricas superficiais, utilizando enriquecimento de dados e uma abordagem focada em negócio para gerar insights acionáveis. Os principais destaques são:

 - **Análise Financeira Robusta:** Os dados de faturamento foram ajustados pela inflação e enriquecidos com um dataset externo de orçamentos. Isso permitiu o cálculo do Retorno sobre Investimento (ROI), a métrica de sucesso mais relevante para o negócio.

 - **Insights Acionáveis por Gênero:** A análise revelou que, embora gêneros como Ação e Aventura gerem alto faturamento bruto, nichos como Terror, Mistério e Animação apresentam um ROI consistentemente superior, representando oportunidades de investimento altamente eficientes.

 - **Análise Temática com NLP:** Utilização de uma nuvem de palavras (wordcloud) sobre as sinopses dos filmes de maior ROI para identificar temas narrativos recorrentes. A análise mostrou que, mesmo em filmes de grande sucesso financeiro, o público se conecta com temas universais de jornadas pessoais, relações humanas e conflitos.

 - **Modelagem Preditiva:** Desenvolvimento de um pipeline de Machine Learning com RandomForestRegressor para prever a nota de um filme no IMDB. O modelo serve como uma ferramenta de apoio à decisão para avaliar o potencial de recepção de novos projetos.

## Tecnologias Utilizadas 🖥️
 - **Linguagem:** Python 3.11+

 - **Bibliotecas Principais:** Pandas, Scikit-learn, Matplotlib, Seaborn, Joblib

 - **Bibliotecas de Enriquecimento:** CPI (para ajuste de inflação), Wordcloud (para NLP)

 - **Ambiente:** Jupyter Notebook no Visual Studio Code

## Como rodar ⌨️

### 1.Pré-requisitos
Ter o Python (versão 3.8 ou superior) instalado.

Ter o Git instalado para clonar o repositório.

### 2.Instalação

git clone https://github.com/amanda-montarroios/projeto_dados_filmes.git

cd dados_filme

cd projeto_dados_filmes

#### 3.Criar o ambiente
python -m venv venv

#### 4.Ativar o ambiente (Windows)
.\venv\Scripts\activate

#### 4.1.Ativar o ambiente (macOS/Linux)
source venv/bin/activate

#### 5.Instale as dependências:
Todas as bibliotecas necessárias estão listadas no arquivo requirements.txt.

Bash

pip install -r requirements.txt

#### 6.Execução
Após a instalação, abra a pasta do projeto no Visual Studio Code. O arquivo principal com toda a análise é o Jupyter Notebook:

notebooks/analise_filmes.ipynb

Abra este arquivo e execute as células em ordem para visualizar todo o processo, desde a limpeza dos dados até a recomendação final.

## Conclusão da Análise 💾
A recomendação final para a PProductions é investir em um filme de Terror ou Mistério com um orçamento controlado (entre $15M e $40M) e duração de 110-140 minutos. A narrativa deve focar em uma jornada de personagem com um forte núcleo emocional para maximizar o engajamento do público e, consequentemente, o Retorno sobre Investimento.

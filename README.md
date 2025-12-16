# NLP_FECAF


Projeto de Análise de Feedbacks com Processamento de Linguagem Natural (PLN)

📋 Sobre o Projeto
Este projeto implementa um sistema completo de análise de feedbacks de clientes utilizando técnicas avançadas de Processamento de Linguagem Natural (PLN) e Machine Learning. O sistema é capaz de:

🔍 Classificar automaticamente sentimentos (positivo, negativo, neutro)

📊 Extrair insights sobre tópicos recorrentes

📈 Analisar padrões temporais e sazonais

🎯 Identificar palavras-chave por categoria

📉 Prever tendências futuras com base em dados históricos

🎯 Objetivos
Automatizar a análise de feedbacks de clientes

Identificar padrões de satisfação e insatisfação

Fornecer insights acionáveis para tomada de decisão

Criar um pipeline reprodutível de análise de textos em português

🛠️ Tecnologias e Bibliotecas
Linguagem e Ambiente
Python 3.12

Google Colab / Jupyter Notebook

Pandas, NumPy para manipulação de dados

Processamento de Linguagem Natural
NLTK: Tokenização, stemming, stopwords

Gensim: Word2Vec para embeddings semânticos

Scikit-learn: TF-IDF, LDA, modelos de ML

Machine Learning
Random Forest, SVM, Regressão Logística

Latent Dirichlet Allocation (LDA) para análise de tópicos

Visualização
Matplotlib, Seaborn, Plotly

WordClouds, heatmaps, gráficos temporais

NetworkX para análise de redes de palavras

Outras
Transformers (BERT para potencial expansão)

TSNE para redução dimensional

Validação cruzada e métricas de avaliação

📁 Estrutura do Projeto
text
├── CÉLULA 1: Instalação e Importações
├── CÉLULA 2: Sistema de Carga de Dados Avançado
├── CÉLULA 3: Carregamento dos Dados e Análise Inicial
├── CÉLULA 4: Pré-processamento de Texto
├── CÉLULA 5: Vetorização Avançada de Texto
├── CÉLULA 6: Análise de Sentimentos com Modelos Tradicionais
├── CÉLULA 7: Visualizações Avançadas e Análise de Padrões
├── CÉLULA 8: WordCloud e Análise de Palavras por Sentimento
├── CÉLULA 9: Dashboard Interativo e Relatório Executivo
└── CÉLULA 10: Exportação de Resultados e Finalização
📊 Métricas e Resultados
O sistema alcançou os seguintes resultados com um dataset de 200 feedbacks:

Acurácia do Modelo: 38.0%

Satisfação do Cliente: 46.5%

Insatisfação Identificada: 35.0%

Feedbacks Neutros: 18.5%

Top Tópicos Identificados:
Tópico 1: Neutro (66.7%) - focado em prazos e conformidade

Tópico 2: Positivo (66.7%) - relacionado a excelência e perfeição

Tópico 3: Negativo (50.0%) - problemas e defeitos

Tópico 4: Positivo (96.8%) - altamente específico positivo

Tópico 5: Negativo (75.0%) - fortemente associado a insatisfação

🚀 Como Executar
Requisitos
bash
pip install nltk gensim wordcloud textblob transformers torch plotly seaborn scikit-learn sentencepiece
Execução
Execute as células em sequência no Google Colab ou Jupyter Notebook

Carregue seu dataset ou use os dados simulados

Acompanhe as análises e visualizações geradas automaticamente

Exporte os resultados completos

📈 Principais Funcionalidades
1. Sistema de Carga de Dados Flexível
Upload de arquivos CSV/Excel/JSON

Carregamento de múltiplos arquivos por categoria

Dataset simulado para testes

Análise automática de estrutura

2. Pipeline Completo de PLN
Limpeza e normalização de texto

Tokenização em português

Remoção de stopwords personalizadas

Stemming com RSLP (português)

Vetorização com TF-IDF e Word2Vec

3. Modelagem Avançada
Comparação de múltiplos algoritmos de ML

Validação cruzada e curvas de aprendizado

Análise de importância de features

Clusterização semântica

4. Visualizações Interativas
WordClouds por sentimento

Heatmaps de correlação tópico-sentimento

Análise temporal de intensidade

Redes de coocorrência de palavras

Dashboard executivo completo

5. Exportação e Relatórios
Dataset completo com análises

Relatório executivo em CSV

Estatísticas detalhadas por sentimento

Análise de erros de classificação

Palavras mais frequentes por categoria

🔍 Análises Realizadas
Análise Temporal
Identificação de tendências ao longo do tempo

Padrões sazonais semanais (pico de negatividade às segundas-feiras)

Evolução da intensidade dos sentimentos

Análise de Tópicos
5 tópicos principais identificados

Distribuição de sentimentos por tópico

Palavras-chave representativas

Análise de Palavras
WordClouds diferenciadas por sentimento

Bigramas mais frequentes

Palavras únicas características

Redes de coocorrência semântica

📊 Resultados Destacados
Insights de Negócio
Segundas-feiras têm maior taxa de reclamações (42.9%)

Tópico 5 concentra 75% dos feedbacks negativos

Palavras-chave positivas: "perfeito", "atendimento", "qualidade"

Palavras-chave negativas: "detesto", "defeito", "não"

Recomendações Estratégicas
Priorizar análise de feedbacks negativos das segundas-feiras

Focar na melhoria dos aspectos relacionados ao Tópico 5

Reforçar pontos fortes identificados no Tópico 4

Implementar dashboard de monitoramento contínuo

📚 Fundamentação Teórica
O projeto aplica conceitos fundamentais de PLN:

Tokenização e Stemming: NLTK com RSLPStemmer para português

Vetorização: TF-IDF para representação lexical + Word2Vec para semântica

Modelagem: Random Forest, SVM e Regressão Logística para classificação

Análise de Tópicos: LDA para descoberta de temas latentes

Avaliação: Métricas de acurácia, F1-score e validação cruzada

📁 Arquivos Gerados
O sistema exporta automaticamente:

analise_completa_feedbacks.csv - Dataset completo com análises

relatorio_executivo_feedbacks.csv - Métricas principais

estatisticas_por_sentimento.csv - Estatísticas detalhadas

analise_erros_classificacao.csv - Análise de erros

palavras_mais_frequentes.csv - Top palavras por categoria

🔮 Próximos Passos
Integração com APIs de plataformas de feedback

Implementação de BERT para análise mais sofisticada

Sistema de alertas em tempo real

Análise comparativa entre diferentes períodos

Expansão para outros idiomas

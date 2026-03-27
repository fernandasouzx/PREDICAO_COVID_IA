# Trabalho Final de Inteligência Artificial 2025/1

> Desafio final da disciplina de Inteligência Artificial 2025/1, ministrada pelo professor Dr. Rafael Teixeira.  
> O objetivo do desafio é prever o risco de morte para pacientes com COVID-19 no Brasil, utilizando dados do Ministério da Saúde que refletem características de pacientes reais brasileiros.

## Objetivo do Projeto

- Criar um modelo preditivo capaz de estimar a **probabilidade de óbito** em pacientes com COVID-19.  
- Utilizar dados reais do **SIVEP-Gripe (Ministério da Saúde/SUS)**, incluindo informações demográficas, clínicas e de atendimento hospitalar.  
- Aplicar técnicas de **pré-processamento, feature engenieer e modelagem preditiva**, considerando a métrica **F1**.

## Modelagem

- Foram testados diferentes algoritmos de machine learning, incluindo **LightGBM**, **Random Forest** e **HistGradientBoostingClassifier**.  
- O modelo **HistGradientBoostingClassifier** apresentou o melhor desempenho com base na métrica **F1**, sendo escolhido como modelo final do projeto.  
- A implementação e os experimentos estão disponíveis no notebook `HistGradientBoostingClassifier.ipynb`.

--- 
## Estrutura do Repositório

├── Artigo/  
│   └── Predição de Risco de Morte SRAG - HistGradientBoostingClassifier.pdf # Artigo final do projeto  

├── data/  
│   ├── dicionario_de_dados.pdf # Descrição das variáveis  
│   ├── train.csv # Dados de treino  
│   ├── test.csv # Dados de teste  
│   ├── sample_submission.csv # Exemplo de submissão  
│   └── train.zip # Versão compactada dos dados  

├── Notebooks/  
│   ├── HistGradientBoostingClassifier.ipynb # Modelo final e experimentos principais  
│   └── prediçãoIA.ipynb # Exploração e testes iniciais  

├── requirements.txt # Dependências do projeto  

├── Makefile  

---
## Equipe

- **Anna Bheatryz M. Santos**  
- **Esther Victória A. Santos**  
- **Fernanda L. Souza**  

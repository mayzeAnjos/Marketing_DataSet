## Objetivo

Desenvolver um modelo de Machine Learning para prever se um cliente irá subscrever (ou não) um depósito a prazo em uma campanha de marketing direto de uma instituição bancária portuguesa. O objetivo é auxiliar o banco a identificar clientes com maior propensão a adquirir o produto, otimizando campanhas telefônicas e reduzindo custos.

---

## Integrantes

- **Mayze dos Anjos Nunes:** Análise Inicial e Compreensão dos Dados
- **Isabele de Almeida Nunes:** Análise Exploratória, Pré-processamento e Separação dos Dados
- **Larissa Carvalho Nascimento Gonçalves:** Modelagem, Avaliação e Discussão dos Resultados

---

## Fonte dos Dados

O conjunto de dados utilizado é o **Bank Marketing Dataset**, disponível no UCI Machine Learning Repository.

- **Fonte:** [UCI Machine Learning Repository - Dataset ID 222](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- **Citação:** Moro, S., Rita, P., & Cortez, P. (2014). Bank Marketing [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5K306.
- **Licença:** Creative Commons Attribution 4.0 International (CC BY 4.0)

O carregamento é feito diretamente no notebook através da biblioteca `ucimlrepo`, utilizando o comando `fetch_ucirepo(id=222)`.

---

# Tipo da Tarefa

**Classificação Binária** — prever se o cliente irá subscrever um depósito a prazo (variável alvo `y`), com duas classes possíveis: `yes` (subscreveu) ou `no` (não subscreveu).

---

##  Como Executar o Notebook no Google Colab
1. Clique no botão abaixo para abrir o notebook diretamente no ambiente do Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SEU_USUARIO_GITHUB/NOME_DO_REPOSITORIO/blob/main/NOME_DO_NOTEBOOK.ipynb)

2. No menu superior do Colab, clique em **Ambiente de execução** -> **Executar tudo** (ou pressione `Ctrl + F9`).
3. Aguarde o processamento de todas as células de código até a geração dos gráficos finais.

---

## Divisão das Contribuições do Grupo

- **Mayze dos Anjos:** Definição do problema, compreensão dos dados (seções 5.1 e 5.2), análise de valores ausentes, duplicatas e distribuição do alvo. Participação no vídeo, criação do repositório, cocriação do README e do notebook.
- **Isabele Nunes:** Análise exploratória dos dados (EDA) com visualizações e pré-processamento/limpeza de atributos. Participação no vídeo, cocriação do notebook.
- **Larissa Carvalho:** Divisão dos dados em Treino/Teste de forma estratificada, balanceamento de classes via SMOTE, implementação e treinamento dos modelos mínimos obrigatórios (`SGDClassifier`, `RandomForestClassifier`) e adicionais (`LogisticRegression`, `XGBoost`, `Baseline`), cálculo das métricas de avaliação, matrizes de confusão, curva ROC e discussão crítica dos resultados. Participação no vídeo, cocriação do README e do notebook.

---

##  Apresentação em Vídeo
- **Link do Vídeo:** [Clique aqui para assistir à apresentação do projeto](https://LINK_DO_SEU_VIDEO_AQUI)

---

##  Declaração de Uso de Ferramentas de Inteligência Artificial
- **Ferramenta Utilizada:** Gemini (Google) e DeepSeek.
- **Finalidade:** Auxílio na estruturação dos scripts Python para modelagem com `scikit-learn`, construção dos gráficos de matriz de confusão/curva ROC e organização da documentação técnica.
- **Forma de Verificação:** Todo o código gerado foi revisado, adaptado aos nomes das variáveis do projeto Bank Marketing, testado e validado no ambiente Google Colab para garantir a ausência de erros e conformidade com as regras da disciplina.

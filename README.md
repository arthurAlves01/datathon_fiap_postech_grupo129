📊 Datathon FIAP Postech — Associação Passos Mágicos

🎯 Sobre o Projeto

Este repositório contém a solução desenvolvida para o Datathon FIAP
Postech, cujo objetivo é utilizar Data Analytics e Machine Learning para
gerar insights educacionais e apoiar a tomada de decisão da Associação
Passos Mágicos, organização social que há mais de 30 anos transforma a
vida de crianças e jovens em situação de vulnerabilidade social por meio
da educação.

A análise foi construída a partir da base de dados educacional referente
aos anos 2022, 2023 e 2024, buscando identificar padrões de
desenvolvimento dos alunos, fatores de risco e oportunidades de melhoria
no programa educacional.

------------------------------------------------------------------------

Links importantes

- Aplicação Streamlit: https://datathon-fiap-129.streamlit.app/
- Vídeo: https://drive.google.com/file/d/1vaTQ9qmndFxaLiSLx6NFHowOO6mq041j/view
- Apresentação: https://docs.google.com/presentation/d/1N-BKkSq1YszlrAAOK9FfO5Sz4U4jlSTJ1IVgtdjLF2E/edit?usp=sharing

------------------------------------------------------------------------

🧠 Problema de Negócio

A Passos Mágicos deseja entender:

-   Como os alunos evoluem academicamente e emocionalmente ao longo do
    programa;
-   Quais fatores impactam desempenho e engajamento;
-   Como identificar alunos em risco de defasagem educacional antes que
    ela aconteça;
-   Evidências quantitativas da efetividade do programa educacional.

------------------------------------------------------------------------

📌 Objetivos do Projeto

Este projeto responde às seguintes frentes analíticas:

1.  Adequação do nível (IAN) — análise da defasagem educacional.
2.  Desempenho acadêmico (IDA) — evolução ao longo dos anos e fases.
3.  Engajamento (IEG) — relação com desempenho e ponto de virada.
4.  Autoavaliação (IAA) — coerência entre percepção e desempenho real.
5.  Aspectos psicossociais (IPS) — identificação de padrões preditivos.
6.  Aspectos psicopedagógicos (IPP) — validação da defasagem.
7.  Ponto de virada (IPV) — fatores determinantes.
8.  Multidimensionalidade (INDE) — combinação de indicadores
    explicativos.
9.  Modelo preditivo — previsão de risco educacional.
10. Efetividade do programa — impacto nas fases educacionais.
11. Insights adicionais — recomendações estratégicas.

------------------------------------------------------------------------

🗂 Estrutura do Repositório

    📦 datathon_fiap_postech_grupo129
    │
    ├── data/                     # Bases de dados (tratadas e auxiliares)
    ├── notebooks/                # Análises exploratórias e modelagem
    ├── src/                      # Funções auxiliares e pipeline
    ├── app/                      # Aplicação Streamlit
    │   └── app.py
    │
    ├── models/                   # Modelos treinados (.pkl)
    ├── images/                   # Imagens utilizadas na apresentação
    │
    ├── requirements.txt          # Dependências do projeto
    ├── README.md                 # Documentação do projeto
    └── .gitignore

------------------------------------------------------------------------

🔎 Metodologia

O projeto foi dividido em cinco etapas principais:

1️⃣ Entendimento do Negócio

-   Interpretação dos indicadores educacionais
-   Definição das perguntas analíticas
-   Tradução das dores de negócio em hipóteses de dados

2️⃣ Preparação dos Dados

-   Limpeza e padronização
-   Tratamento de valores ausentes
-   Engenharia de features
-   Consolidação temporal dos indicadores

3️⃣ Análise Exploratória (EDA)

-   Distribuições dos indicadores
-   Evolução temporal dos alunos
-   Correlações entre dimensões educacionais
-   Identificação de padrões comportamentais

4️⃣ Modelagem Preditiva

Construção de um modelo para prever:

👉 Probabilidade de risco de defasagem educacional

Etapas realizadas:

-   Feature Engineering
-   Split treino/teste
-   Treinamento de modelos supervisionados
-   Avaliação por métricas de classificação
-   Interpretação dos resultados

5️⃣ Deploy da Solução

-   Aplicação interativa em Streamlit
-   Disponibilização do modelo para uso prático
-   Interface para simulação de risco educacional

------------------------------------------------------------------------

🤖 Modelo Preditivo

O modelo foi desenvolvido para identificar alunos com maior
probabilidade de:

-   queda de desempenho;
-   aumento da defasagem;
-   redução de engajamento.

Pipeline do Modelo

-   Seleção de variáveis educacionais e psicossociais
-   Normalização dos dados
-   Treinamento supervisionado
-   Avaliação com métricas como:
    -   Accuracy
    -   Precision
    -   Recall
    -   ROC-AUC

O objetivo principal é apoio preventivo, permitindo intervenção
antecipada da equipe pedagógica.

------------------------------------------------------------------------

📈 Principais Insights

Entre os principais achados:

-   Engajamento possui forte associação com desempenho acadêmico.
-   Indicadores psicossociais antecedem mudanças de performance.
-   Autoavaliação desalinhada pode indicar risco futuro.
-   A evolução entre fases sugere impacto positivo do programa.
-   Combinação multidimensional de indicadores explica melhor o
    desempenho global do que métricas isoladas.

------------------------------------------------------------------------

🖥 Aplicação Streamlit

A aplicação permite:

✅ Inserir indicadores do aluno
✅ Calcular probabilidade de risco
✅ Apoiar decisões pedagógicas
✅ Simular cenários educacionais

Executar localmente

    git clone https://github.com/arthurAlves01/datathon_fiap_postech_grupo129.git

    cd datathon_fiap_postech_grupo129

    pip install -r requirements.txt

    streamlit run app/app.py

------------------------------------------------------------------------

🎬 Entregáveis do Datathon

-   ✅ Repositório GitHub com código completo
-   ✅ Análises exploratórias
-   ✅ Modelo preditivo em Python
-   ✅ Aplicação Streamlit deployada (https://datathon-fiap-129.streamlit.app/)
-   ✅ Apresentação executiva (storytelling)
-   ✅ Vídeo explicativo (até 5 minutos) (https://drive.google.com/file/d/1vaTQ9qmndFxaLiSLx6NFHowOO6mq041j/view)

------------------------------------------------------------------------

🧰 Tecnologias Utilizadas

-   Python
-   Pandas
-   NumPy
-   Scikit-learn
-   Matplotlib / Seaborn
-   Streamlit
-   Git & GitHub

------------------------------------------------------------------------

👥 Equipe

Grupo 129 — FIAP Postech

-   Arthur Alves
-   Jackson dos Santos
-   Luis Henrique
-   Willian Baldin

------------------------------------------------------------------------

🌱 Sobre a Associação Passos Mágicos

A Associação Passos Mágicos atua desde 1992 promovendo transformação
social por meio da educação, oferecendo:

-   ensino de qualidade;
-   suporte psicológico e psicopedagógico;
-   desenvolvimento de protagonismo;
-   ampliação da visão de mundo de crianças e jovens.

O projeto busca utilizar dados como ferramenta para ampliar ainda mais
esse impacto social.

------------------------------------------------------------------------

📬 Contato

Caso queira saber mais sobre o projeto:

📎 Repositório:
https://github.com/arthurAlves01/datathon_fiap_postech_grupo129

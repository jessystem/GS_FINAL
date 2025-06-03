# 📊 Projeto Global Solutions: Desvendando Desastres e Combatendo Fake News em SP

Este repositório contém a entrega do nosso projeto de Global Solutions para a disciplina de Statistics for Machine Learning and AI (1º Semestre - 2025). Nosso time foi desafiado a atuar como cientistas de dados para o Governo de São Paulo, utilizando o poder dos dados para analisar informações críticas e auxiliar no combate à desinformação (Fake News).

## 🎯 A Missão: Dados Contra a Desinformação
Fomos contratados para auxiliar o Governo de São Paulo na análise e refutação de narrativas sobre a gestão de desastres. O cenário proposto é claro: o atual governo iniciou em 2021, e o partido da oposição esteve no poder entre 2016 e 2020. Nosso desafio é investigar diversas "notícias" (cenários hipotéticos) e, com base em análises de dados, classificá-las como "Fake" ou "Not Fake", além de gerar insights e argumentos para defender a gestão governamental.

Para isso, mergulhamos no Sistema Nacional de Informações sobre Segurança de Barragens (SNISB), um dataset rico que nos permite explorar eventos críticos e suas implicações.

## 🛠️ Tecnologias Utilizadas
Este projeto foi desenvolvido utilizando as seguintes ferramentas e bibliotecas:

- Python: Linguagem de programação principal.
- Pandas: Para manipulação e análise de dados.
- NumPy: Para operações numéricas eficientes.
- Matplotlib / Seaborn: Para criação de visualizações e gráficos.
- Scikit-learn: Para modelos de Machine Learning (se utilizados em análises futuras).
- Google Collab :  Ambiente de desenvolvimento interativo.

## 1. Entendendo os Dados (Análise Exploratória Inicial)
Antes de qualquer análise aprofundada, precisamos conhecer nossa base de dados. Este desafio foca na descrição geral do dataset.

a) Quantas linhas e colunas temos no dataset?
b) Quantos municípios e UFs (Unidades Federativas) estão registrados na base?
c) Qual é o período mínimo e máximo registrado para os eventos de desastres?
d) Quantas e quais "descrições de tipologia" (tipos de desastres) temos na base?

## 2. Desvendando Incêndios Florestais (Rebatendo o Blog "Homem Neutro")
O Blog “Homem Neutro” alegou um aumento drástico de incêndios florestais desde o início do governo atual. 
Vamos aos dados para verificar essa afirmação!

- a) Qual a frequência de incêndios florestais antes (período de 2016 a 2020) e depois (a partir de 2021) do governo?
- b) Como podemos gerar um gráfico que mostre claramente essas diferenças?
- c) Com base nos dados, essa alegação é “Fake” ou “Not Fake”?
- d) Como o governo poderia se defender publicamente nesse caso, utilizando os dados?

## 3. Analisando a Questão dos Desabrigados (Respondendo ao X "@SomosDoBrasilOficial")
A conta "@SomosDoBrasilOficial" postou: “Nunca houve na história desse país tantos desabrigados!!! #semcasasempaz”. Será essa uma verdade?

- a) Como podemos gerar um dataset contendo o histórico em SP do número de desabrigados?
- b) Conseguimos criar um gráfico histórico para identificar se houve um pico recorde de desabrigados?
- c) Essa postagem é “Fake” ou “Not Fake” de acordo com a análise?
- d) Que tipo de postagem o governo deveria fazer para responder a essa afirmação com dados?

## 4. Instituições de Ensino Abandonadas? (Análise da Alegação do Partido PLC)
O Partido dos Liberais Conservadores (PLC) afirmou que, "durante o período do governo [atual], as instituições Danificadas cresceram 5%, Destruídas cresceram 7% e no total 10%". Hora de verificar a precisão dessas informações!

- a) Como gerar um dataset com o histórico em SP do número de instituições de ensino danificadas, destruídas e a soma das duas?
- b) É possível comparar esses percentuais nos períodos antes (2016-2020) e depois (a partir de 2021) do governo?
- c) A afirmação do PLC é “Fake” ou “Not Fake” segundo os dados?
- d) Qual postagem o governo deveria fazer para responder a essa afirmação?

## 5. Manifestação na Paulista: Governo Perdeu o Controle? (Análise Crítica para Defesa)
Diante de uma manifestação alegando perda de controle em relação a mortes, feridos, enfermos e desabrigados, e altos gastos com danos materiais, nossa análise é a chave para a defesa.

- a) Como realizar todas as análises necessárias sobre mortos, feridos, enfermos e desabrigados para defender a gestão?
- b) Podemos levantar os gastos com danos materiais que o governo tem enfrentado e analisar suas tendências?
- c) Que diversas análises podemos demonstrar para os jornalistas sedentos por respostas, baseando-nos nos dados?




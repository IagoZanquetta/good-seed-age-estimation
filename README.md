# good-seed-age-estimation
Projeto de visão computacional para estimar a idade de clientes da rede Boa Semente a partir de imagens faciais.

## Visão Geral

Este projeto tem como objetivo desenvolver um modelo de visão computacional capaz de estimar a idade de clientes com base em fotografias faciais. A proposta é apoiar a rede de supermercados **Boa Semente** em tarefas relacionadas à verificação etária, especialmente em contextos de venda de produtos com restrição de idade.

A análise utiliza técnicas de deep learning aplicadas a imagens para treinar e avaliar um modelo capaz de aprender padrões visuais associados à idade.

## Problema de Negócio

A rede **Boa Semente** busca utilizar visão computacional para auxiliar na estimativa da idade de seus clientes. Essa solução pode contribuir para reduzir erros em verificações manuais, agilizar o atendimento e oferecer apoio adicional em situações que envolvem produtos com restrição etária.

Neste projeto, o desafio é construir e avaliar um modelo capaz de estimar idade a partir de imagens faciais, considerando desempenho preditivo e aplicabilidade prática.

## Dados

O conjunto de dados original utilizado neste projeto **não está incluído neste repositório**.

O notebook foi mantido com os outputs salvos para permitir a visualização da análise, da modelagem e das conclusões mesmo sem os arquivos originais.

Para executar o projeto do zero, será necessário adicionar manualmente o dataset original utilizado no notebook.

## Objetivos da Análise

Este projeto busca responder perguntas como:

- É possível estimar a idade de uma pessoa a partir de imagens faciais com desempenho satisfatório?
- Quais técnicas de deep learning são adequadas para esse problema?
- O modelo treinado apresenta qualidade suficiente para apoiar uma aplicação real?
- Como os resultados podem contribuir para o contexto operacional da empresa?

## Etapas do Projeto

O projeto foi desenvolvido nas seguintes etapas:

1. carregamento e inspeção inicial dos dados
2. análise exploratória das imagens e rótulos
3. preparação dos dados para treinamento
4. construção do modelo de visão computacional
5. treinamento e validação
6. avaliação do desempenho
7. interpretação dos resultados
8. conclusões de negócio

## Ferramentas e Bibliotecas

- Python
- Pandas
- NumPy
- Matplotlib
- TensorFlow / Keras
- Pillow
- Jupyter Notebook

## Estrutura do Repositório

```text
good-seed-age-estimation/
├── .gitignore
├── README.md
├── requirements.txt
└── good_seed_age_estimation.ipynb
````

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/IagoZanquetta/good-seed-age-estimation.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd good-seed-age-estimation
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o arquivo `good_seed_age_estimation.ipynb` no Jupyter Notebook, JupyterLab ou VS Code.

> Observação: para executar todas as células do zero, será necessário adicionar manualmente o conjunto de dados original esperado pelo notebook.

## Principais Pontos Analisados

Entre os principais focos do projeto, estão:

* exploração de dados visuais
* preparação de imagens para treinamento
* construção de modelo de deep learning
* avaliação de desempenho preditivo
* interpretação dos resultados
* aplicabilidade prática no contexto de negócio

## Resultados

O notebook inclui:

* análise exploratória inicial
* preparação do problema para visão computacional
* construção e treinamento do modelo
* avaliação dos resultados
* interpretação com foco em negócio
* conclusão final

## Conclusão

Este projeto demonstra como técnicas de visão computacional e deep learning podem ser aplicadas para estimar idade com base em imagens faciais. A análise mostra o potencial de uso desse tipo de solução em contextos operacionais reais, especialmente como ferramenta de apoio à verificação etária e à automação de processos no varejo.

## Autor

**Iago Zanquetta**

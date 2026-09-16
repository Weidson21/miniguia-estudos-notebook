# Miniguia de Estudos de Análise de Dados com NotebookLM

## Contexto

Este projeto foi desenvolvido como parte de um desafio da DIO com o objetivo de utilizar o NotebookLM como ferramenta de apoio ao aprendizado.

O tema escolhido foi **Fundamentos de Análise de Dados com Python e pandas**, buscando compreender os principais conceitos necessários para iniciar os estudos na área de dados.

Durante o projeto, foram utilizadas fontes oficiais e materiais de referência para construir um mapa de aprendizagem, realizar um diagnóstico inicial e explorar diferentes formas de utilização de prompts para organizar e avaliar o conhecimento.

## Objetivos

* Compreender os fundamentos necessários para iniciar os estudos de análise de dados com Python e pandas;
* Organizar os conteúdos em uma sequência progressiva de aprendizagem;
* Utilizar o NotebookLM para sintetizar e organizar informações presentes nas fontes selecionadas;
* Experimentar diferentes estratégias de prompting;
* Identificar dificuldades e melhorar os prompts a partir dos resultados obtidos;
* Criar um material de revisão que possa ser reutilizado posteriormente durante os estudos.

## Curadoria das fontes

Foram selecionadas fontes oficiais e materiais de referência relacionados ao Python e à biblioteca pandas. A seleção buscou priorizar conteúdos que apresentassem os fundamentos necessários para iniciar os estudos de análise de dados.

### Fontes utilizadas

1. **Python — Tutorial oficial**

   * https://docs.python.org/pt-br/3/tutorial/
   * Utilizado para consultar fundamentos da linguagem Python, como estruturas de dados, controle de fluxo e funções.

2. **pandas — Documentação oficial**

   * https://pandas.pydata.org/docs/
   * Utilizado como referência para os principais recursos da biblioteca pandas.

3. **10 minutes to pandas**

   * https://pandas.pydata.org/docs/user_guide/10min.html
   * Utilizado para compreender conceitos fundamentais como Series, DataFrame, seleção, agrupamento e manipulação de dados.

4. **pandas — Getting Started / Intro Tutorials**

   * https://pandas.pydata.org/docs/getting_started/intro_tutorials/index.html
   * Utilizado como material introdutório para exploração, seleção, limpeza e análise de dados.

### Critérios de seleção

As fontes foram escolhidas considerando:

* autoridade das fontes;
* relação direta com o tema do projeto;
* conteúdo introdutório e progressivo;
* possibilidade de utilização como referência durante os estudos;
* documentação oficial das tecnologias utilizadas.

## Engenharia de Prompts e Cicatrizes

Durante o projeto, foram realizados experimentos com diferentes prompts para organizar o conteúdo e utilizar o NotebookLM como ferramenta de aprendizagem ativa.

### Experimento 1 — Construção do mapa inicial

O primeiro prompt teve como objetivo identificar os principais conceitos necessários para compreender os fundamentos da análise de dados com Python e pandas.

A solicitação pediu que os conceitos fossem organizados em uma sequência lógica, apresentando sua importância, relação com Python ou pandas e exemplos práticos.

**Resultado:** o NotebookLM apresentou uma sequência abrangente de conceitos, incluindo fundamentos de Python, leitura de arquivos, Series e DataFrame, exploração, seleção, tratamento de dados ausentes, agrupamento e transformação.

**Cicatriz identificada:** a resposta apresentou muitos conceitos e detalhes técnicos para uma primeira etapa de estudo. Apesar de correta e abrangente, ela não funcionava tão bem como um primeiro mapa de aprendizagem para um iniciante.

### Experimento 2 — Refinamento do mapa de aprendizagem

A partir do problema identificado no primeiro resultado, o prompt foi reformulado para limitar o conteúdo a cinco etapas progressivas:

1. Fundamentos de Python;
2. Estruturas de dados com pandas;
3. Exploração e compreensão dos dados;
4. Limpeza e transformação dos dados;
5. Análise e interpretação dos dados.

Também foram especificados o nível do estudante, os conceitos essenciais e a necessidade de evitar recursos avançados.

**Resultado:** o conteúdo passou a apresentar uma estrutura mais objetiva e adequada para servir como mapa inicial de estudos.

**Aprendizado:** definir claramente o objetivo, o público, o nível de profundidade e o formato esperado da resposta tornou o resultado mais adequado à finalidade do estudo.

### Experimento 3 — Diagnóstico inicial

Depois da criação do mapa de aprendizagem, o NotebookLM foi utilizado para criar um diagnóstico com 10 questões de dificuldade progressiva.

As questões foram distribuídas entre fundamentos de Python, Series e DataFrame, exploração, limpeza e tratamento de dados, agrupamento e análise.

O objetivo foi utilizar o NotebookLM não apenas para apresentar informações, mas também para estimular a participação ativa no processo de aprendizagem.

**Resultado:** foi gerado um conjunto de questões conceituais e práticas que permitiu realizar uma avaliação inicial dos conhecimentos relacionados ao tema.

### Principais aprendizados com os experimentos

Os experimentos mostraram que a qualidade do resultado depende não apenas das fontes utilizadas, mas também da forma como o objetivo é especificado no prompt.

Entre os principais pontos observados estão:

* definir claramente o objetivo da solicitação;
* indicar o nível de conhecimento esperado;
* estabelecer limites para a profundidade da resposta;
* especificar a estrutura desejada;
* utilizar os resultados anteriores para aprimorar novos prompts;
* transformar o NotebookLM de uma ferramenta de consulta em uma ferramenta de apoio ao processo de aprendizagem.

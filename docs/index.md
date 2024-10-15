# Bem-vindo à Wiki de Tecnologias SESIDEV

Este é o ponto de partida para a nossa documentação de tecnologias e boas práticas que utilizamos em nossos projetos. Aqui você encontrará informações sobre diversas ferramentas e frameworks essenciais para o desenvolvimento e implantação de nossas soluções. Explore os tópicos abaixo para aprender mais e contribuir com o crescimento deste repositório de conhecimento.

## Tecnologias Documentadas

### Banco de Dados Relacional (PostgreSQL)
Saiba mais sobre como utilizamos o PostgreSQL para gerenciar dados relacionais com eficiência e robustez.

- [Conceitos Básicos de PostgreSQL](postgress/conceitos-basicos.md)
- [Configuração de Ambiente](postgress/configuracao-ambiente.md)

### Django Rest Framework (DRF)
Aprenda a construir APIs escaláveis e seguras usando o Django Rest Framework, além de boas práticas para lidar com autenticação e autorização.

- [Introdução ao DRF](drf/introducao.md)
- [Autenticação com DRF](drf/autenticacao.md)

### DBT Core
Entenda como utilizamos o DBT Core para transformar dados e criar pipelines de modelagem dentro do contexto de Data Engineering.

- [Modelagem com DBT](dbt/modelagem.md)
- [Execução de Pipelines](dbt/execucao-pipelines.md)

### Apache Airflow
Veja como orquestramos e monitoramos fluxos de trabalho complexos com o Apache Airflow para garantir a eficiência de nossas tarefas de ETL.

- [Introdução ao Airflow](airflow/introducao.md)
- [Criação de DAGs Personalizadas](airflow/criacao-dags.md)

### Jupyter Notebooks
Explore o uso de Jupyter Notebooks para visualização de dados, prototipagem de modelos e análises exploratórias.

- [Ambiente de Desenvolvimento com Jupyter](jupyter/ambiente.md)
- [Boas Práticas de Notebook](jupyter/boas-praticas.md)

### Docker
Descubra como utilizamos o Docker para criar ambientes isolados e replicáveis, facilitando o desenvolvimento e a implantação de nossas aplicações.

- [Conceitos de Containerização](docker/conceitos.md)
- [Criando e Executando Imagens Docker](docker/criacao-imagens.md)

## Organização é a chave de uma boa documentação


- Para exibir a estrutura de pastas como código, você pode usar ```plaintext para criar blocos de código dentro do Markdown.
- Ao manter a indentação correta e os caracteres de barra vertical (`│`) e os ramos (`├──`), a estrutura será apresentada de forma clara e organizada no seu MkDocs.

Isso fará com que a estrutura de pastas apareça como código formatado na página principal da sua wiki (`index.md`).

# Estrutura de Pastas

```plaintext
docs/
├── index.md
├── postgress/
│   ├── conceitos-basicos.md
│   └── configuracao-ambiente.md
├── drf/
│   ├── introducao.md
│   └── autenticacao.md
├── dbt/
│   ├── modelagem.md
│   └── execucao-pipelines.md
├── airflow/
│   ├── introducao.md
│   └── criacao-dags.md
├── jupyter/
│   ├── ambiente.md
│   └── boas-praticas.md
└── docker/
    ├── conceitos.md
    └── criacao-imagens.md
```

## Contribuições

Todos os desenvolvedores da SESIDEV são convidados a contribuir com esta wiki. Se você deseja adicionar um novo artigo ou atualizar uma seção existente, siga as diretrizes de contribuição no repositório GitHub.

Vamos juntos construir um guia completo e útil para a comunidade e para os nossos projetos!

# Bem vindo
## Repositório de Projetos 
- na Nuvem AWS
- de Data Science / Machine Learning

No meu repositório de projetos você encontrará uma lista dos meus projetos mais recentes e interessantes, com uma breve descrição de cada um.

## Projetos Cloud - AWS

### - Criar tabelas no Redshift Serverless e gerar um dashboard com Metabase

Ler 5 arquivos csv a partir de um bucket.
Copiar as tabelas dentro do Redshift Serverless.
Gerar um dashboard com Metabase.
**Serviços: S3, Iam, Redshift Serverless e Metabase.**

Video: https://drive.google.com/file/d/1IRtIfgQOlJlYziuSoF28oyi6KoU4VK3n/view?usp=drive_link

### - Gerar Dados de Vendas e Dashboard no Power BI

Usando a lib Faker criar dados sintéticos de vendas.
Salvar os dados num bucket da AWS.
Gerar um dashboard e atualizar sob demanda ou agendamento.
**Serviços: Git Actions, S3, Iam e Power BI.**

### - MVP de um E-commerce

Construção de um MVP de um site de e-commerce.
O Terraform e o Ansible foi usado nesse projeto.
O Magento foi a base de construção do site.
**Serviços: EC2, IAM, Terraform, Ansible e Magento.**

### - Execução de comandos em servidores na cloud

Dois servidores precisavam ser atualizados com agentes de segurança.
O Terraform foi configurado para criação da infraestrutura e o System Manager aplicou a atualização em cada instância criada.
**Serviços: EC2, IAM, System Manager, SNS e Terraform.**

### - Migração de aplicação on premise para cloud

Uma aplicação, Wiki, rodando localmente foi migrada para execução na AWS.
Foi feito o planejamento do projeto, os recursos foram provisionados e a migração concluida com sucesso.
**Serviços: EC2, RDS, VPN, Subnet e Internet Gateway.**

### - Criar contas de usuários via script na AWS

Foram criados 5 grupos para administrar as permissões dos usuários.
Dentro do CloudShell na AWS, foi executado o script bash que cria o usuário no seu respectivo grupo.
**Tools: Bash, CloudShell, IAM.**

### - Caged - dados de empregos formais no Brasil

Web scrap de dados do site do Caged usando Python.
Dados são salvos num bucket e posteriormente copiados para um cluster do Redshift.
As tabelas geradas são lidas pelo Metabase, que gera um dashboard apresentando os dados.
**Tools: Python, GitHub Action, S3, Redshift e Metabase.**

### - AWS CI/CD - Continous Integration / Continous Delivery

Implementação do CI/CD, usando CodeDeploy, CodeBuild e CodePipeline.
Uma aplicação é recompilada, o código atualizado e a versão nova é levada para um bucket no S3 que hospeda um site estático.

### - Hands on AWS - Load Balancing

Implementação do serviço de Load Balancing, simulando dois ambientes.
Dois grupos de instâncias distintas, onde uma aplicação HTTP rodando em cada instância do grupo é acessada, de acordo com um filtro implementado na url do DNS do load balancer.

---

## Projetos de Data Science e Machine Learning

Este repositório contém uma variedade de projetos desenvolvidos utilizando técnicas de Data Science e Machine Learning. Cada projeto aborda diferentes aspectos e técnicas, desde análise exploratória de dados até implementações de modelos de machine learning avançados. Confira abaixo os projetos disponíveis:

### - Estudo das Transações com Pix no Brasil

Análise das transações via Pix realizadas em 2022 e 2023. Este projeto investiga o total de transações feitas por cidade ao longo do dia, além das transações feitas até o momento em 2023.

### - Campeonato Brasileiro Serie A 2023

Extração de dados de páginas web para criação de uma aplicação web com Streamlit. Uma planilha CSV foi extraída através do Git Actions, que executou um script Python para ler uma página web. Os dados coletados foram tratados e utilizados como dataset para criação de uma aplicação web.

### - Análise de Viagens de Ônibus em 2019

Identificação de insights a partir do serviço prestado de viagens de ônibus. Foram lidos 6GB de dados usando pyspark, realizando agrupamentos para diferentes conjuntos de análise. O projeto também envolveu a geração de diversos gráficos e a previsão da quantidade de viagens para a cidade de São Paulo utilizando o modelo Prophet.

### - Fake Data

Criação de dados sintéticos para testes de modelos e análises. Este projeto inclui templates de dados prontos, como nomes, endereços e sexo, além da capacidade de criar novos dados de acordo com a necessidade e objetivo.

### - Stocks & Prophet

Previsão do valor de ações nos próximos 365 dias utilizando yfinance para extração de dados da bovespa e Prophet para previsão dos preços de fechamento das ações.

### - Colab, MLFlow, Ngrok e Pycaret

Exemplo de integração de ferramentas para análise de Churn. Utiliza Colab como ambiente de desenvolvimento, MLFlow para salvar os artefatos gerados, Ngrok para compartilhar o desenvolvimento do app e Pycaret para tratar, treinar os dados e avaliar os modelos.

### - Github Action: Atualizando um dashboard

Atualização e publicação de dashboard criado com Datapane. A execução dos passos é administrada pelo Github Action, permitindo gerenciar o ambiente de execução e a sequência dos passos.

### - Integrando: PDI, S3 e Power BI

Levando dados via Pentaho PDI até o serviço de repositório AWS, Bucket S3. Buscando os dados no S3 através de scripts Python no Power BI.

### - Chatbot B3

Chatbot que traz a cotação de 3 ações e faz previsões usando a lib Prophet.

### - AutoEncoder

Detecção de anomalias/fraude e remoção de ruído/redução de dimensão utilizando a arquitetura de autoencoder em redes neurais.

### - Previsão de Preço

Projeto que iniciou com a coleta de dados, via scrap em sites de venda de apartamentos.
Seguido pelo tratamento dos dados, treinamento do modelo e deploy na nuvem.
Veja em Artigos e Raio-X

### - Kaggle & Colab

Análise exploratória, treinamento e avaliação de modelos.
- Comparecimento as Consultas no Sus
- Classificação da Pressão Sanguinea
- Segmentação de Clientes

### - Previsão da Ação PETR4

Exemplo de aplicação do algoritmo Arima numa série temporal.

### - Tableau Public

Diversos dashboards construidos com dados públicos.

### - Controle de Peso

Modelo configurado para descoberta dos itens que respeitem critérios.
O peso total <= 10kg.

### - Análise de Acidentes de Transito

Descoberta dos elementos que compõem um acidente de trânsito.

### - Rpubs

Estudos de aplicação de R para criação de gráficos.
Rpbus repositório público.

### - R - Modelo Titanic

Modelo construido usando R.

Cada projeto possui um link para mais detalhes e código fonte. Confira!
## Meu portfolio de projetos:
## https://silviolima07.github.io/
## Artigos:
## https://silviolima07.medium.com/


Espero que você ache esses projetos interessantes! 
Se precisar de mais informações ou tiver alguma dúvida, fique à vontade para entrar em contato.



<!--**silviolima07/silviolima07** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


# Projeto_Boti
Case 2 para processo da Boticário - Parte I

Dado o início do case 2 e as três bases enviadas (2017,2018 e 2019), iniciei as etapas criando um Bucket no Google Cloud Storage

(a) Bucket criado > 'https://console.cloud.google.com/storage/browser/dados_projeto_case2;tab=objects?forceOnBucketsSortingFiltering=true&orgonly=true&project=case-2-boticario&supportedpurview=organizationId'

(b) Upload dos três arquivos nesse bucket > 'dados_projeto_case2'
*Antes de importar os arquivos, converti em CSV dado a indisponibilidade de reconhecimento do formato XLSX para importação

(c) Criação de conjunto de dados no Big Query 

(d) Criação de notebooks de apoio para transformação dos dados

(e) Definição de dataframe a partir das bases de vendas 

(f) Tratamento de dados, remoção de duplicatas e conversão dos dados em formatos padrões como integer, string e datetime 

(g) Após essas etapas, as tabelas foram salvas em uma camada de dados definida como "raw" <> "rw"

(h) Para caracterizar a camada trusted, defini as 4 tabelas pedidas no comando do case utilizando SQL

(i) Acrescentei o desenvolvimento de uma tabela dimensão, com dados de marca e linha pelo ID (chave-primária)

(j) Após as tabelas terem sido salvas, fiz consultas em SQL para validá-las.

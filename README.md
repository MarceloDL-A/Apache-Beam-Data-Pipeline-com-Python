## Engenharia de dados: conhecendo Apache Airflow

1. O que são Data Pipelines Ver primeiro vídeo

- O que são data pipelines e para que servem;

- A diferença dos modelos Batch e Streaming;

- A diferença entre ETL e ELT;

- O que são Data Lakes e seus usos com Data Warehouses;

- O que são o Apache Airflow e Spark, e para que são usados.


2. Airflow: Gancho conectado ao Twitter

- Como instalar e começar a usar o Apache Airflow;

- Como acessar a API to Twitter via código;

- O que são e como criar conectores no Airflow;

- O que são e como criar ganchos no Airflow.


3. Airflow: Exportando dados para o Data Lake

- O que são e como criar operadores no Airflow;

- As características que devemos buscar em um operador;

- O que é e como vamos estruturar o estágio bruto do data lake;

- Os 3 Vs do Big Data;

- O que são e como criar plugins no Airflow.


4. Spark: Consumindo dados brutos do Data Lake

- O que é e como instalar o Apache Spark;

- Como usar o Spark como biblioteca do Python ou pacote independente;

- A iniciar um cluster local e enviar comandos diretamente ao Spark;

- A usar o comando spark_submit e enviar scripts para o Spark;

- A diferença entre dataframes e RDDs;

- Comandos basicos Spark como select, orderBy, printSchema, show, sum e outros;

- A trabalhar com estruturas complexas usando explode para achatar o esquema.


5. Spark: Exportando os dados transformados para o Data Lake

- A exportar dados usando Apache Spark em formatos como JSON e CSV;

- A identificar uma coluna do DataFrame com boa cardinalidade para então particionar os dados;

- Como configurar a quantidade de arquivos em cada partição usando funções como Repartition e Coalesce;

- A dividir os dados no Data Lake usando a arquitetura de medalhas;

- A escrever um trabalho em pyspark usando boas práticas;

- Como integrar o Spark ao Airflow usando conexões e operadores.


6. Finalizando o Pipeline

- A configurar um DAG para executar diariamente;

- A forma como são usados os parâmetros padrão do Airflow;

- Como executar um DAG para dias no passado;

- A extrair informações na camada Gold;

- Sobre a ferramenta Zeppelin de análise de dados usando o Spark.

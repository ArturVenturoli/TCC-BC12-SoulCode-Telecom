# TCC BC12 SoulCode Telecom - Realizado em Abril de 2022
 Este trabalho de conclusão foi realizado em grupo com tema determinado pelos professores.

**Integrantes do grupo:**
Artur Venturoli, Maurício da Silva Barros, Renan Marques, Renato Romão.

**Requisitos do projeto:**

**Descrição**
• Todas as equipes deverão entregar as mesmas especificações, de acordo com o seu respectivo tema.
• Vocês deverão aplicar os conceitos vistos durante o curso para tratar, organizar e modelar os dados de no mínimo 2 datasets escolhidos por vocês seguindo o tema de sua equipe.
• Obrigatoriamente deverá conter as tecnologias Google Cloud Platform(Cloud Storage), Python, Pandas, PySpark, SparkSQL, Apache Beam*, Data Studio, Big Query e MongoDB.

**Principais Habilidades a serem avaliadas**
• Oralidade e comunicação em público.
• Capacidade de argumentação
• Habilidade de codificação em Python e utilização de suas bibliotecas
• Habilidade de interpretação e análise de dados.
• Capacidade de implementação de códigos utilizando as bibliotecas Pandas e PySpark.
• Capacidade de implementação de consultas utilizando a linguagem SQL.
• Capacidade Analítica e Interpretativa.
• Capacidade de organização e grupo


**REQUISITOS OBRIGATÓRIOS**
• Obrigatoriamente os datasets devem ter formatos diferentes (CSV / Json / Parquet / Sql / NoSql) e 1 deles obrigatoriamente tem que ser em CSV.
• Operações com Pandas (limpezas , transformações e normalizações) 
• Operações usando PySpark com a descrição de cada uma das operações.
• Operações utilizando o SparkSQL com a descrição de cada umas das operações.
• Os datasets utilizados podem ser em lingua estrangeira , mas devem ao final terem seus dados/colunas exibidos na lingua PT-BR
• Os datasets devem ser salvos e operados em armazenamento cloud obrigatoriamente dentro da plataforma GCP (não pode ser usado Google drive ou armazenamento alheio ao google)
• Os dados tratados devem ser armazenados também em GCP, mas obrigatoriamente em um datalake(Gstorage ) , DW(BigQuery) ou em ambos.
• Os datasets originais devem ser armazenados em MySql
• Os Dataframe(s) resultante(s) deve(m) estar em uma coleção do mongoDb atlas (informar a key de acesso ao cluster) e preferencialmente criar o usuario (definido pelos professores) e senha (definida pelos professores) no cluster
• Deve ser feito análises dentro do Big Query utilizando a linguagem padrão SQL com a descrição das consultas feitas.
• Deve ser criado no datastudio um dashboard para exibição gráfica dos dados tratados trazendo insights importantes
• E deve ser demonstrado em um workflow simples (gráfico) as etapas de ETL com suas respectivas ferramentas.


**REQUISITOS DESEJÁVEIS**
• Implementar captura e ingestão de dados por meio de uma PIPELINE com modelo criado em apache beam usando o dataflow para o work
• Utilizar o dataflow com algum modelo pré-definido
• Criar plotagens usando pandas para alguns insights durante o processo de Transformação 
• Por meio de uma PIPELINE fazer o carregamento dos dados normalizados diretamente para um DW ou DataLake ou ambos
• Montar um relatório completo com os insights que justificam todo o processo de ETL utilizado
• Levantar custos com a utilização do google cloud no período do projeto e possíveis otimizações de custo
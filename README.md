## Soluções de Engenharia de Dados com PySpark para Análise Macroeconômica Escalável

# 🧠 Resumo da Solução
BigData Clean & Transform é um projeto desenvolvido com Apache Spark em Python (PySpark), voltado para o tratamento, limpeza e transformação de dados econômicos macroestruturais do Reino Unido. Ele exemplifica boas práticas em engenharia de dados para projetos que exigem processamento distribuído, manipulação de datasets grandes e automação de rotinas analíticas em ambiente cloud.

| 💡 Recurso                                   | 🧩 Descrição                                                                                                         |
| -------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| **Setup automático do Spark 3.0**            | Inclui configuração do ambiente Spark/Hadoop e dependências em notebooks Colab para rápida execução em nuvem.        |
| **Ingestão de dados econômicos**             | Carregamento direto de dados CSV macroeconômicos (população e taxa de desemprego) via `wget` remoto.                 |
| **Data Wrangling com PySpark**               | Processos robustos de renomeação, filtragem semântica, tratamento de valores nulos e deduplicação.                   |
| **Filtragem semântica com `left_anti` join** | Remove registros descritivos não analíticos, como linhas com “Units”, garantindo dados puros para análise.           |
| **Engenharia de variáveis temporais**        | Criação de coluna `century` a partir do ano, permitindo agrupamentos históricos de maneira eficiente.                |
| **Paralelização e gravação particionada**    | Dados são reparticionados por século e exportados em CSV, prontos para análises posteriores ou ingestão em sistemas. |


# 🚀 Diferenciais e Valor Agregado

✅ Escalabilidade: Pronto para processar milhões de linhas com o poder do Spark.

✅ Integração com pipelines automatizados: Ideal para ser acoplado a workflows de ETL em sistemas cloud-native.

✅ Foco em dados limpos e confiáveis: Aplicação clara de boas práticas em data cleaning e pré-processamento.

✅ Ambiente portátil e replicável: Projetado para execução em ambientes como Google Colab ou clusters Spark.

# 🔬 Aplicações e Cenários de Uso

Análises econômicas históricas para instituições de pesquisa e bancos.

Projetos de Data Lake com ingestão limpa e transformações iniciais.

Benchmark de aprendizado para quem está evoluindo de Pandas para PySpark.

Treinamentos corporativos em manipulação de grandes volumes de dados com Spark.



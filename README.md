Topics:
- Routine to automatic download csv
- Turn csv to json
- save json on mongo
- set running routine on docker

Tools:
- Jupyter
- Requets
- Pandas
- Flask
- Pymongo

Roteiro:
0. Motivação
    0.1. Porque transformar dados de csv para json e salvar em um banco
    0.2. Porque python
1. Apresentar fonte de dados
    1.1. Qual fonte de dados foi escolhida
    1.2. Como analisar a fonte em busca de definir uma rotina de extração
2. Como consumir a fonte de dados
    2.1. Apresentando Requets
    2.2. Como fazer requisições utilizando a lib
    2.3. Parametrizando URL através de variável de ambiente
3. Tratando e transformando os dados
    3.1. Apresentando Pandas
    3.2. Como ler arquivos CSV utilizando o pandas
    3.3. Tratamento básico
    3.4. Como transformar para arquivo JSON
4. Persistindo os dados 
    4.1. Apresentando MongoDB e Pymongo
    4.2. Como utilizar pymongo
    4.3. Parametrizando credenciais para conectar no banco
5. Configurando rotina de execução
    5.1. Apresentando docker e cron
    5.2. Como executar a rotina periodicamente

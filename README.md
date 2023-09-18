# Projeto de ETL para Cálculo do Valor Bruto de Aluguéis 
Este é um projeto Python que visa realizar uma extração, transformação e carregamento (ETL) de um conjunto de dados em formato CSV contendo informações sobre aluguéis. O objetivo principal deste projeto é calcular o valor bruto, o valor por m2 e o valor bruto por m2 dos aluguéis com base nos dados fornecidos e criar um novo conjunto de dados limpo e processado que reflete esses cálculos. 
## Funcionalidades Principais
- Extração dos dados: Utilizamos a biblioteca Pandas para importar os dados do arquivo CSV de aluguéis e carregá-los em um DataFrame. 
- Limpeza dos dados: Remoção de valores nulos.
- Cálculo do Valor Bruto: Com os dados limpos, calculamos o valor bruto dos aluguéis com base nas informações disponíveis.
- Exportação dos Dados: O resultado final é exportado para um novo arquivo CSV, contendo as informações processadas e o valor bruto calculado para cada aluguel. 
## Base de dados 
O database contêm as seguintes informações:
- Tipo de imóvel
- Bairro onde está localizado o imóvel
- Quantidade de quartos
- Numero de vagas
- Quantidade de suites
- Area do imóvel
- Valor do imóvel
- Valor do condominio
- Valor do IPTU
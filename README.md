# 1º Projeto - EDA - Dados de Logística da empresa Loggi

O projeto a seguir análise dados da empresa Loggi, responsável por realizar entregas ao consumidor final (last-mile) no estado do Distrito Federal do Brasil. A ideia do projeto é mapear as entregas no estado e verificar o que pode ser feito para otimizar e consequentemente reduzir custos.

Este projeto foi inteiramente realizado com Python com as seguintes bibliotecas e tecnologias:

O arquivo base estava no formato .json, logo utilizei a biblioteca JSON para manipulá-lo.
Utilizo o PANDAS para visualizar melhor os dados, como DataFrames.
Faço a limpeza das colunas que possuem dados de latitude e longitude.
Para transformar os dados de latitude e longitude em endereços reais, faço a geocodificação reversa utilizando a biblioteca GEOPY.
Importo dados cartográficos do estado do Distrito Federal disponibilizado pelo IBGE e com os endereços já organizados, crio um mapa de visualização das entregas com o GEOPANDAS.
O mapa de visualização contém a localização de todas as entregas e também dos 3 hubs de distribuição da empresa.
Crio gráficos para visualizar outros dados do arquivo utilizando as bibliotecas MATPLOTLIB e SEABORN.
Utilizo a biblioteca NUMPY para preenchimento automático de uma coluna com base em condição if-else
Para verificar os insights e conclusões tiradas, verificar o item 6. Insights.

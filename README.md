# TRE-RS Secoes and Zona Webscrapper

## Introduction

The initial purpose of this project was to help data analysts and data scientists to work with Brazilian electoral data. The Brazilian Authorities didn't used to release vote data with geographical information directly attached to it. But this changed in the 2022 elections when the Tribunal Superior Eleitoral started to add the location to some of their datasets. The first part of this project (notebooks 1) had the objective of creating that link, but this is not needed anymore.

On notebooks 2 onwards I already use the data from TSE with geographical information included.

## Notebooks distribution:

#### Process voting locations and create datasets easy to connect with voting data (deprecated):

[1 Process Zonas Eleitorais_RS.ipynb](https://github.com/guiml/2022VotesAnalytics/blob/master/1%20Process%20Zonas%20Eleitorais_RS.ipynb)
[1 Process Zonas Eleitorais_SP.ipynb](https://github.com/guiml/2022VotesAnalytics/blob/master/1%20Process%20Zonas%20Eleitorais_SP.ipynb)

#### Various exploratory Data Analytics for 2022 elections: 

[2 Votes BR.ipynb](https://github.com/guiml/2022VotesAnalytics/blob/master/2%20Votes%20BR.ipynb)
[2 Votes CO.ipynb](https://github.com/guiml/2022VotesAnalytics/blob/master/2%20Votes%20CO.ipynb)
[3 Votes NE.ipynb](https://github.com/guiml/2022VotesAnalytics/blob/master/2%20Votes%20NE.ipynb)

#### Visualizations for vote differences: 

[4 Zonas Enderecos.ipynb](https://github.com/guiml/2022VotesAnalytics/blob/master/4%20Zonas%20Enderecos.ipynb)
The outputs of the visualizations can be seen here: [Votes per sessão](https://guiml.github.io/Votos_RS_2oTurno.html) and [Difference of votes heatmap](https://guiml.github.io/Heatmap_Poa_2oTurno.html) 

#### Specific analysis for deputados in Porto Alegre: 
[5 Analise Municipais 2020.ipynb](https://github.com/guiml/2022VotesAnalytics/blob/master/5%20Analise%20Municipais%202020.ipynb)


## Technology and libraries

I used Python 9.3.13 to run this code with the following libraries installed:

* BeautifulSoup
* pandas
* urllib.request
* openpyxl
* Folium
* geopandas
* matplotlib.pyplot
* plotly_express
* numpy 
* folium

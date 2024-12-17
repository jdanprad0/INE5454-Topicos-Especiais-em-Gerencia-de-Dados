# INE5454-Topicos-Especiais-em-Gerencia-de-Dados

This application is a crawler that extracts data from [Wikipedia São Paulo's Page](https://pt.wikipedia.org/wiki/Lista_de_munic%C3%ADpios_de_S%C3%A3o_Paulo), [Wikipedia Rio de Janeiro's Page](https://pt.wikipedia.org/wiki/Lista_de_munic%C3%ADpios_do_Rio_de_Janeiro), [Wikipedia Minas Gerais' Page](https://pt.wikipedia.org/wiki/Lista_de_munic%C3%ADpios_de_Minas_Gerais).

Therefore, as a result from the spider's execution, the files below contain Santa Catarina's cities information:

`minas_gerais.csv` and `minas_gerais.json`, `rio_de_janeiro.csv` and `rio_de_janeiro.json`, `sao_paulo.csv` and `sao_paulo.json`

##

To run our application, please create venv:

`sudo apt-get install python3-venv`
`python3 -m venv webscraping`
`source webscraping/bin/activate`

Install the dependencies with the following command:

`make install`

Then, to run the spider, type the following command:

`make run`

or

`scrapy crawl cities`

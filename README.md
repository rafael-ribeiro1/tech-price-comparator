# Tech Price Comparator
*Web scraper* simples para linha de comandos em Python, para comparar o preço de produtos tecnológicos em várias lojas portuguesas.
> Simple Python Console web scraper to compare prices of tech products in portuguese stores.

### Input
**EAN** - o Número Europeu de Artigo é um código de referência único, que surge normalmente nos códigos de barras. Pode ser obtido na página do produto em alguma das lojas, para obter os preços no comparador.
> **EAN** - European Article Number is a reference code that usually appears in bar codes. It can be obtained from product pages in any store, so the prices can be compared.

### Lojas compatíveis / Compatible stores
* [Globaldata](https://www.globaldata.pt)
* [Switch Technology](https://www.switchtechnology.pt)

###### Dados obtidos / Obtained data
* Nome do produto / Product name
* Preço / Price
* Disponibilidade / Stock
* Link da página do produto / Product page link

### Modos de execução / Run modes
* #### Interativo / Interactive
Após iniciar a execução do script é pedido o EAN. Após verificar os preços, é possível ver os preços na linha de comandos, guardá-los num ficheiro TXT ou CSV.
> After starting the script execution, the user inputs the EAN. After checking the prices, the system asks the user if he wants to see the results in the console or save it in a TXT or CSV file.
* #### Não interativo / Non interactive
    * *soon*

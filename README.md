# Tech Price Comparator
*Web scraper* simples para linha de comandos em Python, para comparar o preço de produtos tecnológicos em várias lojas portuguesas.
> Simple Python Console web scraper to compare prices of tech products in portuguese stores.

### Instalação / Installation
Para poder correr o script é necessário instalar algumas bibliotecas essencias.
> In order to run the script it is needed to install some libraries.
#### requests
```
pip3 install requests
```
#### beautifulsoup4
```
pip3 install beautifulsoup4
```
#### selenium
Seguir os passos 1.2 (use *pip3*) e 1.3 da [documentação oficial](https://selenium-python.readthedocs.io/installation.html).
> Follow the steps 1.2 (use *pip3*) and 1.3 from the [documentation](https://selenium-python.readthedocs.io/installation.html).

Após instalar, altere as seguintes linhas no código da função main() do script, para que funcione:
> After installing, change the following lines of the main() function of the script code, so it works:
``` python
DRIVER_PATH = 'C:/Users/Rafael/Desktop/Programming/msedgedriver.exe'  # Change to your web driver path
driver = webdriver.Edge(executable_path=DRIVER_PATH)  # Change to the function related to your browser
driver.implicitly_wait(5)  # OPTIONAL CHANGE: if your internet connection is too slow, set an higher value
```

### Input
**EAN** - o Número Europeu de Artigo é um código de referência único, que surge normalmente nos códigos de barras. Pode ser obtido na página do produto em alguma das lojas, para obter os preços no comparador.
> **EAN** - European Article Number is a reference code that usually appears in bar codes. It can be obtained from product pages in any store, so the prices can be compared.

### Lojas compatíveis / Compatible stores
* [Globaldata](https://www.globaldata.pt)
* [Switch Technology](https://www.switchtechnology.pt)
* [Prinfor](https://www.prinfor.pt)
* [Worten](https://www.worten.pt)
* [PCDiga](https://www.pcdiga.com)

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

Projeto em que uso o PowerBI para consumir a 
<a href="https://olinda.bcb.gov.br/olinda/servico/PTAX/versao/v1/odata/CotacaoMoedaPeriodoFechamento(codigoMoeda='USD',dataInicialCotacao='02-10-2022',dataFinalCotacao='02-10-2022')?%24select=cotacaoCompra">API</a> 
do BC do Brasil buscando o valor do Dólar Americano (USD) desde 2007 até hoje.


<a href="https://olinda.bcb.gov.br/olinda/servico/PTAX/versao/v1/odata/CotacaoMoedaPeriodoFechamento(codigoMoeda='USD',dataInicialCotacao='02-10-2022',dataFinalCotacao='02-10-2022')?%24select=cotacaoCompra">API</a>

* Para requisitar uma cotação, basta alterar as variáveis *dataInicialCotacao* e *dataFinalCotacao* da url, utilizando o formato mm-dd-aaaa. Obs.: No link acima, está sendo requisitada a cotação de 10 de fevereiro de 2022.

* Também é possível requisitar cotações de outras moedas, para isso, basta  alterar a variável
*codigoMoeda* da url, utilizando um codigo de moeda válido (Ex.: EUR para Euro).

<br>
<a href="https://app.powerbi.com/view?r=eyJrIjoiOTI4NGVmMmQtOWJkZS00MTRmLWE3YTktODYyYWQzYjhmNjA0IiwidCI6ImRjZDI0NDU1LWVkMzQtNDJhZi1hZmJmLTczMzg1ODExMTU5OCJ9">Dashboard</a>

<div align="center">
	<img src="https://github.com/JCazarotto/exchange-rate-USD-BRL/blob/master/dashboard_pbi.png" alt="Dashboard PowerBI"/>
</div> 

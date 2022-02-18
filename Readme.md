Projeto em que uso o PowerBI para consumir a API do BC do Brasil buscando o valor do Dólar Americano (USD) desde 2007 até hoje.

API: https://olinda.bcb.gov.br/olinda/servico/PTAX/versao/v1/odata/CotacaoMoedaPeriodoFechamento(codigoMoeda='USD',dataInicialCotacao='02-10-2022',dataFinalCotacao='02-10-2022')?%24select=cotacaoCompra

* Para requisitar uma cotação, basta alterar as variáveis *dataInicialCotacao* e *dataFinalCotacao* da url, utilizando o formato mm-dd-aaaa. Obs.: No link acima, está sendo requisitada a cotação de 10 de fevereiro de 2022.

* Também é possível requisitar cotações de outras moedas, para isso, basta  alterar a variável
*codigoMoeda* da url, utilizando um codigo de moeda válido (Ex.: EUR para Euro).

<div align="center">
	<img src="https://github.com/JCazarotto/exchange-rate-USD-BRL/blob/master/dashboard_pbi.png" alt="Dashboard PowerBI"/>
</div> 


<iframe title="HISTÓRICO COTAÇÃO USD E EUR PARA BRL - Cotação" width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=dd9d3d5a-a3f5-48f5-ba21-6d995fda05d0&autoAuth=true&ctid=dcd24455-ed34-42af-afbf-733858111598&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLWJyYXppbC1zb3V0aC1iLXByaW1hcnktcmVkaXJlY3QuYW5hbHlzaXMud2luZG93cy5uZXQvIn0%3D" frameborder="0" allowFullScreen="true"></iframe>
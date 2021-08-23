# medicamentos-Brasil
Análise de dados acerca dos preços dos medicamentos. Elaborada para o processo seletivo da LexisNexis

### Tarefa:
Foi utilizado Python com a biblioteca Pandas para a análise dos dados

Database retirado de: https://dados.gov.br/dataset/preco-de-medicamentos-no-brasil-consumidor

1. Dê output no console o seguinte:
	a. O nome dos campos do arquivo	
	b. O produto com o maior preço de fábrica sem impostos (todos se tiver mais que um com o maior preço)
	c. Quais os possíveis tipos de produtos
	d. O produto e preço do genérico mais barato
2. Salve todos os registros com o preço final sem impostos superior a ‘100’, com comercialização 2018 marcada como ‘Sim’ e que sejam Tarja Vermelha em um arquivo chamado “output.csv”
3. Leia o arquivo que você criou no item anterior e ordene o conteúdo por ordem alfabética do campo produto (sobrescreva o arquivo com os registros ordenados).
4. Com o conteúdo deste segundo arquivo, responda:
	a. Qual o valor total (soma) dos preços finais sem imposto?
	b. Quantos tipos diferentes de produtos estão presentes?
	c. Existe algum produto que possua a mesma “substância” de um outro produto do arquivo original com preço final sem impostos inferior a ‘100’?

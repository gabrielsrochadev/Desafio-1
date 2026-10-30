# Desafio Nível 1 - PDV com Descontos (Python)

### O que o código faz
Este programa simula a lógica de um Ponto de Venda (PDV), calculando o valor final de diversas compras através da aplicação de descontos progressivos baseados na idade do cliente e no valor total da compra. No final do processo, emite um relatório sumarizado com todas as métricas financeiras.

### Como ele faz
O código recebe o valor e a idade. Em seguida, verifica se a idade é maior ou igual a 65 para aplicar 20% de desconto. Depois, verifica se o valor já descontado passa de 100 reais para aplicar mais 10%. Ele guarda cada compra numa lista utilizando `.append()` e, ao encerrar o loop através da digitação de "0", soma tudo e mostra o resumo financeiro do dia.

### Como rodar
Para executar o programa, abra o terminal do sistema na pasta `nivel_1` e digite o seguinte comando:
`python pdv.py`

### Tabela de exemplos
| # | Valor (R$) | Idade | Desconto idade | Desconto valor | Valor final esperado |
|---|---|---|---|---|---|
| 1 | 50.00 | 30 | 0% | 0% | R$ 50.00 |
| 2 | 100.00 | 30 | 0% | 0% | R$ 100.00 |
| 3 | 80.00 | 65 | 20% | 0% | R$ 64.00 |
| 4 | 100.00 | 70 | 20% | 0% | R$ 80.00 |
| 5 | 125.00 | 70 | 20% | 0% | R$ 100.00 |
| 6 | 200.00 | 30 | 0% | 10% | R$ 180.00 |
| 7 | 101.00 | 30 | 0% | 10% | R$ 90.90 |
| 8 | 200.00 | 65 | 20% | 10% | R$ 144.00 |
| 9 | 1000.00 | 80 | 20% | 10% | R$ 720.00 |
| 10| 200.00 | 64 | 0% | 10% | R$ 180.00 |

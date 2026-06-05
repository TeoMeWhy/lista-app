# Instrução

Considere a imagem de nota fiscal para extrair as seguintes informações:
- nome do produto
- valor unitário do produto
- data da compra

## Nome do Produto

Para o nome do produto, considere apenas o nome do objeto, descartando marca, medidas, peso e quantidade. Use a lista a seguir como referência:

{produtos}

## Valor Produto

Para valor do produto, em caso de unidades inteiras, considerar o valor unitário. Caso seja em kilogramas/gramas, considere o valor total.

## Resposta

Retorne os dados em formato json na seguinte estrutura:

{resposta}
# css-grid

## container
### grid-template-columns
Determina o número de colunas que o grid terá e a largura de suas colunas
grid-template-columns: 100px 120px 50px;
no exemplo acima o grid terá 3 colunas, a primeira com 100px de largura, a segunda com 120 e a terceira com 50.
caso queira que a tela determina o tamanho e divida igualmente as 3 colunas, basta colocar 'auto' em cada coluna. 
grid-template-columns: auto auto auto;

### grid-template-rows
Determnia o número de linhas que o grid terá e a altura de suas linhas.
funciona da mesma forma que o grid-template-columns, só que para linhas e suas alturas.
grid-template-rows: 100px 120px 50px;

### justify-content
alinha na horizontal as colunas

### align-content
alinha na vertial as linhas

### column-gap
espaçamento entre colunas

### row-gap
espaçamento entre linhas

### gap
atalho para o espaçamento entre linhas e colunas
gap: row-gap column-gap

## items dentro do container
### grid-column
seta o inicio e o fim da coluna
grid-clolumn: inicio/fim
exemplo:
grid-column: 1/3 ou 1/ span 2
grid-column: 1/3 - inicia na coluna 1 e para na coluna 3(ocupa a coluna 1 e 2 mas não a 3)
grid-column: 1/ span 2 - inicia na coluna 1 e termina na 2, ocupando ambas

### grid-row
funciona da mesma forma que o grid-column só que para as linhas

### grid-area
um atalho para setar o espaço ocupado pela coluna e linha no grid
grid-area: row-start / column-start / row-end / column-end
exemplo:
grid-area: 1 / 1 / span 2 / span 2 - inicia na linha 1 e coluna 1 e se expande até a linha 2 e coluna 2.

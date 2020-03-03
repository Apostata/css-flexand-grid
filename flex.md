# Flexbox

## Container
### flex-direction 
determina a direção dos itens no container

coluna ou linha 

coluna - um em baixo do outro
linha - um do lado do outro

as propriedades
justify-content e align-items são afetados pelo flex-direction

#### com flex-direction: row:
justify-content alinha os itens na horizontal 
e o align-items na vertical

#### com o flex-diretion: column é o contrário 

### flex-flow
É um atalho para flex-direction + flex-wrap
flex-flow: flex-direction flex-wrap

### justify-content
### align-items

## items
### order

nos itens dentro do container é possivel mudar a ordem de aparição
order: N

### flex-basis
é o tamanho padrão do elemento

### flex-grow
para responsividade.
é o fator de espaço extra que o item vai pegar na tela.
se um item tem flex-grow: 1 e o outro 2
o de 2 pegará 2 X mais espaço que o primeiro
se só um item tiver o flex-grow, ele ocupara todo espaço em branco
0 significa que ele não irá aumentar preenchendo os espaços em branco.

### flex-shrink
para responsividade.
é o fator de quanto o elemento irá reduzir em relação ao outros em telas menores
por padrão vem setado como 1. 0 significa que ele não irá reduzir.
funciona da mesma form que o flex-grow

### flex
É um atalho para flex-grow + flex-shrink + flex-basis
flex: flex-grow, flex-shrink, flex-basis

### align-self
Sobrescreve o align-items do container, segue também a direção orientada ao flex-direction




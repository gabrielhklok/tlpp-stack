# tlpp-stack
Classe de pilha. Desenvolvida na linguagem TL++ (Linguagem propriet�ria da TOTVS) 
<br /><br />

1. [Defini��o](#Defini��o)
1. [Metodos](#Metodos)
1. [Extras](#Extras)
<br /><br />

## Defini��o
A classe 'Stack' foi desenvolvida com intuito de possibilitar a vida dos desenvolvedores que desejam fazer uso da estrutuda de dados pilha na linguagem TL++. A implementa��o possibilita a utiliza��o da classe de forma gen�rica, ou seja, sem definir um tipo de dado para os elementos, permitindo assim que cada elemento seja de um tipo diferente. Entre tando tamb�m � possivel definir um tipo no momento de instanciar, se isso for feito, todos os elementos da pilha devem ser do tipo definido.
<br /><br />

## Metodos
- new
- push
- pop
- getTop
- size
- isEmpty
<br /><br />

### new( [type] )

M�todo respons�vel por instanciar a classe, o parametro 'type' � do tipo caracter e opcional. Caso seja informado estaremos definindo um tipo para a pilha, que deve ser uma das op��es abaixo:

- "A" (Array)
- "B" (CodeBlock)
- "C" (Character)
- "D" (Date)
- "L" (Logical)
- "N" (Numeric)
- "O" (Object)
<br /><br />

### Exemplo gen�rico
![](assets/stack-generic.gif)
<br />

### Exemplo tipagem forte
![](assets/stack-tipagem-forte.gif)

### push( element )
M�todo para empilhar elementos na pilha, se a pilha tiver um tipo definido, ser� executado uma verifica��o de tipagem no parametro 'element' informado. Par�metro 'element' � obrigat�rio.
<br /><br />
![](assets/stack-push.gif)
<br /><br />

### pop()
M�todo desempilha um elemento da pilha e retorna o mesmo.
<br /><br />
![](assets/stack-pop.gif)
<br /><br />

### getTop()
Retorna o topo da pilha, sem desempilhar.
<br /><br />
![](assets/stack-gettop.gif)
<br /><br />

### size()
M�todo informa a quantidade de elementos na pilha.
<br /><br />
![](assets/stack-size.gif)
<br /><br />

### isEmpty()
M�todo retorna um boleano informando se a pilha est� ou n�o vazia.
<br /><br />
![](assets/stack-isempty.gif)
<br /><br />

## Extras
Veja na pasta ['examples'](https://github.com/gabrielhklok/tlpp-stack/tree/master/examples) alguns exemplos de fontes usando a classe 'Stack'.
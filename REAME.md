# Prolog

Programação baseada em lógica matemática.

## Notas gerais

- As variáveis em prolog começam com letras maiusculas ou _undescore_ (\_);

## Tipos de dados

Todo tipo de dado em prolog é chamado de `termo` que por sua vez pode classificado como:

1. **Variável**

   - Qualquer sequência de caracteres, números e/ou underscore que é precedida (<s>... a sequência</s>) por uma **letra maiúscula** _(ex: Isto, Monkey_And_Banana)_.
   - Qualquer sequência de caracteres, números e/ou underscore que é precedida por um **underscore** \_(ex: \_Isto, \_Monkey_And_Banana)
   - Um underscore simples (`_`). Neste caso a variável é denominada **variável anónima**. Cada variável anónima é diferente da outra ou seja, `_` é diferente de `_`.

2. **Constante**
   1. **Átomo**
      - Qualquer coisa entre aspas simples `''` _(ex: 'Paulo')_.
      - Qualquer sequência de caracteres, números e/ou undescore que é precedida por uma **letra minúscula** _(ex: um_atomo, e25, etc)_.
      - Qualquer sequência contínua de símbolos _(ex: \*\*\*\*+\*\*\*\*\*)_.
      - E muitos outros simbolos como `[]` que identificam listas vazias e a vírgula `,` que simboliza conjunção entre outros.
   2. **Número** - representa números inteiros _(ex: 12, 20, 77)_ e números de ponto flutuante _(ex: 7.77, 45.3)_.
3. **Estrutura composta**
   - _Objectos de dados que possuem vários componentes_.
   - Cada componente pode ser uma estrutura.
   - De forma a combinar componentes em um simples objecto, deve-se escolher um functor.
   - Todos objectos estruturados podem ser representados como árvores. Exemplo: a data pode ser dividida em `dia, mês e ano`. Em forma de functor podemos representar 3 de maio de 2003 como `data(dia, mês, ano)`.

<div style="text-align:center">

![Data functor](./img/functor.png)<br>
_Fig.1 Data functor representation_

</div>

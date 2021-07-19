# materialize-pratica

## Sobre

- Esse repositório tem a finalidade de colocar em prática a conhecimento adquirido com base na documentação oficial do [Materialize](https://materializecss.com/) e pesquisas na internet.

### `Cores`

- Cor de texto

Para aplicar cores aos texto basta adicionar a sua _class_ o nome da cor seguido de _-text_.

> white-text | blue-text | purple-text

_Exemplo:_
``` HTML
    <div>
        <p class="purple-text">Conteúdo da página...</p>
    </div>
```

- Cor de fundo

Para aplicar cor de fundo adicionamos a apenas o nome da dor desejada.

> green | blue | purple

_Exemplo:_
``` HTML
    <div class="purple">
        <p>Conteúdo da página...</p>
    </div>
```

- Lighten e Darken

Para deixar a cor, em geral, de text e fundo por exemplo, mais clara ou escura, adicionamos a _class_ do elemento em questão o __lighten__ ou __darken__.

Para cores mais claras adicionamos o __lighten__, e para cores mais escuras o __darken__, seguidos de numeros de 1 a 5, dependendo do que estiver disponível, para aumentar ou diminuir a intensidade da cor.

_Exemplo para fundo:_
``` HTML
    <div class="red lighten-2">
        <p>Conteúdo da página...</p>
    </div>
```

_Exemplo para texto:_
``` HTML
    <div>
        <p class="green-text text-darken-4">Conteúdo da página...</p>
    </div>
```

### `Sombras`

Propiedade para aplicar sombra: __.z-depth-3__

Seu valor vai de '0' a '5' e o valor padrão '1'.

Neste projeto foi aplicado sombra de nível 3 ao cabeçalho.

### `Tipografia`

- Fonte

Fonte padrão do [Materialize](https://materializecss.com/): `Roboto 2.0`.

- weight

Para alterar o _peso/weight_ de um elemento, deve-se alterar em um arquivo __.css__ a propriedade _font-weight_ com os valores disponíveis pelo framework.

> __Pesos disponíveis__: _200, 300, 400, 500 e 600_

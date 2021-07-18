# materialize-pratica

## Sobre

### Cores

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

_Exemplo:_
``` HTML
    <div class="red lighten-2">
        <p>Conteúdo da página...</p>
    </div>
```

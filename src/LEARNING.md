# Conteúdo das aulas

**Requisitos**: Node.js, VSCode

**Plugins do VSCode**: editorconfig, gitlens, open in browser

## Aula 1

- HTML serve para estruturar a informação em uma página web
- HTML é composto por tags e elementos
- atributos fornecem informações de conteúdo e funcionamento das
tags e elementos
- existem tags/elementos abertos e vazios
- essencialmente temos duas categorias de elementos: inline e block

## Aula 2

- ul, ol e dt são elementos para criação de listas (dt muito pouco usado);
- svg é um formato de imagem para imagens vetoriais;
- temos 3 formas de escrever CSS: inline (peso 3), internal (peso 2), external (peso 1);
- é boa prática utilizar CSS em um arquivo externo para evitar colisões de estilo;
- padding serve para dar espaçamento interno em um elemento;
- margin serve para dar espaçamento externo em um elemento;
- é possível aplicar margem negativa com o margin;
- box-model é uma caixa que envolve todo elemento e consiste de margin, border, padding, height e width;
- a propriedade `box-sizing: border-box` faz com que o padding e a borda não sejam somados com a largura e altura do elemento;
- `*` é o seletor global;

## Aula 3

- utilizamos `%` como unidade de medida para trabalhar com layout fluído;
- para centralizar um elemento horizontalmente utilizamos a `margin` com o valor `auto` e o `width` definido;
- a propriedade `background` nos permite manusear o background de um elemento;
- por padrão o `background-repeat` vem com o valor `repeat`;
- a propriedade `background-size: cover` faz com que a imagem se ajuste ao elemento a fim de evitar distorções;
- para criar um efeito de overlay podemos utilizar o `linear-gradient(rgba(119, 98, 178, 0.6), rgba(119, 98, 178, 0.6)), url(path da imagem)`;
- podemos importar fonts através da tag `<link>`, `@import` ou `@font-face`;
- várias propriedades do CSS são passadas de elemento pai para o filho, por exemplo `font-family`;
- `letter-spacing` aplica espaçamento entre as letras de um texto;
- utilize `text-transform: uppercase` para deixar tudo em texto maiúsculo;
- só utilize letras maiúsculas no HTML caso realmente necessário, por exemplo em siglas;

## Aula 4

- classes no CSS possibilitam o reaproveitamento e isolamento de estilos;
- a propriedade `list-style: none` remove os pontos da lista;
- o `display: inline-block` permite que elementos sejam arranjados lado a lado;
- o atributo `target=_blank` no element `<a>` faz com que o link seja aberto em uma nova aba;
- ao remover o `outline` é boa prática prover alguma forma de enfatizar a interação do usuário com dado elemento;
- pseudo-classe nos permite aplicar um estilo a um elemento sobre um estado especial, por exemplo: `:hover`, `:focus`, `:first-child`, `:visited`, `:checked` ...
- `transition` nos permite criar animações de transição de valores das propriedades;
- flex-box layout provê um modo eficiente de dispor, alinhar e distribuir espaço entre elementos que estão contidos em um container flex, independente das suas dimensões;
- o flex-box é unidirecional, ou seja, só conseguimos trabalhar em um dos eixos (x ou y) por containter;
- a propriedade `flex-direction` possibilita declarar qual a direção dos itens de um container flex;
- os itens de um container flex são flexíveis e adaptam as suas dimensões para se encaixarem no container;
- para realizar a quebra de linha utilizamos a propriedade `flex-wrap: wrap` e definimos a largura de cada elemento que estiver contido em um container flex;

## Aula 5

- a unidade de medida `vh` é equivalente ao valor relativo à altura do viewport;
- `align-items` permite trabalhar com alinhamento dos itens na vertical contando que o `flex-drection` seja `row`;
- `justify-content` permite trabalhar com alinhamento e disposição da horizontal contando que o `flex-drection` seja `row`;
- `align-content` permite o alinhamento dos itens em um container flex com `flex-wrap`;
- o .editorconfig é um arquivo com configurações para o nosso code editor;
## Aula 6

- a tag `main` só é permitida ter uma por página HTML;
- a tag `section` nos permite dividir o conteúdo em seções em um nível mais geral;
- a tag `article` serve para separar blocos de informações em um nível mais específico;
- é uma boa prática nomear as imagens (e tudo) com nomes mais descritíveis possível;
- um component agrupa conteúdo e comportamento que façam sentido estarem juntos;
- `overflow: hidden` faz com que o conteúdo que ultrapassar as dimensões do elemento seja cortado;
- utilizamos imagens como `background-images` para imagens que não se remetem ao conteúdo, ou seja, meramente ilustrativas;
- utilizamos imagens com a tag `img`, imagens que se remetem ao conteúdo;
- um elemento com `position: absolute` se posiciona relativamente ao elemento;
- utilizamos as propriedades `top`, `right`, `bottom`, `left` para posicionar um elemento absoluto;
- a propriedade `z-index` nos permite alterar o nível de profundidade de um elemento, ou seja, alterar o eixo z;
- só conseguimos alterar o `z-index` se ao menos o nosso elemento tiver o `position` relative ou absolute;
- `object-fit: cover` tem o mesmo efeito que `background-size: cover`, porém diretamente em um elemento `img`;

## Aula 7

- a funçao `rgba(red, green, blue, alpha)` permite declarar uma cor com transparência;
- utilize `aria-hidenn="true"` em elementos abertos sem conteúdo para que o leitor de tela não interprete o elemento;
- ARIA é a API de acessibiliade no HTML;
- os pseudo-elementos nos permitem aplicar estilo em um conteúdo interno de um elemento, por exemplo: `::first-letter`, `::first-line`, `::selection`, que é o conteúdo selecionado pelo cursos;
- com os pseudo-elementos `::before` e `::after` conseguimos adicionar um elemento antes ou depois do conteúdo de um elemento;
- em ambos, devemos declarar a propriedade `content`, e tem por padrão o `display:: inline`;

## Aula 8

- o grid layout provê um modo eficiente de dispor, alinhar e distribuir espaçamento entre linhas e colunas contidas em um elemento com
`display: grid`;
- o grid layout é bidirecional, ou seja, conseguimos trabalhar com os dos eixos (x para linhas e y para colunas) ao mesmo tempo;
- através da função `repeat`, conseguimos repetir dimensões das linhas e colunas;
- a propriedade `gap` permite declarar a distância entre linhas e colunas;
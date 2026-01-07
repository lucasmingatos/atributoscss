# Neste estudo eu pratiquei seletores CSS, pseudo-classes e pseudo-elementos para estilizar elementos com base em tipo, atributos, estado e posição no DOM.

## Seletores básicos e por atributo
Usei seletores de elemento para aplicar regras gerais, como input e a com display: block.

Apliquei estilos usando seletor por atributo, como input[type=password] para diferenciar campos específicos.

Seletor de atributo com correspondência parcial: a[href*=palmeiras] para selecionar links cujo href contém uma palavra específica.

Pseudo-classes úteis
:empty para esconder div sem conteúdo (display: none), útil para evitar espaços em branco no layout.

:not(...) como seletor negativo para aplicar estilos em “todos menos X”.

:nth-child(2) para selecionar um elemento pela posição (ex.: o segundo filho dentro do container), útil em listas e grids.

Pseudo-elementos
::first-letter para estilizar a primeira letra de cada parágrafo (efeito drop cap).

:before e :after para inserir conteúdo/decoração antes ou depois de um elemento (ex.: span), ajudando a criar detalhes visuais sem mexer no HTML.

Transformações e dimensionamento
Usei transform: scale(1, 3) para redimensionar um elemento (ex.: um retângulo) mantendo o fluxo do layout controlado.

Reforcei o conceito de box-sizing, incluindo a ideia do border-box para controlar melhor o tamanho final do elemento somando padding e bordas.

Placeholder e estilização de input
Pratiquei a estilização de campos via classe (.input) ajustando tamanho, fonte e cor.

Observei que regras repetidas podem sobrescrever estilos anteriores (cascade), como no caso de duas definições de cor em .input.

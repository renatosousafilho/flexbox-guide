# Flexbox

## Propriedade `display: flex`

Transforma um elemento em um `flex container`.

## Propriedade `flex-direction`

Define o eixo de exibição dos flex items. 

* `row`: Eixo horizontal;
* `column`: Eixo vertical;

## Propriedade `flex-wrap`

* `wrap`: 
* `nowrap`:
* `wrap-reverse`:

## Propriedade `flex-flow`

Unifica as duas propriedades `flex-direction` e `flex-wrap`.

## Propriedade `justify-content`

Define como o flex container distribui o espaço entre os flex items.

```javascript
// https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content
/* Positional alignment */
justify-content: center;     /* Pack items around the center */
justify-content: start;      /* Pack items from the start */
justify-content: end;        /* Pack items from the end */
justify-content: flex-start; /* Pack flex items from the start */
justify-content: flex-end;   /* Pack flex items from the end */
justify-content: left;       /* Pack items from the left */
justify-content: right;      /* Pack items from the right */

/* Baseline alignment */
/* justify-content does not take baseline values */

/* Normal alignment */
justify-content: normal;

/* Distributed alignment */
justify-content: space-between; /* Distribute items evenly
                                   The first item is flush with the start,
                                   the last is flush with the end */
justify-content: space-around;  /* Distribute items evenly
                                   Items have a half-size space
                                   on either end */
justify-content: space-evenly;  /* Distribute items evenly
                                   Items have equal space around them */
justify-content: stretch;       /* Distribute items evenly
                                   Stretch 'auto'-sized items to fit
                                   the container */

/* Overflow alignment */
justify-content: safe center;
justify-content: unsafe center;

/* Global values */
justify-content: inherit;
justify-content: initial;
justify-content: unset;
```

## Propriedade `align-items`

A propriedade CSS align-items estabelece o valor align-self em todos filhos diretos como um grupo. A propriedade align-self estabelece o alinhamento de um certo item dentro do bloco que o contém.

```javascript
/* Palavras-chave básicas */ 
align-items: normal; 
align-items: stretch; 

/* Posicionamento do alinhamento */ 
/* align-items não recebe valores left e right */
align-items: center; /* Itens posicionados ao redor do centro */ 
align-items: start; /* Posiciona itens a partir do início */ 
align-items: end; /* Posiciona itens a partir do fim */ 
align-items: flex-start; /* Posiciona itens-flex a partir do início */ 
align-items: flex-end; /* Posiciona itens-flex a partir do fim */ 
align-items: self-start; 
align-items: self-end; 

/* Alinhamento da baseline */
align-items: baseline; 
align-items: first baseline; 
align-items: last baseline; /* Overflow alinhamento (apenas para alinhamento de posição) */ 
align-items: safe center; 
align-items: unsafe center; 

/* Valores globais */
align-items: inherit; 
align-items: initial; 
align-items: unset;
```

## Propriedade `align-content`

Define o espaçamento entre os espaços entre e ao redor do agrupamento dos flex items.

```javascript
/* Basic positional alignment */
/* align-content does not take left and right values */
align-content: center;     /* Pack items around the center */
align-content: start;      /* Pack items from the start */
align-content: end;        /* Pack items from the end */
align-content: flex-start; /* Pack flex items from the start */
align-content: flex-end;   /* Pack flex items from the end */

/* Normal alignment */
align-content: normal;

/* Baseline alignment */ 
align-content: baseline;
align-content: first baseline;
align-content: last baseline;

/* Distributed alignment */
align-content: space-between; /* Distribute items evenly
                                 The first item is flush with the start,
                                 the last is flush with the end */
align-content: space-around;  /* Distribute items evenly
                                 Items have a half-size space
                                 on either end */
align-content: space-evenly;  /* Distribute items evenly
                                 Items have equal space around them */
align-content: stretch;       /* Distribute items evenly
                                 Stretch 'auto'-sized items to fit
                                 the container */

/* Overflow alignment */
align-content: safe center;
align-content: unsafe center;

/* Global values */
align-content: inherit;
align-content: initial;
align-content: unset;
```

### Outras referências

* https://css-tricks.com/snippets/css/a-guide-to-flexbox
* https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout/Conceitos_Basicos_do_Flexbox

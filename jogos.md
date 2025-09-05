````markdown
# 📝 CSS Games Solutions (com comentários)

Este documento reúne as soluções dos dois jogos educativos de CSS:

- 🌱 **Grid Garden** (28 níveis) – prática de **CSS Grid**
- 🐸 **Flexbox Froggy** (24 níveis) – prática de **Flexbox**

---

## 🌱 CSS Grid Garden – Soluções

### Level 1
```css
grid-column-start: 3; /* Faz o elemento começar na coluna 3 */
````

### Level 2

```css
grid-column-start: 5; /* Faz o elemento começar na coluna 5 */
```

### Level 3

```css
grid-column-end: 4; /* Faz o elemento terminar na linha da coluna 4 */
```

### Level 4

```css
grid-column-end: 2; /* Faz o elemento terminar na linha da coluna 2 */
```

### Level 5

```css
grid-column-end: -2; /* Termina duas colunas antes do fim */
```

### Level 6

```css
grid-column-start: -3; /* Começa três colunas antes do fim */
```

### Level 7

```css
grid-column-end: span 2; /* O elemento ocupa 2 colunas de largura */
```

### Level 8

```css
grid-column-end: span 5; /* O elemento ocupa 5 colunas de largura */
```

### Level 9

```css
grid-column-start: span 3; /* Faz o elemento ocupar 3 colunas a partir de onde está */
```

### Level 10

```css
grid-column: 4 / 6; /* O elemento ocupa da coluna 4 até a 6 (não inclusiva) */
```

### Level 11

```css
grid-column: 2 / 5; /* O elemento vai da coluna 2 até a 5 (não inclusiva) */
```

### Level 12

```css
grid-row-start: 3; /* Faz o elemento começar na linha 3 do grid */
```

### Level 13

```css
grid-row: 3 / 6; /* O elemento ocupa da linha 3 até a 6 */
```

### Level 14

```css
grid-column: 2 / 3; /* O elemento ocupa a coluna 2 */
grid-row: 5 / 6;   /* O elemento ocupa a linha 5 */
```

### Level 15

```css
grid-column: 2 / 6; /* Vai da coluna 2 até a 6 */
grid-row: 1 / 6;   /* Vai da linha 1 até a 6 */
```

### Level 16

```css
grid-area: row-start / column-start / row-end / column-end;

grid-area: 1 / 2 / 4 / 6; /* Linha inicial 1, coluna inicial 2, linha final 4, coluna final 6 */
```

### Level 17

```css
grid-area: 2 / 3 / 5 / 6; /* Linha inicial 2, coluna inicial 3, linha final 5, coluna final 6 */
```

### Level 18

```css
order: 5; /* Muda a ordem do item dentro do grid/flexbox para 5 */
```

### Level 19

```css
order: -1; /* Muda a ordem do item para antes dos demais */
```

### Level 20

```css
grid-template-columns: 50% 10% 25% 5% 10%; /* Define larguras específicas para cada coluna */
```

### Level 21

```css
grid-template-columns: repeat(8, 12.5%); /* Cria 8 colunas iguais de 12.5% cada */
```

### Level 22

```css
grid-template-columns: 100px 3em 40%; /* Define colunas com unidades diferentes (px, em, %) */
```

### Level 23

```css
grid-template-columns: 1fr 5fr; /* Duas colunas: a segunda ocupa 5x o espaço da primeira */
```

### Level 24

```css
grid-template-columns: 50px 1fr 1fr 1fr 50px; /* Colunas fixas nas bordas e flexíveis no meio */
```

### Level 25

```css
grid-template-columns: 75px 3fr 2fr; /* Três colunas: fixa, 3 partes, 2 partes */
```

### Level 26

```css
grid-template-rows: repeat(4, 12.5px) 1fr; /* 4 linhas pequenas + 1 linha que ocupa o resto */
```

### Level 27

```css
grid-template: 60% 40% / 200px; /* 2 linhas (60% e 40%) e 1 coluna fixa de 200px */
```

### Level 28

```css
grid-template: 1fr 50px / 1fr 4fr; /* 2 linhas (flex e fixa) / 2 colunas (flex e maior) */
```

---

## 🐸 Flexbox Froggy – Soluções

### Level 1

```css
justify-content: flex-end; /* Move os itens para a direita */
```

### Level 2

```css
justify-content: center; /* Centraliza os itens horizontalmente */
```

### Level 3

```css
justify-content: space-around; /* Espaçamento igual entre os itens, com espaço nas bordas */
```

### Level 4

```css
justify-content: space-between; /* Espaço igual entre itens, sem espaço nas bordas */
```

### Level 5

```css
align-items: flex-end; /* Alinha os itens na parte inferior */
```

### Level 6

```css
justify-content: center; /* Centraliza na horizontal */
align-items: center;     /* Centraliza na vertical */
```

### Level 7

```css
justify-content: space-around; /* Espaçamento uniforme na horizontal */
align-items: flex-end;         /* Itens no fundo do container */
```

### Level 8

```css
flex-direction: row-reverse; /* Inverte a ordem dos itens (da direita para a esquerda) */
```

### Level 9

```css
flex-direction: column; /* Organiza os itens em coluna */
```

### Level 10

```css
flex-direction: row-reverse; /* Inverte a ordem na horizontal */
justify-content: flex-end;   /* Empurra para a esquerda (fim no sentido invertido) */
```

### Level 11

```css
flex-direction: column;    /* Itens em coluna */
justify-content: flex-end; /* Itens vão para baixo */
```

### Level 12

```css
flex-direction: column-reverse; /* Coluna invertida */
justify-content: space-between; /* Espaço distribuído entre os itens */
```

### Level 13

```css
flex-direction: row-reverse; /* Linha invertida */
justify-content: center;     /* Itens centralizados na horizontal */
align-items: flex-end;       /* Itens na parte inferior */
```

### Level 14

```css
order: 3; /* Muda a ordem do item para aparecer depois dos demais */
```

### Level 15

```css
order: -1; /* Faz o item aparecer antes de todos */
```

### Level 16

```css
align-self: flex-end; /* Alinha só esse item no fundo */
```

### Level 17

```css
order: 1;            /* Muda a ordem do item */
align-self: flex-end; /* Alinha esse item específico no fundo */
```

### Level 18

```css
flex-wrap: wrap; /* Quebra a linha quando não couber */
```

### Level 19

```css
flex-direction: column; /* Organiza em coluna */
flex-wrap: wrap;        /* Quebra em várias colunas se não couber */
```

### Level 20

```css
flex-flow: column wrap; /* Atalho para flex-direction + flex-wrap */
```

### Level 21

```css
align-content: flex-start; /* Grupos de linhas vão para o topo */
```

### Level 22

```css
align-content: flex-end; /* Grupos de linhas vão para baixo */
```

### Level 23

```css
flex-direction: column-reverse; /* Colunas invertidas */
align-content: center;          /* Centraliza os grupos de linhas */
```

### Level 24

```css
flex-flow: column-reverse wrap-reverse; /* Colunas invertidas e quebra invertida */
justify-content: center;               /* Centraliza na horizontal */
align-items: center;                   /* Centraliza na vertical */
```

```

---

```

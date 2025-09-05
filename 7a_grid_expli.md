A diferença entre **grid-template-columns** e **grid-column** no CSS Grid é a seguinte:

- **grid-template-columns** é uma propriedade do container grid usada para definir o número e os tamanhos das colunas da grade (grid). Com ela, você especifica de uma vez todas as colunas explícitas do grid, definindo o layout base do seu container. Exemplo:  
  `grid-template-columns: 100px 1fr 2fr;` cria três colunas com larguras específicas.

- **grid-column** é uma propriedade aplicada a um item dentro do grid (grid item), não ao container. Ela serve para posicionar esse item em colunas específicas da grade, indicando em qual linha de coluna ele começa e termina. Exemplo:  
  `grid-column: 1 / 3;` faz o item ocupar da coluna 1 até a coluna 3 (abrangendo duas colunas).

Resumindo: **grid-template-columns define a estrutura e tamanhos das colunas do container grid**, enquanto **grid-column serve para posicionar ou estender um item em colunas específicas dentro desse grid**.

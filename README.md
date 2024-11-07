# Maravilhas Naturais do Brasil

Este projeto apresenta uma página web criada com HTML e CSS, destacando algumas das paisagens naturais mais impressionantes do Brasil, como as Cataratas do Iguaçu, a Chapada Diamantina e os Lençóis Maranhenses. Abaixo está uma descrição geral das tags, elementos e propriedades utilizadas para a estrutura e o design da página.

## Estrutura Geral do HTML

### `<head>`
- **Preconexão (`<link rel="preconnect">`)**: Melhoramos a performance ao pré-conectar com fontes externas.
- **Meta Tags**:
  - `<meta charset="UTF-8">`: Define a codificação de caracteres como UTF-8.
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Adapta a página para uma boa visualização em dispositivos móveis.
- **Fonte**: A fonte **Open Sans** é carregada do Google Fonts para melhorar a legibilidade e a estética.
- **CSS Externo**: A página usa um arquivo de estilo externo, `style.css`, para definir o design.

### Estrutura do Corpo (`<body>`)
O corpo da página contém uma seção de introdução, uma descrição das paisagens naturais, imagens de destaque, e um footer com informações sobre o autor.

### Estruturas Específicas

- **Header**: Estrutura principal que contém o título e a introdução.
- **Section**:
  - `.description-image`: Exibe uma imagem principal e um texto descritivo sobre o Brasil.
  - `.destinos`: Apresenta as maravilhas naturais, cada uma descrita dentro de um `<article>`, com imagem e informações.
- **Listas Ordenadas (`<ol>`)** e Não Ordenadas (`<ul>`)**: Utilizadas para destacar as características e as atividades recomendadas para cada destino natural.

- **Footer**: Inclui um agradecimento e o nome do desenvolvedor.

## Estrutura de Classes e Estilos no CSS

- **Reset de Estilos**: O seletor universal (`*`) remove margens e padding padrão para garantir consistência no layout.
  
- **Cores e Fontes**:
  - A cor de fundo principal do corpo é definida pela `background-image` com uma imagem de paisagem.
  - Cores de destaque para títulos e seções específicas:
    - `.headline`: Texto em laranja (#e1624f).
    - `.bom-para`: Texto em preto com categorias de atividades em cores exclusivas, como `.trilhas` em marrom e `.caminhadas` em verde.

- **Dimensões e Layout**:
  - A largura da página é definida em 1120px, centralizada usando `left: calc(50% - 560px);`.
  - O container principal `.bg` usa uma cor de fundo suave e bordas arredondadas para dar destaque.

- **Estilização de Texto**:
  - Fonte principal é "Open Sans", aplicada ao seletor `:root`.
  - Títulos e subtítulos são estilizados para chamar atenção, usando `.headline`, `.h1`, e `.h3`.

- **Imagens**:
  - Definidas com largura total (`width: 100%`) e ajuste de altura automático (`height: auto`).
  - Bordas arredondadas para um visual mais suave.

- **Efeitos Visuais**:
  - Linhas divisórias (`.divisor`) para separar seções de conteúdo.
  - `.feito-com` e `.por-dnldev` no footer para estilização personalizada do nome do desenvolvedor.


## Tecnologias Utilizadas

- HTML5 para estrutura da página.
- CSS3 para o estilo e layout.

---

Este projeto celebra as belezas naturais do Brasil e destaca a importância de uma estrutura HTML bem organizada e um design CSS elegante.

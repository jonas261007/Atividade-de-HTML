# Atividade-de-HTML

### Conhecendo o HTML e sua estrutura básica

1. **O que é o HTML e qual é o seu papel na construção de páginas web? Descreva brevemente a estrutura básica de um documento HTML.**

   O HTML (HyperText Markup Language) é a linguagem de marcação utilizada para criar a estrutura básica de páginas web. Ele define o conteúdo e a organização dos elementos dentro de uma página, como texto, imagens, links, e outros tipos de mídia. A estrutura básica de um documento HTML inclui:
   - **<!DOCTYPE html>**: Declaração do tipo de documento.
   - **<html>**: Elemento raiz que encapsula todo o conteúdo da página.
   - **<head>**: Contém metadados como o título da página, links para CSS, scripts e outras configurações.
   - **<body>**: Abriga todo o conteúdo visível da página, como parágrafos, imagens, links, etc.

2. **Como o HTML se relaciona com outras tecnologias da web, como o CSS e o JavaScript? Como essas três tecnologias trabalham em conjunto para criar páginas web interativas e estilizadas?**

   O HTML estrutura o conteúdo de uma página web, enquanto o CSS (Cascading Style Sheets) é usado para estilizar e definir a apresentação desse conteúdo, como cores, layouts e fontes. O JavaScript, por sua vez, é uma linguagem de programação que permite adicionar interatividade à página, como validação de formulários, animações e manipulação dinâmica do conteúdo. Juntas, essas tecnologias possibilitam a criação de páginas web completas, interativas e visualmente atraentes.

### Identificando tags HTML básicas

1. **Cite três tags HTML básicas e explique o propósito de cada uma delas. Dê exemplos de situações em que você as usaria ao construir uma página web.**

   - **<p>**: Define um parágrafo de texto. Usada para separar blocos de texto em uma página.
   - **<h1> a <h6>**: Definem cabeçalhos de diferentes níveis, do mais importante (<h1>) ao menos importante (<h6>). Utilizadas para organizar o conteúdo em seções e subseções.
   - **<a>**: Cria um link para outras páginas ou recursos. Usada para navegação entre páginas ou para links de download.

2. **Além das tags mencionadas, qual é a importância das tags de listagem, como <ul> e <ol>, no contexto da estruturação de conteúdo em uma página? Dê exemplos de quando você escolheria uma sobre a outra.**

   As tags de listagem, como **<ul>** (lista não ordenada) e **<ol>** (lista ordenada), são importantes para organizar o conteúdo em listas, facilitando a leitura e compreensão. Usaria **<ul>** para listar itens sem uma ordem específica, como características de um produto, e **<ol>** quando a ordem dos itens é importante, como etapas de um processo.

### Vinculando páginas, arquivos e âncoras

1. **Como a tag <a> é utilizada para criar links em HTML? Explique como você pode vincular para outras páginas, para arquivos locais e criar âncoras dentro de uma página.**

   A tag **<a>** é usada para criar links em HTML, através do atributo **href**. Para vincular a:
   - **Outras páginas**: `<a href="pagina.html">Clique aqui</a>`
   - **Arquivos locais**: `<a href="arquivo.pdf">Baixar arquivo</a>`
   - **Âncoras dentro da página**: Primeiro, define a âncora com `<a id="seção1">`, depois cria o link com `<a href="#seção1">Ir para a seção 1</a>`.

2. **Além do atributo href, quais outros atributos importantes a tag <a> pode ter? Como o atributo target pode ser usado para controlar como o link é aberto pelo navegador?**

   A tag **<a>** pode ter outros atributos como:
   - **target**: Controla como o link é aberto, por exemplo, `target="_blank"` abre o link em uma nova aba ou janela.
   - **title**: Exibe um texto quando o cursor do mouse passa sobre o link.
   - **rel**: Define a relação entre o documento atual e o documento vinculado, útil para SEO e segurança.

### Incorporando imagens e mídias

1. **Descreva a diferença entre os atributos src e alt em relação à tag <img>. Por que é importante fornecer um atributo alt adequado para imagens?**

   O atributo **src** especifica o caminho da imagem a ser exibida, enquanto o **alt** fornece uma descrição alternativa que é exibida caso a imagem não carregue ou para leitores de tela. É importante fornecer um **alt** adequado para garantir acessibilidade, ajudando pessoas com deficiência visual e melhorando a indexação por motores de busca.

2. **Além de imagens, quais outros tipos de mídia podem ser incorporados em uma página HTML? Como você pode garantir que a mídia incorporada seja responsiva e se ajuste bem em diferentes dispositivos?**

   Outros tipos de mídia que podem ser incorporados incluem vídeos (**<video>**), áudio (**<audio>**), e iframes para conteúdo externo como mapas ou vídeos do YouTube. Para garantir que a mídia seja responsiva, pode-se usar CSS, como definições de largura máxima (**max-width: 100%;**) e media queries para ajustar o layout em diferentes dispositivos.

### Criando tabelas básicas

1. **Quais são as principais tags usadas para criar tabelas em HTML? Explique a diferença entre as tags <th> e <td>, e quando você as usaria.**

   As principais tags usadas para criar tabelas em HTML são:
   - **<table>**: Define o início e o fim de uma tabela.
   - **<tr>**: Define uma linha na tabela.
   - **<th>**: Define uma célula de cabeçalho, usada em linhas ou colunas de cabeçalho.
   - **<td>**: Define uma célula de dados, usada para qualquer outra célula não cabeçalho.

   Usaria **<th>** para destacar os títulos das colunas ou linhas, e **<td>** para os dados correspondentes.

2. **Embora tabelas sejam usadas para exibir dados tabulares, às vezes é recomendado evitá-las em favor de outras formas de apresentação de dados. Por quê? E quais são os cenários em que as tabelas são apropriadas?**

   Tabelas devem ser usadas apenas para dados tabulares, pois seu uso para layout pode dificultar a acessibilidade e a responsividade. Elas são apropriadas quando os dados têm uma relação clara entre linhas e colunas, como em relatórios financeiros, horários ou especificações técnicas.

### Criando formulários

1. **Como a tag <form> é utilizada para criar formulários em HTML? Cite pelo menos três tipos diferentes de campos de entrada (<input>) que podem ser usados em um formulário.**

   A tag **<form>** cria um formulário para coleta de dados do usuário, contendo diferentes tipos de campos de entrada, como:
   - **<input type="text">**: Campo de texto para entrada de dados curtos.
   - **<input type="email">**: Campo específico para entrada de endereços de e-mail.
   - **<input type="password">**: Campo para entrada de senhas, onde os caracteres são ocultados.

2. **Além dos campos de entrada, quais outros elementos podem ser incluídos em um formulário para melhorar a usabilidade e a experiência do usuário?**

   Outros elementos incluem:
   - **<textarea>**: Para entrada de texto longo.
   - **<select>**: Para criar listas suspensas de opções.
   - **<button>**: Para criar botões de envio ou de interação.

### Técnicas avançadas de estruturação com elementos HTML5 semânticos

1. **O que são elementos HTML5 semânticos e por que são importantes na estruturação de uma página? Cite três exemplos de elementos semânticos e explique quando você os usaria.**

   Elementos HTML5 semânticos têm significado claro, indicando ao navegador e aos desenvolvedores o propósito do conteúdo. São importantes para SEO e acessibilidade. Exemplos:
   - **<header>**: Usado para o cabeçalho da página ou de seções.
   - **<article>**: Para conteúdo independente e reutilizável, como posts de blogs.
   - **<footer>**: Para rodapé da página ou de seções, contendo informações como créditos e links.

2. **Além da semântica, como os elementos HTML5 podem afetar a acessibilidade das páginas web? Por que é fundamental considerar a acessibilidade ao escolher elementos de estruturação?**

   Elementos HTML5 melhoram a acessibilidade ao fornecer uma estrutura clara e reconhecível para tecnologias assistivas, como leitores de tela. Considerar a acessibilidade é fundamental para garantir que todos os usuários, incluindo aqueles com deficiências, possam navegar e entender o conteúdo da página.

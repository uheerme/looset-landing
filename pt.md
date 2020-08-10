---
layout: blocks
title: Looset | Principal
description: Uma família de ferramentas para explorar projetos grandes e complexos.
date: 2020-07-26T15:00:00.000-03:00
page_sections:
- template: navigation-header
  block: header-1
  logo: "/uploads/2020/07/11/logo.png"
  navigation-left:
  - link: "/"
    link_text: "<strong>pt</strong>/en"
  navigation-right:
  - link: "an-architecture"
    link_text: Blog
  - link: "/pt#looset-diagram"
    link_text: Looset Diagram
  - link: "/pt#looset-code"
    link_text: Looset Code
  background-color: ''
- template: hero-banner-w-image
  block: hero-2
  headline: Visualização de Código Fonte
  content: Uma família de ferramentas para explorar projetos grandes e complexos.
  cta:
    enabled: true
    url: pt/#developer-time
    button_text: <i class="fas fa-angle-double-down"></i>
  image:
    image: "/uploads/2020/07/13/looset-diagram-gif.gif"
    alt_text: Product Shot
    has-shadow-box: true
    url: ''
  background_image: ''
  background-color: var(--bg)
  headline-color: var(--headline-color)
  content-color: var(--content-color)
- template: 2-column-text
  block: two-column-1
  col_2:
    content: Isso é possível graças a um simples <strong>analizador estático</strong>
      que identifica <strong>Blocos de Código</strong> e um identificador, o que na
      maioria dos casos são os nomes de funções. O analizador básico aproveita do
      fato que desenvolvedores separam os Blocos de Código por <strong>linhas em branco</strong>
      e usam <strong>indentação </strong>apropriada. Por isso funciona com <strong>qualquer
      linguagem de programação </strong>, o que é perfeito pra usar em projetos que
      misturam HTML, CSS, Javascript, C#, Java, Clojure, Go, Rust, Bash, R, Ruby,
      Swifty, SQL, Kotlin, Lua, Scala, VBA, Python, Haskell, Cobol, Lolcode, etc.
    headline: Funciona com Todas as Linguagens
    headline-color: var(--headline-color)
    content-color: var(--content-color)
    background-color: ''
  col_1:
    content: O problema é quando estamos diante de um projeto gigante que não conhecemos,
      seria ótimo se todo projeto fosse dividido em módulos, tivesse boa documentação,
      testes e bons nomes de funções e variáveis que são compatíveis com as regras
      de negócio, mas a vida não é sempre assim.
    headline: Projetos de Software raramente tem código limpo
    headline-color: var(--headline-color)
    content-color: var(--content-color)
    background-color: ''
  background-color: var(--bg)
- template: content-feature
  block: feature-1
  headline-color: var(--headline-color-secondary)
  content-color: var(--content-color-secondary)
  media_alignment: Right
  background-color: var(--bg-secondary)
  headline: Tempo do desenvolvedor
  media:
    image: "/uploads/2020/07/24/data-charts.gif"
    alt_text: 'Gráfico de pizza: Menos que um mês 30%, De um a três meses 44.70%,
      De três a seis meses 17.40%, De seis a nove meses 5.10%, De nove a doze meses
      1.70%, Mais de um ano 1.20%.'
    has-shadow-box: false
  content: 'Gasta-se muito tempo pra entender código. Uma <a href="https://insights.stackoverflow.com/survey/2018#work-_-how-long-do-developers-expect-new-coworkers-to-take-to-be-productive"
    title="">pesquisa do StackOverflow</a> mostrou que é esperado de <strong>mais
    de 70%</strong> de desenvolvedores experientes demorar <strong>mais de um mês
    para se tornarem produtivos</strong> num novo projeto.<br><br>Na média, desenvolvedores
    gastam apenas 5% de seu tempo <strong>escrevendo e editando</strong> código, mais
    de <strong>80%</strong> do tempo é gasto <strong>entendendo e navegando</strong>
    pelo código <a href="https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=4781&amp;context=sis_research"
    title="Measuring program comprehension: A large-scale field study with professionals.">(XIA,
    2018)</a>.'
  HtmlId: developer-time
- template: title-no-bottom-padding
  block: title
  content: Looset Diagram
  HtmlId: looset-diagram
  background-color: var(--bg-secondary)
  content-color: var(--content-color-secondary)
  headline-color: var(--headline-color-secondary)
  headline: ''
  title-color: var(--headline-color-secondary)
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: Visualize como o sistema é afetado ao fazer mudanças específicas;<br><br>
    Melhore a comunicação entre stakeholders mostrando como o produto evoluiu pelo
    tempo; <br><br>Estime o tempo das tarefas com mais precisão entendendo o quão
    complexas elas são.
  content: ''
  media:
    alt_text: Diagrama de dependências
    image: "/uploads/2020/07/14/gif-2.gif"
    has-shadow-box: true
  HtmlId: diagram
  background-color: var(--bg-secondary)
  headline-color: var(--content-color-secondary)
  content-color: var(--content-color-secondary)
- template: content-feature
  block: feature-1
  media_alignment: Right
  content: Looset Diagram te ajuda a <strong>entender o código</strong> que você trabalha
    te dando mais que apenas texto colorido num editor e mostrando um <strong>grafo
    de chamadas</strong>. <br><br>Ele gera altomaticamente diagramas onde cada Bloco
    de Código é um nó e uma conexão é criada quando um Bloco de Código referencia
    outro. Quando um <strong>diretório é fechado</strong>, todos seus Blocos de Código
    são <strong>escondidos dentro do diretório</strong> e suas conexão passam a apontar
    para o nó do diretório, atuando como uma <strong>caixa preta</strong>.
  headline: Projetos enormes passam a fazer sentido
  media:
    image: "/uploads/2020/07/14/gif-3.gif"
    alt_text: ''
    has-shadow-box: true
  HtmlId: ''
  background-color: var(--bg-secondary)
  headline-color: var(--headline-color-secondary)
  content-color: var(--content-color-secondary)
- template: title-no-bottom-padding
  block: title
  headline: ''
  content: Looset Code
  HtmlId: looset-code
  content-color: var(--content-color-secondary)
  background-color: var(--bg-secondary)
  headline-color: var(--headline-color-secondary)
  title-color: var(--headline-color-secondary)
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: Looset Code ajuda desenvolvedores a <strong>navegar pelo código</strong>
    de maneira eficiente, evitando abrir vários arquivos ao mesmo tempo, e <strong>mostrando
    os Blocos de Código</strong> que estão trabalhando, simultaneamente <strong>numa
    única tela</strong>.
  content: ''
  media:
    image: "/uploads/2020/07/15/gif-4.gif"
    alt_text: Mostra apenas os Blocos de Código selecionados.
    has-shadow-box: true
  HtmlId: ''
  background-color: var(--bg-secondary)
  headline-color: var(--content-color-secondary)
  content-color: var(--content-color-secondary)
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: Resolva seu problema de documentação desatualizada
  content: 'Veja quando a documentação e o código se desincronizam: A <strong>data
    do último commit </strong>é mostrada tanto no código quanto na sua docstring,
    então desenvolvedores podem instantaneamente compará-las e ter certeza que podem
    <strong> confiar na informação</strong.'
  media:
    image: "/uploads/2020/07/16/gif-5.gif"
    alt_text: Aviso em amarelo quando docstring se desatualiza em relação ao código.
    has-shadow-box: true
  HtmlId: ''
  background-color: var(--bg-secondary)
  headline-color: var(--headline-color-secondary);
  content-color: var(--content-color-secondary);
- template: 1-column-embed
  block: one-column-embed
  embed: '<iframe width="800" height="500" style="box-shadow: 20px 13px 20px 0px #0000004f;"
    src="https://www.youtube.com/embed/x5mZcIVAPcg" frameborder="0" allow="accelerometer;
    autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'
  background-color: var(--bg-secondary)
- template: hero-banner-w-embed
  block: hero-embed
  headline-color: var(--content-color-secondary)
  content-color: var(--content-color-secondary)
  background-color: var(--bg-secondary)
  content: Muito projeto Open Source é feito de graça, mas infelizmente eu não posso
    me dar ao luxo de trabalhar a quantidade de horas que esse projeto demanda sem
    receber. Kickstarter é uma plataforma de financiamento coletivo onde você pode
    contribuir com qualquer quantia e só é cobrado se eu alcançar meu objetivo.
  embed: <iframe src="https://www.kickstarter.com/projects/looset-team/looset/widget/card.html?v=2"
    width="430" height="510" frameborder="0" scrolling="no"></iframe>
  headline: Você pode apoiar o Looset agora mesmo
  background_image: ''
  cta:
    enabled: true
    url: https://www.kickstarter.com/projects/looset-team/looset?ref=ahrz8q
    button_text: Campanha Kickstarter
- template: signup-bar
  block: cta-bar
  email_recipient: JpSoares106@gmail.com
  content: Gostaria de receber atualizações sobre o projeto por email?
  button-text: Me Inscrever
  background-color: "#4b7153"
  content-color: var(--content-color)
- template: detail-content
  block: text-1
  headline: Mais Conteúdo
  content: "<ul><li><p>Um <a href=\"https://youtu.be/ktVpk1UukKA\" title=\"Toda a
    família Looset\" target=\"_blank\">video demo</a> de futuras ferramentas: Looset
    Glossary e Looset Page;</p></li><li><p>Uma <a href=\"https://forms.gle/5vbfc54MRXcBodKc7\"
    title=\"Google Forms survey\" target=\"_blank\">pesquisa</a> para entender quais
    ferramentas beneficiariam mais os desenvolvedores;</p></li><li><p>Um <a href=\"https://github.com/JpOnline/looset/blob/master/tools-overview/README.md\"
    title=\"Tools Overview\" target=\"_blank\">post</a> com uma visão geral sobre
    as quatro ferramentas.</p></li><li><p><a href=\"/looset-landing\">English version
    \U0001F1EC\U0001F1E7</a></p></li></ul>"
  background-color: var(--bg)
  headline-color: var(--headline-color)
  content-color: var(--content-color)
- template: simple-footer
  block: footer-1
  content: <a href="https://jponline.github.io/site/" title="Jp's site">By Jp</a>
  background-color: var(--bg)
  content-color: var(--content-color)

---

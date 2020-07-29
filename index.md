---
layout: blocks
title: Source Code Visualizaiton
date: 2020-07-26T15:00:00.000-03:00
page_sections:
- template: navigation-header
  block: header-1
  logo: "/uploads/2020/07/11/logo.png"
  navigation:
  - link: "#looset-diagram"
    link_text: Looset Diagram
  - link: "#looset-code"
    link_text: Looset Code
  background-color: ''
- template: hero-banner-w-image
  block: hero-2
  headline: Source Code Visualization
  content: A family of tools to explore big or unknown codebases.
  cta:
    enabled: true
    url: https://youtu.be/x5mZcIVAPcg
    button_text: Get it!
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
    content: This is possible by a simple <strong>static analyzer</strong> that identify
      <strong>Code Blocks</strong> and an identifier, what in most cases are functions
      and its name. The basic analyzer rely in the fact that developers split Code
      Blocks by <strong>blank lines</strong> and use appropriate <strong>indentation</strong>.
      It works with <strong>any language</strong>, this is why it's perfect to be
      used in projects that mix HTML, CSS, Javascript, C#, Clojure, Python, Haskell,
      Cobol, Lolcode, etc.
    headline: All Languages Supported
    headline-color: var(--headline-color)
    content-color: var(--content-color)
    background-color: ''
  col_1:
    content: The problem is when we are facing a big codebase that we don't know,
      it would be great if every project is split well in modules, have good documentation,
      tests and functions and variables are named accordingly with the domain entities,
      but this is not always true.
    headline: Source Code is rarely clean
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
  headline: Developer time
  media:
    image: "/uploads/2020/07/24/data-charts.gif"
    alt_text: "Pie chart: Less than a month\t30%, One to three months 44.70%, Three
      to six months 17.40%, Six to nine months 5.10%, Nine months to a year 1.70%,
      More than a year 1.20%."
    has-shadow-box: false
  content: 'Code takes time to understand, <a href="https://insights.stackoverflow.com/survey/2018#work-_-how-long-do-developers-expect-new-coworkers-to-take-to-be-productive"
    title="">StackOverflow survey</a> showed that <strong>more than 70%</strong> of
    experient software developers are expect to take <strong>more than a month to
    become productive</strong> in a new project.<br><br>On average, developers spend
    only <strong>5%</strong> of their time <strong>writing and editing</strong> code,
    more than <strong>80%</strong> of the time is spent on <strong>understanding and
    navigation</strong> <a href="https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=4781&amp;context=sis_research"
    title="Measuring program comprehension: A large-scale field study with professionals.">(XIA,
    2018)</a>.'
  HtmlId: ''
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
  headline: Visualize how your whole system is affected when doing specific changes;<br><br>Improve
    communication by showing how the product evolved over time;<br><br>Estimate how
    long tasks will take by understanding their complexity.
  content: ''
  media:
    alt_text: not yet
    image: "/uploads/2020/07/14/gif-2.gif"
    has-shadow-box: true
  HtmlId: diagram
  background-color: var(--bg-secondary)
  headline-color: var(--content-color-secondary)
  content-color: var(--content-color-secondary)
- template: content-feature
  block: feature-1
  media_alignment: Right
  content: Looset Diagram helps you to <strong>understand the code</strong> you work
    with by giving more than just text colored in an editor and showing a <strong>graph
    of call references</strong>. <br><br>It automatically generates graph diagrams
    where each Code Block is a node and a connection is created when a Code Block
    references another Code Block. When a <strong>folder is collapsed</strong> all
    its Code Blocks get <strong>hidden inside the folder</strong> and their connections
    start to point to the folder, acting as a <strong>black box</strong>. It's simple
    to explain and beautiful to see.
  headline: Collapsable nodes
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
  headline: Looset Code helps developers who want to <strong>walk through the codebase</strong>
    efficiently by avoiding managing several opened files and <strong>showing Code
    Blocks</strong> they are working simultaneously <strong>in one screen</strong>.
  content: ''
  media:
    image: "/uploads/2020/07/15/gif-4.gif"
    alt_text: Show only selected Code Blocks.
    has-shadow-box: true
  HtmlId: ''
  background-color: var(--bg-secondary)
  headline-color: var(--content-color-secondary)
  content-color: var(--content-color-secondary)
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: Documentation and Code Synchronization
  content: 'See when documentation and code get out of sync: The <strong>last commit
    date </strong>is shown both to the Code Block and its docstring, so developers
    can instantly compare it to be sure they can <strong>trust the information</strong>.'
  media:
    image: "/uploads/2020/07/16/gif-5.gif"
    alt_text: Yellow warning when docstring and code get out of sync.
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
- template: hero-banner-w-image
  block: hero-2
  headline-color: var(--content-color-secondary)
  content-color: var(--content-color-secondary)
  background-color: var(--bg-secondary)
  content: 'A lot of open source code gets done for free, but unfortunately I can
    not afford to spend the amount of time this project requires for free. Kickstarter
    is a platform where you can contribute with any amount and you only get charged
    if it reaches the goal. '
  image:
    image: "/uploads/2020/07/27/kickstarter-logo.png"
    alt_text: Kickstarter logo
    url: https://youtu.be/x5mZcIVAPcg
    has-shadow-box: false
  headline: You can support Looset now
  background_image: ''
  cta:
    enabled: true
    url: ''
    button_text: Kickstarter Campaign
- template: signup-bar
  block: cta-bar
  email_recipient: JpSoares106@gmail.com
  content: Would you like to receive updates by email?
  button-text: Subscribe
  background-color: "#4b7153"
  content-color: var(--content-color)
- template: detail-content
  block: text-1
  headline: More Content
  content: "<ul><li><p>A <a href=\"https://youtu.be/ktVpk1UukKA\" title=\"The whole
    Looset Family\">video demo</a> of future tools: Looset Glossary and Looset Page;</p></li><li><p>A
    <a href=\"https://forms.gle/5vbfc54MRXcBodKc7\" title=\"Google Forms survey\">survey</a>
    for devs to understand which tools would benefit them better;</p></li><li><p>An
    overview <a href=\"https://github.com/JpOnline/looset/blob/master/tools-overview/README.md\"
    title=\"Tools Overview\">README</a> of the four tools.</p></li><li hidden><p>Versão
    em Português \U0001F1E7\U0001F1F7</p></li></</ul>"
  background-color: var(--bg)
  headline-color: var(--headline-color)
  content-color: var(--content-color)
- template: simple-footer
  block: footer-1
  content: <a href="https://jponline.github.io/site/" title="Jp's site">By Jp</a>
  background-color: var(--bg)
  content-color: var(--content-color)

---

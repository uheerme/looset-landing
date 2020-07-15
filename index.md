---
layout: blocks
title: A source code explorer for big or unknown projects
date: 2020-07-08T00:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2020/07/11/logo.png"
  navigation:
  - link: "#looset-diagram"
    link_text: Looset Diagram
  - link: "#looset-code"
    link_text: Looset Code
  cta:
    url: https://youtu.be/ktVpk1UukKA
    button_text: Watch Demo
  background-color: ''
- template: hero-banner-w-image
  block: hero-2
  headline: Source Code Visualization
  content: A family of tools to explore big or unknown code bases.
  cta:
    enabled: true
    url: https://youtu.be/ktVpk1UukKA
    button_text: Demo on Youtube
  image:
    image: "/uploads/2020/07/13/looset-diagram-gif.gif"
    alt_text: Product Shot
  background_image: ''
  background-color: " rgba(252, 250, 252, 1);"
  headline-color: black
  content-color: "#666"
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
    headline-color: "--headline-color"
    content-color: "--content-color"
    background-color: ''
  col_1:
    content: The problem is when we are facing a big code base that we don't know,
      it would be great if every project is split well in modules, have good documentation,
      tests and functions and variables are named accordingly with the domain entities,
      but this is not always true.
    headline: Source Code is rarely clean
    headline-color: var(--headline-color)
    content-color: var(--content-color)
    background-color: ''
  background-color: var(--bg)
- template: title-no-bottom-padding
  block: title
  content: <img src="/uploads/2020/07/11/diagram-logo.png">
  HtmlId: looset-diagram
  background-color: ''
  content-color: "#666"
  headline-color: black
  headline: ''
  title-color: black
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: Looset Diagrams helps developers who wants to <strong>understand the code</strong>
    they are working by giving more than just text colored in a editor and showing
    a <strong>graph of call references</strong> between Code Blocks.
  content: ''
  media:
    alt_text: not yet
    image: "/uploads/2020/07/14/gif-2.gif"
  HtmlId: diagram
  background-color: ''
  headline-color: black
  content-color: "#666"
- template: content-feature
  block: feature-1
  media_alignment: Right
  content: It automatically generates graph diagrams where each Code Block is a node
    and a connection is created when a Code Block references another Code Block. When
    a <strong>folder is collapsed</strong> all its Code Blocks get <strong>hidden
    inside the folder</strong> and their connections start to point to the folder,
    acting as a <strong>black box</strong>. It's simple to explain and beautiful to
    see.
  headline: Collapsable nodes
  media:
    image: "/uploads/2020/07/14/gif-3.gif"
    alt_text: ''
  HtmlId: ''
  background-color: ''
  headline-color: black
  content-color: "#666"
- template: title-no-bottom-padding
  block: title
  headline: ''
  content: <img src="/uploads/2020/07/11/code-logo.png">
  HtmlId: looset-code
  content-color: "#666"
  background-color: ''
  headline-color: black
  title-color: black
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: 'Looset Code helps developers who want to <strong>walk through the code
    base</strong> efficiently by avoiding managing several opened files and <strong>showing
    Code Blocks</strong> they are working simultaneously <strong>in one screen</strong>. '
  content: ''
  media:
    image: "/uploads/2020/07/15/gif-4.gif"
    alt_text: ''
  HtmlId: ''
  background-color: ''
  headline-color: black
  content-color: "#666"
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: Documentation and Code Synchronization
  content: 'See when documentation and code get out of sync: The <strong>last commit
    date </strong>is shown both to the Code Block and its docstring, so developers
    can instantly compare it to be sure they can <strong>trust the information</strong>.'
  media:
    image: ''
    alt_text: ''
  HtmlId: ''
  background-color: ''
  headline-color: black
  content-color: "#666"
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: Custom levels of abstractions
  content: 'With Labels developers have a general overview of the code base better
    than with the file system. A Label is very similar to a folder: it can contain
    Code Blocks and other Labels. The difference is they can be in more than a Label
    at the same time. E.g. a Code Block called <code>getFeatureIdsAt</code> can be
    in the <code>Main API</code>, so if we expand the Label we can see it''s there,
    but the same Code Block can also be in the <code>Point</code> Label and we can
    see it in both places.'
  media:
    image: ''
    alt_text: ''
  HtmlId: ''
  background-color: ''
  headline-color: black
  content-color: "#666"
- template: detail-content
  block: text-1
  headline: More Content
  content: '<ul><li><p>A <a href="https://youtu.be/ktVpk1UukKA" title="The whole Looset
    Family">video demo</a> of future tools: Looset Glossary and Looset Page;</p></li><li><p>A
    <a href="https://forms.gle/5vbfc54MRXcBodKc7" title="Google Forms survey">survey</a>
    for devs to understand which tools would benefit them better;</p></li><li><p>An
    overview <a href="https://github.com/JpOnline/looset/blob/master/tools-overview/README.md"
    title="Tools Overview">README</a> of the four tools.</p></li></ul>'
  background-color: ''
  headline-color: black
  content-color: "#666"
- template: simple-footer
  block: footer-1
  content: <a href="https://jponline.github.io/site/" title="Jp's site">By Jp</a>
  background-color: ''
  content-color: "#666"

---
foo bar
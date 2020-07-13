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
- template: hero-banner-w-image
  block: hero-2
  headline: Source Code Visualization
  content: A family of tools to explore big or unknown code bases.
  cta:
    enabled: true
    url: https://youtu.be/ktVpk1UukKA
    button_text: Demo on Youtube
  image:
    image: "/uploads/2020/07/07/screencast-python-poetry-org-2020-07-07-10_26_08.gif"
    alt_text: Product Shot
  background_image: ''
- template: 1-column-text
  block: one-column-1
  headline: Source Code is rarely clean
  content: The problem is when we are facing a big code base that we don't know, it
    would be great if every project is split well in modules, have good documentation,
    tests and functions and variables are named accordingly with the domain entities,
    but this is not always true.
- template: title-no-bottom-padding
  block: title
  content: <img src="/uploads/2020/07/11/diagram-logo.png">
  HtmlId: looset-diagram
  headline: ''
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: Looset Diagrams helps developers who wants to <strong>understand the code</strong>
    they are working by giving more than just text colored in a editor and showing
    a <strong>graph of call references</strong> between Code Blocks.
  content: ''
  media:
    alt_text: not yet
    image: ''
  HtmlId: diagram
- template: content-feature
  block: feature-1
  media_alignment: Right
  content: It automatically generates graph diagrams where each Code Block is a node
    and a connection is created when a Code Block references another Code Block. When
    a folder is collapsed all its Code Blocks get hidden inside the folder and their
    connections start to point to the folder, acting as a black box. It's simple to
    explain and beautiful to see.
  headline: Graph of Code Blocks references
  media:
    image: ''
    alt_text: ''
  HtmlId: ''
- template: 1-column-text
  block: one-column-1
  headline: All Languages Support!
  content: This is possible by a simple <strong>static analyzer</strong> that identify
    <strong>Code Blocks</strong> and an identifier, what in most cases are functions
    and its name. The basic analyzer rely in the fact that developers split Code Blocks
    by <strong>blank lines</strong> and use appropriate <strong>indentation</strong>.
    It works with <strong>any language</strong>, this is why it's perfect to be used
    in projects that mix HTML, CSS, Javascript, C#, Clojure, Python, Haskell, Cobol,
    Lolcode, etc.
- template: title-no-bottom-padding
  block: title
  headline: ''
  content: <img src="/uploads/2020/07/11/code-logo.png">
  HtmlId: looset-code
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: 'Looset Code helps developers who want to <strong>walk through the code
    base</strong> efficiently by avoiding managing several opened files and <strong>showing
    Code Blocks</strong> they are working simultaneously <strong>in one screen</strong>. '
  content: ''
  media:
    image: ''
    alt_text: ''
  HtmlId: ''
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: See when documentation and code get out of sync
  content: The <strong>last commit date </strong>is shown both to the Code Block and
    its docstring, so developers can instantly compare it to be sure they can <strong>trust
    the information</strong>.
  media:
    image: ''
    alt_text: ''
  HtmlId: ''
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
- template: detail-content
  block: text-1
  headline: More Content
  content: '<ul><li><p>A <a href="https://youtu.be/ktVpk1UukKA" title="The whole Looset
    Family">video demo</a> of future tools: Looset Glossary and Looset Page;</p></li><li><p>A
    <a href="https://forms.gle/5vbfc54MRXcBodKc7" title="Google Forms survey">survey</a>
    for devs to understand which tools would benefit them better;</p></li><li><p>An
    overview <a href="https://github.com/JpOnline/looset/blob/master/tools-overview/README.md"
    title="Tools Overview">README</a> of the four tools.</p></li></ul>'
- template: simple-footer
  block: footer-1
  content: <a href="https://jponline.github.io/site/" title="Jp's site">By Jp</a>

---
foo bar
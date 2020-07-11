---
layout: blocks
title: Looset
date: 2020-07-08T00:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2020/07/11/logo.png"
  navigation:
  - link: "#diagram"
    link_text: Looset Diagram
  - link: "#features"
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
  headline: All Languages Support!
  content: This is possible by a simple <strong>static analyzer</strong> that identify
    <strong>Code Blocks</strong> and an identifier, what in most cases are functions
    and its name.<br><br>The basic analyzer rely in the fact that developers split
    Code Blocks by blank lines and use appropriate indentation.<br><br>It works with
    any language, this is why it's perfect to be used in projects that mix HTML, CSS,
    Javascript, C#, Clojure, Python, Haskell, Cobol, Lolcode, etc.
- template: full-width-media-element
  block: media-1
  image: "/uploads/2020/07/10/diagram-logo.png"
  caption: ''
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
  headline: ''
  media:
    image: ''
    alt_text: ''
  HtmlId: ''
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: <strong>Swap &amp; Switch<span class="light">&nbsp;</span></strong><span
    class="light">the Blocks to create sites quickly</span>
  content: Quickly assemble and create custom sites with 16 design blocks for seven
    different sections.
  media:
    image: "/uploads/2020/07/07/welcome-to-screencastify-the-1-s.gif"
    alt_text: uBuild Blocks Mock-Up
  HtmlId: ''
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: <strong>Customize Blocks</strong><span class="light">&nbsp;to make quick
    edits throughout your new site</span>
  content: Each block comes with custom Front Matter that can easily be edited in
    Forestry's UI.
  media:
    image: "/uploads/2018/06/21/edit.gif"
    alt_text: Customize Blocks
  HtmlId: ''
- template: full-width-media-element
  block: media-1
  image: "/uploads/2018/06/21/theme.png"
  caption: All Available Blocks
- template: detail-content
  block: text-1
  headline: Steps to Build a Site!
  content: <p>uBuild is an open-source Jekyll based theme that doubles as a builder
    tool inside the Forestry content manager. It's easy to get started!</p><ol><li><p>Fork
    the <a href="https://github.com/forestryio/ubuild-jekyll">repo</a> and import
    the site into <a href="https://forestry.io/">Forestry</a> (or use <a href="https://forestry.io/blog/ubuild-a-new-theme-for-static-sites-using-blocks#even-quicker-start">our
    magic button</a>).</p></li><li><p>Click on 'Add New' in Forestry and select the
    Page-Builder template.</p></li><li><p>Add and customize the available Blocks and
    preview them as you go along.</p></li><li><p>Read <a href="https://forestry.io/blog/ubuild-a-new-theme-for-static-sites-using-blocks/">our
    article</a> and create your own Blocks.</p></li></ol>
- template: simple-footer
  block: footer-1
  content: Hello world! ❤︎

---
foo bar
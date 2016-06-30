Non-semantic elements:
- <div>
- <span>

Semantic Elements:
- <header>
- <nav>
- <section>
- <article>
- <main>
- <aside>
- <footer>
- <mark>

## Div-itis!
Overusing <div> tags for defining semantic sections makes automatic outlining impossible.

i.e
```
"Is that <div> part of the outline of the page, defining a section or a subsection?" Or "is it only a presentational <div>, only used for styling?")
```
For assistive technology, automatic outlining is important. Information gets presented to the users according to the structure of the document.

Merging several documents is hard: inclusion of a sub-document in a main document means changing the level of the HTML Headings Element so that the outline is kept. This is solved in HTML5 as the newly introduced sectioning elements (<article>, <section>, <nav> and <aside>) are always subsections of their nearest ancestor section, regardless of what sections are created by internal headings.

A document can have special sections containing information that is not part of, though it is related to, the main flow, like an advertisement block or an explanation box. HTML5 introduces the <aside> element allowing such sections to not be part of the main outline.

Sections containing information related not to the document but to the whole site, like logos, menus, table of contents, or copyright information and legal notices. For that purpose, HTML5 introduces three new elements: <nav> for collections of links, such as a table of contents, <footer> and <header> for site-related information. Note that <header> and <footer> are not sectioning content like <section>, rather, they exist to semantically mark up parts of a section.

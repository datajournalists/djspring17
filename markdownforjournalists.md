# What is Markdown and why journalists use it?

Markdown is ["a text-to-HTML conversion tool for web writers"](http://daringfireball.net/projects/markdown/), created by John Gruber to help you focus on writing instead of worrying about document formatting and what happens to that formatting when your document is converted to another format (hint: a mess).

This means that the text you write using the Markdown syntax is converted to HTML (and it can be exported to .PDF, .doc and other formats without problems).

Markdown uses common punctuation characters.
E.g.: asterisks around a `*word in italic*` convert it into a *word in italic* and in HTML as `<i>word in italic</i>`. Two asterisks? `**word in bold**` translates into **word in bold** and `<b>word in bold</b>`. Markdown has syntax for headlines, lists, block quotes, links and more (see below). Very relevant: ["it is used in all forms of writing in Github".](https://guides.github.com/features/mastering-markdown/)

One caveat: you can write content and turn it into HTML but you will have to add the HTML page structure tags (E.g. `<!document type>`, `<body>`, etc.).

## Helps reporters write fast and collaborate

Many newsrooms and journalists use it to write their content, especially if it goes through a process of editing and collective web production that involves designers and programmers.

Here is a use case, that [Poynter wrote about](https://www.poynter.org/2015/keeping-up-with-the-times-free-tech-for-nonprofit-newsrooms/384231/) not so long ago: "Investigative reporters at the Marshall Project write directly in Google Docs and share their copy with an editor when they’re done. Then, a script Vong wrote converts the text into markdown language that graphic designer will use when designing the story for the Marshall site".

Markdown is one of the tools several digital news operations adopt to "reduce barriers between programmers and non-programmers" working together, [found](http://towcenter.org/reducing-barriers-between-programmers-and-non-programmers-in-the-newsroom/) the Tow Center for Digital Journalism.

Reporters at NPR and ProPublica use it to handle copy as part of their workflow, [Vox Media purchased Editoria.ly](http://stet.editorially.com/articles/editorially-joins-vox-media/) (a startup that redefined the writing and collaboration experience with Markdown among other features), to boost Vox's already innovative publishing technology; and platforms and startups like Stack Overflow, Carto, Codeacademy, to name a few, [have adapted Markdown as their content formatting tool](https://carto.com/blog/why-we-use-markdow).

Why? It is dead easy to learn it and to write very fast with it without worrying about conversion issues (forget about wrong spacing, text styling and errors handling simple HTML tags).

## Learn it in five minutes

Because Markdown documents are plain text documents, you can use any text editor to create and edit a document. This means that you can write Markdown in [Sublime Text](https://www.sublimetext.com/), [Atom](www.atom.io), [Vim](http://www.vim.org/), [Visual Studio](https://code.visualstudio.com/docs), [Brackets](http://brackets.io/), [Notepad++](https://notepad-plus-plus.org/) or whatever text editor you prefer. Just **remember** to save the document as `filename.md` or `filename.markdown`.

Here is the basic syntax to write in Markdown format (via Github's ["Mastering Markdown"]((https://guides.github.com/features/mastering-markdown/)).


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

- Bulleted
- List

1. Numbered
2. List

**Bold**
*Italic*
***Italics & bold together***
`Code`

Horizontal line
*******

> Block quotes

[Link](url)

To add an image: ![Image](src)

```

For more examples and syntax options see:
- [A guide to Markdown for simpler web writing](https://scotch.io/bar-talk/a-guide-to-markdown-for-simpler-web-writing
).
- [John Gruber's Markdown original page](https://daringfireball.net/projects/markdown/)
- [A Markwdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Pick and use a Markdown editor

While a text editor gives you a fast way to create a `.md` document, the real benefit of using Markdown is evident when you need to convert the file into another format for publication, like HTML, .PDF (book) or a Word document (traditional proof reading).

If you are in journalism, as you read before, you may write a story in Markdown, convert it into HTML and then add some CSS and Javascript; may send the `.md` file to an editor, and interactive graphics colleague or a front end web developer. Chances are that you will be doing lots of this in a Github repository that you all have access to.

Since that’s your case, you will be better off using one of the many Markdown editors that exist. You can search for [“best Markdown editors”](https://www.google.com/search?num=50&client=firefox-b-ab&q=%22best+markdown+editors%22&oq=%22best+markdown+editors%22&gs_l=serp.3..0l2j0i22i30k1l8.6222.10539.0.10858.7.7.0.0.0.0.79.391.6.6.0.foo%2Cewh%3D0%2Cnso-enksa%3D0%2Cnso-enfk%3D1%2Cnso-usnt%3D1%2Cnso-qnt-npqp%3D0-2%2Cnso-qnt-npdq%3D0-5%2Cnso-qnt-npt%3D0-13%2Cnso-qnt-ndc%3D300%2Ccspa-dspm-nm-mnp%3D0-065%2Ccspa-dspm-nm-mxp%3D0-1625%2Cnso-unt-npqp%3D0-2%2Cnso-unt-npdq%3D0-35%2Cnso-unt-npt%3D0-1%2Cnso-unt-ndc%3D300%2Ccspa-uipm-nm-mnp%3D0-0125%2Ccspa-uipm-nm-mxp%3D0-0875%2Ccfro%3D1%2Cewh%3D0%2Cnso-enksa%3D0%2Cnso-enfk%3D0...0...1.1.64.serp..1.6.390...0i67k1j0i7i30k1j0i13k1j0i30k1.4y9J40xDMGw) to find the one you like the most.

I have prepared a short list of personal favorite desktop based and web-based editors that let you save and sync as well as preview how your Markdown looks like in real time while writing. This saves you time and effort.

1. [Stackedit](https://stackedit.io): Online editor that allows you to sync and save your documents in Google Drive and Dropbox as well as share the files. A good intro tool.
2. [IA Writer](https://ia.net/writer/): Payed desktop app for Mac (it costs $3,99). Simple, clean and includes several features like distraction-free, templates, spelling, and syncs with Dropbox and iCloud. I am bias. This is the one I use in my desktop computer.
3. [Atom](www.atom.io): Open source, free of cost. It’s a text editor but it includes the markdown preview. After you install Atom, go to the top menu option: “Packages” and choose “Markdown preview”: “Toggle preview”. Since it’s developed by Github it is *Github ready*. It is been known for speed problems but lately seems to be a whole lot better.
4. [MacDown](http://macdown.uranusjr.com/) (Mac only): Open source and free of cost. Lots of users.
5. [Prose.io](http://prose.io/): Open source and free of cost, web-based editor. Built for “managing content on GitHub”. Development Seed, the company that created it, eats it’s own dog food. They use it to serve CMS free websites. Features: “Use it to create, edit, and delete files, and save your changes directly to GitHub”. Used by journalists who are familiar with Github and Jekyll, a static site generator that offers writing and editing features.
6. [Dillinger.io](http://dillinger.io/): Open source, web based, free of cost. You can sync and save documents to Drive, Github, Dropbox and Medium.
7. [Classeur.io](http://classeur.io/): Freemium online and desktop. By the creators of Stackedit.

There are [many](https://www.slant.co/topics/899/~best-markdown-editor-for-os-x), many [more](https://speckyboy.com/markdown-tools-editors/) options. Just try a few until you find the one for you.

Did I mention you can add [emojis](http://www.webpagefx.com/tools/emoji-cheat-sheet/) in some of the extended Markdown versions, like the one used by Github?

```
  :metal:
  :clap:
  :rocket:
  :tada:
 ```
 :metal:
 :clap:
 :rocket:
 :tada:

 [//]: # (This is how you write comments in your Markdown. It won't show in the HTML page.)

# Charting tools to explore and choose from for your data analysis

There are hundreds of authoring tools and code for charting and doing all sorts of graphics is rich and diverse in every way. However, when choosing which path you will take it all comes down to your needs and ability, so ask yourself the following questions:

- How much time do you have to create the chart? Is it for publication on a deadline? For little time use existing authoring tools. Quartz, Globe and Mail, Vox, NPR and many other newsrooms created charting tools to produce simple charts on the fly. It's about speed, accuracy, easy authoring and cross browser compatibility.
- Is it for data analysis to visualize the data to understand it better for your reporting? Is it for a simple data analysis or a complex calculation with a lot of data? In the first cases you are ok with off the shelve tools. For more complex stuff you may use R with visualization packages but the learning curve at the beginning is steep.
- Is it for data analysis and publication of a project where you can take time to work on it? Do you have statistical and a medium to high level of coding skills? You may produce customized visualizations which will require knowing Javascript and libraries to produce data driven visualizations, like [D3](https://d3js.org/), [D3plus](https://d3plus.org/), [C3js](http://c3js.org/) and so many others (see [Awesome charting](https://github.com/zingchart/awesome-charting#free-and-open-source-libraries) and [Awesome dataviz](https://github.com/fasouto/awesome-dataviz)).
- What are your personal preferences? The same way you like some writing styles more than others, different programming syntax styles appeal to different minded people and you will like one language more than others. When it comes to code for data analysis you can see an excellent example in this [infographic comparison between Python and R](https://www.datacamp.com/community/tutorials/r-or-python-for-data-analysis)).

## Not much time, fast publication, regular data analysis

For our work I chose a short list of charting options. Like a food menu, this combo is like a lunch box for every day consumption. There are way more options you can explore by yourself.

- [Datawrapper](www.datawrapper.de): You are probably familiar with it already. Fast and simple way to create the most common charts in the online platform and then use the embed code or download as an SVG or PNG. Free account ha some limitations.

- [Graphik](http://maxharlow.com/graphik/): Online authoring for bar charts and line charts. Quick and dirty.

- [Chartbuilder](https://github.com/Quartz/Chartbuilder): Developed at Quartz to create simple graphics fast. They use it so much that created a new section of Quartz called [Atlas](https://www.theatlas.com/) that stores all the charts. With it you can:
  - Create [charts with the online builder](https://quartz.github.io/Chartbuilder/))
  - Download Chartbuilder from the [repository](https://github.com/Quartz/Chartbuilder) to your computer and follow the [guide to setup and deploy](https://github.com/Quartz/Chartbuilder#getting-started-with-chartbuilder). You need to install Node.js.
  - Brand it as you see fit. Follow [this "how to" guide](http://www.storybench.org/install-brand-version-chartbuilder/) by our friends at Storybench.

- [Playfair:](http://www.austinclemens.com/Playfair/playfair.html) A very friendly and powerful open source web app for creating static annotated charts. Why I like it:
  - [Mega easy to deploy:](https://github.com/equitablegrowth/Playfair#easy-to-deploy) You go to Playfair's [github repository](https://github.com/equitablegrowth/Playfair), clone it to your computer and open playfair.html in your browser and  :boom: you've deployed Playfair in local, and you can start using it.
  - [Power and flexibility](https://github.com/equitablegrowth/Playfair#power-and-flexibility-ggplot2-style-graphing) Offers many charting options and "it uses the [ggplot2](http://ggplot2.org/) concept of overlaying various chart elements on top of one another to create a complex chart. Playfair does not care what type of data you have - dates, numbers, and categories are all understood". It's small and yet resourceful.
  - [Annotations/on-chart editing:](https://github.com/equitablegrowth/Playfair#annotation-and-on-chart-editing) This is a very useful feature. It "includes a number of tools for adding annotations directly to a chart to help explain the graphic. These include adding arrows, callout lines, and arbitrary text annotations. On-chart editing refers to Playfair's tools for editing text, data, and other elements directly on the chart simply by dragging or right-clicking."
  [Create a theme:](https://github.com/equitablegrowth/Playfair#easy-to-theme) "If you want to use custom themes and save your graphs, you'll have to deploy Playfair to a server. This takes a little technical know-how but is basically as simple as uploading the Playfair folder to a server and changing the permissions for the scripts in the cgi-bin folder to 755".
  - It´s creator [posts makeovers](http://austinclemens.com/blog/tag/playfair/) of charts that have been created in newsrooms and makes a new version with Playfair, explaining the process.
  - You can [try it online](http://austinclemens.com/Playfair/playfair.html) and read a [tutorial](http://www.austinclemens.com/Playfair/playfair_docs/tutorial1.html) with chart examples

Downside: it does not produce interactive charts (only .PNG and .SVG)

- [Chart Tool](https://github.com/globeandmail/chart-tool) by the Globe and Mail: "Platform for creating, storing and displaying beautiful, responsive embeddable charts. Designed to fit the needs of a fast-paced mobile and print newsroom". It produces charts in:
    SVGs that are both responsive and interactive, via an embed code
    JPGs and PNGs for use as thumbnails and sharing on social media
    PDFs that can be almost immediately dropped into a print content management system
  - Has an [online demo builder](https://chart-tool-demo.herokuapp.com/new) you can use.
  - Lots of chart types: Line, Area, Stacked area, Column, Stacked column, Bar, Stacked bar and Multiline charts.    
  - Configurable basic annotations
  - Is open source so you can clone [the repository](https://github.com/globeandmail/chart-tool#getting-started) to your computer for local work. You will need to install Node.js, Meteor and Gulp (links in the repo) to [get started](https://github.com/globeandmail/chart-tool#getting-started).
  - Further down the line if you have some javascript, css skills you can [customize it](https://github.com/globeandmail/chart-tool/blob/master/tutorials/customizing.md) and you can deploy it to your own server, following [this guide](https://github.com/globeandmail/chart-tool/blob/master/tutorials/deploying.md)

---

Pending to be added

- The Gamma (still on experimental mode)

- Orange (visual data mining, great and simple)

- The Daily Graphics NPR tool



Tableau public

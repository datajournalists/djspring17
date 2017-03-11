# Charting tools to explore and choose from for your data analysis

There are hundreds of authoring tools and code for charting and doing all sorts of graphics is rich and diverse in every way. However, when choosing which path you will take it all comes down to your needs and ability, so ask yourself the following questions:

- How much time do you have to create the chart? Is it for publication on a deadline? For little time use existing authoring tools. Quartz, Globe and Mail, Vox, NPR and many other newsrooms created charting tools to produce simple charts on the fly. It's about speed, accuracy, easy authoring and cross browser compatibility.
- Is it for data analysis to visualize the data to understand it better for your reporting? Is it for a simple data analysis or a complex calculation with a lot of data? In the first cases you are ok with off the shelve tools. For more complex stuff you may use R with visualization packages but the learning curve at the beginning is steep.
- Is it for data analysis and publication of a project where you can take time to work on it? Do you have statistical and a medium to high level of coding skills? You may produce customized visualizations which will require knowing Javascript and libraries to produce data driven visualizations, like [D3](https://d3js.org/), [D3plus](https://d3plus.org/), [C3js](http://c3js.org/) and so many others (see [Awesome charting](https://github.com/zingchart/awesome-charting#free-and-open-source-libraries) and [Awesome dataviz](https://github.com/fasouto/awesome-dataviz)).
- What are your personal preferences? The same way you like some writing styles more than others, different programming syntax styles appeal to different minded people and you will like one language more than others. When it comes to code for data analysis you can see an excellent example in this [infographic comparison between Python and R](https://www.datacamp.com/community/tutorials/r-or-python-for-data-analysis)).

## Not much time, fast publication, regular data analysis

For our work I chose a short list of charting options. Like a food menu, this combo is like a lunch box for every day consumption. There are way more options you can explore by yourself.

1. [Datawrapper](www.datawrapper.de): You are probably familiar with it already. Fast and simple way to create the most common charts in the online platform and then use the embed code or download as an SVG or PNG. Free account ha some limitations.

2. [Graphik](http://maxharlow.com/graphik/): Online authoring for bar charts and line charts. Quick and dirty.

3. [Raw Graphs](http://rawgraphs.io): "RAW Graphs is an open source data visualization framework built with the goal of making the visual representation of complex data easy for everyone". It's goal is to be the "link between spreadsheet applications (e.g. Microsoft Excel, Apple Numbers, OpenRefine) and vector graphics editors (e.g. Adobe Illustrator, Inkscape, Sketch)".
Why I like it:
  - You can choose many graph options to create a graph in the web app super fast and embed it or export it.  
  - You just need to upload .csv or .tsv files or copy and paste data from Excel, Google Spreadsheets, TextEdit, etc) into the online editor.
  - Select the type of graph you want to use (has a wide gallery: Scatter Plot, Convex Hull, Delaunay Triangulation, Hexagonal Binning, Voronoi Tessellation, Box plot, Circular Dendrogram, Cluster Dendrogram, Circle Packing, Clustered Force Layout, Sunburst, Treemap, Alluvial Diagram, Parallel Coordinates, Bar chart, Pie chart, Gantt Chart, Area graph, Bump Chart, Horizon graph, Streamgraph) or [add your custom charts](https://github.com/densitydesign/raw/wiki/Adding-New-Charts).
  - Define what goes into each axis, which data point is the label and how you want to group data points. You can customize width and height as well as the color scale, among other options.
  - Get an embed code of the SVG or download as .svg, .png or as reordered data in a .json file.
  - Raw Graphs is open source and developed by Density Design from Italy. You can run it locally in your computer if you prefer. [Here is the repository and instructions](https://github.com/densitydesign/raw).

4. [Chartbuilder](https://github.com/Quartz/Chartbuilder): Developed at Quartz to create simple graphics fast. They use it so much that created a new section of Quartz called [Atlas](https://www.theatlas.com/) that stores all the charts. With it you can:
  - Create [charts with the online builder](https://quartz.github.io/Chartbuilder/))
  - Use it locally in your computer. To do so download Chartbuilder from the [repository](https://github.com/Quartz/Chartbuilder) to your computer and follow the [guide to setup and deploy](https://github.com/Quartz/Chartbuilder#getting-started-with-chartbuilder). You need to install Node.js. Here is [another guide](http://maliksingleton.com/2014/10/setup-chartbuilder-locally/) by Malik Singleton
  - Brand it as you see fit. Follow [this "how to" guide](http://www.storybench.org/install-brand-version-chartbuilder/) by our friends at Storybench.

5. [Playfair:](http://www.austinclemens.com/Playfair/playfair.html) A very friendly and powerful open source web app by Austin Clemens for creating static annotated charts. Why I like it:
  - [Mega easy to deploy:](https://github.com/equitablegrowth/Playfair#easy-to-deploy) You go to Playfair's [github repository](https://github.com/equitablegrowth/Playfair), clone it to your computer and open playfair.html in your browser and  :boom: you've deployed Playfair in local, and you can start using it.
  - [Power and flexibility](https://github.com/equitablegrowth/Playfair#power-and-flexibility-ggplot2-style-graphing) Offers many charting options and "it uses the [ggplot2](http://ggplot2.org/) concept of overlaying various chart elements on top of one another to create a complex chart. Playfair does not care what type of data you have - dates, numbers, and categories are all understood". It's small and yet resourceful.
  - [Annotations/on-chart editing:](https://github.com/equitablegrowth/Playfair#annotation-and-on-chart-editing) This is a very useful feature. It "includes a number of tools for adding annotations directly to a chart to help explain the graphic. These include adding arrows, callout lines, and arbitrary text annotations. On-chart editing refers to Playfair's tools for editing text, data, and other elements directly on the chart simply by dragging or right-clicking."
  [Create a theme:](https://github.com/equitablegrowth/Playfair#easy-to-theme) "If you want to use custom themes and save your graphs, you'll have to deploy Playfair to a server. This takes a little technical know-how but is basically as simple as uploading the Playfair folder to a server and changing the permissions for the scripts in the cgi-bin folder to 755".
  - It´s creator [posts makeovers](http://austinclemens.com/blog/tag/playfair/) of charts that have been created in newsrooms and makes a new version with Playfair, explaining the process.
  - You can [try it online](http://austinclemens.com/Playfair/playfair.html) and read a [tutorial](http://www.austinclemens.com/Playfair/playfair_docs/tutorial1.html) with chart examples
  - Small downside: it does not generate interactive charts (only .PNG and .SVG)

6. [Chart Tool](https://github.com/globeandmail/chart-tool) by the Globe and Mail: "Platform for creating, storing and displaying beautiful, responsive embeddable charts. Designed to fit the needs of a fast-paced mobile and print newsroom". It produces charts in:
    SVGs that are both responsive and interactive, via an embed code
    JPGs and PNGs for use as thumbnails and sharing on social media
    PDFs that can be almost immediately dropped into a print content management system
  - Has an [online demo builder](https://chart-tool-demo.herokuapp.com/new) you can use.
  - Lots of chart types: Line, Area, Stacked area, Column, Stacked column, Bar, Stacked bar and Multiline charts.    
  - Configurable basic annotations
  - Is open source so you can clone [the repository](https://github.com/globeandmail/chart-tool#getting-started) to your computer for local work. You will need to install Node.js, Meteor and Gulp (links in the repo) to [get started](https://github.com/globeandmail/chart-tool#getting-started).
  - Further down the line if you have some javascript, css skills you can [customize it](https://github.com/globeandmail/chart-tool/blob/master/tutorials/customizing.md) and you can deploy it to your own server, following [this guide](https://github.com/globeandmail/chart-tool/blob/master/tutorials/deploying.md)

7. [Timeline Storyteller](https://timelinestoryteller.com/) by Microsoft: Think of it as the Timeline JS for graphics and visual storytelling with many very useful features. Why I like it:
  - Browser based with online editor.
  - Many timeline options, scales and layouts. It has controls for "filtering, highlighting, and annotation. You can export images of a timeline or assemble and record a story about your data and present it within the application."
  - Include data in .CSV and .JSON formats or from a public Google Spreadsheet.
  - Since it's a timeline each event requires a start date.
  - You load timeline data (JSON, CSV, Google Spreadsheet).
  - Choose "a combination of representation, scale, and layout from the menu at the top of the screen". See the [guide](http://timelinesrevisited.github.io/supplemental/gallery/) "on selecting appropriate combinations for your story. Mouseover these options to view a tooltip that describes how they might be useful".
  - Edit the canvas. You can "click on events to annotate" with captions and images, "resize and reposition" captions and images or "highlight events without showing label".
  - A very useful feature is that you can record the "canvas as a scene, which retains labels, captions, and images; enter playback mode" and "navigate to previous / next recorded scene".
  - Export the "canvas as a PNG or SVG, or export the series of scenes as an animated GIF or as a JSON Blob (.cdc extension)".

  At the time I write this (March, 2017) Timeline Storyteller is still "a research prototype under development at Microsoft Research". According to the authors, they "plan to release the code as open source in the coming months".

8. [The Gamma](http://thegamma.net/) (beta): It is still early to see where this project by Tomas Petricek from the Alan Turing Institute will go, but it's very promising because it aims to be a programming tool for journalists that thinks of a data driven article as an executable program, that could help reduce analysis errors and deal with a crucial part of any data story: **reproducibility**. Or, in other words, being able to see and verify that the underlying code and calculations of a project **are correct** and check the data sources used by you. This provides a new level of transparency and trust letting others review the steps you took to produce your data driven project.
What I like about it (besides the aforementioned):
- You can summarize data in a easy way to create graphics and tables. It comes with a **built-in pivot type provider**: less *jargon*? "Understands your data source and exposes all operations in an easy to discover way".
- Still trying it so I can't say for sure but it promises that "you can understand the code even without programming experience" by mixing the logic spreadsheet utilities, like filtering, sorting, grouping, sum, rank, etc., with programming language on it's live editor and preview the results.
- Star by a) reading the [Exploring](http://thegamma.net/exploring/) section to understand the language and logic b) [Publishing](http://thegamma.net/publishing/) to understand how to add data and work with it. c) [Developers page](http://thegamma.net/developers/) to read details and follow the instructions to download The Gamma's npm package and add other necessary components to have your local setup. **Beware:** If you are on deadline and/or don't know how to work with Rest services, command line or JS, don't try The Gamma yet. It can be a bit complicated at first. Is a good way to learn more about data wrangling and programming but the on-boarding process for journalists is THE thing The Gamma needs improvement with.
[Short presentation](http://tpetricek.github.io/Talks/2016/open-storytelling/#/)
[Programming Tools for Data Journalism: video workshop](https://www.youtube.com/watch?v=cYoO2RvZn7Y)

Next to add in the list:

- SQLPad 

- Orange

- The NPR Daily Graphics Rig





Tableau public

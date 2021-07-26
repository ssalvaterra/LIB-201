# Network Analysis
A Network Analysis is simply a study of relationships among a group of connected things. The "things" could be people, cities, cells in the body, etc.! The idea of a network analysis is to visualize these relationships, so you can see the patterns (or lack thereof) in connections within the network.
<!--screenshot of sample network-->

We use network analysis to ask questions about the players in the network, like 
* Who is the most/least influential?
* What are some of the roles of the different things in this network?
* How connected are the things in this network?
* Are there distinct subgroups or "neighborhoods" in this network?

For the Smith Papers collection, we are asking these questions, more or less! 

| Question | Smith Papers Translation |
| ------------------------- | --------------------- |
| Who is the most influential? | Which person wrote the most letters to the most people? |
| How connected is this network? | Did everyone write letters to each other, or just some people? |
| What are the distinct groups? | Who wrote to each other most often? |

<!--Assessment on what a network analysis is/could be-->

# Network Analysis Terms
Most softwares that facilitate Network Analyses use a different vocabulary. You'll learn about what each part of a network is in this section, and in the next section, we'll talk about different ways analyze those parts. <!--Link to slideshow or reuse as images-->

## Networks
<p><img src="https://github.com/hillaryAHR/LIB-201/blob/main/network-analysis-lecture-files/Slide3.JPG" alt="example of a simple network with 6 green and pink nodes and edges" width="" height="" /></p>

A network is a visual representation of relationships between entities. The network alone does not always share the context of the relationships (e.g. "These are people who talk to each other in this book," or "These are the flight paths among major airlines,"), but they do highlight relationships. In doing so, they show how different players dominate (or not!) those relationships.

<!--assessment on network - can you have a network where nodes are not connected?-->
## Paths
<p><img src="https://github.com/hillaryAHR/LIB-201/blob/main/network-analysis-lecture-files/Slide4.JPG" alt="example of a simple network the nodes circled" width="" height="" /></p>

Paths are the length from one node to the next. In this image, the path length from Ben to Anna is 1, but the path length from Ben to Cara is 2, and so on. The average length of each path will tell us how _dense_ the network is, or in other words, how connected everyone is to each other. If everyone is connected to everyone by 1 path, the network is 100% dense! 

## Nodes
<p><img src="https://github.com/hillaryAHR/LIB-201/blob/main/network-analysis-lecture-files/Slide5.JPG" alt="example of a simple network the nodes circled" width="" height="" /></p>

## Edges
<p><img src="https://github.com/hillaryAHR/LIB-201/blob/main/network-analysis-lecture-files/Slide6.JPG" alt="example of a simple network the nodes circled" width="" height="" /></p>

* Undirected
* Directed
  * Source
  * Target



## Degree
## Centrality
<!--Assessment on terms-->

# Analyzing relational data
Did that phrase make your stomach turn? Don't worry! We are not actually doing math in this class, but we will be using mathematic concepts. Let's break it down.

## Degree Centrality
## Closeness Centrality
## Betweenness Centrality
## Eigenvector Centrality

<!--do I need an additional section on cleaning data? Or is that a separate conversation for earlier?-->

# Data Modeling for Visualizing a Network

In order to tell the software (which we go over in the next section) how to recognize which nodes are connected, and by what paths, we are going to create a spreadsheet with two columns, at minimum. 

<!--link to spreadsheet for existing network-->
<!--Add more on cleaning and strcutring from NA-worklog-->

# Software for visualizing a network analysis

There are several different softwares for visualizing a network, and they all serve different purposes. We are going to use XYZ <!--Gephi? Cytoscape? Palladio? Other?--> because it is free, has a relatively low accessibility bar, and most importantly, will allow us to use the visualization to answer our question.

## Installation
<!--link to download page-->
<!--link to a tutorial-->


## Tutorials and further readings on network analysis:
* Thomas Padilla and Brandon Locke. "Introduction to Network Analysis." http://www.thomaspadilla.org/cytoscape/ 
* Miriam Posner, "Network Analysis." http://miriamposner.com/classes/dh101f16/tutorials-guides/data-visualization/network-analysis/ 
* Miriam Posner, "Creating a Network Graph with Gephi." http://miriamposner.com/dh101f14/wp-content/uploads/2014/11/Creating-a-Network-Graph-with-Gephi.pdf
* Katayoun Torabi. Introduction to Gephi. 2020 Programming4Humanists Presentation
* Programming Historian, "From Hermeneutics to Data to Networks: Data Extraction and Network Visualization of Historical Sources." https://doi.org/10.46430/phen0044 
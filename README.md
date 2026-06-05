# Punch-Drunk Love Data Essay

On the [PTAnnotated website](https://digbmc.github.io/pt-annotated/), certain screenshots of Punch-Drunk Love are marked with the "intertextualities" tag. These specific screenshots contain references to other pieces of media. However, there is no way to see all the works being referenced without going through the screenshots one by one. The purpose of this data visualization is to allow users to easily see the connection between references, as well as the type of media being referenced (film, book, etc.).

## Network Graphs

I used a network graph to best show the connections between references. The hope is that this graph could be expanded to include other PTA films, exhibiting which works he tends to allude to multiple times. 

## Guide to Graph

The graph is made up of nodes and edges. Nodes are represent the media being referenced and can be clicked on in order to see metadata such as year and creator. You can also see which annotated screenshot the information is being pulled from.

The media types that align with the colors are films, artwork, books, creators, and genres. Creators refer to people whose style or type of work is being referred to, but not a specific product of theirs (e.g. Charlie Chaplin's physical comedy). Genres similarly refer to the thematic and structural elements shared throughout a category, but not a specific piece of media (e.g. high sharp music in horror movies).  

<iframe src="https://claraeks.github.io/dataviz/#" title="Punch-Drunk Love Visualization" height="600" width="900"></iframe>

See full screen version [here](https://claraeks.github.io/dataviz/#).

## Methodology

All data was pulled from the PTAnnotated website, I hand inputed it into CSV files to make up a collection of [nodes](https://1drv.ms/x/c/46c8a422e8e8a3b1/IQCIqXsqt5E9RJOyBobPoeHqAa2gxJQQUG5TvAuqdmZIG40?e=BEvoR5) and [edges](https://1drv.ms/x/c/46c8a422e8e8a3b1/IQBucAcClxDxTKgQXlo_MBCPAfcgUAHaOC4NA1IFMOZ7lGk?e=fg4Dek). The graph was developed using Gephi, exported using Sigma.js, hosted on [GitHub](https://github.com/claraeks/dataviz), and the interactive element was created using tools from the Oxford Internet Institute [InteractiveVis project](https://github.com/oxfordinternetinstitute/InteractiveVis).

This graph only represents a portion of the current annotations for Punch-Drunk Love, it is meant to be a sample of what could be done with this data and is not indicative of the entire film or project. Some annotations were specifically not included as I was unsure how to visualize the connection.



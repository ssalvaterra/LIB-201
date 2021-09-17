# Mapping Spatial and Temporal data
Why make a map or a timeline? What's the point? What kinds of questions do these answer?

Think of the data we've already gathered in the Smith letters. Which data allow themselves to tell a spatial story? How can we supplement those data with contextual information that we can incorporate into the already established data?

## Objectives
- Understand what geospatial data is, how it is organized, and what it could include.
- Identify and manage files, including, but not limited to the Smith Papers Collection, for creating a timeline or mapping visualization
- Address a research question using an original map or timeline
- Identify further resources ( primary and/or secondary sources) as context to support a spatial or temporal analysis

## Lessons
1. Primary and Secondary Source Research
2. Timelines
3. Geospatial Data
<!--4. Writing a research question and plan, or planning a -->

## Required Reading
- White, Phil. (2014). "Story map blog" https://blogs.library.duke.edu/data/2014/10/28/story-maps/
- Manuel Gimond, 2021, "Introduction to GIS," _Intro to GIS and Spatial Analysis_. https://mgimond.github.io/Spatial/introGIS.html
- Shannon Mattern, 2015, "Gaps in the Map: Why we're mapping everything, and why not everything can, or should, be mapped." https://wordsinspace.net/2015/09/18/gaps-in-the-map-why-were-mapping-everything-and-why-not-everything-can-or-should-be-mapped/ 

## Further Reading (optional)
- Lisa Charlotte Rost, 2021, "Which color scale to use when visualizing data" _Datawrapper_, https://blog.datawrapper.de/which-color-scale-to-use-in-data-vis/
- J. B. Harley, 1989, "Deconstructing the Map," _Cartographica_, 26(2), http://hdl.handle.net/2027/spo.4761530.0003.008

Example Mapping projects
- "Torn Apart/Separados," http://xpmethod.columbia.edu/torn-apart/volume/2/index 
- "Native Land" https://native-land.ca/
- Maps of the Starkville Civil Rights Project: https://starkvillecivilrights.msstate.edu/wordpress/the-place/ 
- Olivia Ildefonso, 2021, "Top Mapping Mistakes," CUNY Academic Commons, https://digitalfellows.commons.gc.cuny.edu/2021/05/12/top-mapping-mistakes/

## Acknowledgements
- "Introduction to Mapping," Olivia Ildefonso. https://curriculum.dhinstitutes.org/workshops/mapping/
- Jessica Davila Greene, et al. "GIS and Historical Research" presentation. https://osf.io/b8wvn/

## Ethical considerations
Many maps, especially digital mapping projects, use a 2-dimensional representation (i.e. flat) of the earth, which is just a part of the inaccuracies of our world that maps represent. Like historical records, maps (and even timelines!) are incomplete choices that represent human experience of the world. As you create maps and/or timelines, consider these questions, adapted from <a href="https://curriculum.dhinstitutes.org/workshops/mapping/lessons/?page=4">DH Institutes Curriculum</a>, that critically examine the process of map-making:
* <b>How are you collecting data?</b> Are you gathering data, or using existing data? What are the limitations of either, and what choices lead to this decision (convenience? access? most appropriate?)
* <b>What is missing from your data?</b> If you collect population information, which populations are you including/excluding? What boundaries (county? state? neighborhood?) define the map?
* <b>What symbols represent data?</b> Be aware of the colors and symbols you use to represent information. These choices can affect how others interpret your map! 
* <b>Are you using images in your media?</b> If you use images to supplement your data, be sure they are either public domain or licensed for reuse, and pay appropriate acknowledgements.

# 1. Primary and Secondary Source Research

We will be gathering research for this project to give context to the letters and the events that the people in the letters are describing. Our timelines and our maps will likely contain other primary and secondary sources. 

## What are Primary and Secondary Sources
Primary sources are often considered more "direct" pieces of evidence that are directly from someone's point of view or report on what is happening in the moment. These could include things like letter (ahem!), newspapers (depending on the time period you're researching), interviews, autobiographies or diaries, photographs, and more. 

**Bias in primary sources.** Just because a primary source is considered direct or in "real time," it is still from the point of view of someone who (like all of us!) has opinions, perspectives, and bias. All historical documents are written by an author with a specific point of view, and no matter how objective the author may try to appear, their unique perspectives and inclinations influence the document. Keep this in mind! 

Secondary sources are usually interpretive, aren't usually published,posted, or shared in the moment something is occurring, and often include primary sources in discussion with ideas or hypotheses.

## Finding and Evaluating Resources
You can find both primary and secondary sources in a number of places for researching topics from the Smith Collection. For our upcoming projects, we will look in several places, including, but not limited to:
* Websites (i.e. blogs, news sites, .orgs, .govs, etc.). 
    * Blogs can show you someone else's perspective on a related topic, link to other sources, etc.
    * You can find reports and data on government or organizational websites like the <a href="https://archives.gov">National Archives and Records Administration</a> or <a href="http://mshistorynow.mdah.state.ms.us/">Mississippi History Now</a>, from the Mississippi Department of Archives and History.
    * Wikipedia (gasp!) can even get you started with background information on a topic you're unfamiliar with! The external and reference links at the bottom of the page are also usually good breadcrubms to follow. 
* <a href="https://mlp.ent.sirsi.net/client/en_US/muw">Library books</a>. Books (or book chapters) are a great way to take a deep dive into a topic. For establishing a foundation for a research topic that involves culture, history, major events...books are a great place to start.
* <a href="http://libguides.muw.edu/az.php">Library databases</a>. Search library databases for things like scholarly articles, news, reviews, and more.
* Digital collections or archives
    * Our own <a href="https://athenacommons.muw.edu/">AthenaCommons</a> contains digitized letters from the Smith Papers Collection.
    * The University of Mississippi's eGrove repository has a digitized collection of <a href="https://egrove.olemiss.edu/sta_msblubk/">MS Blue Books</a>, which contain historical legislative information relevant to our collection.

## What you need will depend on where you go! 

### Researching Tips:
* Evaluating resources - 
* Determine a source's relevance to your topic, not the other way around
* Index and Tables of Contents
* Reusing online images
* Organizing your research

## Citing sources
We are always taught to cite our sources, so expect the sources you use to do the same! Look for citation information within a source, and cite the sources you use.

<!--check in: research scenario, search for a book/article about a topic, explain the bias of a primary source, which one is primary? Which one is secondary? What might this document tell us and how could we use it? What to look for when searching for an image?-->


# 3. Geospatial Data

<p><img src="https://github.com/hillaryAHR/LIB-201/blob/main/mapping-images/MS-sample-map.JPG" alt="Screenshot of a map of MS with counties outlined in red, and with 3 points in Tupelo, Pittsboro, and Meridian">

Maps are layers of data represented by shapes, lines, and points. Layers usually include a:
* Base map layer - something you put all of your layers on top of. This could be a historic map, a map with specific boundaries, a topographical map, etc., etc.!
* Shapefiles - these are files that contain shapes, lines, and points that correspond to places, and include information on them. An example would be a point (like a city) and its geographical location (latitude, longitude). Other examples can include county boundaries, rivers, buildings, population (census) data, and routes in between locations. These are just a few possibilities! There are 2 kinds of shapefile data:
    * Vector Data - this is discrete data, like the examples mentioned above. 
    * Raster Data (we will not use raster data in this class) - this includes data that is continuous, like weather patterns or elevation.

## Selecting data
Maps are often built with tables of attributes that correspond to locations. You would collect data **relevant to your question** that you hope to answer through mapping certain points. For example, if you wanted to show the proximity of Mississippi's rivers to certain locations, you would look for the data to accentuate this. Your basemap would not overemphasize streets, but the landscape. Your vector data could include an outline of Mississippi and the shapes rivers make, and your locations (or points) would demonstrate this proximity.

<!--screenshot/example-->

## Finding Vector Data
Points, lines, polygons

## Mapping tools
* QGIS (requires download)
* Google MyMaps
* StoryMapJS

## Check-in
<!--multiple choice - define terms, give an example of what vector data could include, show a map, and describe the layers within it-->

# 2. Timelines
Both maps and timelines use spreadsheets to associate information with a spot on a "map." Timelines associate information with dates, ranges of time. Why create a timeline? If you would like to show the progression of or change in data over time, a timeline will visualize this for you.

<!--screenshot-->

## Timeline tools
* TimelineJS
* Palladio
* Neatline

## Check-in
<!--find a >
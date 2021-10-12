# Jstortest_01
<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Chap's Talkin' 'bout Star Trek Again"
       author="Chap"
       banner="https://cdn.shopify.com/s/files/1/0018/7337/9427/collections/StarTrek_collection_banner_1920x300-General_ce52d0c7-f0fc-4856-bcc5-7d22aa5b268c_1400x.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Let's Talk About Narrative Potential

Look, I know it's a very me thing to say, but I think that we can utilize this technology for fandom. I mean, I know that fanlore does this better and has a more accessible layout. But I'm not talking about nonfiction fan writing, I'm talking about fan fiction. Look at him. He looks at the camera like how he looks at Spock, with an unexamined lust deep in his eyes. God, think of the possibilities.[^1]
<param ve-image 
       label="Captain Kirk" 
       description="an image of William Shatner as Captain Kirk" 
       license="CBS" 
       url="https://www.startrek.com/sites/default/files/styles/content_full/public/images/2019-07/89abe98de6071178edb1b28901a8f459.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Star Trek Database: James T Kirk](https://www.startrek.com/database_article/james-t-kirk)

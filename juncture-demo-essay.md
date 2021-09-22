<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="SG Test: Pompeii"
       author="JSTOR Labs team"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/a/a1/Garden_pompei_site.jpeg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q125414"> <!-- Pompey -->
<param ve-entity eid="Q336806"> <!-- Domenico Fontana -->
<param ve-entity eid="Q43332"> <!-- Pompeii -->
<param ve-entity eid="Q36600"> <!-- The Hague -->
<param ve-entity eid="Q3523"><!-- The Secret Museum -->
<param ve-entity eid="Q524"><!-- Mt. Vesuvius -->

# Pompeii - or, I'm changing the demo info to see what happens next

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/7/7b/Via_dell%27Abbondanza_1.JPG">

# Basic usage

## Image

Not to be confused with the Roman leader Pompey, Pompeii was a Roman city famously destroyed by the eruption of Mt. Vesuvius.[^1] Domenico Fontana was one of the first to 'excavate' there.
<param ve-image 
       label="Forum at Pompeii" 
       description="Photo from Wikicommons" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/3/32/Atrium%2C_Pompeii_%2814978508290%29.jpg">

## Map

Here, I've picked up the identifier number from the wikipedia page on Pompeii (under 'wikidata') and put it into the map code.
<param ve-map center="Q43332" zoom="13" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph. Here, you get a picture first; if you then click the 'location' icon, you get a map. I've given the 'map' parameter the wikidata identifier for the Secret Museum, where much of the erotic art found at Pompeii was kept safely away. I wonder if it'll display its location. Only one way to find out!
<param ve-image 
       url="https://upload.wikimedia.org/wikipedia/commons/5/56/Pan_copulating_with_goat_1.JPG">
<param ve-map center="Q3523" zoom="11">
<param ve-compare curtain 
              url="https://iiif.juncture-digital.org/banner/?url=https://raw.githubusercontent.com/shawngraham/demo/master/before.jpg" 
              label="slide 1">
<param ve-compare 
              url="https://iiif.juncture-digital.org/banner/?url=https://raw.githubusercontent.com/shawngraham/demo/master/after.jpg" 
              label="slide2">


# References

[^1]: [Wikipedia: Pompeii](https://en.wikipedia.org/wiki/Pompeii)

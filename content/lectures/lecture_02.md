% Geographic Data Science - Lecture II
% (New) Spatial Data
%[Dani Arribas-Bel](http://darribas.org)

#
## "Yesterday"

- Introduced the (geo-)data revolution
    
    * What is it?
    * Why now?

- The *need* of **(geo-)data science** to make sense of it all

## Today

- Traditional data: refresher
- New sources of spatial data
- Challenges
- (Cool) examples

# 

## *Good old* spatial data

## *Good old* spatial data

[[source](https://www.youtube.com/embed/RY2J8ETZzLo)]

<iframe width="660" height="415" src="https://www.youtube.com/embed/RY2J8ETZzLo" frameborder="0" allowfullscreen></iframe>

## *Good old* spatial data (+)

Traditionally, datasets used in the (social) sciences are:

* Collected for the purpose --> **carefully** designed
* **Detailed** in information ("*...rich profiles and portraits of the country...*")
* **High quality**

## *Good old* spatial data (-)

But also: 

* Massive enterprises ("*...every single person...*) --> **costly**
* But **coarse** in resolution (to preserve pricacy they need to be
  aggregated)
* **Slow**: the more detailed, the less frequent they are available

## Examples

* Decenial census (and census geographies)
* Longitudinal surveys
* Customly collected surveys, interviews, etc.
* Economic indicators
* ...

#
## New sources of (spatial) data

## New sources of (spatial) data

Tied into the (geo-)data revolution, new sources are appearing that are:

* **ACCIDENTAL** --> created for different purposes but available for analysis
  as a side effect
* Very diverse in nature, resolution, and detail but, potentially, much more
  **detailed** in both space and time
* Quality also varies greatly

## New sources of (spatial) data

We can split them at three levels, based on how they originate:

* **[Bottom up]** "Citizens as sensors"
* **[Intermediate]** Digital businesses/businesses going digital
* **[Top down]** Open Government Data

## Citizens as sensors

* Technology has allowed widespread adoption of sensors (bands, smartphones,
  tablets...) 
* (Almost) every aspect of human life is subject to leave a digital trace that can be
  collected, stored and analyzed
* Individuals become content/data creators (sensors, *Goodchild, 2007*)
* *Why relevant for geographers?* --> Most of it (80%?) has some form of
  spatial dimension

## Example: [Livehoods](http://livehoods.org)

<div style="height: 600px;" markdown="1">
![](../content/lectures/figs/l02_livehoods.png)
</div>

## Businesses moving online

* Many of the elements and parts of bussiness activities have been
  computerized in the last decades
* This implies, without any change in the final product or activity per se, a
  lot more digital data is "available" about their operations
* In addition, enirely new business activities have been created based on the
  new technologies ("internet natives")
* Much of these data can help researchers better understand how cities work

## Example: [Walkscore](https://www.walkscore.com/)

<div style="height: 600px;" markdown="1">
![](../content/lectures/figs/l02_walkscore.png)
</div>

## Open data for open governments

Government institutions release (part of) their internal data in open format.
Motivations ([Shadbolt, 2010](http://eprints.soton.ac.uk/268787/)):

* Transparency and accountability
* Economic and social value
* Public service improvement 
* Creation of new industries and jobs

## [Global Open Data Index'14](http://global.census.okfn.org/)

<div style="height: 600px;" markdown="1">
![](../content/lectures/figs/l02_okn_odi.png)
</div>

## Example: [BikeShare Map](http://oobrien.com/bikesharemap/)

<div style="height: 600px;" markdown="1">
![](../content/lectures/figs/l02_bikesharemap.jpg)
</div>

[Source](http://oobrien.com/wp-content/uploads/2013/06/bikesharemap.jpg)

## Class Quiz

## Class Quiz

In pairs, 2 minutes to discuss the origin of the following sources of
(geo-)data:

* Geo-referenced tweets <span class="fragment">  --> Bottom-up </span>
* Land-registry house transaction values <span class="fragment"> --> Open Government </span>
* Google maps restaurant listing <span class="fragment"> --> Digital businesses </span>
* ONS Deprivation Indices <span class="fragment"> --> Traditional (not accidental!) </span>
* Liverpool bikeshare service station status <span class="fragment"> --> Open Government Data </span>

#
## Challenges

## Challenges

* Bias
* Technical barriers to access
* The need of new methods

## Bias

* Traditionally, data used by urban researchers meets some quality standards (representativity, accuracy...)
* The *accidental* nature means new data sources will not always meet such
  standards 
* This implies researchers need to have extra care and put more thought into
  what conclusions they can reach from analyses with new sources of data
* In some cases, bias can even run in favour of researchers, but this should
  never be taken for granted

## Technical barriers to access

* Much of these data are available
* However, their accidental nature makes them not be *directly* available
* Usually, a **different set of skills** is required to tap into their power

    * Basic programming
    * Computing literacy (understanding of the internet, APIs, databases...)
    * Software savvy-ness (a.k.a. "go beyond Word and Excel")

## (New) Methods

The nature of these data is not exactly the same as that of more traditional
datasets. For example:

* Spatial aggregation: Polygons Vs. Points
* Temporal aggregation(frequency): Decadal Vs. Real-time

Some of this does not "play well" with techniques employed traditionally to
analyze data in Geography. 

## (New) Methods

<center>
<img src="../content/lectures/figs/l02_square_circle.jpg" style="width:500px;height:500;">
</center>

<center>
[[source](https://www.flickr.com/photos/epublicist/3546059144)]
</center>

## (New) Methods

To be able to extract as much insight as possible from these new sources of
data --> *borrow* techniques from other disciplines, or even *create* new ones

Examples: 

* Visualization
* Machine learning 

But also others like bayesian inference, network science...

## Methods - Visualization

* Display of graphical summaries
* Arguably, not new to Geography, but more emphasis should be put on it
* Powerful to both *obtain* (explore the data) and *communicate* findings
  (tell stories with data)

Example: [Public Transit in Boston](http://mbtaviz.github.io/)

## Methods - Machine learning

* Originated in computer science, blended with statistics
* Focus on prediction and pattern recognition
* Two main types of learning:

    * **Supervised**: present the computer some true relationships to "learn" a
      model, then use the model to infer others where no prediction is
      available (e.g. [Google flu trends](http://www.google.org/flutrends/))
    * **Unsupervised**: "let the data speak"... and the machine pick up the
      structure (e.g. [Livehoods](http://livehoods.org))

#
## New **Vs** Old?

**Traditional** data:

* High quality, detailed, and reliable
* Costly, coarse, and slow

**Accidental** data:

* Cheap, fine-grained, and fast
* Less reliable, harder to access, and potentially uninteresting

## New **and** Old!

<center>
<img src="../content/lectures/figs/l02_cake.jpg" style="width:500px;height:500;">
</center>

<center>
[[source](https://www.flickr.com/photos/kimberlykv/1414216225/in/photolist-39Yedn-cg51c-aPnd1a-6ycQ1g-39Yekr-fYoqEy-rsv5bX-83fuCd-e3MAae-9r6Ygz-AaQxC-i6smU-9VTTkr-86xwNr-5ZgCYg-7XtJCo-7GNZhD-5pV4Sn-2pRF-4oTo48-7YTrmC-b82Qui-qBFpzQ-e3MmKz-cPkb2h-6H9VEU-7fPhRd-6Xr7Cb-4pMfnz-4PbvSh-bDB9NK-9DQkmv-7DeHYS-7PPkGa-bGe5zR-9tCRQj-aMnfQX-dCn5Tw-97yk9R-9gNgRv-7iajjd-qwJw1v-cBaLCy-6ksVZt-8zimG7-buL1BE-64rAXB-e7syZf-q9Mdhv-oLgJYa)]
</center>

## Avoid the [streetlight effect](https://en.wikipedia.org/wiki/Streetlight_effect)


<center>
<img src="https://d262ilb51hltx0.cloudfront.net/max/800/1*X59CVJB_MOJTouxMkBiHSQ.jpeg" alt="Streetlight effect" style="width:400px;height:400;">
</center>

<center>
[[source](https://d262ilb51hltx0.cloudfront.net/max/800/1*X59CVJB_MOJTouxMkBiHSQ.jpeg)]
</center>

#
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Geographic Data Science'15 - Lecture 1</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://darribas.org" property="cc:attributionName" rel="cc:attributionURL">Dani Arribas-Bel</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.



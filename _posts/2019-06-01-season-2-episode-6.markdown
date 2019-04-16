---
layout: post
title: "EP018 Coastal modeling with STORM"
date: 2019-06-01 00:00:00
author: Admin
categories: 
 - user
 - developer
 - podcast
#Title of the podcast episode without the episode number
podcast_episode_title: Coastal modeling with STORM
#Image of the blog post
img: FFS015_header.png
#Thumbnail of the blog post
thumb: FFS015_thumb.png
#Link to the mp3 file of the episode
podcast_link: http://media.blubrry.com/flossforscience/archive.org/download/FLOSSforscienceEP015BenMarwick/FLOSSforscience_EP015_BenMarwick.mp3
#Link to the ogg file of the episode
podcast_link_ogg: http://media.blubrry.com/flossforscience/archive.org/download/FLOSSforscienceEP015BenMarwick/FLOSSforscience_EP015_BenMarwick.ogg
#File size in MB of the mp3 file
podcast_file_size: 35.6 MB
#File size in MB of the ogg file
podcast_file_size_ogg: 38.9 MB
#Length of the episode in minutes (is the same for ogg and mp3)
podcast_duration: "1:13:52"
#File size in bytes of the mp3 file
podcast_length: 35591012
#File size in bytes of the ogg file
podcast_length_ogg: 38911790
#Unique id of the mp3 file (sha256)
podcast_guid: 0475c22464c90bab2682162fe7f509e0a21192bcb1a9136963abb6a2c6e9c504
#“full” for normal episodes; “trailer” to promote an upcoming show, season, or episode; or “bonus” for extra content related to a show, season, or episode.
podcast_episode_type: full
#Season number only
podcast_season_number: 02
#Episode number only
podcast_episode_number: 003
#Subtitle of the episode 
podcast_subtitle: An interview with Ben Marwick
#Description of the podcast
podcast_description: |
  For episode 15, we interview the Associate Professor of Archaeology Ben Marwick. We start our discussion with an overview of some FLOSS tools he uses and how much FLOSS are used in  archaeology. He shares with us his experience in regard to working completely in the open with GitHub and his hope that open science will become the norm in the future. We also discuss about rrtools  and his propositions on how to greatly improve the reproducibility of science. As a closing though he shares with us his arguments why early career researchers should invest time to learn and transition to FLOSS tools.  
---

<audio controls>
  <source src="{{ page.podcast_link_ogg }}" type="audio/ogg">
  <source src="{{ page.podcast_link }}" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

# Outline

For episode 15, we interview the Associate Professor of Archaeology Ben Marwick. We start our discussion with an overview of some FLOSS tools he uses and how much FLOSS are used in  archaeology. He shares with us his experience in regard to working completely in the open with GitHub and his hope that open science will become the norm in the future. We also discuss about rrtools  and his propositions on how to greatly improve the reproducibility of science. As a closing though he shares with us his arguments why early career researchers should invest time to learn and transition to FLOSS tools. 

# About Jason Fleming: 

Dr. Jason Fleming is a principal consultant and co-founder of Seahorse Coastal Consulting, LLC. He began working with ADCIRC during his PhD program and then worked as a Postdoctoral Researcher with Dr. Rick Luettich at the UNC Chapel Hill Institute of Marine Sciences in 2002. Over the last fifteen years, Jason's role as the development coordinator for ADCIRC has given him the opportunity to work on every part of the code. He has developed key ADCIRC features, including the symmetric vortex tropical cyclone model, HWind support, and native netCDF and XDMF output. Jason is also the Lead Developer and Operator for the ADCIRC Surge Guidance System (ASGS), a software automation system for ADCIRC that he operated in real time for official decision support during the Deepwater Horizon event as well as Hurricanes Gustav, Irene, Isaac, Sandy, was Matthew, Irma, Florence among others.

# About Carola Kaiser:

Carola Kaiser is an IT consultant at the LSU Center for Computation and Technology. She is  the lead software and web developer of the Coastal Emergency Risks Assessment ([CERA](http://coastalrisk.live)) storm surge visualization tool. Carola has in-depth knowledge of spatial data formats, geo-data structures, and web mapping technologies, especially in the field of coastal ecosystem forecasting systems. Her primary focus is set on the development of Internet-based spatial frameworks and web applications that link modeling tools, monitoring, and sophisticated IT techniques to support storm surge forecasts along the coasts of the U.S.
The CERA visualization technology has been intensely and successfully used by emergency managers and federal and state U.S agencies. CERA was deployed during severe hurricane events like Hurricanes Isaac, Harvey, and Michael in the Gulf of Mexico and Hurricanes Sandy, Matthew, Irma, and Florence along the U.S. east coast.

# A brief project summary:

In a landfalling tropical cyclone, the wind pushes huge amounts of water onto shore. Many hurricane forecast systems typically focus on a storm’s track and maximum wind speeds. However, it is the storm surge that often poses the greatest danger to human life since the rise of water can be as rapid as several feet in just a few minutes.

The ADCIRC storm surge model, a computer model with a 25 year track record of success, calculates the wind-wave and storm surge corresponding to the latest official hurricane forecast track. We use supercomputers to recalculate and update the model projections every time a new NHC forecast advisory is issued. That helps our users understand the potential impacts and timing of storm surge. We have also developed a software package (ADCIRC Surge Guidance System – ASGS) that we use on high performance computers to recalculate and update these ADCIRC projections every time a new forecast advisory is issued. 

And finally, we show the storm surge maps on an interactive web mapper (Coastal Emergency Risks Assessment – [CERA](https://cera.coastalrisk.live)) to help our users understand the potential impacts and timing of storm surge. The CERA website provides useful information to decision makers and first responders to support their due diligence efforts during impending or active hurricanes to achieve better outcomes to protect lives and properties.

# Links

* [CERA](https://cera.coastalrisk.live)
* [ADCIRC ](http://adcirc.org/)
* [HPX](http://stellar-group.org/libraries/hpx/)
* [LibGeoDecomp](http://www.libgeodecomp.org/)

Listen to this episode here or add our [rss feed](https://flossforscience.com/feed.xml) to your favourite podcast application. 

You can also download this episode as [MP3]({{ page.podcast_link }}) or [OGG]({{ page.podcast_link_ogg }}). 

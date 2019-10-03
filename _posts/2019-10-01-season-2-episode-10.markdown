---
layout: post
title: "EP022 Symbolic Calculation with Maxima"
date: 2019-09-04 00:00:00
author: Admin
categories: 
 - developer
 - podcast
#Title of the podcast episode without the episode number
podcast_episode_title: "High-level Scientific Computing with GNU Octave"
#Image of the blog post
img: FFS021_header.png
#Thumbnail of the blog post
thumb: FFS021_thumb.png
#Link to the mp3 file of the episode
podcast_link: https://media.blubrry.com/flossforscience/archive.org/download/FFS021_juan_pablo_carbajal_gnu_octave/FLOSSforscience_EP021_Juan_Pablo_Carbajal_GNU-Octave.mp3
#Link to the ogg file of the episode
podcast_link_ogg: https://media.blubrry.com/flossforscience/archive.org/download/FFS021_juan_pablo_carbajal_gnu_octave/FLOSSforscience_EP021_Juan_Pablo_Carbajal_GNU-Octave.ogg
#File size in MB of the mp3 file
podcast_file_size: 22.5 MB
#File size in MB of the ogg file
podcast_file_size_ogg: 21.9 MB
#Length of the episode in minutes (is the same for ogg and mp3)
podcast_duration: "0:46:30"
#File size in bytes of the mp3 file
podcast_length: 22464651
#File size in bytes of the ogg file
podcast_length_ogg: 21915004
#Unique id of the mp3 file (sha256)
podcast_guid: 562305a86bc282406a0704ab991e53b1af6b90c6e5f5a2cd9ceb930f3b8b9cf7
#“full” for normal episodes; “trailer” to promote an upcoming show, season, or episode; or “bonus” for extra content related to a show, season, or episode.
podcast_episode_type: full
#Season number only
podcast_season_number: 02
#Episode number only
podcast_episode_number: 009
#Subtitle of the episode 
podcast_subtitle: An interview with Juan Pablo Carbajal
#Description of the podcast
podcast_description: |
  In episode 21, we interviewed Juan Pablo Carbajal, an Argentinian physicist currently working as a postdoctoral researcher in the Department of Urban Water Management at the ETH domain in Switzerland. We had a great discussion about GNU Octave and how it can help scientists. We compared its core functions and its expandability through packages to its commercial equivalent Matlab and its toolboxes. An interesting feature of GNU Octave that we explored with Juan is the possibility to migrate code from Matlab directly to GNU Octave and to a certain point maintain code compatible with both. Juan shared with us that since the introduction of an integrated GUI in 2015, he noticed a continuous growth in popularity for the project. We then discussed about a few of the reasons why companies are  interested by GNU Octave and why universities should teach using free/libre software. Before asking our usual quick questions, Juan talked with us about the reasons why FLOSS is important for science and the importance of exposing non-FLOSS users to the benefits of FLOSS.

  00:00:00 Message to our listeners
  00:00:29 Intro
  00:00:45 Introducing Juan Pablo Carbajal
  00:01:32 30 seconds elevator pitch for GNU Octave
  00:02:20 How does the Octave programming language compares to other common programming languages
  00:03:23 Compatibility between GNU Octave and Matlab
  00:06:29 Matlab's toolboxes compared to GNU Octave packages
  00:07:31 Simulink models with GNU Octave
  00:09:06 Parallel processing with GNU Octave
  00:10:40 The issue with CUDA in GNU Octave
  00:11:48 How GNU Octaves differs rom other open source Matlab equivalents
  00:13:34 Syntax compatibility to ease transition and reusing code from Matlab
  00:15:11 Resources to start using GNU Octave
  00:16:40 GNU Octave's graphical user interface and the old QT Octave GUI
  00:20:14 GNU Octave's graphical user interface compared to Matlab
  00:22:11 Why GNU Octave and not simply Octave
  00:23:06 GNU Octave licence
  00:24:01 How often he uses GNU Octave
  00:24:18 Juan's numerous contributions to the project
  00:25:27 GNU octave for companies
  00:27:45 Arguments for teaching with GNU Octave instead of Matlab
  00:29:32 How many are involved in the project?
  00:30:37 Communication channels within the project
  00:31:34 Is the project actively looking for developers?
  00:32:11 Skills required to contribute
  00:33:14 The two-level language dilemma
  00:34:59 Juan's vision about FLOSS and its importance for science
  00:37:09 Possible negative impacts of FLOSS and converting non-FLOSS users
  00:40:17 The most notable scientific discovery in recent years
  00:41:46 Juan's favourite text processing tools
  00:42:38 Things we forgot to ask about
  00:43:57 Anything else to share?
  00:44:25 How to contact Juan
  00:44:50 Outro

---

<audio controls>
  <source src="{{ page.podcast_link_ogg }}" type="audio/ogg">
  <source src="{{ page.podcast_link }}" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

# Outline

In episode 21, we interviewed Robert Dodier

# About Robert Dodier:

Robert Dodier has a background in mathematics, computer science, and
engineering. At present he's writing software for a medical app for
smart phones. In times past he has worked on machine learning, agent
systems, and forecasting electrical demand, among other topics. He has
a special interest in Bayesian inference and decision analysis.


# About Maxima:

Maxima is derived from the Macsyma system, developed at MIT in the
years 1968 through 1982 as part of Project MAC. MIT turned over a copy
of the Macsyma source code to the Department of Energy in 1982; that
version is now known as DOE Macsyma.  A copy of DOE Macsyma was
maintained by Professor William F. Schelter of the University of Texas
from 1982 until his death in 2001.  In 1998, Schelter obtained
permission from the Department of Energy to release the DOE Macsyma
source code under the GNU Public License, and in 2000 he initiated the
Maxima project at SourceForge to maintain and develop DOE Macsyma, now
called Maxima.

# Links

* [GNU Octave home page](www.octave.org)
* [Octave Forge: packages for GNU Octave](https://octave.sourceforge.io/)
* [GNU Octave’s wiki](https://wiki.octave.org)
* [GPU acceleration for GNU Octave](https://sourceforge.net/projects/octave-ocl/)
* [GNU Octave virtual classroom (Spanish)](https://sites.google.com/site/octavecole/)
* [Publications using Octave](https://wiki.octave.org/Publications_using_Octave)
* [Introduction to GNU Octave (2nd Edition)](https://www.lulu.com/shop/jason-lachniet/introduction-to-gnu-octave/paperback/product-23933033.html)
* [Octave’s projects page](https://wiki.octave.org/Projects)
* [Summer of code ideas](https://wiki.octave.org/Summer_of_Code_Project_Ideas)


Listen to this episode here or add our [rss feed](https://flossforscience.com/feed.xml) to your favourite podcast application. 

You can also download this episode as [MP3]({{ page.podcast_link }}) or [OGG]({{ page.podcast_link_ogg }}). 

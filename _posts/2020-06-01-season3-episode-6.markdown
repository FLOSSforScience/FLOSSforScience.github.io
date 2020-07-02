---
layout: post
title: "EP029 Distributing Python packages with setuptools"
date: 2020-07-01 00:00:00
author: Admin
categories: 
 - developer
 - podcast
#Title of the podcast episode without the episode number
podcast_episode_title: "Distributing Python packages with setuptools"
#Image of the blog post
img: FFS029_header.jpg
#Thumbnail of the blog post
thumb: FFS029_thumb.jpg
#Link to the mp3 file of the episode
podcast_link: https://media.blubrry.com/flossforscience/archive.org/download/ffs-ep-029-setuptools/FFS_EP029_setuptools.mp3
#Link to the ogg file of the episode
podcast_link_ogg: https://media.blubrry.com/flossforscience/archive.org/download/ffs-ep-029-setuptools/FFS_EP029_setuptools.ogg
#File size in MB of the mp3 file
podcast_file_size: 32.4 MB
#File size in MB of the ogg file
podcast_file_size_ogg: 32.7 MB
#Length of the episode in minutes (is the same for ogg and mp3)
podcast_duration: "1:07:17"
#File size in bytes of the mp3 file
podcast_length: 32441919
#File size in bytes of the ogg file
podcast_length_ogg: 32653256
#Unique id of the mp3 file (sha256)
podcast_guid: 66ff8ae1bf6ca9d3ae8996a79c89c27b4d8664bf6613367962e573353d4fb886
#“full” for normal episodes; “trailer” to promote an upcoming show, season, or episode; or “bonus” for extra content related to a show, season, or episode.
podcast_episode_type: full
#Season number only
podcast_season_number: 03
#Episode number only
podcast_episode_number: 6
#Subtitle of the episode 
podcast_subtitle: An interview with Jason R Coombs
#Description of the podcast
podcast_description: |
  In episode 29, we interviewed Jason R Coombs from the setuptools project. We started with a discussion about his background and his interest for Python and other programming languages. Following that, we had a thorough discussion about setuptools. We covered topics such as how he got involved in the project, the nature and composition of a Python package, why packaging your code can be important even for small projects, the hidden complexity of binary packages in the Python Package Index and how to maintain compatibility between Python versions. We also had a brief segment about the security aspects of Python packages. He informed us about how you could start contributing to the project and where to discuss Python packaging. We then followed with a general discussion about FLOSS in science and the problem of long-term maintenance in academia. We concluded the interview with our usual quick questions. 

  00:00:00.000 Intro
  00:00:23 Introducing Jason R. Coombs
  00:01:28 The first programming languages he learned and how he got into Python
  00:03:46 New interesting programming languages
  00:05:07 His favourite past Python projects
  00:06:53 His one minute elevator pitch for setuptools
  00:08:00 The relation between setuptools, PIP and Anaconda
  00:10:43 How he got involved with the setuptools project
  00:14:43 What is a Python package ?
  00:16:07 What can be included in a package?
  00:16:36 At which point is it beneficial to create a package ?
  00:18:04 Managing compatibility with multiple versions of Python
  00:20:33 Advantages of packages for small projects
  00:22:46 How much work is required to create a package ?
  00:25:05 Files required to create a Python package
  00:27:45 Licenses and readme for Python packages
  00:30:51 The nature of distribution archives
  00:31:27 Compatibility of binary archives
  00:32:39 Eggs and wheel files
  00:34:32 Dealing with non portable packages in the Python Package Index across multiple operating systems
  00:37:49 Uploading packages to the Python Package Index
  00:39:12 Review for broken or malicious code
  00:40:08 Vulneraility from package removal in the Python Package Index
  00:43:24 Package name collisions
  00:45:13 How many packages are in the Python Package Index
  00:45:25 Alternatives to the main Python Package Index
  00:46:35 Other packaging tools
  00:47:39 How many developpers are involved in the project
  00:48:31 Communication channels and discussions about Python packaging
  00:49:53 Openings for new contributors
  00:50:59 Skills required to contribute
  00:52:24 The challenge of long term maintenance of packages in academia
  00:55:43 His vision about the importance of FLOSS for the openess of science
  00:59:18 Disadvantage of using FLOSS
  01:01:24 The most notable scientific discovery in recent years
  01:02:13 Favourite text processing tool
  01:03:23 A topic in science about which he recently changed his mind
  01:04:50 Contact informations
  01:05:23 Conclusion

---

<audio controls>
  <source src="{{ page.podcast_link_ogg }}" type="audio/ogg">
  <source src="{{ page.podcast_link }}" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

# Outline

In episode 29, we interviewed Jason R Coombs from the setuptools project. We started with a discussion about his background and his interest for Python and other programming languages. Following that, we had a thorough discussion about setuptools. We covered topics such as how he got involved in the project, the nature and composition of a Python package, why packaging your code can be important even for small projects, the hidden complexity of binary packages in the Python Package Index and how to maintain compatibility between Python versions. We also had a brief segment about the security aspects of Python packages. He informed us about how you could start contributing to the project and where to discuss Python packaging. We then followed with a general discussion about FLOSS in science and the problem of long-term maintenance in academia. We concluded the interview with our usual quick questions. 

# About Python setuptools:

Setuptools is the dominant way to build Python packages for distributing that functionality to other users via pip and the Python Package Index. Setuptools support simple, pure-Python packages all the way to complex packages requiring compilation (such as from C or Rust) and features like entry points and console scripts.

# About Jason R. Coombs:

Jason has been a Python enthusiast for over two decades and a contributor to open-source for just as long. As a core contributor to Python and maintainer of over 140 packages in PyPI, Jason has worked tirelessly to streamline packaging workflows and automate best practices around package distribution. Jason has used Python across government, commercial, and non-profit sectors to produce enterprise-grade software on Python. Jason is currently a Site Reliability Manager at Google in Pittsburgh.

# Links

* [Setuptools](https://pypi.org/project/setuptools)
* [CherryPy](https://cherrypy.org)
* [Jason R. Coombs](https://www.jaraco.com/)
* [Python Packaging Users Guide](https://packaging.python.org/)

# Related epsiodes

* [EP007 A Guide to Software Licenses in Science](https://flossforscience.com/podcast/season-1-episode-7)

Listen to this episode here or add our [rss feed](https://flossforscience.com/feed.xml) to your favourite podcast application. 

You can also download this episode as [MP3]({{ page.podcast_link }}) or [OGG]({{ page.podcast_link_ogg }}). 

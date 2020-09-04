---
layout: post
title: "EP030 Spack: a package manager for supercomputers"
date: 2020-03-09 00:00:00
author: Admin
categories:
 - developer
 - podcast
#Title of the podcast episode without the episode number
podcast_episode_title: "Spack: a package manager for supercomputers"
#Image of the blog post
img: FFS030_header.png
#Thumbnail of the blog post
thumb: FFS030_thumb.jpg
#Link to the mp3 file of the episode
podcast_link: https://media.blubrry.com/flossforscience/archive.org/download/ffs-ep-030-spack/FFS_EP030_Spack.mp3
#Link to the ogg file of the episode
podcast_link_ogg:  https://media.blubrry.com/flossforscience/archive.org/download/ffs-ep-030-spack/FFS_EP030_Spack.ogg
#File size in MB of the mp3 file
podcast_file_size: 25.3 MB
#File size in MB of the ogg file
podcast_file_size_ogg: 26.5 MB
#Length of the episode in minutes (is the same for ogg and mp3)
podcast_duration: "0:52:26"
#File size in bytes of the mp3 file
podcast_length: 25326866
#File size in bytes of the ogg file
podcast_length_ogg: 26478989
#Unique id of the mp3 file (sha256)
podcast_guid: 13716329014667f17da4b9650965be78d5dd34aa171d2fd448ae451f6f6caaa0
#“full” for normal episodes; “trailer” to promote an upcoming show, season, or episode; or “bonus” for extra content related to a show, season, or episode.
podcast_episode_type: full
#Season number only
podcast_season_number: 03
#Episode number only
podcast_episode_number: 07
#Subtitle of the episode
podcast_subtitle: An interview with Todd Gamblin
#Description of the podcast
podcast_description: |
  In episode 30, we interviewed Todd Gamblin from the Lawrence Livermore National Laboratory about the Spack project. We discussed his current research project along with his involvement in Spack. We widely discussed the philosophy of Spack, some usage patterns, its capabilities for managing package management in HPC clusters as well as standalone computers and which operating systems it supports at the moment. Todd shared with us his opinion on the trend for containerized workloads to achieve reproducible science and why it may not be the goal we need to set. He highlighted for us the similarities and differences between EasyBuild and Spack as well as the origin of those differences. We finished the interview with our usual quick questions. 

  00:00:00 Intro music
  00:00:17 Introduction
  00:00:36 Introducing Todd Gamblin
  00:00:58 His current research topics
  00:01:23 Spack as official duties
  00:01:43 Spack usage at Lawrence Livermore National Laboratory
  00:02:01 Other research projects
  00:02:47 Profiling in HPC
  00:04:24 His role as leader of software packaging technology for the exascale computing project
  00:04:58 One-minute elevator pitch for Spack
  00:05:34 Spack's usage philosophy compared to other package managers
  00:06:59 Installation from source code or binary?
  00:07:28 Spack's usage in the top500 super computers
  00:07:49 Geographical distribution of users
  00:08:18 Number of packages in the repo and some examples
  00:09:05 Managing computer clusters with Spack's automation capabilities
  00:11:04 Module files in Spack
  00:12:32 Syntax of a Spack package file
  00:13:43 Configuration of compiler flags
  00:15:00 Importing python libraries in the Spack files
  00:15:48 The procedure to submit a package
  00:16:27 Review process for new packages
  00:17:34 Reasons for rejection of Spack packages
  00:18:01 Operating systems supported by Spack
  00:18:23 WSL and Spack
  00:18:58 Restricting packages to certain hardware and software configurations
  00:20:04 Build testing and nightly builds
  00:21:28 Working with containers in a Spack environment
  00:22:25 Deploying prebuilt containers
  00:23:05 About the "universality" of containers
  00:24:16 His opinion on containerized applications for reproducible science
  00:26:17 Spack's log file to document reproducibility
  00:27:13 Reproducing older results
  00:28:10 Specifying requirements on compilers
  00:30:39 Post-installation verification test
  00:31:10 Using Spack on a standalone computer instead of HPC systems
  00:32:56 Differences between EasyBuild and Spack
  00:34:24 EasyBuild in the top500
  00:34:49 Transitionning between EasyBuild and Spack
  00:35:38 Other alternatives
  00:36:23 Using EasyBuild and Spack on the same system
  00:38:36 When did the project start?
  00:39:53 External contributions to Spack
  00:40:53 How many core developpers?
  00:41:30 Organization of the community and governance model
  00:43:06 Who decides which package is accepted in the repo?
  00:44:38 Spack's choice of software license
  00:47:09 Todd's vision about the importance of FLOSS for the openness of science
  00:48:13 Possible negative impacts of FLOSS
  00:48:58 Most notable recent scientific discovery
  00:49:14 Favourite text processing tool
  00:49:25 A topic in science about which he recently changed his mind about
  00:49:58 Anything else we forgot to ask?
  00:50:09 How to contact Todd
  00:50:46 Conclusion

---

<audio controls>
  <source src="{{ page.podcast_link_ogg }}" type="audio/ogg">
  <source src="{{ page.podcast_link }}" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

# Outline

In episode 30, we interviewed Todd Gamblin from the Lawrence Livermore National Laboratory about the Spack project. We discussed his current research project along with his involvement in Spack. We widely discussed the philosophy of Spack, some usage patterns, its capabilities for managing package management in HPC clusters as well as standalone computers and which operating systems it supports at the moment. Todd shared with us his opinion on the trend for containerized workloads to achieve reproducible science and why it may not be the goal we need to set. He highlighted for us the similarities and differences between EasyBuild and Spack as well as the origin of those differences. We finished the interview with our usual quick questions. 

# About Spack:

Spack is a package/dependency manager for scientific computing, with a
rapidly growing open source community. It aims to address many of the
complexities of native, multi-language, cross-platform dependency
management. With over 500 contributors from academia, industry, and
government laboratories, Spack has a wide range of use cases, from
small-scale development on laptops and clusters, to software release
management for the U.S. Exascale Computing Project (ECP), to software
deployment at large supercomputer facilities. Recently, Spack has added
features for devops and software development workflows, including
reproducible deployment. Spack virtual environments can be versioned and
reproduced with abstract `spack.yaml` files or concrete (exact)
`spack.lock` files. New releases of Spack include direct support for
creating containers, parallel/distributed builds, and Gitlab CI pipelines
for building environments.

# About Todd Gamblin:

Todd Gamblin is a Computer Scientist in the Advanced Technology Office in
Livermore Computing at Lawrence Livermore National Laboratory. His
research focuses on scalable tools for measuring, analyzing, and
visualizing parallel performance data. In addition to his research, Todd
leads LLNL's DevRAMP (Reproducibility, Analysis, Monitoring, and
Performance) team and the Software Packaging Technologies project in the
U.S. Exascale Computing Project. He also created Spack.

# Links

- [spack.io website](https://spack.io)
- [Spack on GitHub](https://github.com/spack/spack)
- [Spack Documentation](https://spack.readthedocs.io)
- [Spack Tutorial](https://spack-tutorial.readthedocs.io)
- [Join Spack Slack!](https://spackpm.herokuapp.com)

Listen to this episode here or add our [rss feed](https://flossforscience.com/feed.xml) to your favourite podcast application.

You can also download this episode as [MP3]({{ page.podcast_link }}) or [OGG]({{ page.podcast_link_ogg }}).

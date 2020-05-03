---
layout: post
title: "Spack"
date: 2020-04-08 00:00:00
author: Admin
categories:
 - developer
 - podcast
#Title of the podcast episode without the episode number
podcast_episode_title: "Spack"
#Image of the blog post
img: FFS027_header.png
#Thumbnail of the blog post
thumb: FFS027_thumb.jpg
#Link to the mp3 file of the episode
podcast_link:
#Link to the ogg file of the episode
podcast_link_ogg:
#File size in MB of the mp3 file
podcast_file_size:
#File size in MB of the ogg file
podcast_file_size_ogg:
#Length of the episode in minutes (is the same for ogg and mp3)
podcast_duration:
#File size in bytes of the mp3 file
podcast_length:
#File size in bytes of the ogg file
podcast_length_ogg:
#Unique id of the mp3 file (sha256)
podcast_guid:
#“full” for normal episodes; “trailer” to promote an upcoming show, season, or episode; or “bonus” for extra content related to a show, season, or episode.
podcast_episode_type: full
#Season number only
podcast_season_number: 03
#Episode number only
podcast_episode_number: 07
#Subtitle of the episode
podcast_subtitle: An interview with Todd Gamblin
#Description of the podcast
podcast_description:

---

<audio controls>
  <source src="{{ page.podcast_link_ogg }}" type="audio/ogg">
  <source src="{{ page.podcast_link }}" type="audio/mpeg">
Your browser does not support the audio element.
</audio>

# Outline

TBD

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

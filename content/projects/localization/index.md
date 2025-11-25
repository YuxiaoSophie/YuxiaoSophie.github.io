---
date: "2022-05-24T00:00:00Z"
show_date: false
external_link: ""
weight: 20
image:
  caption: 
  focal_point: "Center"
  preview_only: true
links:
# - icon: photo-video
#   icon_pack: fa
#   name: Slides
#   url: Summary.pptx
# - icon: scroll
#   icon_pack: fa
#   name: Paper
#   url: https://dl.acm.org/doi/10.1145/3746059.3747768
- icon: video
  icon_pack: fa
  name: Video
  url: video_2x.mp4
# - icon: clipboard
#   icon_pack: fa
#   name: Poster
#   url: poster.pdf
# - icon: github
#   icon_pack: fab
#   name: Workshop materials
#   url: https://github.com/shilaan/example-manuscripts
# - icon: twitter
#   icon_pack: fab
#   name: Tweet 
#   url: https://twitter.com/shilaan01/status/1413946789699325953
title: "Robot Particle Filter Localization"
summary: > 
    Developed and implemented a Monte Carlo Localization algorithm with ray casting and probabilistic resampling to enable real-time pose estimation of a TurtleBot.
    
reading_time: false
commentable: false
show_related: false
show_links: false
authors: 
  - admin
star_admin_here: false
click_title: true
---

<video controls style="width:100%; max-width: 800px; display:block; margin: 0 auto;">
  <source src="video_2x.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<br>

I contributed to design a Monte Carlo Localization algorithm to enable a TurtleBot to estimate its pose in a known occupancy grid map using noisy odometry and laser scan data. I also implemented measurement models using ray casting and probabilistic resampling, achieving robust real-time localization in ROS2 and RViz.

{{< page_links >}}
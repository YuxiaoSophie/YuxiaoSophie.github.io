---
date: "2022-05-24T00:00:00Z"
show_date: false
external_link: ""
weight: 10
image:
  caption: 
  focal_point: "Center"
  preview_only: true
links:
# - icon: scroll
#   icon_pack: fa
#   name: Paper
#   url: https://dl.acm.org/doi/10.1145/3746059.3747768
- icon: video
  icon_pack: fa
  name: Video
  url: video_1.5x.mp4
# - icon: clipboard
#   icon_pack: fa
#   name: Poster
#   url: poster.pdf
# - icon: photo-video
#   icon_pack: fa
#   name: Slides
#   url: https://many-analysts.netlify.app/#1
# - icon: github
#   icon_pack: fab
#   name: Workshop materials
#   url: https://github.com/shilaan/example-manuscripts
# - icon: twitter
#   icon_pack: fab
#   name: Tweet 
#   url: https://twitter.com/shilaan01/status/1413946789699325953
title: "Robot Q-Learning Manipulation"
summary: > 
    Developed a Q-learning-based reinforcement learning system in ROS2 and Python for a TurtleBot to autonomously perceive, learn, and manipulate objects using ArUco marker detection and robotic arm control.
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
  <source src="video_1.5x.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<br>

I implemented a reinforcement learning system that enabled a TurtleBot to learn optimal object placement strategies through simulated rewards and policy training. After training a Q-matrix to maximize long-term rewards, I integrated computer vision with object detection and robotic arm control, allowing the robot to autonomously perceive its environment and place colored objects at designated AR tags based on the learned policy. 

{{< figure src="gesture.jpg" caption="" >}}

To enhance human-robot interaction, I also trained a gesture recognition system to classify gestures in real-time for interactive control. 

{{< page_links >}}
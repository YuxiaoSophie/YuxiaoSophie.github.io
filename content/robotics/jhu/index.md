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
- icon: photo-video
  icon_pack: fa
  name: Slides
  url: Summary.pptx
# - icon: scroll
#   icon_pack: fa
#   name: Paper
#   url: https://dl.acm.org/doi/10.1145/3746059.3747768
- icon: video
  icon_pack: fa
  name: Video
  url: video.mov
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
title: "Cockroach Robot Locomotion Over Complex Obstacles"
summary: > 
    Constructed a physics-based cockroach-inspired robot simulation in MuJoCo to investigate locomotion and obstacle traversal, focusing on pitch-to-roll transitions and evaluating strategies across different contact conditions.
    
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
  <source src="video.mov" type="video/quicktime">
  Your browser does not support the video tag.
</video>

<br>

I contributed to a project focused on cockroach-inspired robot locomotion across complex terrain, working to simulate and optimize the robot's traversal behavior. Specifically, I took the lead in independently developing physics-based simulations with careful validation of contact dynamics. 

Drawing from prior lab studies of how cockroaches and robots traverse beam obstacles, I enhanced the simulation model by incorporating dynamic roll and pitch degrees of freedom and introducing stochastic vertical oscillations under varying frequencies and beam stiffnesses. This allowed me to examine how posture changes, especially transitions from pitch to roll, improve traversal performance. To reduce the simulation-reality gap, I iteratively refine the model through quantitative comparison with empirical measurements, aligning transition probabilities and traversal and transition times from both cockroach and robot experiments. 

In collaboration with a master's student, I further helped apply reinforcement learning to the simulation framework I developed, aiming to support learning-based control strategies for energy-efficient traversal. 

{{< page_links >}}
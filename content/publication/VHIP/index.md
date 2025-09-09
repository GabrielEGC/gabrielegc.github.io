---
title: 'A Control Approach for the Variable-Height Inverted Pendulum Based on Sliding Mode Control With Input Saturation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Gabriel Garcia

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2019-10-15T00:00:00Z'
doi: '10.1109/Humanoids43949.2019.9035056'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In 2019 IEEE-RAS 19th International Conference on Humanoid Robots (Humanoids)
#publication_short: In *Humanoids*

abstract: Maintaining the balance when a robot is pushed forward is fundamental for legged robots. An essential topic in the literature is capture point; it is the place where the robot can step to in order to recover from the push. In this work, we study the Variable-Height Inverted Pendulum (VHIP) as the model for a pushed robot. We found all of the points that are allowed to be a capture point for given initial velocities of the center of mass and actuator limitations. We also develop a controller to reach a capture point using the reaction force to the ground as input variable. We pay attention to the unilateral contact and the maximum-value of a function of the reaction force. First, we obtain the necessary conditions that must be satisfied to be able to achieve balance by providing a decomposition of the VHIP into a new Divergent Component of Motion and a Convergent Component of Motion. Then we present two control laws to stabilize the system and we show that the region of attraction is equivalent to the region of necessary condition for balance. Finally, we briefly discuss the physical places where balance can be achieved.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Sliding Mode Control
  - Bipedal Robot
  - Reduced Models

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: ''
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'VHIP recovery'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
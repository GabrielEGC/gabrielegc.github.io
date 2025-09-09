---
title: 'Torque Control in Position-Controlled Robots using an Inverse Dynamic Task'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Gabriel Garcia
  - Emanuel Muñoz-Panduro
  - Oscar Ramos

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2020-12-19T00:00:00Z'
doi: '10.1109/CDC42340.2020.9303751'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In 2020 59th IEEE Conference on Decision and Control (CDC)
#publication_short: In *Humanoids*

abstract: Many position-controlled robots are being used in research and industry in the world, but many tasks require torque control instead of position control, in order to exert specific forces in the environment. This is often called the admittance control problem. In this paper, we present a solution for position-controlled robots by estimating their hidden internal control law using Neural Networks and mitigating the fitting errors with an integral term in the control law. Compared to classical approaches, we no longer consider that the control law is decoupled between motors but it can be highly sophisticated and nonlinear. We show our results in simulation by performing torque tracking and force-position task control.


# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Torque Control
  - Robotics
  - Machine Learning

# Display this page in the Featured widget?
featured: true

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
  caption: 'Force-Position hybrid arm model'
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
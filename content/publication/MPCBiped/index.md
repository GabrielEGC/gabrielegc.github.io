---
title: 'MPC-based Locomotion Control of Bipedal Robots with Line-Feet Contact using Centroidal Dynamics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Gabriel Garcia
  - Robert Griffin
  - Jerry Pratt

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2021-07-19T00:00:00Z'
doi: '10.1109/HUMANOIDS47582.2021.9555775'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In 2020 IEEE-RAS 20th International Conference on Humanoid Robots (Humanoids)
publication_short: In *Humanoids*

abstract: Recently we have seen a lot of progress done in dynamic locomotion with quadrupedal robots using the Single-Rigid Body Model, which contains simplified dynamics that considers the robot a single “potato”. This approach performs poorly when the robot contains heavy links, because those links take a considerable momentum to move and because they also change the overall inertia of the robot. In this paper, we generalize the SRBM using the Centroidal Dynamics model plus an orientation variable, whose dynamics contain the linearized effects of other links’ momentum and variable inertia. We are designing this Enhanced Centroidal Dynamics using the Full-Body Dynamics, so the trajectories we obtain are instantaneously dynamically feasible. We show our approach in a full-body dynamic simulation of the MIT Humanoid, a biped with line-feet contact, and we show a simplification in the modeling of the wrenches that can be applied with line-feet.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Model Predictive Control
  - Convex Optimization

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
  caption: 'MIT Biped'
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
slides: example
---

#{{% callout note %}}
#Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the _Slides_ button to check out the example.
#{{% /callout %}}

#Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

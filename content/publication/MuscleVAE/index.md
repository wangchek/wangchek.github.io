---
title: "MuscleVAE: Model-Based Controllers of Muscle-Actuated Characters"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Xiyan Xu
- Libin Liu

# Author notes (optional)
author_notes:
-
-
- "Corresponding Authors"


date: "2023-12-01T00:00:00Z"
doi: "https://doi.org/10.1145/3610548.3618137"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Graphics(Proceedings of SIGGRAPH Asia 2023)*
publication_short: In *SIGGRAPH Asia*

abstract: "In this paper, we present a simulation and control framework for generating biomechanically plausible motion for muscle-actuated characters. We incorporate a fatigue dynamics model, the 3CC-r model, into the widely-adopted Hill-type muscle model to simulate the development and recovery of fatigue in muscles, which creates a natural evolution of motion style caused by the accumulation of fatigue from prolonged activities. To address the challenging problem of controlling a musculoskeletal system with high degrees of freedom, we propose a novel muscle-space control strategy based on PD control. Our simulation and control framework facilitates the training of a generative model for muscle-based motion control, which we refer to as MuscleVAE. By leveraging the variational autoencoders (VAEs), MuscleVAE is capable of learning a rich and flexible latent representation of skills from a large unstructured motion dataset, encoding not only motion features but also muscle control and fatigue properties. We demonstrate that the MuscleVAE model can be efficiently trained using a model-based approach, resulting in the production of high-fidelity motions and enabling a variety of downstream tasks.
"

# Summary. An optional shortened abstract.
summary: We present MuscleVAE, a comprehensive muscle simulating and controlling framework with fatigue modelling embeded. Using model-based reinforcement learning, our framework can generate of high-fidelity motions and enable a variety of downstream tasks.

tags: [Muscle Simulation, Physcics Character Animation]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: Video
   url: https://www.youtube.com/
 - name: Code
   url: https://github.com/wangchek/MuscleVAE

url_pdf: 'Muscle-VAE/static/author_version.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/wangchek/MuscleVAE'
url_slides: ''
url_source: ''
# url_video:  'https://www.youtube.com/watch?v=ELZ7m4rLCgk'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
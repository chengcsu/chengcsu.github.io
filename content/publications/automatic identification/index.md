---
title: 'Automatic Identification of Individual African Leopards in Unlabeled Camera Trap Images'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Agnieszka Miguel
  - Anthony A. Maciejewski

# Author notes (optional)
# author_notes:
 # - 'Equal contribution'
 # - 'Equal contribution'

date: '2024-03-26T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-26T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Automation Science and Engineering*
publication_short: In *T-ASE*

abstract: This article describes an algorithm to solve the real-world animal identification problem, i.e., determine the unknown number of K individual animals in a dataset of N unlabeled camera-trap images of African leopards, provided by Panthera. To determine the leopards’ IDs, we propose an effective automated algorithm, that consists of segmenting leopard bodies from images, scoring similarity between image pairs, and clustering followed by verification. To perform clustering, we employ a modified ternary search that uses a novel adaptive k-medoids++ clustering algorithm. The best clustering is determined using an expanded definition of the silhouette score. A new post-clustering verification procedure is used to further improve the quality of a clustering. The algorithm was evaluated using the Panthera dataset that consists of 677 individual leopards taken from 1555 images, and resulted in a clustering with an adjusted mutual information score of 0.958 as compared to 0.864 using a baseline k-medoids++ clustering algorithm. Note to Practitioners—We proposed an effective automated algorithm to solve the real-world animal identification problem - identifying K unknown individual animals in N images of a given species, with most animals only represented by a single image. This algorithm is different from other methods that assume all images in a dataset are from known individuals and thus regard the animal ID problem as a retrieval identification task. Our approach consists of a new adaptive k-medoids++ clustering algorithm and a novel post-clustering verification procedure. The clustering is performed based on the degree of similarity between all image pairs in the dataset with the result validated using an expanded definition of the silhouette score. The accuracy of our algorithm was demonstrated on a real-world image dataset of African leopards, a small dataset with a relatively large ratio of K/N, provided by Panthera. 

# Summary. An optional shortened abstract.
summary: This article describes an algorithm to solve the real-world animal identification problem, i.e., determine the unknown number of K individual animals in a dataset of N unlabeled camera-trap images of African leopards, provided by Panthera.

tags:
  - Animal identification
  - Machine Learning

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/TASE.2024.3379553

# Custom links
links:
  - type: pdf
    url: ./Automatic%20Identification%20of%20Individual%20African%20Leopards%20in%20Unlabeled%20Camera%20Trap%20Images.pdf
  - type: code
    url: https://github.com/chengcsu/Automatic-individual-animal-identification
#  - type: dataset
#    url: https://github.com/HugoBlox/hugo-blox-builder
#  - type: slides
#    url: https://www.slideshare.net/
#  - type: source
#    url: https://github.com/HugoBlox/hugo-blox-builder
#  - type: video
#    url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

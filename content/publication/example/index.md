---
title: "Scheduling Algorithms in Map Reduce"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
# - Robert Ford

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

# date: "2013-07-01T00:00:00Z"
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: International Journal on Recent and Innovation Trends in Computing and Communication
publication_short: In *IJRITCC*

abstract: Data generated in the past few years cannot be efficiently manipulated with the traditional way of storing techniques as it is a large-scale dataset, and it can be structured, semi-structured, or unstructured. To deal with this kind of enormous dataset Hadoop framework is used, which supports the processing of large dataset in a distributed computing environment. Hadoop uses a technique named as MapReduce for processing and generating a large dataset with a parallel distributed algorithm on a cluster. It automatically handles failures and data loss due to its fault-tolerance property. The scheduler is a pluggable component of the MapReduce framework. Hadoop MapReduce framework uses various scheduler as per the requirements of the task. FIFO (First In First Out) is a default algorithm used by Hadoop, in which the jobs are executed in the order of their arrival. This paper will discuss myriad of schedulers such as FIFO, Capacity Scheduler, LATE Scheduler, Fair Scheduler, Delay Scheduler, Deadline Constraint Scheduler, and Resource Aware Scheduler. Besides these schedulers, we also conducted study of comparison of schedulers like Round Robin, Weighted Round Robin, Self-adaptive Reduce Scheduling (SARS), Self-adaptive MapReduce Scheduling (SAMR), Dynamic Priority Scheduling, Learning Scheduling, Classification & Optimization-based Scheduler (COSHH), Network-Aware, Match-matching, and Energy-Aware Scheduler. Hopefully, this study will enhance the understanding of the specific schedulers and stimulate other developers and consumers to make accurate decisions for their specific research interests.

# Summary. An optional shortened abstract.
summary: This review paper illustrates the architecture of Hadoop and the map-reduce framework. It demonstrates the comparison of map-reduce schedulers and their pros and cons. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ijritcc.org/index.php/ijritcc/article/view/5342/5287'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://ijritcc.org/index.php/ijritcc/article/view/5342'
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

# {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

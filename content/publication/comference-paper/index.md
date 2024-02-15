---
title: Human activity efficiency analysis AI system

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin

# Author notes (optional)
author_notes: ''

date: ''
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-30T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: []

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: National Tsing Hua University[(NTHU)](https://www.nthu.edu.tw/), advised by [Min Sun](https://aliensunmin.github.io/)

abstract: |
  This is an event analysis system related to factory production efficiency, which utilizes computer vision and artificial intelligence for inference and analysis. The goal of the system is to improve factory production efficiency by employing an AI detection system that capable of analyzing factory scenes.

  ### Problems
  Additionally, the system is designed to be quickly <u style="color: #7dafe2;">optimized</u> through both <u style="color: #7dafe2;">daily data</u> or <u style="color: #7dafe2;">new data</u> for business objectives. 
  [check demo](https://snapshots.raintank.io/dashboard/snapshot/W0V2YJHHJXK3hahhYR6WbBSKBpav1jX3)

  ### Project Achievements
  * Designed an active learning and data enrichment strategy, aiming to analyze weaknesses and extract crucial data from daily videos. This strategy further leverages prompt engineering to improve performance of [SAM](https://segment-anything.com/), resulting in high-quality data generation. This approach has successfully reduced labeling costs by <b style="color: red;">33%</b> while increasing accuracy by <b style="color: red;">20%</b>.
  * [Grafana](https://grafana.com/) and MySQL integration for effective monitoring and [data visualization](https://snapshots.raintank.io/dashboard/snapshot/W0V2YJHHJXK3hahhYR6WbBSKBpav1jX3).

  ### Technical Contributions
  * Data processing and management pipeline:
  The processing and selection for <u style="color: #7dafe2;">millions</u> of surveillance camera images per day highlight the <u style="color: #7dafe2;">large-scale data</u> processing challenges we encounter. This involves <u style="color: #7dafe2;">data collection, analyzing</u>, and <u style="color: #7dafe2;">selection</u> from <u style="color: #7dafe2;">various domains</u>.
  * Enhanced the zero-shot inference capabilities of [SAM: ](https://segment-anything.com/) 
  Improved [SAM's](https://segment-anything.com/) zero-shot inference abilities through prompt engineering, resulting in more accurate scene analysis and crucial data extraction.
  * Real-time data visualization:
  Integrated [Grafana](https://grafana.com/) with MySQL for real-time data visualization for backend analysis.
  * <u style="color: #7dafe2;">Independently</u> Implemented both the prompt engineering enhancement for [SAM](https://segment-anything.com/), <u style="color: #7dafe2;">Activate learning</u> strategy and the [Grafana](https://grafana.com/)-MySQL integration, it demonstrating individual technical skills.

  ### Collaborating companies: [Mirle](https://www.mirle.com.tw/)

  
# Summary. An optional shortened abstract.
summary: |
  <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grafana Dashboard Demo For Event Analysis</title>
    <style>
      .zoomed-iframe {
        zoom: 0.6;
        width: 100%;
        height: 750px;
        border: none;
      }
      .caption {
          font-size: 12px;
          text-align: center;
      }
    </style>
  </head>
  <body>
      <iframe class="zoomed-iframe" src="https://snapshots.raintank.io/dashboard/snapshot/W0V2YJHHJXK3hahhYR6WbBSKBpav1jX3"></iframe>
      <p class="caption">Grafana Event Analysis Dashboard Demo</p>
  </body>
  </html>

  <em><small style="background-color: #c5c5f7; color: #330066; padding: 5px;">LargeScaleProjects/Git/Python/PyTorch/Object-Detection/ActiveLearning/OpenCV/MySQL/Grafana</small></em><br>
  <small><em>Mar 2022 – June 2023</em></small>
  * Designed an active learning and data enrichment strategy, aiming to analyze weaknesses and extract crucial data from daily videos. This strategy further leverages prompt engineering to improve performance of [SAM](https://segment-anything.com/), resulting in high-quality data generation. This approach has successfully reduced labeling costs by <b style="color: red;">33%</b> while increasing accuracy by <b style="color: red;">20%</b>.
  * [Grafana](https://grafana.com/) and MySQL integration for effective monitoring and [data visualization](https://snapshots.raintank.io/dashboard/snapshot/W0V2YJHHJXK3hahhYR6WbBSKBpav1jX3).<br><br>
  Collaborating companies: [Mirle](https://www.mirle.com.tw/)

tags: ['Large scale project', 'Active learning', 'Object detection', 'Python', 'PyTorch', 'OpenCV', 'Git', 'MySQL', 'Grafana']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grafana Dashboard Demo For Event Analysis</title>
    <style>
      .zoomed-iframe {
        zoom: 0.6;
        width: 100%;
        height: 600px;
        border: none;
      }
      .caption {
          font-size: 12px;
          text-align: center;
      }
    </style>
  </head>
  <body>
      <iframe class="zoomed-iframe" src="https://snapshots.raintank.io/dashboard/snapshot/W0V2YJHHJXK3hahhYR6WbBSKBpav1jX3"></iframe>
      <p class="caption">Grafana Event Analysis Dashboard Demo</p>
  </body>
  </html> -->
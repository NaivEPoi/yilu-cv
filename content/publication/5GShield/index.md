---
title: 'Guardians of the Air: In-Device Detection of 5G Control-Plane Threats'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Tianwei Wu
  - Abdullah Al Ishtiaq
  - Tianchang Yang
  - admin
  - Kai Tu
  - Zeyu Song
  - Ridwanul Hasan Tanvir
  - Md Toufikuzzaman
  - Shagufta Mehnaz
  - Syed Rafiul Hussain

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-05-18T00:00:00Z'
# doi: '10.1145/3576915.3623113'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *the 47th IEEE Symposium on Security and Privacy*
publication_short: In *SP 26*

abstract: We present 5GShield, the first in-device framework for detecting and mitigating control-plane threats in 5G networks. 5GShield works with two complementary modules called ConnSentinel and ExFinder. By utilizing a novel observation of temporal and spatial consistency in broadcast messages among cells under the same tracking area and frequency, ConnSentinel inspects initial cell broadcast messages from nearby base stations to identify and block suspicious base stations that expose anomalous configuration before connection establishment. On the other hand, a machine-learning-based ExFinder module continuously monitors observable control-plane traffic to detect ongoing protocol-level attacks. For ExFinder, we develop a novel graph representation construction mechanism and integrate it with a hybrid pipeline for anomaly detection and attack classification. To support training and evaluation, we curate the first comprehensive dataset combining diverse benign traces from commercial 5G deployments with malicious traces derived from known 4G and 5G control-plane attacks. Experimental results show that 5GShield achieves 99.6% precision and 97.0% recall in detecting both known and zero-day attacks, based on anomaly detection over UE-visible control-plane behavior. Furthermore, 5GShield is lightweight, consuming less than 3.75% of the memory and is deployable on modern commercial devices.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - 5G
  - Intrusion Detection
  - Machine Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '5GShield.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

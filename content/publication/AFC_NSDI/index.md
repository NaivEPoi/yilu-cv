---
title: 'A Systematic Threat Analysis and Practical Attacks on Automated Frequency Coordination Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tianchang Yang
  - Arupjyoti Bhuyan
  - Syed Rafiul Hussain

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-05-04T00:00:00Z'
# doi: '10.1145/3576915.3623113'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *the 23rd USENIX Symposium on Networked Systems Design and Implementation*
publication_short: In *NSDI 25*

abstract: The 6 GHz band, traditionally reserved for mission-critical incumbent systems such as public safety communications, utility infrastructure, and fixed satellite services, has recently been opened for Wi-Fi devices. This expansion introduces a critical coexistence challenge of ensuring that unlicensed Wi-Fi Access Points (APs) do not interfere with incumbent operations. To manage this risk, regulators mandated the use of Automated Frequency Coordination (AFC) systems that assign spectrum access to Wi-Fi APs based on their locations. In this work, we present the first systematic security analysis of AFC systems. In particular, we analyze the trust assumptions of AFC systems and uncover design lapses and deployment mishaps in this model. Our analysis reveals that the AFC's dependence on unauthenticated data sources, including GNSS/GPS and Wi-Fi-based localization (for location), DNS (for service discovery), and NTP (for time synchronization), creates practical off-path attack vectors that allow adversaries to manipulate control-plane parameters without breaking cryptographic protections between APs and AFC servers. For example, using inexpensive, off-the-shelf software-defined radios, an off-path adversary can spoof the GPS signals received by an AP, falsifying its reported location to either disable 6 GHz transmissions or cause harmful interference with incumbent services. We validate these vectors empirically on commercial APs from four major vendors and evaluate four commercial and one open-source AFC servers to measure real-world impact. We also propose potential mitigations and analyze the trade-offs between usability and security to formulate our recommendations to harden AFC deployments and 6 GHz APs.  

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Wi-Fi
  - Automated Frequency Coordination
  - Vulnerbility Research

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'AFC_Attacks_NSDI.pdf'
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

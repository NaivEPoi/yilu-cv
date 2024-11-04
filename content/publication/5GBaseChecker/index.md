---
title: 'Logic Gone Astray: A Security Analysis Framework for the Control Plane Protocols of 5G Basebands'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kai Tu
  - Abdullah Al Ishtiaq
  - Syed Md Mukit Rashid
  - admin
  - Weixuan Wang
  - Tianwei Wu
  - Syed Rafiul Hussain

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-08-14T00:00:00Z'
# doi: '10.1145/3576915.3623113'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *the 33rd USENIX Security Symposium*
publication_short: In *USENIX Security 24*. **Distinguished Paper Award**

abstract: We develop 5GBaseChecker—an efficient, scalable, and dynamic security analysis framework based on differential testing for analyzing 5G basebands' control plane protocol interactions. 5GBaseChecker first captures basebands' protocol behaviors as a finite state machine (FSM) through black-box automata learning. To facilitate efficient learning and improve scalability, 5GBaseChecker introduces novel hybrid and collaborative learning techniques. 5GBaseChecker then identifies input sequences for which the extracted FSMs provide deviating outputs. Finally, 5GBaseChecker leverages these deviations to efficiently identify the security properties from specifications and use those to triage if the deviations found in 5G basebands violate any properties. We evaluated 5GBaseChecker with 17 commercial 5G basebands and 2 open-source UE implementations and uncovered 22 implementation-level issues, including 13 exploitable vulnerabilities and 2 interoperability issues. 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - 5G devices
  - Software Testing
  - Vulnerbility Research

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'usenixsecurity24-tu.pdf'
url_code: 'https://github.com/SyNSec-den/5GBaseChecker.git'
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

*Distinguished Paper Award*

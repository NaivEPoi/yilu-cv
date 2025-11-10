---
title: 'Evaluating Time-Bounded Defense Against RRC Relay in 5G Broadcast Messages'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tao Wan
  - Tianwei Wu
  - Syed Rafiul Hussain

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-06-30T00:00:00Z'
doi: '10.1145/3734477.3734718'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *the 18th ACM Conference on Security and Privacy in Wireless and Mobile Networks*
publication_short: In *WiSec 25*.

abstract: As 5G and future generations of mobile networks aim to provide faster and more secure wireless connections, 5G broadcast messages remain unprotected. Hence, a user device cannot verify the identity of a base station before establishing the connection and starting the registration procedure. This long-existing loophole enables various types of fake base station (FBS) attacks. To protect end-users from these attacks, a practical solution is to introduce a digital signature for these broadcast messages. However, an FBS may also have the ability to relay a digitally signed broadcast message from a benign base station to bypass the protection. Considering that a relayed message needs extra time to reach a user device, a time-bounded defense mechanism can be used on top of the digital signature to offer replay protection. Although previous work proposed such a solution, none have implemented it or evaluated it against relay attacks. Hence, to evaluate the performance of our proposed digital signature scheme and the time-bounded defense, we implemented the solution against relay attacks using an open-source 5G system. Our results show that the overhead introduced is acceptable and that the time-bounded defense is effective against relay attacks.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - 5G Authentication
  - Applied Cryptography
  - Security Protocols

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'SIB-Auth.pdf'
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

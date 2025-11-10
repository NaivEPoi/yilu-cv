---
title: 'CoreCrisis: Threat-Guided and Context-Aware Iterative Learning and Fuzzing of 5G Core Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Tianchang Yang
  - Abdullah Al Ishtiaq
  - Syed Md Mukit Rashid
  - Ali Ranjbar
  - Kai Tu
  - Tianwei Wu
  - Md Sultan Mahmud
  - Syed Rafiul Hussain

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-08-14T00:00:00Z'
# doi: '10.1145/3576915.3623113'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *the 34th USENIX Security Symposium*
publication_short: In *USENIX Security 25*

abstract: We develop CoreCrisis, a stateful black-box fuzz-testing framework for 5G core network (5GC) implementations. Unlike previous stateful security analysis efforts of cellular networks which rely on manually-crafted, static test inputs and are limited to identifying only logical errors, CoreCrisis employs a dynamic two-step approach. Initially, CoreCrisis builds an initial finite state machine (FSM) representation of the 5GC's implementation using only benign (i.e., positive) inputs with its efficient and scalable divide-and-conquer and property-driven equivalence checking learning. During fuzzing, it utilizes the learned FSM to target underexplored states and introduces state-aware mutations to generate and test attacking (i.e., negative) inputs. Based on the responses observed from the core network, CoreCrisis continuously refines the FSM to better guide its exploration and find vulnerabilities. Evaluating CoreCrisis on three open-source and one commercial 5GC implementations, we identified 7 categories of deviations from the technical specifications and 13 crashing vulnerabilities. These logical and crashing vulnerabilities lead to denial-of-service, authentication bypass, and billing fraud.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - 5G core network
  - Software Testing
  - Vulnerbility Research

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'usenixsecurity25-dong-yilu.pdf'
url_code: 'https://github.com/SyNSec-den/CoreCrisis.git'
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

---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Security Architecture for Protecting Safety-Critical Railway Infrastructure"
authors:
  - "Christoph Krauß"
  - "Maria Zhdanova"
  - "Michael Eckel"
  - "Stefan Katzenbeisser"
  - "Markus Heinrich"
  - "Don Kuzhiyelil"
  - "Jasmin Cosic"
  - "Matthias Drodt"
date: 2021-03-05T00:00:00+02:00
doi: ""
isbn: "978-3-645-50189-7"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-05T00:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "embedded world Conference 2021"
publication_short: "ewC2021"

abstract: |
  Digitization, connectivity, and use of commercial off-the-shelf technologies has reached safety-critical areas such as the railway sector. This creates new opportunities for attacks and makes it necessary to integrate IT security measures into railway command and control systems (CCS). However, the integration of security mechanisms into a system certified according to the railway safety standard EN 50128 is a big challenge. This article gives an overview of an IT security architecture, which allows to operate security measures on safety systems such as object controllers. It consists of a hardware platform with a Trusted Platform Module (TPM) 2.0, a MILS (Multiple Independent Levels of Safety and Security) Separation Kernel (SK), and various security applications. The TPM serves as security anchor and enables, e.g., secure storage, measured boot, and remote attestation to detect tampering with the system software. The MILS OS ensures freedom of interference when running safety and security applications.

# Summary. An optional shortened abstract.
summary: |
  This article gives an overview of an IT security architecture, which allows to operate security measures on safety systems such as object controllers. It consists of a hardware platform with a Trusted Platform Module (TPM) 2.0, a MILS (Multiple Independent Levels of Safety and Security) Separation Kernel (SK), and various security applications. The TPM serves as security anchor and enables, e.g., secure storage, measured boot, and remote attestation to detect tampering with the system software. The MILS OS ensures freedom of interference when running safety and security applications.

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://shop.weka-business-communication.com/Sonderpublikationen-dsb/embedded-world-Conference-2021-DIGITAL-Proceedings.html
url_code: 
url_dataset: 
url_poster: 
url_project: 
url_slides: 
url_source: 
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [haselnuss]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


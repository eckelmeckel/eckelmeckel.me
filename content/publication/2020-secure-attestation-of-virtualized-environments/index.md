---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Secure Attestation of Virtualized Environments"
authors:
  - "Michael Eckel"
  - "Andreas Fuchs"
  - "Jürgen Repp"
  - "Markus Springer"
date: 2020-09-01T00:00:00+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-01T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "35th International Conference on ICT Systems Security and Privacy Protection – IFIP SEC 2020"
publication_short: "IFIP SEC 2020"

abstract: |
  Securing the integrity of virtualized environments like clouds is challenging yet feasible.
  Operators have discovered the advantages of virtualization technology in terms of flexibility, scalability, cost-effectiveness, and availability.
  Applications range from network and embedded devices to big data centers and cloud computing.
  Trusted Computing technology can be employed to protect the integrity of a system by leveraging a Trusted Platform Module (TPM) and remote attestation.
  
  Existing research on remote attestation of virtualized environments differs in scalability, resource consumption, and provided security guarantees.
  While some approaches scale at large and use the TPM efficiently, they are way more intrusive, requiring changes to hypervisor and Virtual Machines (VMs).
  Others render entirely impractical with an increasing number of VMs, caused by the TPM being the bottleneck.
  
  In this paper we analyze existing work on remote attestation for virtualized environments and discuss benefits as well as shortcomings.
  We identify an approach that provides adequate security and is easy to implement but is prone to relay attacks.
  We improve that approach by developing countermeasures, while maintaining existing security guarantees.
  Our contribution requires only minimal changes to the hypervisor system, keeping existing attestation protocols intact.
  We implement and evaluate on production-grade hardware, and compare our improved attestation approach with the most sophisticated alternative approach.
  With performance measurements and further evaluations we show that our solution outperforms the other approach for a small number of VMs, as used in network devices and embedded systems.

# Summary. An optional shortened abstract.
summary: |
  In this paper we analyze existing work on TPM-based remote attestation for virtualized environments and discuss benefits as well as shortcomings.
  We identify an approach that provides adequate security and is easy to implement but is prone to relay attacks.
  We improve that approach by developing countermeasures, while maintaining existing security guarantees.
  We implement and evaluate on production-grade hardware.
  With performance measurements and further evaluations we show that our solution is viable.

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


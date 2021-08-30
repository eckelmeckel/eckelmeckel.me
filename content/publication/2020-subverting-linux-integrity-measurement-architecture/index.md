---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Subverting Linux' Integrity Measurement Architecture"
authors:
  - "Felix Bohling"
  - "Tobias Mueller"
  - "Michael Eckel"
  - "Jens Lindemann"
date: 2020-08-25T00:00:00+02:00
doi: "10.1145/3407023.3407058"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-25T00:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 15th International Conference on Availability, Reliability and Security – ARES 2020"
publication_short: "ARES 2020"

abstract: |
  Integrity is a key protection objective in the context of system security. This holds for both hardware and software. Since hardware cannot be changed after its manufacturing process, the manufacturer must be trusted to build it properly. However, it is completely different with software. Users of a computer system are free to run arbitrary software on it and even modify BIOS/UEFI, bootloader, or Operating System (OS).

  Ensuring that only authentic software is loaded on a machine requires additional measures to be in place. Trusted Computing technology can be employed to protect the integrity of system software by leveraging a Trusted Platform Module (TPM). Measured Boot uses the TPM to record measurements of all boot software in a tamper-resistant manner. Remote attestation then allows a third party to investigate these TPM-protected measurements at a later point and verify whether only authentic software was loaded.

  Measured Boot ends with loading and running the OS kernel. The Linux Integrity Measurement Architecture (IMA) extends the principle of Measured Boot into the OS, recording all software executions and files read into the TPM. Hence, IMA constitutes an essential part of the Trusted Computing Base (TCB).

  In this paper, we demonstrate that the security guarantees of IMA can be undermined by means of a malicious block device. We validate the viability of the attack with an implementation of a specially-crafted malicious block device in QEMU, which delivers different data depending on whether the block has already been accessed. We analyse and discuss how the attack affects certain use cases of IMA and discuss potential mitigations.

# Summary. An optional shortened abstract.
summary: |
   In this paper, we demonstrate that the security guarantees of the Linux Integrity Measurement Architecture (IMA) can be undermined by means of a malicious block device.
   We validate the viability of the attack with an implementation of a specially-crafted malicious block device in QEMU, which delivers different data depending on whether the block has already been accessed.
   We analyse and discuss how the attack affects certain use cases of IMA and discuss potential mitigations.

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

url_pdf:  https://dl.acm.org/doi/10.1145/3407023.3407058?cid=99659558618
url_code: https://github.com/timr1994/libusim
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


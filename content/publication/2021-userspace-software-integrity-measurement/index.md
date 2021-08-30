---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Userspace Software Integrity Measurement"
authors:
  - "Michael Eckel"
  - "Tim Riemann"
date: 2021-08-17T00:00:00+02:00
doi: "10.1145/3465481.3470018"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-17T00:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The 16th International Conference on Availability, Reliability and Security – ARES 2021"
publication_short: "ARES 2021"

abstract: |
  Todays computing systems are more interconnected and sophisticated than ever before. Especially in healthcare 4.0, services and infrastructures rely on cyber-physical systems (CPSes) and Internet of Things (IoT) devices. This adds to the complexity of these highly connected systems and their manageability. Even worse, the variety of emerging cyber attacks is becoming more severe and sophisticated, making healthcare one of the most important sectors with major security risks. The development of appropriate countermeasures constitutes one of the most complex and difficult challenges in cyber security research. Research areas include, among others, anomaly detection, network security, multi-layer event detection, cyber resiliency, and integrity protection.

  Securing the integrity of software running on a device is a desirable protection goal in the context of systems security. With a Trusted Platform Module (TPM), measured boot, and remote attestation there exist technologies to ensure that a system has booted up correctly and runs only authentic software. The Linux Integrity Measurement Architecture (IMA) extends these principles into the operating system (OS), measuring native binaries before they are loaded. However, interpreted language files, such as Java classes and Python scripts, are not considered executables and are not measured as such. Contemporary OSes ship with many of these and it is vital to consider them as security-critical as native binaries.

  In this paper, we introduce Userspace Software Integrity Measurement (USIM) for the Linux OS. USIM enables interpreters to measure, log, and irrevocably anchor critical events in the TPM. We develop a software library in C which provides TPM-based measurement functionality as well as the USIM service, which provides concurrent access handling to the TPM based event logging. Further, we develop and implement a concept to realize highly frequent event logging on the slow TPM. We integrate this library into the Java Virtual Machine (JVM) to measure Java classes and show that it can be easily integrated into other interpreters. With performance measurements we demonstrate that our contribution is feasible and that overhead is negligible.

# Summary. An optional shortened abstract.
summary: |
  In this paper, we introduce Userspace Software Integrity Measurement (USIM) for the Linux OS.
  USIM enables interpreters to measure, log, and irrevocably anchor critical events in the Trusted Platform Module (TPM).
  We develop a software library in C which provides TPM-based measurement functionality as well as the USIM service, which provides concurrent access handling to the TPM based event logging.
  Further, we develop and implement a concept to realize highly frequent event logging on the slow TPM.
  We integrate this library into the Java Virtual Machine (JVM) to measure Java classes and show that it can be easily integrated into other interpreters.
  With performance measurements we demonstrate that our contribution is feasible and that overhead is negligible.

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

url_pdf: https://dl.acm.org/doi/10.1145/3465481.3470018?cid=99659558618
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


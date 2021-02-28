---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Softwaredesign für Dynamische Integritätsmessungen bei Linux"
authors:
  - "Kai-Oliver Detken"
  - "Marcel Jahnke"
  - "Thomas Rix"
  - "Andre Rein"
  - "Michael Eckel"
date: 2017-09-19T00:00:00+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2017-09-19T00:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "D•A•CH Security 2017"
publication_short: "D•A•CH Security 2017"

abstract: |
  Die meisten Sicherheitstools versuchen schädliche Programme anhand ihrer Signatur oder anhand ihres Verhaltens zu erkennen.
  Dies hat allerdings einen entscheidenden Nachteil, denn damit diese Erkennung funktionieren kann, muss das Schadprogramm oder Verhalten bereits bekannt sein.
  Ein anderer Ansatz ist es, die ausführbaren Programme direkt auf Änderungen im Programmcode zu überwachen.
  Dies macht z.B. die Integrity Measurement Architecture (IMA) im Linux-Kernel.
  Diese misst Userspace- und/oder Kernelspace-Programme bevor diese ausgeführt werden.
  Aber viele Systeme werden nur einmal gestartet und laufen dann lange Zeit, ohne dass sie neugestartet werden.
  Das bedeutet, dass während der Laufzeit auftretende Programmcode-Änderungen nicht erkannt werden können.
  Daher verfolgte dieses Kooperationsprojekt den Ansatz der Dynamic Runtime Attestation (DRA), basierend auf dem Vergleich zwischen geladenem Programmcode und bekannten Referenzwerten.

  DRA ist ein komplexer Ansatz, der verschiedene Komponenten und komplexe Attestierungsverfahren beinhaltet.
  Daher ist eine flexible und erweiterbare Architektur erforderlich.
  In dem Kooperationsprojekt wurde eine Architektur entwickelt und erfolgreich in einem Prototyp umgesetzt.
  Um die nötige Flexibilität und Erweiterbarkeit zu erreichen, ist in den beteiligten Komponenten die Attestierungsstrategie (Guideline) zentral umgesetzt.
  Die Guidelines definieren die nötigen Schritte für alle Attestierungsoperationen, wie z.B. Messungen, Referenzwert-Generierung und Verifikation.

# Summary. An optional shortened abstract.
summary: |
  Die meisten Sicherheitstools versuchen schädliche Programme anhand ihrer Signatur oder anhand ihres Verhaltens zu erkennen.
  Dies hat den Nachteil, dass das Schadprogramm oder dessen Verhalten bereits bekannt sein muss.
  Ein anderer Ansatz ist es, ausführbare Programme direkt auf Änderungen im Programmcode zu überwachen, bevor diese ausgeführt werden.
  Mit diesem Ansatz ist es allerdings nicht möglich zur Laufzeit auftretenden Programmcode-Änderungen zu erkennen.
  Der in dieser Publiaktion vorgestellte Ansatz der TPM-basierten Dynamic Runtime Attestation (DRA) basiert auf dem Vergleich zwischen geladenem Programmcode und bekannten Referenzwerten.
  Um die nötige Flexibilität und Erweiterbarkeit zu erreichen, wird in den beteiligten Komponenten die Attestierungsstrategie (Guideline) zentral umgesetzt, welche die nötigen Schritte für alle Attestierungsoperationen, wie z.B. Messungen, Referenzwert-Generierung und Verifikation definieren.

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

url_pdf: 
url_code:
url_dataset:
url_poster:
url_project:
url_slides: https://www.detken.net/papers/DACH-Security2017_DRIVE.pdf
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


---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a class="btn btn--primary" href="{{ '/files/CV_Lea_Stallbaum.pdf' | prepend: base_path }}"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i> Download CV (PDF)</a></p>

Academic Education
======
* **03/2022 –:** Doctoral Degree in Political Science, Johannes Gutenberg University Mainz
  * Supervisor: Prof. Dr. Claudia Landwehr

* **10/2019 – 02/2022:** Master of Arts "Governance and Public Policy – Staatswissenschaften", University of Passau

* **10/2016 – 07/2019:** Bachelor of Science "Public Governance across Borders", University of Münster, University of Twente

Academic Employment
======
* **03/2022 –:** Doctoral Researcher, Department of Political Science, Johannes Gutenberg University Mainz
  * DFG-funded project *Conceptions of Democracy among Political Elites and Citizens* (03/2022 – 08/2026)
  * DFG-funded project *False Consensus Beliefs in Politics and their Effects on Legitimacy* (Research Group Big Structural Change) (09/2026 –)

* **01/2020 – 02/2022:** Student Assistant and Tutor, Jean-Monnet Chair for European Politics, University of Passau

* **04/2019 – 09/2019:** Student Tutor, Institute for Political Science, University of Münster

Publications
======
{% for category in site.publication_category %}
{% assign has_entries = false %}
{% for post in site.publications %}{% if post.category == category[0] %}{% assign has_entries = true %}{% endif %}{% endfor %}
{% if has_entries %}
### {{ category[1].title }}
<ul>{% for post in site.publications reversed %}{% if post.category == category[0] %}
  {% include archive-single-cv.html %}
{% endif %}{% endfor %}</ul>
{% endif %}
{% endfor %}

Invited Talks and Workshops
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Conference Presentations
======
* EPSS Annual Meeting (2026)
* Jahrestagung AK Analytische Politische Theorie, DVPW (2025)
* ECPR General Conference (2023, 2025)
* ECPR Joint Sessions, Workshop "Authoritarian Nostalgia and Populist Radical Right Parties" (2025)
* DVPW-Kongress (2024)
* APSA Annual Meeting (2024)
* ECPR Joint Sessions, Workshop "Generations and Political Change" (2023)

Academic Teaching
======
* **Master Seminar** *Inhaltsanalysen in der Politikwissenschaft: Theorie und Praxis* [Text Analyses in Political Science: Theory and Application], Johannes Gutenberg University Mainz
  * Summer Term 2023, Summer Term 2025
  * Evaluation: 1.33 (2023), 1.32 (2025) [1 = very good, 6 = very bad]

* **Tutorial** *Einführung in die Grundlagen des wissenschaftlichen Arbeitens* [Introduction to the Basics of Scientific Practice], University of Passau
  * Summer Term 2020, Winter Term 2020/2021, Summer Term 2021, Winter Term 2021/2022

* **Tutorial** *Statistik I* [Statistics I], University of Münster
  * Summer Term 2019

Additional Training
======
* **2025 – 2026:** WissKomm Academy – Kompetenztraining Wissenschaftskommunikation [Competence Training for Science Communication], Akademie der Wissenschaften und der Literatur, Mainz
* **2026:** GESIS Panel.dbd Insight Days, GESIS, Mannheim
* **2023 – 2025:** Rheinland-Pfalz-Zertifikat für Hochschuldidaktik [Certificate for University Teaching], Center for Quality Assurance and Development, Mainz
* **2023:** Summer Institute in Computational Social Science (SICSS), University of Munich
* **2023:** Training Course on Factorial Survey Design, GESIS Summer School, Cologne

Academic Service
======
* Journal Reviewer for *Democratization*, *Electoral Studies*, *Political Research Exchange*, *Zeitschrift für Soziologie*

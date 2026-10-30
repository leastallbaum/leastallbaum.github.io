---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
{% assign cv_pdf = '/files/CV_Lea_Stallbaum.pdf' | prepend: base_path %}

<p><a class="btn btn--primary" href="{{ cv_pdf }}" download><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i> Download CV (PDF)</a></p>

<object data="{{ cv_pdf }}#view=FitH" type="application/pdf" style="width: 100%; height: 85vh; min-height: 640px;" aria-label="Academic CV of Lea Stallbaum (PDF)">
  <p>Your browser cannot display the PDF here. <a href="{{ cv_pdf }}">Open or download the CV (PDF)</a>.</p>
</object>

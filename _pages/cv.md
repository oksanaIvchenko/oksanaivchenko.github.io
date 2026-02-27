---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**Download:** [PDF version of my CV]({{ base_path }}/files/CV_Oksana_Ivchenko.pdf)

---

## Profile
PhD researcher in Language Sciences specializing in eye-tracking, medical text simplification, and NLP.  
Experienced in designing and analyzing eye-tracking experiments, building annotated corpora, and training transformer-based language models to predict reading behavior.

---

## Education
- **PhD in Language Sciences**, University of Lille (STL — UMR CNRS 8163), *2021–present*  
  *Eye-tracking annotation of a simplified French corpus for automatic prediction of reading behavior* (Supervisor: Natalia Grabar)

- **MA in Language Sciences**, University of Lille, *2019–2021*  
  Thesis: *Simplification of medical texts* (Supervisor: Natalia Grabar)

- **Professional training**, Dr.-Maria-Probst-Schule / Robert-Kümmert-Akademie, Würzburg (Germany), *2017–2018*  
  Training in educational and social support for individuals with disabilities

- **DAAD Scholarship / Academic exchange**, University of Bamberg (Germany), *2012*

- **BA in Philology (German & English)**, Pedagogical University of Kryvyi Rih (Ukraine), *2008–2012*

---

## Research Experience
- **Research Engineer**, CNRS (ANR CLEAR Project), Lille, France, *2022; 2024–2025*  
  Modeling reading behavior in French medical texts using eye-tracking annotated corpora.

- **Research Fellow (STSM)**, University of Galway, Galway, Ireland, *09/2024*  
  Conducted research on enhancing eye-fixation prediction using Large Language Models (LLMs) (MultiplEYE COST Action).

- **Visiting Researcher (funded research stay)**, SFB 1102, Saarland University, Saarbrücken, Germany, *04–07/2024*  
  Conducted research on the processing of medical terminology using eye-tracking data.

---

## Teaching & Supervision (highlights)
- **Co-supervision (Bachelor’s thesis)**, Saarland University (Data Science & AI), *2025*  
  *Classifying Expertise of Readers in the Medical Domain.*

- **Instructor**, University of Lille:  
  Syntax (Bachelor, 24h), 2024  
  Experimental Linguistics (Master 1, 24h), 2023  
  Semantics (Bachelor, 144h), 2022–2024  
  Teaching Assistant: Syntax + Phonetics/Phonology (Bachelor, 18h), 2022–2023

- **German language instructor (A1–C1)**, *2016–present* (2500+ hours)

---

## Continuing Education
- **3rd Summer School on Deep Learning and LLMs for NLP (RANLP 2025)**, Varna, Bulgaria — team ranked 1st place in the LLM application competition.
- **ESSLLI**, Ljubljana & Galway.
- **Methods in Language Sciences (Eye-Tracking & NLP)**, Ghent University.
- **Python for NLP Spring School**, Nancy.
- Online training in Python and neural networks (Udemy).

---

## Skills
- **Programming & Data:** Python (pandas, NumPy, SciPy, scikit-learn, matplotlib), PyTorch, Hugging Face Transformers  
- **Research:** eye-tracking experiment design (Tobii Pro Spectrum), corpus construction, statistical analysis  
- **Tools:** LaTeX, Git, Linux  
- **Languages:** Ukrainian (native), German (C2), English (C2), Russian (C2), French (C1), Dutch (B1)

---

## Peer-reviewed publications
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

## Talks, workshops & posters
<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

## Teaching (full list)
<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

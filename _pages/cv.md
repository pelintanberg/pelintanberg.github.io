---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
<br>

# Education
* **PhD Candidate**, Psychology (Cognitive Neuroscience), *2018 – Present*
* **MA**, Psychology (Cognitive Neuroscience), *2016 – 2018*
  * *Thesis:* Memory Bias for Threat-Related Information in Social Anxiety
* **BSc**, Honours Psychology with Biology Minor, *2012 – 2016*
  * *Thesis:* Attention and Contrast Judgments: Does Attention Alter Appearance?

<br>

# Proficiencies

| Skill                      | Software                                        |
|----------------------------|-------------------------------------------------|
| Programming                | R, Python, HTML, CSS, E-Prime                   |
| Data Collection/Management | Qualtrics, Excel, OSF, Google Suite             |
| Data Analysis              | R, Python, jamovi, JASP, SPSS                   |
| Creative                   | GIMP, Audacity                                  |

<br>

# Publications
  <ol>
    {% assign sorted = site.publications | sort: 'date' | reverse %}
    {% for post in sorted %}
    {% include archive-single-cv.html %}
    {% endfor %}
  </ol>
  <br>

# Talks
  <ol>
    {% assign sorted = site.talks | sort: 'date' | reverse %}
    {% for post in sorted %}
    {% include archive-single-talk-cv.html %}
    {% endfor %}
  </ol>
  <br>

# Teaching
  <ol>
    {% assign sorted = site.teaching | sort: 'date' | reverse %}
    {% for post in sorted %}
    {% include archive-single-cv.html %}
    {% endfor %}
  </ol>
  <br>

# Service and Leadership
* Associate Editor
  * Mind Pad (Canadian Psychological Association)
* Peer Reviewer
  * Personality and Individual Differences
  * Quarterly Journal of Experimental Psychology
  * PLOS One
  * Mind Pad (Canadian Psychological Association)
  * Journal of Gerontology: Psychological Sciences
  * Journal of Experimental Psychology: Learning, Memory, and Cognition
* Conference Organizer
  * University of Waterloo Psychology Discovery Conference 2020
  * Canadian Society for Brain, Behaviour, and Cognitive Science 2019 Conference
* Leadership Positions
  * University of Waterloo Campus Wellness Student Advisory Committee Member
  * Student Representative, Project Review Committee (Graduate Studies Endowment Fund)
  * Secretary, Graduate Association of Students in Psychology
  * Panel Member (Mental Health Experts), President's Advisory Committee on Student Mental Health
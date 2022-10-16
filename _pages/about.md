---
layout: about
title: About
permalink: /
subtitle:

profile:
  align: right
  image: prof_pic.jpeg
  image_circular: true # crops the image to make it circular
  address: >
    <p>34-B-340</p>
    <p>Mekelweg 5</p>
    <p>2628CD Delft, The Netherlands</p>
cv_pdf: cv_eng_kougiatsos.pdf
news: true  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

<p style='text-align: justify;'>Nikos Kougiatsos, MSc is currently a PhD Candidate within the Transport Engineering and Logistics Section of the Maritime and Transport Technology Department. 
He received his diploma in the field of Naval Architecture and Marine Engineering from the National Technical University of Athens (NTUA), Greece in 2020. During his Master studies, he received two scholaships from the American Bureau of Shipping (ABS) as well as the Ch. Papakyriakopoulou scholarship for his excellent academic performance. <p>

{% if site.data.repositories.github_users %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.html username=user %}
  {% endfor %}
</div>
{% endif %}

---

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}

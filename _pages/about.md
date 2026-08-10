---
permalink: /
title: "👋 Hello there, I'm Daniel!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<br>
🎓 I am an incoming graduate student at Stanford University, in the Department of Linguistics. Until Spring 2026, I was at Brown University, where I got my M.S. in Computer Science and had the pleasure of being advised by Professor Ellie Pavlick. Before that, I also received a B.S. in Mathematics - Computer Science and B.A. in Linguistics at Brown University.

🔎 I am interested in the intersection of cognitive science/linguistics and artificial intelligence, with a particular focus on mechanistic interpretability. I believe there is a genuinely profound synergy to be found, but that there is a lot of work to do.

⚠️ I am also involved in AI safety. I am concerned with both societal and existential risks, as I view AI safety issues through the broad lens of automation.

🤝 Feel free to reach out to me about anything. I am always happy to connect!

## Topics of Interest

🔬 Current and Past Research: Mechanistic Interpretability, Semantics and Pragmatics, Language Acquisition, Geometry and Graph Theory

🎈 Other Interests: Embodied Intelligence, Comparative Literature and Philology, Critical Theory, Music Theory


## Publications

{% if site.publication_category %}
{% for category in site.publication_category %}
{% assign title_shown = false %}
{% for post in site.publications reversed %}
{% if post.category != category[0] %}
{% continue %}
{% endif %}
{% unless title_shown %}
<h2>{{ category[1].title }}</h2><hr />
{% assign title_shown = true %}
{% endunless %}
{% include archive-single.html %}
{% endfor %}
{% endfor %}
{% else %}
{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}
{% endif %}

## Selected Experiences
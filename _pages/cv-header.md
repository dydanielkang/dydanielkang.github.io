<style>
  .cv-profile-header { margin-bottom: 1.5em; }
  .cv-profile-header h2 { margin-bottom: 0.1em; }
  .cv-profile-bio { margin: 0.3em 0 0.6em; }
  .cv-profile-contact { list-style: none; margin: 0 0 0.8em; padding: 0; }
  .cv-profile-contact li { display: block; margin-bottom: 0.3em; }
  .cv-profile-links { list-style: none; margin: 0; padding: 0; }
  .cv-profile-links li { display: inline-block; margin: 0 1.2em 0.4em 0; }
</style>

<div class="cv-profile-header">

  <ul class="cv-profile-contact">
    {% if site.author.email %}<li><i class="fas fa-fw fa-envelope"></i> <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></li>{% endif %}
    {% if site.author.phone %}<li><i class="fas fa-fw fa-phone"></i> {{ site.author.phone }}</li>{% endif %}
    {% if site.author.location %}<li><i class="fas fa-fw fa-location-dot"></i> {{ site.author.location }}</li>{% endif %}
  </ul>

  <ul class="cv-profile-links">
    {% if site.author.googlescholar %}<li><a href="{{ site.author.googlescholar }}" target="_blank"><i class="ai ai-google-scholar ai-fw"></i> Google Scholar</a></li>{% endif %}
    {% if site.author.github %}<li><a href="https://github.com/{{ site.author.github }}" target="_blank"><i class="fab fa-fw fa-github"></i> GitHub</a></li>{% endif %}
    {% if site.author.linkedin %}<li><a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank"><i class="fab fa-fw fa-linkedin"></i> LinkedIn</a></li>{% endif %}
  </ul>
</div>
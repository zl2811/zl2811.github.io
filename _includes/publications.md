<h2 id="publications">Publications</h2>

<div class="publications">
  <ol class="bibliography">
    {% for link in site.data.publications.main %}
    <li class="publication-item">
      <article class="pub-card">
        {% if link.image %}
        <div class="pub-media">
          <a class="pub-image-link" href="{{ link.image }}" target="_blank" rel="noopener" aria-label="View full-size figure for {{ link.title }}">
            <img src="{{ link.image }}" alt="{{ link.image_alt | default: link.title }}" class="teaser" loading="lazy" decoding="async">
          </a>
          {% if link.conference_short %}
          <span class="badge">{{ link.conference_short }}</span>
          {% endif %}
        </div>
        {% endif %}

        <div class="pub-content">
          <h3 class="title"><a href="{{ link.pdf }}" target="_blank" rel="noopener noreferrer">{{ link.title }}</a></h3>
          <div class="author">{{ link.authors }}</div>
          <div class="periodical"><em>{{ link.conference }}</em></div>

          <div class="links" aria-label="Resources for {{ link.title }}">
            {% if link.pdf %}
            <a href="{{ link.pdf }}" class="btn" target="_blank" rel="noopener noreferrer">PDF</a>
            {% endif %}
            {% if link.code %}
            <a href="{{ link.code }}" class="btn" target="_blank" rel="noopener noreferrer">Code</a>
            {% endif %}
            {% if link.page %}
            <a href="{{ link.page }}" class="btn" target="_blank" rel="noopener noreferrer">Paper Page</a>
            {% endif %}
            {% if link.bibtex %}
            <a href="{{ link.bibtex }}" class="btn" target="_blank" rel="noopener noreferrer">BibTeX</a>
            {% endif %}
            {% if link.notes %}
            <span class="pub-note">{{ link.notes }}</span>
            {% endif %}
          </div>
        </div>
      </article>
    </li>
    {% endfor %}
  </ol>
</div>

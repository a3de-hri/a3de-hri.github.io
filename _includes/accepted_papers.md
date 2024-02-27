


{% if site.sections.accepted_papers %}

<a class="anchor" id="accepted_papers"></a>
## Accepted Papers

{% for paper in site.data.accepted_papers %}
	{% include accepted_paper.html paper=paper %}
{% endfor %}

{% endif %}

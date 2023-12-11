### HCI, HRI and Robotics
{% for paper in site.data.hci %}
{{ paper.author }} ({{ paper.year }}). {{ paper.title }}. *{{ paper.venue }}*. [Link]({{ paper.link }})
{% endfor %}
<br />
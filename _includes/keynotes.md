{% if site.data.keynotes %} 

### Keynote Speakers
{% for speaker in site.data.keynotes %}
<img src="assets/img/{{ speaker.image }}"> 
#### {{ speaker.name }}
#### _{{ speaker.company }}_
#### **{{ speaker.title }}**
{% endfor %} 
{% endif %}

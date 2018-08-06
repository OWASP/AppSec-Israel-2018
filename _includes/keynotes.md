{% if site.data.keynotes %} 
<br /> 

## Keynote Speakers

  {% for speaker in site.data.keynotes %}
<img src="assets/img/{{ speaker.image }}" style="width:320px"> 
### {{ speaker.name }}
#### <em style="font-style: italic;">{{ speaker.company }}</em>
#### <strong style="font-size:large; font-weight:300; text-decoration:underline;">{{ speaker.title }}</strong>
<br />

  {% endfor %} 

{% endif %}

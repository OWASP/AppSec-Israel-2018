---
---

## Capture The Flag


The conference is around the corner, it is time to sharpen your minds and prepare for the CTF!


This year, professionals from various places, led by Tomer Zait (F5 networks) and Nimrod Levy (Scorpiones) worked hard to create a new, interesting, unique challenge, all in the field of application security.


So, if you feel like giving it a try, make sure to sign up (with a valid email address) in the following link:

[https://owaspil.ctf.today/](https://owaspil.ctf.today/)


The challenge will be opened on Wednesday, September 5th, at 10am.


Good Luck :)

{% if site.data.sponsors.ctf %}
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.ctf %}
	<span class="sponsor community-sponsor">
	  <a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		{% if sponsor.image == %}
		  <span>{{ sponsor.name }}</span>
		{% else %}
		  <img src="assets/img/Sponsors/{{ sponsor.image }}" style="padding: 4px;">
		{% endif %}
	  </a>
	</span>
{% endfor %}
</div>
{% endif %}
---
title: |
  Keynote: Jim Manico - founder of Manicode Security
---
{% assign keynote = site.data.keynotespeakers[0] %}
{% if site.safe %}{% assign baseUrl = "/AppSec-Israel-2018/" %}{% else %}{% assign baseUrl = "/" %}{% endif %}

# Keynote: {{keynote.title}}

{{keynote.description}}

<aside class="keynote">
	<div class="image" style="background-image: url({{baseUrl}}assets/images/keynotes/{{keynote.image}});{{keynote.style}}; background-position: center top;"></div>
	<div>
		<h2>{{keynote.name}}</h2>
		<h3>{{keynote.company}}</h3>
		<p>{{keynote.bio}}</p>
	</div>
</aside>

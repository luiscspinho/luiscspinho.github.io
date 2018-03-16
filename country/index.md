---
layout: page
title: Posts by country
excerpt:
image:
---
<div id="main" role="main" ><br>
<img src="../images/flags/itinerary.png"/> <big>Itineraries</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Itinerary' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/flags/eg.png"/> <big>Egypt</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Egypt' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/flags/la.png"/> <big>Lao</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Lao' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/flags/kh.png"/> <big>Cambodia</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Cambodia' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/flags/vn.png"/> <big>Vietnam</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Vietnam' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/flags/in.png"/> <big>India</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'India' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/flags/mm.png"/> <big>Myanmar</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Myanmar' %}
	<a href="{{ site.url }}{{ post.url }}">
		<div class="image" data-content="{{post.title}}">
			<img src="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
		</div>
	</a>
	{% endif %}
{% endfor %}
</div>
</div>
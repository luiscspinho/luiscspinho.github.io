---
layout: page
title: Posts by country
excerpt:
image:
---
<div id="main" role="main" ><br>
<img src="../images/blank.JPG" alt="" data-echo="../images/flags/itinerary.png"/> <big>Itineraries</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Itinerary' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/blank.JPG" alt="" data-echo="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/blank.JPG" alt="" data-echo="../images/flags/il.png"/> <big>Israel</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Israel' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/blank.JPG" alt="" data-echo="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/blank.JPG" alt="" data-echo="../images/flags/ir.png"/> <big>Iran</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Iran' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/blank.JPG" alt="" data-echo="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/blank.JPG" alt="" data-echo="../images/flags/eg.png"/> <big>Egypt</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Egypt' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/blank.JPG" alt="" data-echo="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/blank.JPG" alt="" data-echo="../images/flags/la.png"/> <big>Lao</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Lao' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/blank.JPG" alt="" data-echo="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/blank.JPG" alt="" data-echo="../images/flags/kh.png"/> <big>Cambodia</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Cambodia' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/blank.JPG" alt="" data-echo="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/blank.JPG" alt="" data-echo="../images/flags/vn.png"/> <big>Vietnam</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Vietnam' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/blank.JPG" alt="" data-echo="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/blank.JPG" alt="" data-echo="../images/flags/in.png"/> <big>India</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'India' %}
		<a href="{{ site.url }}{{ post.url }}">
			<div class="image" data-content="{{post.title}}">
				<img src="../images/blank.JPG" alt="" data-echo="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
			</div>
		</a>
	{% endif %}
{% endfor %}
</div>
<br><br>

<img src="../images/blank.JPG" alt="" data-echo="../images/flags/mm.png"/> <big>Myanmar</big><br><br>
<div>
{% for post in site.posts %}
	{% if post.tags contains 'Myanmar' %}
	<a href="{{ site.url }}{{ post.url }}">
		<div class="image" data-content="{{post.title}}">
			<img src="../images/blank.JPG" alt="" data-echo="../images/{{post.image.feature}}" height="250" width="250" style="height:141px;margin-bottom: 4px"/>
		</div>
	</a>
	{% endif %}
{% endfor %}
</div>
</div>
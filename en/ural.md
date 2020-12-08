---
layout: page
title: ural / en
permalink: /en/ural/

text-title-nav: Ivan Kovylyaev
background: http://photo.uralphoto.tk/photo/01155.jpg
lang: en
text-title: video
text-description: 
---
<h3 class="h1 pb-1">ural</h3>
<div class='row' style=''>
	{% for post in site.categories.ural %}
	<div class='col-12 col-sm-6 col-md-4 col-lg-4 col-xl-4'>
		<iframe width="100%" height="300px" src="{{ post.content }}" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	</div>
	{% endfor %}
</div>
<style type="text/css">
  .port{width: 100%;border-radius: 00px; display: inline-block;} 
</style>

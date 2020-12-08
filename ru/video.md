---
layout: page
title: видео / ru
permalink: /ru/video/

text-title-nav: Иван Ковыляев
background: http://photo.uralphoto.tk/photo/01155.jpg
lang: ru
text-title: видео
text-description: 
---
<h3 class="h1 pb-1">видео</h3>
<div class='row'>
	{% for post in site.categories.video %}
	<div class='col-12 col-sm-6 col-md-4 col-lg-4 col-xl-4'>
		<iframe width="100%" height="300px" src="{{ post.content }}" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	</div>
	{% endfor %}
</div>
<style type="text/css">
  .port{width: 100%;border-radius: 00px; display: inline-block;} 
</style>

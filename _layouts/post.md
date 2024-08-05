---
layout: default
---
<main class="page">
	<nav class="navbar navbar-expand-lg navbar-dark">
	  <a class="navbar-brand" href="{{ site.url }}"><img src="{{ site.url }}/img/digital_light.svg" alt="{{ page.text-title-nav }}" style="height: 80px;"></a>
	  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
	    <span class="navbar-toggler-icon"></span>
	  </button>
		<div class="collapse navbar-expand navbar-collapse" id="navbarSupportedContent">
	    <ul class="navbar-nav mr-auto navBox" style="position: absolute; right: 40px">
			{% for link in site.data.navigation %}
				{% assign class = "" %}
				{% if link.lang == page.lang %}
					{% if link.link == page.url %}
						{% assign class = class | append: " active" %}
					{% endif %}
					<li class="nav-item">
						<a href="{{ link.link }}" class="{{ class }} nav-link">{{ link.name }}</a>
					</li>
				{% endif%}
			{% endfor %}
	      <li style="width: 40px;"></li>
	      <li class="nav-item">
	        <a class="nav-link" href="{{ site.url }}/">ru</a>
	      </li>
	      <li class="nav-item">
	        <a class="nav-link" href="{{ site.url }}/en">en</a>
	      </li>
	    </ul>
	  </div>
	</nav>
</main>
<div class="main-body container-fluid" style="padding: 0 40px">
{{content}}
</div>
<footer class="row">
	<div class="col-6 p-0 m-0">
		&copyvideo.ikovylyaev.com 2020<br>
		<a href='{{site.url}}/terms'>terms of use</a> | <a href='{{site.url}}/policy'>privacy policy</a>
	</div>
	<div class="col-6 p-0 m-0" style='text-align: right'>
		<ul class="nav social-links">
		  <li class="nav-item">
		    <a class="nav-link" href="http://vk.com/ikovylyaev"><i class="fab fa-vk"></i></a>
		   </li>
		   <li class="nav-item">
		    <a class="nav-link" href="http://instagram.com/ikovylyaev"><i class="fab fa-instagram"></i></a>
		   </li>
		   <li class="nav-item">
	            <a class="nav-link" style="color: #fff;" href="https://www.youtube.com/channel/UCf9GOVc0qKKPB-Ee3LfH_uw"><i class="fab fa-youtube"></i></a>
	           </li>
		   <li class="nav-item">
		    <a class="nav-link" href="http://500px.com/azimytfoto"><i class="fab fa-500px"></i></a>
		   </li>
		   <li class="nav-item">
		    <a class="nav-link" href="https://www.behance.net/ikovylyaev"><i class="fab fa-behance"></i></a>
		   </li>
		   <li class="nav-item">
		    <a class="nav-link" href="http://github.com/ikovylyaev"><i class="fab fa-github"></i></a>
		   </li>
		</ul>
	</div>

</footer>

---
layout: default
---
<div class='container mt-5'>
	<nav class="navbar navbar-expand-lg navbar-dark" style='padding-bottom: 40px;'>
	  <a class="navbar-brand" href="{{ site.url }}">
	  <img src="{{ site.url }}/img/digital_light.svg" alt="{{ page.text-title-nav }}" style="height: 60px;"></a>
	  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
	    <span class="navbar-toggler-icon"></span>
	  </button>
		<div class="collapse navbar-expand navbar-collapse" id="navbarSupportedContent">
	    <ul class="navbar-nav mr-auto navBox" style="position: absolute; right: 0px">
			<li class="nav-item mr-4">
				<a href="http://ikovylyaev.com" class="nav-link">дизайн</a>
			</li>
	      	<li class="nav-item mr-4">
				<a href="http://video.ikovylyaev.com" class="active nav-link">фото и видео</a>
			</li>
			<li class="nav-item">
				<a href="http://nature.ikovylyaev.com" class="nav-link">урал</a>
			</li>
	    </ul>
	  </div>
	</nav>
	<section class='row'>
	  {{ content }}
    </section>
<footer class="row" style="margin-top: 200px;">
	<div class="col-6 m-0">
		&copyikovylyaev.com 2021<br>
		<a href='{{site.url}}/terms'>terms of use</a> | <a href='{{site.url}}/policy'>privacy policy</a>
	</div>
	<div class="col-6 m-0" style='text-align: right'>
		<ul class="nav social-links">
		  <li class="nav-item">
		    <a class="nav-link" href="http://vk.com/ikovylyaev"><i class="fab fa-vk"></i></a>
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

</main>

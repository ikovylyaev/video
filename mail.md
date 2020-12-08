---
layout: page
title: Thanks for your letter
permalink: /mail/
background: http://ikovylyaev.com/img/back.jpg
lang: en
text-title: thanks for your letter
text-description: i'll answear your letter when i will have a free time
---



<style type="text/css">
	body:before{
		background: url({{ site.url }}/img/00150.jpg); 
		background-position: center; 
		-webkit-background-size: cover;
		-o-background-size: cover;
		background-size: cover;
		position: absolute;
		width: 100%;
		height: 100%; 
		z-index: -2;
		top: 0px;
		left: 0px;
		content: "";
	}
	body:after{
		position: absolute;
		background: rgba(21,21,21,0.3);
		width: 100%;
		height: 100%; 
		z-index: -1;
		top: 0px;
		left: 0px;
		content: "";
	}
	footer{
		position: fixed;
		bottom: 40px;
		width: calc(100vw - 80px);
		right: 40px;
		padding: 0px;
		margin: 0px;
	}
	
</style>

<div style="position: absolute; top: 50%; left: 50%; transform: translateX(-50%) translateY(-50%); text-align: center;">
	<h1>{{ page.text-title }}</h1>
	<p>{{ page.text-description }}</p>
	<p class='row text-center'><a href="{{site.url}}/" class="btn btn-light col-6 offset-3 ">home</a></p>
</div>

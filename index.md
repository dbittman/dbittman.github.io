---
layout: default
title: dbittman
description: This is my site. Welcome.
keywords: github pages, Jekyll, foundation 5
---

<div class="row">
<div class="large-12 columns middle text-center">
</div>
</div>

<div class="row">
	<div class="large-3 columns panel">
		<div class="row">
			<h4>About Me</h4>
			<p>A 22 year old systems programmer who loves low-level code, hacking and breaking things,
			and re-inventing the wheel.</p>
			<p>Download my <a href="download/resume.pdf">resum&#233;</a></p>
			<div class="row text-center">
			<a href="http://facebook.com/daniel.a.bittman" target="_blank">      <img src="icons/facebook.png"   style="background-color:#3B5998;"></a>
			<a href="http://github.com/dbittman" target="_blank">                <img src="icons/github.png"     style="background-color:#4183C4;"></a>
			<a href="http://twitter.com/danielbittman" target="_blank">          <img src="icons/twitter.png"     style="background-color:#FFFFFF;"></a>
			<a href="https://www.linkedin.com/in/danielbittman" target="_blank"> <img src="icons/linkedin.png"   style="background-color:#007FB1;"></a>
			<a href="mailto:danielbittman1@gmail.com" target="_blank">           <img src="icons/gmail.png"      style="background-color:#DD4B39;"></a>
			<a href="http://google.com/+DanielBittman" target="_blank">          <img src="icons/googleplus.png" style="background-color:#D14836;"></a>
			<a href="http://www.youtube.com/user/danielbittman1" target="_blank"><img src="icons/youtube.png"    style="background-color:#CD332D;"></a>
			</div>
		</div>
		<hr>
		<div class="row text-center">
		<h4><a href="physics/index.html">Physics Stuff</a></h4>
		</div>
		<hr>
		<div class="row">
			<h4>Projects</h4>

			<ul>
				<li><a href="seaos/index.html">SeaOS Kernel and Operating System</a></li>
				<li><a href="basil/index.html">BASIL Assembly Language</a></li>
				<li><a href="http://github.com/dbittman/hanabi-ai">AI for the Hanabi Card Game</a></li>
			</ul>
		</div>
	</div>
	<div class="large-9 columns">
	<div class="post-index">
			{% for post in site.posts %}
				<br>
				<h4 style="display: inline;"><a href='{{ post.url }}'>{{ post.title }}</a></h4>
				<span>{{ post.date | date: "%B %-d, %Y" }}</span> 
				<p style="padding: 0px 4px;">{{ post.excerpt }}</p>
			{% endfor %}
	</div>
	</div>
</div>


<div class="row"> 
</div>

<div class="row">
</div>


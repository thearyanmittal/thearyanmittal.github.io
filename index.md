---
layout: home
title: Home
---

<div id="intro-wrapper" class="l-text">
	<div id="intro-title-wrapper">
		<div id="intro-title-text-wrapper">
			<h1 id="intro-title">Hi, I'm <br> Aryan Mittal</h1>
			<div id="intro-subtitle">I'm a student at Georgia Tech.</div>
			<div id="intro-title-socials">
				{% for link in site.data.social-links %}
					{% if link.on-homepage == true %}
						{% include social-link.html link=link %}
					{% endif %}
				{% endfor %}
			</div>
		</div>
		<div id="intro-image-wrapper">
			<!-- <img id="intro-image" src="/images/msft.jpg"></div> -->
			<img id="intro-image" src="/images/casual.jpg">
		</div>
	</div>
	<div id="everything-else" class="l-middle">
		<a href="/resume.pdf"><div><i class="fa fa-portrait icon icon-right-space"></i>Resume</div></a>
		<a href="/projects"><div><i class="fas fa-laptop-code icon icon-right-space"></i>Projects</div></a>
		<a href="/lrmc-rankings"><div><i class="fas fa-football-ball icon icon-right-space"></i>LRMC Rankings</div></a>
	</div>
	<hr class="l-middle home-hr">
	<div>
		Hi! I’m Aryan, a Machine Learning graduate student at <img class="intro-logo" style="width: 24px; padding-bottom: 3px;" src="/images/gt.svg"> Georgia Tech, an incoming Risk Technology Intern at <img class="intro-logo" style="width: 20px; padding-bottom: 3px;" src="/images/millennium.svg"> Millennium, and a former Software Engineering Intern at <img class="intro-logo" style="width: 18px; padding-bottom: 3px;" src="/images/microsoft.svg"> Microsoft and <img class="intro-logo" style="width: 15px; padding-bottom: 3px;" src="/images/ups.svg"> UPS.
	</div>
	<div style="height: 1rem"></div>
	<div>
		I’m interested in machine learning, statistics, optimization, and their application in sports analytics and quantitative finance.
	</div>
	<div style="height: 1rem"></div>
	<div>
		In my free time, I am an avid Atlanta sports fan. When I’m not busy cheering on my <img class="intro-logo" style="width: 36px; padding-bottom: 3px;" src="/images/braves.svg"> Braves, <img class="intro-logo" style="width: 22px; padding-bottom: 3px;" src="/images/falcons.svg"> Falcons, or <img class="intro-logo" style="width: 20px; padding-bottom: 7px;" src="/images/buzz.svg"> Yellow Jackets, you can probably find me playing a board game or watching a movie.
	</div>
</div>

<hr class="l-middle home-hr">

<h2 class="feature-title">Featured <a href="/projects">Projects</a></h2>

<div class="cover-wrapper cover-wrapper-3-col l-page">
	{% assign sortedPublications = site.categories.projects | sort: 'feature-order' %}
	{% for feature in sortedPublications %}
		{% if feature.featured == true %}
			{% include feature.html feature=feature %}
		{% endif %}
	{% endfor %}
</div>

<br>

[gt]: https://www.gatech.edu "Georgia Tech"
[math]: https://math.gatech.edu/ "Georgia Tech School of Mathematics"
[coc]: https://www.cc.gatech.edu "Georgia Tech College of Computing"
---
permalink: r/basic-charts/
title: R Graphing Library Plotly Basic Charts
description: Plotly's R graphing library makes interactive, publication-quality graphs online. Examples of how to make basic charts.
name: More Basic Charts
layout: langindex
language: r
display_as: basic
has_thumbnail: true
thumbnail: thumbnail/mixed.jpg
page_type: example_index
order: 20
---


<header class="--welcome">
	<div class="--welcome-body">
		<!--div.--wrap-inner-->
		<div class="--title">
			<div class="--category-img"><img src="https://plot.ly/gh-pages/documentation/static/images/r-small.png" alt=""></div>
			<div class="--body">
				<h1>Plotly R Library Basic Charts</h1>
				<p>{{page.description}}</p>
			</div>
		</div>
	</div>
</header>

		{% assign languagelistimg = site.posts | where:"language","r" | where:"display_as","basic" | where:"has_thumbnail",true | where: "layout","base" | sort: "order" %}
        {% include documentation_eg.html %}

---
layout: post
title: "도미노피자 챗봇 도미챗"
date: 2018-07-01
categories:
  - App
  - Web
  - GraphicDesign
description: test,test,test 
image: https://leemina458.github.io/images/pages/201807_domino.png
image-sm: https://leemina458.github.io/images/thumbs/201807_domino.png
link : http://naver.com
---

<ul class="inform">
	<li class="preview__date" itemprop="datePublished" datetime="{{ page.date | date_to_xmlschema }}">- 작업기간 : {{ page.date | date: "%Y년 %-m월부터 약 %-d개월 이내" }}</li>
	<li class="preview__category" itemprop="description">- 카테고리 :
		{% for categories in page.categories %}
           <a href="/category/{{ categories }}/"># {{ categories }}</a>     
      	{% endfor %}</li>
	<li class="preview__excerpt" itemprop="description">- 작업 내용 : </li>
	<!-- <li class="preview__link" itemprop="link">- 더보기 : <a href="{{ page.link }}" target="_blank">{{ page.link }}</a></li> -->
</ul>



![_config.yml]({{ page.image }})

---
layout: post
title: "에어릭스 집진기 모니터링 시스템"
date: 2017-01-06
categories:
  - Web
  - HTML,CSS
  - GraphicDesign
image: https://leemina458.github.io/images/pages/20170106_aerix_thingarx.png
image-sm: https://leemina458.github.io/images/thumbs/20170106_aerix_thingarx.png
---

<ul class="inform">
	<li class="preview__date" itemprop="datePublished" datetime="{{ page.date | date_to_xmlschema }}">- 작업기간 : {{ page.date | date: "%Y년 %-m월부터 약 %-d개월 이내" }}</li>
	<li class="preview__category" itemprop="description">- 카테고리 :
		{% for categories in page.categories %}
           <a href="/category/{{ categories }}/"># {{ categories }}</a>     
      	{% endfor %}</li>
	<li class="preview__role" itemprop="role">- 역할(참여율) : 디자인(100%)</li>
	<li class="preview__excerpt" itemprop="description">- 작업 내용 : 산업용 집진기를 센서별로 관제하고 원격 제어할 수 있는 스마트 IoT 시스템입니다.</li>
	<!-- <li class="preview__link" itemprop="link">- 더보기 : <a href="{{ page.link }}" target="_blank">{{ page.link }}</a></li> -->
</ul>


![_config.yml]({{ page.image }})
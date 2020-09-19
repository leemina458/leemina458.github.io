---
layout: post
title: "금형센터 생산관제 시스템"
date: 2018-01-03
categories:
  - Design
image: https://leemina458.github.io/images/pages/20180103_sf_dashboard.png
image-sm: https://leemina458.github.io/images/thumbs/20180103_sf_dashboard.png
---

<ul class="inform">
	<li class="preview__date" itemprop="datePublished" datetime="{{ page.date | date_to_xmlschema }}">- 작업기간 : {{ page.date | date: "%Y년 %-m월부터 약 %-d개월 이내" }}</li>
	<li class="preview__category" itemprop="description">- 카테고리 :
		{% for categories in page.categories %}
           <a href="/category/{{ categories }}/"># {{ categories }}</a>     
      	{% endfor %}</li>
	<li class="preview__role" itemprop="role">- 역할(참여율) : 디자인(90%)</li>
	<li class="preview__excerpt" itemprop="description">- 작업 내용 : 금형공장의 생산·설비 가동 현황 등을 모니터링하고 이력을 관리하는 시스템입니다.</li>
	<!-- <li class="preview__link" itemprop="link">- 더보기 : <a href="{{ page.link }}" target="_blank">{{ page.link }}</a></li> -->
</ul>


![_config.yml]({{ page.image }})
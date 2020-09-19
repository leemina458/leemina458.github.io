---
layout: post
title: "홈 IoT"
date: 2016-06-03
categories:
  - Design
image: https://leemina458.github.io/images/pages/20160703_chungho_IoT.png
image-sm: https://leemina458.github.io/images/thumbs/20160703_chungho_IoT.png
---

<ul class="inform">
	<li class="preview__date" itemprop="datePublished" datetime="{{ page.date | date_to_xmlschema }}">- 작업기간 : {{ page.date | date: "%Y년 %-m월부터 약 %-d개월 이내" }}</li>
	<li class="preview__category" itemprop="description">- 카테고리 :
		{% for categories in page.categories %}
           <a href="/category/{{ categories }}/"># {{ categories }}</a>     
      	{% endfor %}</li>
	<li class="preview__role" itemprop="role">- 역할(참여율) : 디자인(100%)</li>
	<li class="preview__excerpt" itemprop="description">- 작업 내용 : 스마트정수기를 필두로 IoT 가전제품을 실시간 모니터링 및 제어하는 서비스입니다. iOS/Android 각각의 네이티브앱으로 개발하였습니다.</li>
	<!-- <li class="preview__link" itemprop="link">- 더보기 : <a href="{{ page.link }}" target="_blank">{{ page.link }}</a></li> -->
</ul>


![_config.yml]({{ page.image }})
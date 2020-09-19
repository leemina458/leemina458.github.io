---
layout: post
title: "챗봇 주문관리 서비스"
date: 2018-07-01
categories:
  - Design
image: https://leemina458.github.io/images/pages/20180701_dom_chatbot.png
image-sm: https://leemina458.github.io/images/thumbs/20180701_dom_chatbot.png
link : https://domichat.dominos.co.kr/html/Chatting.html?_no=2945
---

<ul class="inform">
	<li class="preview__date" itemprop="datePublished" datetime="{{ page.date | date_to_xmlschema }}">- 작업기간 : {{ page.date | date: "%Y년 %-m월부터 약 %-d개월 이내" }}</li>
	<li class="preview__category" itemprop="catetory">- 카테고리 :
		{% for categories in page.categories %}
           <a href="/category/{{ categories }}/">#{{ categories }}</a>     
      	{% endfor %}</li>
    <li class="preview__role" itemprop="role">- 역할(참여율) : 디자인(100%)</li>
    <li class="preview__excerpt" itemprop="description">- 작업 내용 : 챗봇 기능을 접목시킨 자동화 주문서비스입니다. 모바일웹/하이브리드앱에서 이용할 수 있습니다.</li> 
    <li class="preview__link" itemprop="link">- 더보기 : <a href="{{ page.link }}" target="_blank">서비스 바로가기</a></li>
</ul>

![_config.yml]({{ page.image }})

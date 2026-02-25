---
layout: default
title: home
---

# 환영이요
- 이곳은 jekyll로 만든 블로그 입니다

  > 마쿠다운 펴하다


  # 최근 포스터
{% for post in site.posts %}
- [{{ _post.title }}] ({{ post.url }}) - {{ post.data | data: "%Y년 %n월 %d일" }}
{% endfor %}

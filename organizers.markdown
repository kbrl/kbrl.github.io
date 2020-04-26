---
layout: page
title: Organizers
permalink: /organizers/
---

* [Asim Munawar](https://researcher.watson.ibm.com/researcher/view.php?person=jp-ASIM) (IBM Research)
* [Kartik Talamadupula](http://www.ktalamad.com/) (IBM Research) 
* [Marc-Alexandre Côté](https://www.microsoft.com/en-us/research/people/macote/) (Microsoft Research, Montréal)
* [Xingdi (Eric) Yuan](https://xingdi-eric-yuan.github.io/) (Microsoft Research, Montréal)
* [Hiroki Mori](https://researchmap.jp/hirokimori1981/?lang=english) (Waseda University)



# Organizers

<!-- prettier-ignore -->
<div class="container">
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endfor %}
  </div>
</div>

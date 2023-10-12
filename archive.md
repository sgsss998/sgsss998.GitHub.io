---
layout: page
title: "买前须知"
description: "及文章汇总"
header-img: "img/orange.jpg"
---


<ul class="listing">
{% for post in site.posts %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  {% if year != y %}
    {% assign year = y %}
    <li class="listing-seperator">{{ y }}</li>
  {% endif %}
  <li class="listing-item">
    <time datetime="{{ post.date | date:"%Y-%m-%d" }}">{{ post.date | date:"%Y-%m-%d" }}</time>
    <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>


买前买后须知，共享死绑被顶免费调剂处理。
死绑均会偶尔被顶，如购买谋黄忠被顶，会提供新的谋黄忠账号给您使用，相似度百分之90！实时解决顶号风险。
如调剂号查到自己的主号已经黑了无人登录，切回去重新耍。
回收为转售后4到6折，首月7折，玩儿到腻，也可折价换购，按回收价多退少补，关于市场从来都是下降趋势，调剂包赔均为一年制365天。
信誉问题0差评，回收转手后回收也可自行转手，如购买包赔，转手后自动失效！
不定期抽奖月卡，天子令，商道酬信。
简洁明了，事儿妈勿扰！
购买联系微信：19840175476

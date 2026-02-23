---
title: "MM Group - Team"
layout: gridlay
excerpt: "MM Group: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 **We are  looking for new PhD students and Master students to join the team!**


Jump to [staff](#staff), [phd students](#phd-students), [master students](#master-students), [alumni](#alumni).

## Staff
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: {{ member.email }}</i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Phd Students
{% assign number_printed = 0 %}
{% for member in site.data.phdstudents %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}



## Master Students 
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


## Alumni

|**Name**|**Year of Graduation**||||||||**Employer**|
| -- | :--: |--|--|--|--|--|--|--|--|
|Boyuan Zhang|2025||||||||Huawei|
|Deng Li|2025||||||||Jingdong|
|Xu Chen|2025||||||||Postdoctoral Fellow at Harbin Institute of Technology (Shenzhen Campus)|
|Runhua Jiang|2025||||||||Xiamen Municipal Government|
|Yikang Wei|2024||||||||HiThink Research|
| Tuo Li | 2024 |||||||| Baidu |
| Shibin Liu  | 2024 |||||||| King Base |
| Yucheng Shi |          2023          |      |      |      |      |      |      |      | Zhengzhou University |
| Kunhong Wu | 2023 |||||||| China Resources Bank of Zhuhai |
| Jian Liu | 2023 |||||||| China Mobile Communications Corporation |
| Fei Zhou | 2023 |||||||| Meituan |
| Jianqiao An | 2022 |||||||| Baidu |
| Xinrui Li | 2022 |||||||| Baidu |
| Yuandu Lai | 2022 |||||||| Huawei |
| Fan Jia | 2022 |||||||| Megvii |
| Liang Li | 2022 |||||||| The 54th Research Institute of China Electronics Technology Group Corporation |
| Aming Wu | 2021 |||||||| Xidian University |
| Xuanwei Chen | 2021 |||||||| State Grid Zhejiang Electric Power Corporation |
| Pin Jiang | 2021 |||||||| Tencent |
| Run Li | 2021 |||||||| No.713 Research Institute of China Shipbuilding Industry Corporation |
| Haitao Zhang | 2021 |||||||| Baidu |
| Xiaomeng Song | 2020 |||||||| ByteDance |
| Qiang Wang | 2020 |||||||| Bank of China |
| Huiyun Wang | 2019 |||||||| Tianjin Urban Planning and Design Research Institute |
| Bo Wang | 2019 |||||||| Beijing Jiaotong University |
| Kun Gao | 2018 |||||||| Puyang Commission for Discipline Inspection |
| Yuanyuan Ge | 2018 |||||||| FOXCONN |
| Nan Song | 2018 |||||||| No.707 Research Institute of China Shipbuilding Industry Corporation |
| Youjiang Xu | 2018 |||||||| Douyin |
| Ziwei Yang | 2018 |||||||| HIKVISION |
| Guang Li | 2017 |||||||| Xiaomi |
| Shubo Ma | 2017 |||||||| China Construction Bank |
| Chengyue Zhang | 2017 |||||||| Aibee |
| Shichao Zhao | 2017 |||||||| Aibee |
| Baixiang Fan | 2016 |||||||| State Grid Tianjin Electric Power Corporation |
| Yanbin Liu | 2016 |||||||| University of Technology Sydney |
| Qiang Guo | 2016 |||||||| Guotai Junan Securities |
| Jianguang Zhang | 2016 |||||||| HengShui University |




















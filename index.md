---
layout: default

stories:
- hed: 'Targeted: Pasco’s sheriff created a futuristic program to stop crime before it happens. It monitors and harasses families across the county.'
  url: 'https://projects.tampabay.com/projects/2020/investigations/police-pasco-sheriff-targeted/intelligence-led-policing/'
  img: 'targeted.jpg'
  class: big
- hed: 'Pasco’s sheriff uses grades and abuse histories to label schoolchildren potential criminals. The kids and their parents don’t know.'
  url: 'https://projects.tampabay.com/projects/2020/investigations/police-pasco-sheriff-targeted/school-data/'
  img: 'pascoschool.jpg'
  class: half
- hed: 'The man behind the machine: Pasco Sheriff Chris Nocco built a controversial data-driven approach to policing. He also built a wide circle of powerful friends who don’t question his tactics.'
  url: 'https://projects.tampabay.com/projects/2020/investigations/police-pasco-sheriff-targeted/chris-nocco/'
  img: 'nocco.jpg'
  class: half
- hed: 'Heartbroken: Johns Hopkins promised to elevate All Children’s Heart Institute. Then patients started to die at an alarming rate.'
  url: 'http://www.tampabay.com/projects/2018/investigations/heartbroken/all-childrens-heart-institute/'
  img: 'leslie.jpg'
  class: big
- hed: 'A baby left All Children’s with a needle in her heart'
  url: 'http://www.tampabay.com/investigations/2018/04/20/a-baby-left-all-childrens-with-a-needle-in-her-heart/'
  img: 'ach.jpg'
- hed: 'Hellfire from above: Tampa Electric knew the procedure was dangerous. It sent workers in anyway.'
  url: 'http://www.tampabay.com/projects/2017/investigations/tampa-electric/big-bend-hellfire-from-above/'
  img: 'hellfire.jpg'
  class: half
- hed: 'Tampa Electric accounts for nearly half of Florida power plant deaths'
  url: 'http://www.tampabay.com/news/publicsafety/teco-accounts-for-nearly-half-of-florida-power-plant-deaths-data-shows/2329687'
  img: 'teco.jpg'
  class: half
- hed: 'In Harm’s Way: Gun injuries and deaths among Florida kids have spiked. One child is shot every 17 hours.'
  url: 'http://www.tampabay.com/projects/2017/special-report/florida-guns-children-deaths-harms-way/'
  img: 'harms.jpg'
- hed: 'Worthy of Survival: Angel Santiago survived the massacre at the Pulse nightclub. To feel worthy of survival, he would need to make something of his life.'
  url: 'http://www.tampabay.com/projects/2016/features/pulse-shooting-survivor-angel-santiago-recovery/'
  img: 'pulse.jpg'
  class: big
---

## Selected work

<div class="selected">
{% for story in page.stories %}

<a class="story{% if story.class %} {{story.class}}{% endif %}" href="{{story.url}}">
  <div class="img" style="background-image:url('img/{{story.img}}')"></div>
  <p class="hed">{{story.hed}}</p>
</a>

{% endfor %}
</div>

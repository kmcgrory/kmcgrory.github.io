---
layout: default

stories:
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

---

## About

<img class="right" src="img/mcgrory.jpg"/>

Kathleen McGrory is the deputy investigations editor and an investigative reporter at the [Tampa Bay Times](http://tampabay.com). Her series on a Johns Hopkins children’s hospital unearthed an alarming rate of patient fatalities and led to the resignation of six top hospital officials. It was a finalist for the 2019 Pulitzer Prize for Investigative Reporting and won the George Polk Award for Local Reporting and an IRE award.

Before joining the Times in 2015, Kathleen spent seven years as a metro reporter for the [Miami Herald](http://miamiherald.com) and two years as a government reporter in the Tampa Bay Times/Miami Herald Tallahassee Bureau. She speaks Spanish and holds degrees from the Columbia University Graduate School of Journalism and Hamilton College in Clinton, N.Y. 

Email her at [kmcgrory@tampabay.com](mailto:kmcgrory@tampabay.com). Follow her on Twitter at [@kmcgrory](http://twitter.com/kmcgrory).



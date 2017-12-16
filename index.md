---
layout: default

stories:
- hed: 'Hellfire from above: Tampa Electric knew the procedure was dangerous. It sent workers in anyway.'
  url: 'http://www.tampabay.com/projects/2017/investigations/tampa-electric/big-bend-hellfire-from-above/'
  img: 'hellfire.jpg'
- hed: 'Tampa Electric accounts for nearly half of Florida power plant deaths'
  url: 'http://www.tampabay.com/news/publicsafety/teco-accounts-for-nearly-half-of-florida-power-plant-deaths-data-shows/2329687'
  img: 'teco.jpg'
- hed: 'In Harm’s Way: Gun injuries and deaths among Florida kids have spiked. One child is shot every 17 hours.'
  url: 'http://www.tampabay.com/projects/2017/special-report/florida-guns-children-deaths-harms-way/'
  img: 'harms.jpg'
- hed: 'Worthy of Survival: Angel Santiago survived the massacre at the Pulse nightclub. To feel worthy of survival, he would need to make something of his life.'
  url: 'http://www.tampabay.com/projects/2016/features/pulse-shooting-survivor-angel-santiago-recovery/'
  img: 'pulse.jpg'
- hed: 'Criticized for HIV spike, Florida takes hundreds of cases off the books'
  url: 'http://www.tampabay.com/news/health/criticized-for-hiv-spike-florida-takes-hundreds-of-cases-off-the-books/2270876'
  img: 'hiv.jpg'
- hed: 'Field of Dakota Dreams: A group of football players from Miami ventured to rural North Dakota in pursuit of a college education — and a new life.'
  url: 'http://media.miamiherald.com/static/media/projects/2013/field-of-dakota-dreams/'
  img: 'dakota.jpg'
---

# Kathleen McGrory

Kathleen McGrory is a reporter on the [Tampa Bay Times](http://tampabay.com) investigations team. She was previously the newspaper’s health and medicine reporter. Before joining the Times in 2015, Kathleen spent seven years as a metro reporter for the [Miami Herald](http://miamiherald.com) and two years as a government reporter in the Tampa Bay Times/Miami Herald Tallahassee Bureau. 

She speaks Spanish and holds degrees from the Columbia University Graduate School of Journalism and Hamilton College in Clinton, N.Y. 

Email her at [kmcgrory@tampabay.com](mailto:kmcgrory@tampabay.com). Follow her on Twitter at [@kmcgrory](http://twitter.com/kmcgrory).

---

## Selected work

{% for story in page.stories %}
- ![ ](img/{{story.img}}) [{{story.hed}}]({{story.url}})
{% endfor %}
---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_mlss-skoltech.jpg
widget1:
  title: "Machine Learning Summer School"
  url: 'http://mlss.cc'
  image: banner_mlss.jpg
  text: 'The Machine Learning Summer School (MLSS) will be held at Skoltech in Moscow, Russia, from Aug. 26 to Sep. 6, 2019. 
  The MLSS presents topics at the core of modern machine learning, from fundamentals to state-of-the-art practice.  
  It is offered to PhD students, but also to researchers and professionals. 
  Its speakers are leading academic and industry experts.' 
widget2:
  title: "Skoltech"
  url: 'http://www.skoltech.ru'
  image: banner_skoltech.jpg
  text: 'Skoltech is a leading research university founded by a group of nine Russian institutions and organizations in collaboration with the Massachusetts Institute of Technology (MIT). 
  Among others, it aims at the conduction of cross-cutting interdisciplinary research driven by modern applications in the fields of computational and data sciences.'
widget3:
  title: "Moscow"
  url: '/venue/'
  image: banner_moscow.jpg
  text: 'Moscow is the capital of Russia and one of the largest cities in Europe. A historic town with modern infrastructure easily reachable from all major cities. 
  Located on the river Moskva, in the west of the country, its landmarks include the Red Square, the Bolshoi Theatre, the Gorky Park, VDNH and the Tretyakov gallery.'

#  
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /application
  text: Apply now ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

{% include alert info='Important Dates' %}
* Mon, 4 March 2019: Application system opens.
* Fri, 5 April 2019 23:59 Pacific Time: Deadline for applications.
* Fri, 12 April 2019 23:59 Pacific Time: Deadline for submission of reference letters.
* Mon, 6 May 2019: Notification of acceptance.
* Fri, 17 May 2019: Registration fees due.
* Mon, 26 August to Fri, 6 September 2019: MLSS takes place.
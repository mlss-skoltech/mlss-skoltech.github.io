---
layout: profiles
title: "Speakers & Topics"
subheadline: "Academics and practitioners"
teaser: "Following experts will be speaking at the school"
permalink: "/speakers-topics/"
header: no
image:
    title: header_speakers.jpg
    caption: Speakers at MLSS
  
authors:
 - name: Michel Besserve
   id: michel-besserve
   topic: MRI
   institution-logo: /images/logos/mpi_logo-124x100.png
 - name: Ulrich Bauer
   topic: Topological Data Analysis
   institution-logo: /images/logos/tum_logo-308x100.png
 - name: Michael Bronstein
   id: michael-bronstein
   topic: Graph Neural Networks
   institution-logo: /images/logos/imperial_logo-380x100.png
   pic: /images/speakers/speaker_bronstein_1173x433.png
   bio: >
    Michael Bronstein (PhD 2007, Technion, Israel) is a professor at Imperial College London, 
    where he holds the Chair in Machine Learning and Pattern Recognition and Royal Society Wolfson Merit Award. 
    He holds/has held visiting appointments at Stanford, Harvard, MIT, and TUM. 
    Michael's main research interest is in theoretical and computational methods for geometric data analysis. 
    He is a Fellow of IEEE and IAPR, ACM Distinguished Speaker, and World Economic Forum Young Scientist. 
    He is the recipient of multiple prestigious awards, including four ERC grants, two Google Faculty awards, and the 2018 Facebook Computational Social Science award. 
    Besides academic work, Michael was a co-founder and technology executive at Novafora (2005-2009) developing large-scale video analysis methods, 
    and one of the chief technologists at Invision (2009-2012) developing low-cost 3D sensors. Following the multi-million acquisition of Invision by Intel in 2012, 
    Michael has been one of the key developers of the Intel RealSense technology in the role of Principal Engineer. His most recent venture is Fabula AI, a startup 
    dedicated to algorithmic detection of fake news using geometric deep learning.
 - name: Nicolò Cesa-Bianchi
   id: nicolo-cesa-bianchi
   topic: Online Learning
   institution-logo: /images/logos/milano_logo-100x100.png
   pic: /images/speakers/speaker_cesabianchi_2112×2816.jpg
   bio: >
    Nicolò Cesa-Bianchi is professor of Computer Science at the University of Milan, Italy. His main research areas include the design and analysis of machine learning algorithms, 
    particularly in the online learning model, the study of algorithms for multiarmed bandit problems with applications to personalized recommendations and online auctions, 
    and graph analytics with applications to social networks and bioinformatics. He is co-author of the monographs "Prediction, Learning, and Games" and "Regret Analysis of 
    Stochastic and Nonstochastic Multi-armed Bandit Problems".
 - name: Arthur Gretton
   id: arthur-gretton
   topic: Kernels
   institution-logo: /images/logos/ucl_logo-341x100.png
 - name: Joris Mooij
   id: joris-mooij
   topic: Causality
   institution-logo: /images/logos/uva_logo-314x100.png
---


{% if page.authors %}
  {% for author in page.authors %}
  <ul>
    <li>
      <a href = "#{{ author.id }}"> {{ author.name }} ({{ author.topic }})</a>
    </li>
  </ul>
	{% endfor %}
{% endif %}
* and more to come!

{% if page.authors %}
  {% for author in page.authors %}
    {% include _widget-author.html widget=author %}
	{% endfor %}
{% endif %}
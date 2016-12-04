---
layout: page
title: About
permalink: /about/
---

### ![edu]({{ site.baseurl }}/images/edu.png) Education
{% for edu in site.education %} 
     
#### {{ edu.school }} 
 
##### {{ edu.start }} - {{ edu.end }} 
{{ edu.subject }} 
{{ edu.level }} 
{% endfor %} 


### ![work]({{ site.baseurl }}/images/work.png) Professional Experience

#### CDG : Caisse de Dépôt et de Gestion

##### July - August 2016
Designed, developed, and implemented a web application for the internal rating model of the CDG  
Tools :  **Spring MVC Framework, Liferay, Hibernate, iText**

### Contact me

[email@domain.com](mailto:email@domain.com)

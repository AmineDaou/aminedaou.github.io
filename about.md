---
layout: page
title: About
permalink: /about/
---

### ![edu]({{ site.baseurl }}/images/edu.png) Education
{% for edu in site.education %} 
     
#### {{ edu.school }} :mortar_board:
 
##### {{ edu.start }} - {{ edu.end }} 
{{ edu.subject }} 
{{ edu.level }} 
{% endfor %} 


### ![work]({{ site.baseurl }}/images/work.png) Professional Experience
{% for experience in site.experiences %} 

#### {{ experience.employer }} :briefcase:

##### {{ experience.date }}
{{ experience.description }}  
Tools :  {% for tool in experience.tools %} <span class="label label-info label-padded"> {{ tool }} </span> &nbsp; {% endfor %}
{% endfor %} 
### Contact me

[aminedaoudimail@gmail.com](mailto:aminedaoudimail@gmail.com)

## ![work]({{ site.baseurl }}/images/work.png) Professional Experience
{% for experience in site.experiences %} 

#### :briefcase: {{ experience.employer }}

##### {{ experience.date }}
{{ experience.description }}  
Tools :  {% for tool in experience.tools %} <span class="label label-info label-padded"> {{ tool }} </span> &nbsp; {% endfor %}

* * *
{% endfor %} 

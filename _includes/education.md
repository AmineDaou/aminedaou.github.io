## ![edu]({{ site.baseurl }}/images/edu.png) Education
{% for edu in site.education %} 
     
#### :mortar_board: {{ edu.school }}
 
##### {{ edu.start }} {% if edu.end != blank %} - {% endif %} {{ edu.end }} 
{{ edu.subject }} 
{{ edu.level }}
{% if forloop.last != true %}

* * *
{% endif %}
{% endfor %} 

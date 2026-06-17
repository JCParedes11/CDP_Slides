---
title: Pizza as a Service 2.0
layout: post
permalink: /PizzaAsAService/
theme: beige
 
slides:
 - title: Pizza as a Service 2.0
   slide-data: Cloud Data Processing<br> Tarea #997<br> Julio Paredes
 
     
 - title: Slide 2
   slide-data: This is second slide

   
 - title: Slide 3
   slide-data: This is third slide

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}

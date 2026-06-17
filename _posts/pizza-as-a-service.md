---
title: Pizza as a Service 2.0
layout: post
permalink: /pizza-as-a-service/
theme: beige

slides:
 - title: Pizza as a Service 2.0
   slide-data: Computación en la Nube<br>Tarea #997<br>Julio Paredes

 - title: ¿Qué es Pizza as a Service?
   slide-data: Es una analogía utilizada para explicar los diferentes modelos de servicio en la nube y cómo se distribuyen las responsabilidades entre el usuario y el proveedor.

 - title: Modelos de Servicio en la Nube
   slide-data: IaaS - Infrastructure as a Service<br>PaaS - Platform as a Service<br>SaaS - Software as a Service

 - title: IaaS
   slide-data: El proveedor administra la infraestructura.<br> El usuario administra sistemas operativos, aplicaciones y datos.

 - title: Ventajas de IaaS
   slide-data: |
     Mayor control<br>
     Alta flexibilidad<br>
     Escalabilidad

 - title: Desventajas de IaaS
   slide-data: |
     Requiere conocimientos técnicos<br>
     Mayor administración

 - title: Casos de Uso IaaS
   slide-data: |
     Máquinas virtuales<br>
     Hosting de aplicaciones<br>
     Laboratorios virtuales

 - title: PaaS
   slide-data: |
     El proveedor administra infraestructura y plataforma.<br>
     El usuario administra aplicaciones y datos.

 - title: Ventajas de PaaS
   slide-data: |
     Desarrollo rápido<br>
     Menor administración<br>
     Fácil despliegue

 - title: Desventajas de PaaS
   slide-data: |
     Menor control<br>
     Dependencia del proveedor

 - title: Casos de Uso PaaS
   slide-data: |
     Desarrollo web<br>
     APIs<br>
     Aplicaciones empresariales

 - title: SaaS
   slide-data: |
     El proveedor administra todo.<br>
     El usuario únicamente utiliza el software.

 - title: Ventajas de SaaS
   slide-data: |
     Fácil uso<br>
     Actualizaciones automáticas<br>
     Acceso desde cualquier lugar

 - title: Desventajas de SaaS
   slide-data: |
     Menor personalización<br>
     Dependencia de Internet

 - title: Casos de Uso SaaS
   slide-data: |
     Correo electrónico<br>
     Ofimática<br>
     Videoconferencias

 - title: Ejemplos
   slide-data: |
     IaaS: AWS EC2, Azure VM, Google Compute Engine<br>
     PaaS: Google App Engine, Azure App Service<br>
     SaaS: Microsoft 365, Google Workspace, Zoom

 - title: Conclusiones
   slide-data: |
     Pizza as a Service facilita la comprensión de los modelos cloud.<br>
     Cada modelo ofrece distintos niveles de control y administración.

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}


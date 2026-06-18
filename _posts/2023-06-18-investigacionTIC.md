---
title: TIC
layout: post
permalink: /InvestigacionTIC/
theme: league
 
slides:
 - title: TIC
   slide-data: Cloud Data Processing<br> Tarea 997<br> Julio Paredes<br>
 
     
 - title: 1.1 Solucion estratificada de problemas en TIC
   slide-data: <b>Descripción:</b><br>
   Es un enfoque que divide sistemas complejos en capas o niveles organizados.<br><br>
   <b>Características:</b><br>
   • División por capas<br>
   • Modularidad<br>
   • Separación de responsabilidades<br>
   • Facilidad de mantenimiento<br><br>
   <b>Casos de uso:</b><br>
   • Arquitectura de software<br>
   • Redes de computadoras<br>
   • Sistemas empresariales<br><br>
   <b>Ejemplos:</b><br>
   • Modelo OSI<br>
   • Arquitectura cliente-servidor<br>
   • Sistemas ERP

     
 - title: 1.1.a Virtualización por interpretación pura
   slide-data: <b>Descripción:</b><br>
   Ejecuta instrucciones del sistema invitado una por una mediante interpretación directa.<br><br>
   <b>Características:</b><br>
   • Interpretación instrucción por instrucción<br>
   • No compila código<br>
   • Alta compatibilidad<br>
   • Bajo rendimiento<br><br>
   <b>Casos de uso:</b><br>
   • Emulación de sistemas antiguos<br>
   • Investigación de software<br>
   • Educación<br><br>
   <b>Ejemplos:</b><br>
   • Bochs<br>
   • QEMU (modo emulación)<br>
   • Emuladores de consolas

     
 - title: 1.1.b Virtualización por recompilación dinámica
   slide-data: <b>Descripción:</b><br>
   Traduce bloques de instrucciones a código nativo durante la ejecución.<br><br>
   <b>Características:</b><br>
   • Traducción en tiempo real<br>
   • Mejora de rendimiento<br>
   • Reutilización de código compilado<br>
   • Optimización dinámica<br><br>
   <b>Casos de uso:</b><br>
   • Máquinas virtuales modernas<br>
   • Emulación de videojuegos<br>
   • Compatibilidad entre arquitecturas<br><br>
   <b>Ejemplos:</b><br>
   • QEMU (TCG)<br>
   • Rosetta 2<br>
   • DynamoRIO 

     
 - title: 1.1.c Virtualización por hipervisión (bare metal)
   slide-data: <b>Descripción:</b><br>
   El hipervisor se ejecuta directamente sobre el hardware físico para crear máquinas virtuales.<br><br>
   <b>Características:</b><br>
   • Acceso directo al hardware<br>
   • Alto rendimiento<br>
   • Aislamiento de sistemas<br>
   • Escalabilidad<br><br>
   <b>Casos de uso:</b><br>
   • Centros de datos<br>
   • Cloud computing<br>
   • Infraestructura empresarial<br><br>
   <b>Ejemplos:</b><br>
   • VMware ESXi<br>
   • Microsoft Hyper-V<br>
   • Xen
 
---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}

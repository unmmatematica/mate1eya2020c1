---
items:
  - nombre: Actividades
    descripcion: es lo que se realizará ese día durante el horario de clase.
  - nombre: Tareas
    descripcion: es lo que queda para hacer para la siguiente clase.
---

# Glosario

## Cursada

{% for item in page.items %}
* **{{item.nombre}}:** {{item.descripcion}}
{% endfor %}

---
items:
  - nombre: Actividades
    descripcion: es lo que se realizará ese día durante el horario de clase.
  - nombre: Tareas
    descripcion: es lo que queda para hacer para la siguiente clase. Se entrega **solamente** si se indica que hay que hacerlo.
---

# Glosario

## Cursada

{% for item in page.items %}
* **{{item.nombre}}:** {{item.descripcion}}
{% endfor %}

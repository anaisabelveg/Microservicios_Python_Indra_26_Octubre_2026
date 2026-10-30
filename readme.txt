Os he vuelto a subir el ejemplo17 de Docker.

  - El problema estaba en run.py porque mantenia el host: 127.0.0.1 y entonces docker no puede acceder.
  - La solucion es cambiarlo a 0.0.0.0
  - Con eso ya funciona siguiendo los pasos del pdf que teneis en el repositorio.


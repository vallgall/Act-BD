# Archivos JSON de Colecciones de Actividad

Este repositorio contiene archivos JSON que representan datos de una actividad relacionada con partidos de fútbol. Estos archivos están destinados a ser utilizados como datos iniciales para una base de datos MongoDB.

## Contenido

### `resultados.json`

Este archivo contiene documentos JSON que representan los resultados de varios partidos de fútbol. Cada documento incluye información como el identificador del partido (`_id`), el equipo ganador, los puntajes de los equipos involucrados y detalles adicionales del partido.

Ejemplo:

```json
[
  {
  "_id": 3,
  "equipo_ganador": "Equipo 1",
  "puntajes": {
    "Equipo 1": 4,
    "Equipo 3": 0
  },
  "detalles": "Dominio absoluto del Equipo 3"
},
  // ... otros documentos
]

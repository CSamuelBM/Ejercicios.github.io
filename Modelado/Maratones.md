# Carreras

## Listado de Entidades

### carreras (**ED**)

- id_carrera (**PK**)
- nombre_carrera
- tipo_carrera (**FK**)
- fecha
- tiempo
- mejor_tiempo
- altitud
- lugar
- pais (**FK**)
- foto

### tipos carreras (**EC**)

- id_tipo_carrera (**PK**)
- descripcion
- distancia

### Paises (**EC**)

- id_pais (**PK**)
- nombre_pais

### Relaciones

Una **Carrera** _Pertenece_ a un **Tipo de Carrera** (_1_ a _1_)

Una **Carrera** se _Corre_ en un **Pais** (_1_ a _1_)
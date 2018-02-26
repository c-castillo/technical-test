## Pregunta 1

## Pregunta 2

```sql

SELECT rut, titulo
FROM personas JOIN cursos ON personas.rut = cursos.rut_profesor
```
(Cualquier respuesta que mencione un JOIN está correcta, el tipo de JOIN no es relevante)

## Pregunta 3

### 3a
```
- Minificación de assets (js/css) -> reducción de tamano
- Usar CDN para assets (caché, geolocalización)
- Servidor web entrega respuestas comprimidas usando gzip
```

### 3b

- `git checkout -b`: Crear un nuevo branch(rama) a partir de una ya existente
- `git add`: Agregar cambios que irán en el próximo commit
- `git cherry-pick`: Seleccionar uno o mas commits de una rama para agregarlos en otra
- `git fetch`: Obtener índice remoto de nuevas branches (sincronizar branches)


### 3c

- Usar una herramienta de generación de artefactos (estilo maven, gradle, capistrano, etc)
- Empaquetar la app en containers de docker, y transferirlos a un servidor remoto
- Usar una herramienta de CI/CD como Jenkins, Travis, GoCD, CircleCI
- Usar un platform-as-a-service como Heroku (el servicio se encarga de hacer deploy)

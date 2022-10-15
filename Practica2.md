# Listado de entidades y sus atributos

## Artistas 
- Nombre artístico (artista_id)
- Nombre real(fk)
- Fecha de nacimiento
- Nacionalidad
- Año de inicio(fk)
- Genero musical (pk)

## Discos
- Nombre (disco_id)
- Fecha de lanzamiento
- Nombre de su artista (pk)
- Cantidad de canciones(fk)

## Canciones
- Nombre (cancion_id)
- Nombre de su interprete(fk)
- Duracion
- Nombre del disco al que pertenece (pk)

## Genero
- Nombre (genero_id)
- Instrumentación(fk)
- Lugar de origen
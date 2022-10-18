# Listado de entidades y sus atributos

## Artistas 
- Nombre artístico (artista_id)
- Nombre real
- Fecha de nacimiento
- Nacionalidad
- Año de inicio
- Genero musical (genero_id)(pk)

## Discos
- Nombre (disco_id)
- Fecha de lanzamiento
- Nombre de su artista (artista_id)(fk)
- Cantidad de canciones

## Canciones
- Nombre (cancion_id)
- Nombre de su interprete (artista_id)(fk)
- Duracion
- Nombre del disco al que pertenece(disco_id)

## Genero
- Nombre (genero_id)
- Instrumentación
- Lugar de origen
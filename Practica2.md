# Listado de entidades y sus atributos

## Artistas 
- Nombre artístico (artista_id)(pk)
- Nombre real
- Fecha de nacimiento
- pais_id(pk)
- Año de inicio
- genero_id (fk)

## Discos
- Nombre (disco_id)(pk)
- Fecha de lanzamiento
- artista_id (fk)
- cancion_id(fk)

## Canciones
- Nombre (cancion_id)(pk)
- artista_id (fk)
- Duracion
- disco_id(fk)

## Genero
- Nombre (genero_id)(pk)
- Instrumentación
- pais_id(pk)

## Paises
- Nombre 
- Iso2

## Tabla de relaciones 
- Nombre artistico puede tener un género (1-1)
- Nombre disco puede tener un artista(1-1)
- Nombre disco puede tener varias canciones (1-M)
- Nombre cancion puede tener un solo disco (1-1)
- Nombre cancion puede tener solo un artista (1-1)
- Nombre género puede tener un solo pais (1-1)
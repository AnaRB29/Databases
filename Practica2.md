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

## Diagrama 
![Diagrama](https://media.discordapp.net/attachments/930177756011053086/1035215391661772901/Diagrama2710.jpg?width=847&height=476)

## Reglas del negocio 

1. Aristas

- Crear un artista 
- Leer todos los artistas
- Leer un artista en particular.
- Actualizar un artista.
- Eliminar un artista.

2. Discos 

- Crear un disco.
- Leer todos los discos.
- Leer todas los discos de un artista.
- Leer un disco en particular.
- Actualizar el disco.
- Eliminar un disco.

3. Canciones 

- Crear una cancion. 
- Leer todas las canciones.
- Leer todas las canciones de un artista. 
- Leer todas las canciones de un disco.  
- Leer una cancion en particular.
- Actualizar una cancion.
- Eliminar una cancion.

4. Generos

- Crear un genero. 
- Leer todos los generos. 
- Leer un genero en particular.
- Leer el genero de un disco
- Leer el genero de una cancion 
- Leer el genero de un artista
- Actualizar un genero.
- Eliminar un genero.

5. Paises 
- Crear un pais.
- Leer todos los paises.
- Leer un país en particular.
- Actualizar un país.
- Eliminar un país.
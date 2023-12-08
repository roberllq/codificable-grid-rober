# Codificable Grid Components

## Asignación

Desarrollar nuevos componentes para la web de Codificable e implementar mejoras a ciertos componentes actuales utilizando CSS Grid

- <a href="https://www.figma.com/file/KdM1M43yFmCSdrYKGKlViX/Codificable-UI?type=design&node-id=0%3A1&mode=design&t=KvbQk0JxcdWkqD5j-1" target="_blank">Diseño en Figma</a>

## Pancake Stack

<figure>
  <img src="https://res.cloudinary.com/dwdgpw20b/image/upload/v1693431004/illustrations/pancake-stack_sj6qn1.png" />
  <figcaption>Clásico pancake stack para header, main y footer</figcaption>
</figure>

### Requerimiento

- Crear un "objeto" (capa en ITCSS) llamado `pancake-stack` que sirva para la distribución general del sitio web. Este objeto debe definir 3 filas. La primera y última deben de ser de tamaño automático (definido por su contenido) pero la segunda debe crecer para ocupar todo el alto del contenedor.
- El contenedor en sí mismo debe ocupar todo el alto de la ventana del navegador. Como resultado, el footer siempre debe estar ubicado al final de la ventana.

## Componente Features

<figure>
  <img src="https://res.cloudinary.com/dwdgpw20b/image/upload/v1693431504/illustrations/features2_huvdoz.png" />
  <figcaption>Componente Features</figcaption>
</figure>

### Requerimiento

- Crear el componente `features` siguiendo las especificaciones de Figma
- En pantallas pequeñas, el encabezado y la lista de features deben estar en la misma columna.
- En pantallas mayores a 640px, la lista de features debe tener 2 columnas.
- En pantallas mayores a 1024px, el encabezado debe ir en una columna a la izquierda y las 2 columnas de features a la derecha

<img src="https://res.cloudinary.com/dwdgpw20b/image/upload/v1693432070/illustrations/features2_iwl2ye.gif" />

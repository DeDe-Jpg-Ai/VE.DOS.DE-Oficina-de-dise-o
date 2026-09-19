# ve.dos.de : Oficina de Diseño

Sitio del estudio. Es una sola página, sin dependencias ni compilación: se
abre `index.html` y funciona.

## Estructura

```
index.html                 todo el sitio: estructura, estilos y guión
fotos/
  diseno-editorial/        8 obras
  identidad-visual/        3 obras
  grafica-arquitectonica/  3 obras
  documentacion-de-obra/   4 obras, una con galería propia en casa-1/
  fotografia-arquitectura/ 4 obras
```

Los nombres de carpeta van en minúscula, sin espacios ni tildes, porque el
servidor web distingue mayúsculas de minúsculas.

## Cómo cargar una obra nueva

1. Poné la foto en la carpeta del servicio que corresponda.
2. En `index.html`, buscá la lista `SERVICES` y agregá una línea en el
   servicio, con el nombre del archivo, el nombre de la obra, el año y el
   lugar.
3. Si la obra tiene varias fotos, creá una carpeta propia (como `casa-1/`) y
   sumá `shots` con la lista de fotos, en el orden en que se van a ver.

## Ver el sitio mientras se trabaja

Las fotos no cargan abriendo el archivo con doble clic: hace falta un
servidor. Con Python instalado, desde esta carpeta:

    python -m http.server 5173

y abrir http://localhost:5173

## Publicado en

GitHub Pages. Cada cambio que se sube a la rama principal queda en línea en
un par de minutos.

## Tipografía

El sitio usa la Arial instalada en cada computadora. Los archivos de Arial son
de Monotype y no se publican acá. Donde no haya Arial, la página cae a
Helvetica o a la sans serif del sistema.

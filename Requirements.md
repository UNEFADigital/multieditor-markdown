# Requerimientos

## 1. Características Generales del Proyecto

+ Mútiples archivos (1 a la vez).
+ Panel de vista previa.
+ Parseo de sintaxis [Markdown][1].
+ Persistencia (usando LocalStorage).
+ Control de Edición.
+ Inclusión de elementos WYSIWYG.
+ Tablas e imágenes.
+ Última fecha y hora de modificación.

## 2. Historias de usuario.

+ [ ] Como usuario, quiero poder escribir información en múltiples archivos usando sintaxis [Markdown][1], con su respectiva vista previa en HTML.
+ [ ] Como usuario, quiero ver 3 paneles con el mismo ancho: uno correspondiente a la lista de archivos, otro correspondiente a la edición del archivo (1 a la vez) y otro correspondiente a la vista previa (en HTML) del archivo.
+ [ ] Como usuario, quiero listar múltiples archivos, cuyo nombre de archivo sea la primera linea escrita en el archivo.
+ [ ] Como usuario, quiero que los cambios se guarden en el archivo cada vez que se presione un botón de guardar, y que dichos cambios se vean reflejados en el panel de vista previa HTML.
+ [ ] Como usuario, quiero poder crear nuevos archivos (máximo hasta 8 archivos).
+ [ ] Como usuario, quiero ver una barra de herramientas contextuales con herramientas de inserción de negrita, cursiva, y todos los elementos correspondientes a la sintaxis [Markdown][1].
+ [ ] Como usuario, quiero poder deshacer y rehacer los cambios realizados a un archivo siempre que no lo haya guardado (máximo hasta 8 acciones).
+ [ ] Como usuario, quiero poder incluir tablas, imágenes y enlaces manualmente.
+ [ ] Como usuario, quiero ver que cada archivo refleje la última fecha y hora de modificación debajo del nombre del archivo en el panel de la lista de archivos.
+ [ ] Como usuario, quiero que no permita guardar archivos que no tengan al menos una linea de texto.

[1]: http://daringfireball.net/projects/markdown/

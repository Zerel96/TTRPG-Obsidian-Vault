---
sticker: lucide//info
cssclasses:
  - tag-text
---
![[Conceptos.png|banner-fade banner+tall p+ct]]
# Conceptos
Aquí Dispondrás de todos los Conceptos creados actualmente para esta sesión.

>[!info|bg-c-yellow] Importante
>recuerda que deberás modificar las listas manualmente según las aventuras que vayas creando

#### Listado de Conceptos

```dataview
TABLE WITHOUT ID
file.link as Nombre,join(file.tags, " ") as Etiquetas
FROM "D&D Base de Datos/Reino de Sagraria/Conceptos"
SORT file.link asc
WHERE file.name != this.file.name
```


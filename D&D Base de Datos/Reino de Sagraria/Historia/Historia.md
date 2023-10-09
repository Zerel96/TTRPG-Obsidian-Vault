![[Historia.png|banner-fade banner+tall p+ct]]
# Historia
Aquí Dispondrás de todos las historias creadas actualmente para esta sesión.

>[!info|bg-c-yellow] Importante
>recuerda que deberás modificar las listas manualmente según las aventuras que vayas creando

#### Listado de Historias

```dataview
TABLE WITHOUT ID
file.link as Nombre,join(file.tags, " ") as Etiquetas
FROM "D&D Base de Datos/Reino de Sagraria/Historias"
SORT file.link asc
WHERE file.name != this.file.name
```


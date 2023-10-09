---
sticker: lucide//meh
---
![[NPC.png|banner-fade banner+tall p+tcc]]
# NPC

Aquí Dispondrás de todos los Personajes No Jugables (NPC) creados actualmente para todas las sesiones que se te ocurran.

>[!info|bg-c-yellow] Importante
>recuerda que deberás añadir las listas manualmente según las aventuras que vayas creando

#### Listado de NPC
>[!cards|dataview]
>```dataview
> TABLE WITHOUT ID
> "**" + file.link + "**", embed(foto) as "Foto", "Raza: #" + Raza, Aventura
>FROM "D&D Base de Datos/Reino de Sagraria/NPC"
> SORT file.name asc
> WHERE file.name != this.file.name
> ```

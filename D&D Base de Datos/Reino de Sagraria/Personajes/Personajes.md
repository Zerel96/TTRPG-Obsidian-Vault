---
sticker: lucide//user
---
![[Personajes.png|banner-fade banner+tall p+bcc]]
# Personajes

Aquí Dispondrás de todos los personajes creados actualmente para todas las sesiones que se te ocurran.

>[!info|bg-c-yellow] Importante
>recuerda que deberás añadir las listas manualmente según las aventuras que vayas creando

#### Listado de Personajes
>[!cards|dataview]
>```dataview
> TABLE WITHOUT ID
> "**"+ file.link + "**", Foto, "Raza: #" + Raza, Aventura
> FROM "D&D Base de Datos/Reino de Sagraria/Personajes"
> SORT file.name asc
> WHERE file.name != this.file.name
> ```

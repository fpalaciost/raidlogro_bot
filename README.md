# raidlogro_bot

Las funciones básicas del bot son:
- Permite *modo silencio* y *modo ruido*. Comandos `/modo silencio` y `/modo ruido`
- Indica la ubicación del gimnasio en el que hay una incursión. Entiende los nombres comunes por los que la gente conoce al gimnasio, aunque sean diferentes de los que ha puesto PoGo. Funciona por defecto para Logroño pero se puede configurar en otras ubicaciones.

## Primeros pasos
- Añade este robot a un grupo
- Da al robot permisos de administración para que pueda borrar mensajes

## Modo silencio 
En modo silencio, el robot:
- Borrará los mensajes que no contienen unos patrones (regexp) que se pueden personalizar por grupo. Ejemplo "esperad x minutos", "+1 a zzzzz", etc.
- Borra stickers, gifs y otro tipo de spam variado
- Nunca borra los mensajes de los administradores
- No borra mensajes de usuarios a quienes se les ha dado *altavoz*

## Altavoces
- Dar un "altavoz" a un usuario, para no borrar sus mensajes. Comando `/altavoz @usuariotelegram`
- Quitar altavoz. Comando `/altavoz @usuariotelegram off`


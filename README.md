# mccapes - Base de Datos de Capas
Capas personalizadas para Minecraft 1.8.9 Forge con el mod **MCCape**.

## ¿Cómo asignar una capa a un jugador?

### Opción 1: Mediante `capes.json` (Recomendada)
Edita el archivo `capes.json` y añade el nombre o UUID del jugador con el archivo que desees:

```json
{
  "users": {
    "3mgc": "momo.gif",
    "grannydestroyer": "momo.gif",
    "amigo1": "fire.png"
  }
}
```

### Opción 2: Archivo directo por Nick o UUID
También puedes subir directamente un archivo con el nombre del jugador dentro de la carpeta `capes/`:
- `capes/TuNick.gif`
- `capes/TuNick.png`
- `capes/uuid-del-jugador.png`

---

## Capas disponibles en este repositorio
- `momo.gif`: Capa animada Ultra HD (1024x512) de Momo bailando.
- `default.png`: Capa geométrica cian oscuro estilo LabyMod.
- `fire.png`: Capa con diseño de llamas de fuego.
- `plantilla.png`: Plantilla guía con colores explicativos.

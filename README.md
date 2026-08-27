# Parche de NPCs para Project Zomboid B42

Parche de Java necesario para el mod **MC Refugiados de Knox — NPCs para
Multijugador [B42]**.

## ➜ [Descargar la última versión](../../releases/latest)

---

## Español

### Qué es

Project Zomboid no dibuja en pantalla a ningún personaje humano que no sea el
jugador: el motor los excluye del render. Este parche corrige esa exclusión.

Sin él, el mod se instala correctamente y **no aparece ningún NPC**.

Es lo mismo que usan el resto de mods de NPCs para Build 42.

### Quién lo instala

**Cada jugador, en su propio ordenador.**

En el servidor **no hace falta**: el servidor solo lleva el mod. Si eres
administrador, avisa a tus jugadores de que tienen que instalarlo ellos o no
verán a nadie.

### Cómo se instala

1. Descarga `NPC-MC-B42.exe` desde [Releases](../../releases/latest)
2. Ábrelo y pulsa el botón
3. Entra al juego

El instalador te enseña antes la lista exacta de archivos que va a escribir.

### Cómo se desinstala

**No modifica ningún archivo original del juego.** Solo deja un archivo suelto
en la carpeta de Project Zomboid:

```
zombie\characters\IsoSurvivor.class
```

Borrarlo deja el juego exactamente como estaba.

### Windows va a mostrar un aviso

La primera vez saldrá **«Windows protegió su PC»** con el editor marcado como
desconocido. Pulsa **Más información** → **Ejecutar de todas formas**.

Sale porque el ejecutable no está firmado con un certificado de firma de código,
que es de pago y de renovación anual. El programa funciona igual.

Si prefieres comprobar que el archivo es el que dice ser, este es su hash. En
PowerShell:

```powershell
Get-FileHash "NPC-MC-B42.exe" -Algorithm SHA256
```

| Versión | SHA-256 |
|---|---|
| 1.0.0 | `9815dbbdf4aa041bed490e7f35dc65d2f78acf370a9b44bc49a385fd33e720a8` |

### Compatibilidad

- Project Zomboid **Build 42** — probado en 42.20
- Windows
- Multijugador y un jugador

### Ayuda

[discord.gg/manncos](https://discord.gg/manncos)

---

## English

### What it is

Project Zomboid does not draw any human character other than the player: the
engine excludes them from rendering. This patch corrects that exclusion.

Without it the mod installs correctly and **no NPC appears**.

It's the same approach other Build 42 NPC mods use.

### Who installs it

**Each player, on their own machine.**

It is **not needed on the server**: the server only needs the mod. If you're an
admin, tell your players they must install it themselves or they'll see nobody.

### How to install

1. Download `NPC-MC-B42.exe` from [Releases](../../releases/latest)
2. Open it and press the button
3. Launch the game

The installer shows you the exact list of files it will write before writing
anything.

### How to uninstall

**It does not modify any original game file.** It only drops a loose file into
the Project Zomboid folder:

```
zombie\characters\IsoSurvivor.class
```

Deleting it leaves the game exactly as it was.

### Windows will show a warning

The first time you'll get **"Windows protected your PC"** with the publisher
listed as unknown. Click **More info** → **Run anyway**.

This happens because the executable isn't signed with a code signing
certificate, which is a paid, yearly subscription. The program works fine.

If you'd rather verify the file is what it claims to be, here's its hash. In
PowerShell:

```powershell
Get-FileHash "NPC-MC-B42.exe" -Algorithm SHA256
```

| Version | SHA-256 |
|---|---|
| 1.0.0 | `9815dbbdf4aa041bed490e7f35dc65d2f78acf370a9b44bc49a385fd33e720a8` |

### Compatibility

- Project Zomboid **Build 42** — tested on 42.20
- Windows
- Multiplayer and singleplayer

### Support

[discord.gg/manncos](https://discord.gg/manncos)

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

Hay dos formas. **La primera es la recomendada.**

#### A) ZIP — 2 KB, sin avisos de Windows

1. Descarga `NPC-MC-B42-manual.zip` desde [Releases](../../releases/latest)
2. Copia la carpeta `zombie` que lleva dentro a la carpeta de Project Zomboid
   (di que sí al combinar carpetas)
3. Entra al juego

Tiene que quedar así:

```
...\ProjectZomboid\zombie\characters\IsoSurvivor.class
```

No hay nada que ejecutar, así que Windows no dice nada.

#### B) Instalador — un botón

1. Descarga `NPC-MC-B42.exe` desde [Releases](../../releases/latest)
2. Ábrelo y pulsa el botón

Hace exactamente lo mismo que el ZIP. **Windows puede bloquearlo al
descargarlo** — mira el apartado de abajo.

### Cómo se desinstala

**No modifica ningún archivo original del juego.** Solo deja un archivo suelto
en la carpeta de Project Zomboid:

```
zombie\characters\IsoSurvivor.class
```

Borrarlo deja el juego exactamente como estaba.

### Windows y el instalador

Windows puede **bloquear el `.exe` al descargarlo** o mostrar «Windows protegió
su PC» al abrirlo.

No es que el archivo tenga nada: es que **hace exactamente lo que hace un
instalador** — lleva un archivo dentro, lo extrae y lo escribe en la carpeta del
juego pidiendo permisos. Sin un certificado de firma de código, que es de pago y
de renovación anual, la heurística de Windows no distingue eso de un programa
malicioso.

**Si te pasa, usa el ZIP.** Hace lo mismo, son 2 KB, y no hay nada que ejecutar.

Si prefieres el instalador: **Más información** → **Ejecutar de todas formas**.

Si prefieres comprobar que el archivo es el que dice ser, este es su hash. En
PowerShell:

```powershell
Get-FileHash "NPC-MC-B42.exe" -Algorithm SHA256
```

| Archivo | SHA-256 |
|---|---|
| `NPC-MC-B42.exe` | `9815dbbdf4aa041bed490e7f35dc65d2f78acf370a9b44bc49a385fd33e720a8` |
| `NPC-MC-B42-manual.zip` | `302c85aadbd4ef3d376d499e93799573bf0a7cd00d3e91c2a4ccb8b3fd1a0597` |

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

Two ways. **The first one is recommended.**

#### A) ZIP — 2 KB, no Windows warnings

1. Download `NPC-MC-B42-manual.zip` from [Releases](../../releases/latest)
2. Copy the `zombie` folder inside it into your Project Zomboid folder
   (say yes to merging folders)
3. Launch the game

It should end up like this:

```
...\ProjectZomboid\zombie\characters\IsoSurvivor.class
```

There's nothing to run, so Windows says nothing.

#### B) Installer — one button

1. Download `NPC-MC-B42.exe` from [Releases](../../releases/latest)
2. Open it and press the button

It does exactly the same as the ZIP. **Windows may block it on download** —
see the section below.

### How to uninstall

**It does not modify any original game file.** It only drops a loose file into
the Project Zomboid folder:

```
zombie\characters\IsoSurvivor.class
```

Deleting it leaves the game exactly as it was.

### Windows and the installer

Windows may **block the `.exe` on download**, or show "Windows protected your
PC" when you open it.

There's nothing wrong with the file: it's that **it does exactly what an
installer does** — carries a file inside, extracts it and writes it into the
game folder asking for permissions. Without a code signing certificate, which
is a paid yearly subscription, Windows' heuristics can't tell that apart from a
malicious program.

**If it happens, use the ZIP.** It does the same thing, it's 2 KB, and there's
nothing to run.

If you'd rather use the installer: **More info** → **Run anyway**.

If you'd rather verify the file is what it claims to be, here's its hash. In
PowerShell:

```powershell
Get-FileHash "NPC-MC-B42.exe" -Algorithm SHA256
```

| File | SHA-256 |
|---|---|
| `NPC-MC-B42.exe` | `9815dbbdf4aa041bed490e7f35dc65d2f78acf370a9b44bc49a385fd33e720a8` |
| `NPC-MC-B42-manual.zip` | `302c85aadbd4ef3d376d499e93799573bf0a7cd00d3e91c2a4ccb8b3fd1a0597` |

### Compatibility

- Project Zomboid **Build 42** — tested on 42.20
- Windows
- Multiplayer and singleplayer

### Support

[discord.gg/manncos](https://discord.gg/manncos)

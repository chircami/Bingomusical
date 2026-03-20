# 🎵 Bingo Musical

> Un bingo interactivo con música — elige tu época favorita, genera cartillas personalizadas con QR y escucha cada canción en directo gracias a la API de iTunes.

![Bingo Musical](https://img.shields.io/badge/version-1.0.0-gold?style=flat-square)
![HTML](https://img.shields.io/badge/HTML-solo%20archivo-purple?style=flat-square&logo=html5)
![Sin dependencias](https://img.shields.io/badge/dependencias-ninguna-green?style=flat-square)
![License](https://img.shields.io/badge/licencia-MIT-blue?style=flat-square)

---

## 📋 Tabla de contenidos

- [¿Qué es?](#-qué-es)
- [Demo](#-demo)
- [Características](#-características)
- [Categorías musicales](#-categorías-musicales)
- [Cómo jugar](#-cómo-jugar)
- [Instalación y uso](#-instalación-y-uso)
- [Despliegue en GitHub Pages](#-despliegue-en-github-pages)
- [Tecnologías](#-tecnologías)
- [Estructura del proyecto](#-estructura-del-proyecto)
- [Notas sobre el audio](#-notas-sobre-el-audio)
- [Capturas de pantalla](#-capturas-de-pantalla)
- [Contribuir](#-contribuir)
- [Licencia](#-licencia)

---

## 🎯 ¿Qué es?

**Bingo Musical** es una aplicación web de una sola página (`bingo-musical.html`) que convierte el clásico bingo en una experiencia musical. En lugar de números, se cantan canciones. Cada jugador recibe una cartilla con 12 canciones escogidas al azar de un catálogo de 90 temas, y la aplicación va sorteando las canciones una a una reproduciendo automáticamente su preview de 30 segundos desde iTunes.

Pensado para **fiestas, reuniones familiares, noches de juegos y eventos corporativos**.

---

## 🌐 Demo

Si tienes el proyecto desplegado en GitHub Pages, sustituye la siguiente URL por la tuya:

```
https://TU-USUARIO.github.io/bingo-musical/bingo-musical.html
```

---

## ✨ Características

| Función | Descripción |
|---|---|
| 🎵 **6 categorías musicales** | 70s/80s/90s, Años 2000, Actuales, Españolas, Italianas y Mixta |
| 🎲 **90 canciones por categoría** | Cada partida usa un catálogo diferente según la época elegida |
| 🎫 **Cartillas personalizadas** | Cada jugador recibe una cartilla con 12 canciones aleatorias |
| 📱 **Código QR por cartilla** | Cada cartilla genera un QR escaneable para guardarla en el móvil |
| 🔊 **Audio en directo** | Preview de 30 segundos vía iTunes Search API (funciona sin clave) |
| ▶️ **Control de reproducción** | Play, pausa, barra de progreso y control de volumen |
| 📋 **Casillero visual** | Las 90 canciones en pantalla se van marcando conforme se cantan |
| ↺ **Restablecer juego** | Reinicia la partida sin perder los jugadores ni las cartillas |
| 🏆 **Declaración de BINGO** | Botón dedicado con animación de confetti para el ganador |
| 📱 **Responsive** | Funciona en móvil, tablet y escritorio |
| 🚫 **Sin backend** | Todo funciona en el navegador, sin servidor ni base de datos |

---

## 🎼 Categorías musicales

### 🕺 70s · 80s · 90s
Rock clásico, pop, disco y grunge de las décadas doradas. Queen, Led Zeppelin, ABBA, Bee Gees, Michael Jackson, Madonna, The Police, Nirvana, Oasis, Radiohead, U2, Prince, David Bowie y mucho más.

### 💿 Años 2000
Los grandes hits del nuevo milenio. Britney Spears, Eminem, Beyoncé, Amy Winehouse, Lady Gaga, Linkin Park, The Killers, Green Day, Adele, Katy Perry, Bruno Mars, Justin Bieber, Drake y más.

### 🔥 Actuales
Los temas más recientes (2019–2024). Taylor Swift, Bad Bunny, Rosalía, The Weeknd, Billie Eilish, Olivia Rodrigo, Harry Styles, Dua Lipa, BTS, Karol G, Ed Sheeran, SZA y más.

### 🇪🇸 Canciones Españolas
Lo mejor de la música en español de todos los tiempos. Mecano, Alejandro Sanz, Shakira, Rosalía, C. Tangana, Maná, Enrique Iglesias, Karol G, Bad Bunny, Héroes del Silencio, Melendi, Joan Manuel Serrat, Nino Bravo y más.

### 🇮🇹 Canciones Italianas
El mejor repertorio italiano desde los años 50 hasta hoy. Vasco Rossi, Lucio Battisti, Laura Pausini, Eros Ramazzotti, Andrea Bocelli, Mina, Lucio Dalla, Jovanotti, Al Bano & Romina Power, Zucchero, Claudio Baglioni y más.

### 🎲 Mixta
Una selección equilibrada de todas las categorías anteriores. La opción más variada y sorprendente para grupos heterogéneos.

---

## 🎮 Cómo jugar

### Preparación

1. **Abre la aplicación** en el navegador.
2. **Elige una categoría** musical en la pantalla de inicio.
3. **Añade los jugadores** — escribe el nombre de cada participante.
4. Pulsa **"Generar Cartillas"** — cada jugador recibirá una cartilla con 12 canciones.
5. Cada jugador puede **escanear su QR** para guardar su cartilla en el móvil.
6. Pulsa **"¡Comenzar el Juego!"** cuando todos tengan su cartilla.

### Durante el juego

1. El presentador pulsa **"▶ Siguiente canción"** para sortear una canción al azar.
2. La canción aparece en el panel **"Ahora suena"** y comienza a reproducirse automáticamente.
3. La canción se **marca en el casillero** de 90 canciones (panel grande).
4. Cada jugador comprueba si esa canción está en **su cartilla** y la tacha.
5. El presentador puede **pausar** la música y el juego en cualquier momento.
6. El juego continúa hasta que alguien complete su cartilla.

### Ganar

Cuando un jugador complete las 12 canciones de su cartilla, debe gritar **¡BINGO!** y pulsar el botón dorado en la aplicación. La app mostrará al ganador con una lluvia de confetti 🎉.

### Restablecer

Si quieres repetir la partida con los mismos jugadores y cartillas, pulsa **"↺ Restablecer juego"** (disponible en la cabecera y en el tablero). Se borran las canciones cantadas pero se mantienen los jugadores y cartillas.

Para empezar una partida completamente nueva, pulsa **"🔄 Nueva Partida"** en la pantalla de ganador.

---

## 🚀 Instalación y uso

### Opción 1 — Uso local (sin instalación)

Simplemente descarga `bingo-musical.html` y ábrelo en cualquier navegador moderno:

```bash
# Clonar el repositorio
git clone https://github.com/TU-USUARIO/bingo-musical.git

# Abrir en el navegador (macOS)
open bingo-musical.html

# Abrir en el navegador (Linux)
xdg-open bingo-musical.html

# Abrir en el navegador (Windows)
start bingo-musical.html
```

> ⚠️ **Nota sobre el audio en local:** Algunos navegadores bloquean la API de iTunes cuando el archivo se abre como `file://`. Si el audio no funciona en local, usa la Opción 2 (GitHub Pages) o sirve el archivo con un servidor local:
>
> ```bash
> # Con Python 3
> python3 -m http.server 8080
> # Luego abre: http://localhost:8080/bingo-musical.html
> ```

### Opción 2 — GitHub Pages (recomendado)

Ver sección [Despliegue en GitHub Pages](#-despliegue-en-github-pages) más abajo.

---

## 📦 Despliegue en GitHub Pages

GitHub Pages es la forma más sencilla de tener la aplicación online de forma gratuita. El audio de iTunes funciona perfectamente desde un dominio `https://`.

### Paso 1 — Crear el repositorio

Ve a [github.com/new](https://github.com/new) y crea un repositorio público llamado `bingo-musical`.

### Paso 2 — Subir el archivo

```bash
# Inicializar git en tu carpeta local
git init
git add bingo-musical.html README.md
git commit -m "🎵 Initial commit - Bingo Musical"

# Conectar con GitHub y subir
git remote add origin https://github.com/TU-USUARIO/bingo-musical.git
git branch -M main
git push -u origin main
```

### Paso 3 — Activar GitHub Pages

1. Ve a tu repositorio en GitHub.
2. Haz clic en **Settings** (Configuración).
3. En el menú lateral, haz clic en **Pages**.
4. En **Source**, selecciona la rama `main` y la carpeta `/ (root)`.
5. Haz clic en **Save**.

### Paso 4 — Acceder a la aplicación

En aproximadamente 1–2 minutos tu app estará disponible en:

```
https://TU-USUARIO.github.io/bingo-musical/bingo-musical.html
```

GitHub te mostrará la URL exacta en la sección Pages de la configuración.

### Actualizar la aplicación

Cada vez que hagas cambios:

```bash
git add bingo-musical.html
git commit -m "✨ Descripción de los cambios"
git push
```

GitHub Pages se actualizará automáticamente en segundos.

---

## 🛠️ Tecnologías

El proyecto es intencionalmente minimalista — **un solo archivo HTML** sin frameworks ni bundlers:

| Tecnología | Uso |
|---|---|
| **HTML5** | Estructura de la aplicación |
| **CSS3** | Estilos, animaciones y layout responsivo con CSS Grid |
| **JavaScript (ES2020+)** | Lógica del juego, sorteos, marcado de cartillas |
| **iTunes Search API** | Preview de audio de 30s (gratuita, sin clave API) |
| **QR Server API** | Generación de códigos QR para las cartillas |
| **Google Fonts** | Tipografías Bebas Neue y DM Sans |

### APIs externas utilizadas

```
# Preview de audio (30 segundos, gratuita)
https://itunes.apple.com/search?term={canción}&media=music&entity=song&limit=5

# Generación de QR (gratuita, sin registro)
https://api.qrserver.com/v1/create-qr-code/?size=62x62&data={texto}
```

Ambas APIs son gratuitas y no requieren ninguna clave de API ni registro.

---

## 📁 Estructura del proyecto

```
bingo-musical/
│
├── bingo-musical.html    # Aplicación completa (todo en un archivo)
└── README.md             # Este archivo
```

### Estructura interna del HTML

```
bingo-musical.html
├── <style>               # Todos los estilos CSS
├── #screen-home          # Pantalla de selección de categoría
├── #screen-setup         # Pantalla de configuración de jugadores
├── #screen-cards         # Pantalla de cartillas con QR
├── #screen-game          # Pantalla principal del juego
│   ├── .now-playing      # Panel "Ahora suena" + reproductor de audio
│   ├── .board-grid       # Casillero con las 90 canciones
│   └── .game-right       # Panel lateral con mini-cartillas de jugadores
├── #screen-winner        # Pantalla de ganador con confetti
├── #modal-reset          # Modal de confirmación de reinicio
└── <script>              # Toda la lógica JavaScript
    ├── CATALOGS{}        # 6 catálogos de 90 canciones cada uno
    ├── Audio engine      # Reproductor iTunes
    ├── QR generator      # Generación de QR
    └── Game logic        # Sorteo, marcado, cartillas, etc.
```

---

## 🔊 Notas sobre el audio

### ¿Cómo funciona?

Al sortear cada canción, la aplicación realiza una búsqueda en la **iTunes Search API** usando el título y el artista. Si encuentra una preview disponible, la reproduce automáticamente. Las previews tienen una duración de **30 segundos**.

### ¿Funciona siempre?

- ✅ **GitHub Pages / cualquier servidor HTTPS** → Funciona perfectamente.
- ✅ **Servidor local** (`localhost`) → Funciona.
- ⚠️ **Abriendo el HTML directamente** (`file://`) → Puede fallar en algunos navegadores por políticas CORS.
- ❌ **Dentro de iframes sandboxed** (como previsualizadores online) → No funciona.

### Canciones sin preview

Algunas canciones muy antiguas o con restricciones de distribución pueden no tener preview disponible en iTunes. En ese caso la aplicación lo indica con un mensaje y puedes pasar a la siguiente canción.

---

## 📸 Capturas de pantalla

### Pantalla de inicio — Selección de categoría
```
┌─────────────────────────────────────────┐
│           🎵 BINGO MUSICAL              │
│        Elige tu época favorita          │
│                                         │
│  ┌──────────┐  ┌──────────┐  ┌───────┐ │
│  │ 🕺 70s   │  │ 💿 2000s │  │ 🔥    │ │
│  │ 80s 90s  │  │          │  │ Act.  │ │
│  └──────────┘  └──────────┘  └───────┘ │
│  ┌──────────┐  ┌──────────┐  ┌───────┐ │
│  │ 🇪🇸 Esp. │  │ 🇮🇹 Ita. │  │ 🎲    │ │
│  │          │  │          │  │ Mixta │ │
│  └──────────┘  └──────────┘  └───────┘ │
└─────────────────────────────────────────┘
```

### Pantalla de juego
```
┌───────────────────────────────────────────────┐
│ 🎵 Bingo Musical          [↺ Restablecer] [🏆] │
│ Cantadas: 12  Restantes: 78  Jugadores: 3      │
│                                                │
│ ┌──────────────────────┐  ┌──────────────────┐│
│ │ 🎵 AHORA SUENA       │  │ 🎫 CARTILLAS     ││
│ │ Canción 12 de 90     │  │                  ││
│ │ BOHEMIAN RHAPSODY    │  │ 🎫 Ana           ││
│ │ Queen · 1975         │  │ [12 celdas]      ││
│ │ [▶ Siguiente] [⏸]   │  │                  ││
│ │ ══════════════ 🔊    │  │ 🎫 Pedro         ││
│ └──────────────────────┘  │ [12 celdas]      ││
│                            └──────────────────┘│
│ ┌─── CASILLERO 90 CANCIONES ────────────────┐  │
│ │ #1  #2  #3  #4  #5  #6  #7  #8  #9 ...   │  │
│ └────────────────────────────────────────────┘  │
└───────────────────────────────────────────────┘
```

---

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Si quieres añadir canciones, nuevas categorías o mejorar el diseño:

1. Haz un **fork** del repositorio.
2. Crea una rama para tu mejora:
   ```bash
   git checkout -b feature/canciones-latinas
   ```
3. Realiza tus cambios en `bingo-musical.html`.
4. Haz commit con un mensaje descriptivo:
   ```bash
   git commit -m "✨ Añade categoría de canciones latinas"
   ```
5. Sube tu rama:
   ```bash
   git push origin feature/canciones-latinas
   ```
6. Abre un **Pull Request**.

### Ideas para contribuir

- 🎵 Nuevas categorías: canciones francesas, latinas, de los 50s, bandas sonoras de películas...
- 🌍 Traducción de la interfaz a otros idiomas
- 🎨 Nuevos temas de color
- 📊 Estadísticas de partida (tiempo jugado, canciones por jugador...)
- 🔧 Modo de edición para personalizar el catálogo de canciones

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Puedes usarlo, modificarlo y distribuirlo libremente, incluso para fines comerciales, siempre que mantengas el aviso de copyright.

```
MIT License — Copyright (c) 2024
```

---

## 🙏 Créditos

- **iTunes Search API** por Apple — previews de audio gratuitas.
- **QR Server** ([qrserver.com](https://goqr.me/api/)) — generación de QR gratuita.
- **Google Fonts** — tipografías Bebas Neue y DM Sans.
- Desarrollado con ❤️ para hacer el bingo más divertido.

---

<div align="center">
  <strong>¿Te ha gustado el proyecto? ¡Dale una ⭐ en GitHub!</strong>
</div>

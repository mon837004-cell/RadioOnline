<div align="center">

# 📻 Radio Forocochera

### Tu radio online del mundo entero: directorio, globo 3D, favoritos y enlaces para compartir

[![Abrir la radio](https://img.shields.io/badge/▶_Abrir_la_radio-Live-2ea44f?style=for-the-badge)](https://mon837004-cell.github.io/RadioOnline/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![MapLibre](https://img.shields.io/badge/MapLibre_GL-396CB2?style=for-the-badge&logo=maplibre&logoColor=white)

**Miles de emisoras de todo el planeta, un globo terráqueo para explorarlas, favoritos, temas, temporizador y enlaces que abren la emisora directamente.**
Una sola página, sin instalar nada y sin registros. 🎶

[🚀 **Probar ahora**](https://mon837004-cell.github.io/RadioOnline/)

[✨ Características](#-características) · [🌍 Globo](#-el-globo-de-emisoras) · [🔗 Compartir](#-compartir-emisoras) · [🧰 Tecnologías](#-tecnologías)

</div>

---

## ✨ Características

### 🌍 Directorio mundial de emisoras
- 📡 Conectado a la API abierta de **[Radio Browser](https://www.radio-browser.info/)**, con miles de emisoras de todo el mundo.
- 🔎 **Buscador** por nombre de emisora, ciudad o estilo.
- 🗺️ **Filtro por país** (con el número de emisoras de cada uno) y 🎸 **filtro por género**: Rock, Pop, Jazz, Clásica, Flamenco, Electrónica, 80s, 90s y muchos más.
- 🎲 Si no buscas nada, descubres emisoras **variadas** cada vez que entras.
- 🎠 Listado en **carrusel horizontal** con efecto de perspectiva al desplazar (en los navegadores compatibles) y botón para **cargar más emisoras**.
- 🪪 Cada tarjeta muestra el logo, país, región, bitrate y etiquetas de la emisora.
- 📚 Al volver al catálogo desde Favoritos o desde el globo, **se queda justo donde lo dejaste**.

### 🎧 Reproductor
- ▶️ Reproducción y pausa con un toque, con **animación de carga** mientras conecta.
- 📊 **Ecualizador animado** que reacciona al audio cuando la emisora lo permite.
- 🔊 **Volumen** que recuerda tu último ajuste.
- 🎵 **Título de la canción o del programa en tiempo real**, actualizado cada 10 segundos en las emisoras que lo emiten.
- ▶️ **Pulsa sobre el título** y se abre **YouTube** buscando esa canción: la app, si estás en el móvil y la tienes instalada, o una pestaña nueva en el ordenador.
- ⏱️ **Temporizador de apagado**: elige minutos u horas y verás la cuenta atrás en el propio botón.
- 🔄 **Reanudación automática** al volver a la pestaña si el sonido se cortó sin que lo pausaras tú.
- 📱 Integración con los **controles del sistema** (pantalla de bloqueo y notificaciones): reproducir, pausar y detener, con el nombre de la emisora y la canción.

### ⭐ Favoritos
- 💾 Guarda tus emisoras con la estrella; se quedan en tu navegador.
- 📥 **Exporta** tu lista a un archivo JSON y 📤 **impórtala** en otro dispositivo o navegador. Al importar se fusiona con la que ya tienes, sin duplicados.

### 🎨 Temas
Elige el aspecto que más te guste; se guarda para la próxima vez.

| Tema | Estilo |
|---|---|
| 🔵 Clásico Azul | Elegante y sobrio |
| 🌆 Cyberpunk Morado | Neones nocturnos |
| 🌆 Cyberpunk Azul | Futurista y frío |
| 💻 Verde Matrix | Estilo terminal |
| 🔥 Atardecer Fuego | Cálido y vibrante |
| 🖤 OLED Puro | Negro total, ideal para pantallas OLED |

---

## 🌍 El globo de emisoras

Pulsa **🌍 Globo** y explora las emisoras sobre un **globo terráqueo 3D** con imágenes de satélite.

- 📍 Cada punto es una emisora con ubicación. Los puntos cercanos se **agrupan** al alejarte y se separan al acercarte.
- 🏷️ Los nombres aparecen al acercarte y se ocultan solos cuando se pisan, dando prioridad a las más escuchadas.
- 🗺️ **Selector de país** para cargar solo las emisoras de uno, o de **todo el mundo** (avisa antes, muestra una barra de progreso y se puede cancelar).
- 🪪 **Toca un punto** y aparece una **ficha** con el logo, nombre, país, bitrate y etiquetas, con botones para ▶ **reproducir** y ★ **guardar en favoritos**.
- 📌 En el catálogo, las tarjetas de emisoras con coordenadas tienen un **icono de ubicación**: al pulsarlo, el globo vuela hasta esa emisora y la deja marcada con su nombre siempre visible.
- 🌐 Gira despacio hasta que lo tocas. Se cierra con **☰ Lista** o con la tecla `Esc`.
- ⚡ La librería del mapa **solo se descarga al abrir el globo**, así que no ralentiza el arranque.

---

## 🔗 Compartir emisoras

- 📲 Botón de **compartir** en el reproductor, con el menú nativo del móvil (WhatsApp, Telegram, mensajes…).
- 🧭 El enlace abre **tu radio** con la emisora ya cargada y sonando, y aparece la primera de la lista para poder guardarla en favoritos o volver a compartirla.
- 🔔 Si el navegador bloquea el sonido automático al abrir el enlace, la emisora queda cargada con el aviso *"Pulsa play para escuchar"*.
- 🆔 Las emisoras del directorio se comparten por su identificador (`?emisora=…`), así que el enlace siempre pide la dirección actualizada. Las que no lo tienen (por ejemplo, favoritos importados de una copia antigua) se comparten con el stream, el nombre y el país (`?stream=…`).
- 🖥️ En un ordenador sin menú de compartir, el enlace se copia al portapapeles.

---

## 🎶 Títulos de canciones y programas

La radio muestra el título de lo que suena, sea una canción o un programa, en las emisoras que lo envían, y lo va actualizando mientras escuchas. Si pulsas sobre él, se abre YouTube buscando esa canción. Las emisoras que no incluyen el título en su señal no pueden mostrarlo.

---

## 🛡️ Robusto

- 🌐 Usa **varios servidores** de la API y cambia de uno a otro si alguno falla.
- 🔁 **Reintenta** la conexión automáticamente si el directorio no responde a la primera.
- ⚡ Guarda en caché la lista de países para **arrancar más rápido**.
- 🔒 Las preferencias (tema, volumen, país, género y favoritos) se guardan en el navegador, y si el almacenamiento está bloqueado la radio sigue funcionando.
- 🧘 Respeta la opción de **reducir movimiento** del sistema.
- 📱 Diseño **adaptable**: pensado para el móvil y cómodo en el ordenador.

---

## 🧰 Tecnologías

| | |
|---|---|
| 🧱 **Base** | HTML5, CSS3 y JavaScript puro, todo en un único `index.html`, sin build ni dependencias que instalar |
| 📡 **Datos** | [Radio Browser API](https://api.radio-browser.info/) |
| 🌍 **Globo** | [MapLibre GL JS](https://maplibre.org/) con proyección de globo, cargado bajo demanda desde jsDelivr |
| 🛰️ **Imágenes** | Teselas de satélite y etiquetas de [Esri](https://www.esri.com/) |
| 🔤 **Tipografías** | Google Fonts |

## 📂 Estructura

```
📦 RadioOnline
 ┣ 📄 index.html   → toda la aplicación (HTML + CSS + JS)
 ┣ 🖼️ Icono.png    → logo de la radio
 ┣ 📄 LICENSE      → licencia (todos los derechos reservados)
 ┗ 📄 README.md    → este archivo
```

---

## 📄 Licencia

© 2026 RamperDjs **Todos los derechos reservados.**
Puedes ver el código y usar la radio libremente, pero no copiarlo, modificarlo ni redistribuirlo sin permiso por escrito del autor. Consulta el archivo [`LICENSE`](LICENSE) para los detalles.

---

## 🙏 Créditos

- 📡 Emisoras y metadatos: [Radio Browser](https://www.radio-browser.info/), un directorio comunitario y abierto de radios.
- 🌍 Globo: [MapLibre GL JS](https://maplibre.org/) e imágenes de satélite de Esri, Maxar y Earthstar Geographics.
- 📻 Cada emisora es propiedad de sus respectivos titulares; esta aplicación solo enlaza con sus streams públicos.

<div align="center">

**Hecho con ❤️ y mucha música** 🎶

</div>

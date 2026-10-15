# RadioOnline
Radio con emisoras online de todo el mundo

# 📻 Radio Mundial (Tampermonkey UserScript)

**Radio Mundial** es un script de usuario avanzado diseñado para Tampermonkey que te permite acceder a un directorio global de emisoras de radio de todo el planeta directamente desde Google[cite: 1]. Utiliza la API pública de *Radio-Browser* para ofrecer búsqueda en tiempo real, reproducción persistente y gestión avanzada de favoritos[cite: 1].

---

## ✨ Características Principales

* **🌐 Directorio Global de Emisoras**: 
  * Conexión inteligente a múltiples servidores espejo de la API de *Radio-Browser* con tolerancia a fallos[cite: 1].
  * Listado filtrado por popularidad (número de clics) y capacidad de explorar emisoras de cualquier país o género musical[cite: 1].

* **⭐ Gestión Avanzada de Favoritos**:
  * Sistema de marcado rápido con estrellas (`★` / `☆`) guardado de forma persistente mediante `GM_setValue` y respaldo en `localStorage`[cite: 1].
  * **Exportación e Importación JSON**: Permite descargar tu lista de emisoras favoritas en un archivo `.json` o importar copias de seguridad fácilmente desde tu equipo[cite: 1].
  * Opción para vaciar la lista completa con un solo clic[cite: 1].

* **🎧 Reproductor Persistente y Mini-barra Flotante**:
  * Barra de reproducción flotante e integrada que no se interrumpe al navegar[cite: 1].
  * Control de volumen deslizante con sincronización y guardado automático de la preferencia del usuario[cite: 1].
  * Indicadores visuales en tiempo real del estado de conexión, reproducción y carga de audio[cite: 1].

* **🔄 Sistema de Autorreanudación Inteligente**:
  * Detecta automáticamente si la reproducción se ha pausado debido a un evento externo o pérdida de foco y facilita su reanudación al interactuar de nuevo con la página o recuperar la visibilidad de la pestaña[cite: 1].

* **🎨 Diseño y Usabilidad Adaptativa (Responsive)**:
  * Interfaz modal moderna en modo oscuro, optimizada tanto para equipos de escritorio como para pantallas móviles[cite: 1].
  * Búsqueda instantánea con retardo (*debounce*) para optimizar las peticiones al catálogo mientras escribes[cite: 1].

---

## 🛠️ Especificaciones Técnicas

* **Plataforma**: Tampermonkey / Violentmonkey / Greasemonkey[cite: 1].
* **Sitios compatibles**: `https://www.google.com/*`, `https://google.com/*`[cite: 1].
* **Permisos (`@grant`)**: `GM_getValue`, `GM_setValue`[cite: 1].
* **Dependencias**: Ninguna (JavaScript vainilla optimizado para alto rendimiento y bajo consumo de recursos)[cite: 1].

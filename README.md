# 📻 Radio Mundial (Tampermonkey UserScript)

**Radio Mundial** es un script de usuario avanzado diseñado para Tampermonkey que te permite acceder a un directorio global de emisoras de radio de todo el planeta directamente desde Google. Utiliza la API pública de *Radio-Browser* para ofrecer búsqueda en tiempo real, reproducción persistente y gestión avanzada de favoritos.

## ✨ Características Principales

* **🌐 Directorio Global de Emisoras**: 
  * Conexión inteligente a múltiples servidores espejo de la API de *Radio-Browser* con tolerancia a fallos.
  * Listado filtrado por popularidad (número de clics) y capacidad de explorar emisoras de cualquier país o género musical.

* **⭐ Gestión Avanzada de Favoritos**:
  * Sistema de marcado rápido con estrellas (`★` / `☆`) guardado de forma persistente mediante `GM_setValue` y respaldo en `localStorage`.
  * **Exportación e Importación JSON**: Permite descargar tu lista de emisoras favoritas en un archivo `.json` o importar copias de seguridad fácilmente desde tu equipo.
  * Opción para vaciar la lista completa con un solo clic.

* **🎧 Reproductor Persistente y Mini-barra Flotante**:
  * Barra de reproducción flotante e integrada que no se interrumpe al navegar.
  * Control de volumen deslizante con sincronización y guardado automático de la preferencia del usuario.
  * Indicadores visuales en tiempo real del estado de conexión, reproducción y carga de audio.

* **🔄 Sistema de Autorreanudación Inteligente**:
  * Detecta automáticamente si la reproducción se ha pausado debido a un evento externo o pérdida de foco y facilita su reanudación al interactuar de nuevo con la página o recuperar la visibilidad de la pestaña.

* **🎨 Diseño y Usabilidad Adaptativa (Responsive)**:
  * Interfaz modal moderna en modo oscuro, optimizada tanto para equipos de escritorio como para pantallas móviles.
  * Búsqueda instantánea con retardo (*debounce*) para optimizar las peticiones al catálogo mientras escribes.

---

## 🛠️ Especificaciones Técnicas

* **Plataforma**: Tampermonkey / Violentmonkey / Greasemonkey.
* **Sitios compatibles**: `https://www.google.com/*`, `https://google.com/*`.
* **Permisos (`@grant`)**: `GM_getValue`, `GM_setValue`.
* **Dependencias**: Ninguna (JavaScript vainilla optimizado para alto rendimiento y bajo consumo de recursos).

# dashboards/

Tableros interactivos, servidos por GitHub Pages.

Cada archivo es **autónomo**: lleva la librería, los estilos, el script y los
datos adentro. Abre con doble clic, sin servidor y sin internet. Es el mismo
archivo que recibe un cliente — por eso el portfolio lo muestra tal cual, en
vez de una captura.

| Archivo | Origen | Estado |
|---|---|---|
| `attrition.html` | `Antigravity/design/tickets/T-001` | **provisional, en castellano** |

## attrition.html, qué falta antes de publicarlo

1. **Reemplazarlo por la versión en inglés.** El sitio está en inglés y el
   tablero está en castellano. El JSON traducido ya existe; se construye con
   `python3 frontend/build.py T-001-en` en el repo Antigravity.
2. **Esperar el T-003.** La versión de hoy tiene cuatro títulos de eje
   encimados o cortados. En el portfolio eso dice "lo armó un script y nadie
   lo miró".

No se publica hasta que esos dos estén. El archivo está acá para poder probar
los enlaces del sitio, no para que lo vea nadie.

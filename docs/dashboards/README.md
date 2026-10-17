# dashboards/

Tableros interactivos, servidos por GitHub Pages.

Cada archivo es **autónomo**: lleva la librería, los estilos, el script y los
datos adentro. Abre con doble clic, sin servidor y sin internet. Es el mismo
archivo que recibe un cliente — por eso el portfolio lo muestra tal cual, en
vez de una captura.

| Archivo | Origen | Idioma | Estado |
|---|---|---|---|
| `attrition.html` | `Antigravity` · T-001 → T-003 | en-US | listo para publicar |

## Cómo se regenera

En el repo `Antigravity`:

```bash
python3 design/traducir.py T-001 design/datos/T-001-en.json
python3 frontend/build.py T-001-en
cp output/portfolio-sample-ibm-hr-analytics/tablero-employee-attrition.html \
   ../Data_Analytics_Projects/docs/dashboards/attrition.html
```

La versión en castellano del mismo tablero sale de `build.py T-001`, sin tocar
una línea de código: el idioma y los textos viven en el JSON.

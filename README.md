# Archivos que hablan

Presentación en español sobre OCR e ICR, basada en el HTML proporcionado.

## Desarrollo

Sitio estático, sin dependencias ni compilación. Desde la carpeta del repositorio:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

## Despliegue en Vercel

Importar este repositorio en Vercel y seleccionar el preset **Other**, sin comando de compilación y con directorio de salida `.`. También se puede ejecutar `npx vercel --prod` tras iniciar sesión.

Las imágenes se sirven desde `https://ocr-icr-documentos.vercel.app/assets/`; requieren que ese sitio siga disponible.

## PDF completo

En la presentación, pulsa **Guardar PDF** y selecciona **Guardar como PDF** en el cuadro de impresión. Exporta todas las páginas, sin márgenes y con **Gráficos de fondo** activados. El formato es horizontal (16:9), con las 22 diapositivas, una por página. Usa preferiblemente Chrome o Edge desde un computador.

La exportación se hace en el navegador para conservar las imágenes que ya carga el sitio. El PDF es estático: los controles y animaciones no son interactivos. Los resultados adicionales de los desplegables de respaldo no se añaden como páginas; se exportan las 22 diapositivas principales.

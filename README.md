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

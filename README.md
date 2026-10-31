# Incrustador de PDFs

Herramienta web para **incrustar archivos de cualquier tipo dentro de un PDF** (Word, Excel, PowerPoint, imágenes, texto, otros PDF…) directamente desde el navegador.

Todo el procesamiento se hace en local: **ningún archivo se sube a un servidor**.

## Características

- Interfaz de estilo neón, con soporte para arrastrar y soltar.
- Admite cualquier tipo de archivo como adjunto.
- Lista de archivos con opción de quitar cada uno antes de incrustar.
- Descarga del resultado como `nombre_incrustado.pdf`.
- Un único archivo HTML, sin instalación ni servidor.

## Uso

1. Abre `pdf-embedder.html` en tu navegador (doble clic) o accede a la versión publicada en GitHub Pages.
2. Selecciona o arrastra el **PDF** base.
3. Selecciona o arrastra los **archivos a incrustar**.
4. Pulsa **Incrustar archivos**.
5. Pulsa **Descargar PDF**.

Los archivos incrustados aparecen en el panel de adjuntos del lector de PDF (Adobe Acrobat, Foxit, Chrome, etc.).

## Tecnologías

- HTML, CSS y JavaScript puro.
- [pdf-lib](https://pdf-lib.js.org/) 1.17.1, cargada desde cdnjs.
- Tipografías Orbitron e Inter, desde Google Fonts.

## Limitaciones

- Requiere conexión a internet para cargar pdf-lib y las tipografías.
- No admite PDF protegidos con contraseña.
- Con archivos muy grandes (cientos de MB) el navegador puede ir lento o quedarse sin memoria.

## Origen

Versión web de un script de escritorio en Python (Tkinter + PyMuPDF).

## Autoría

Software desarrollado por **DLR**.

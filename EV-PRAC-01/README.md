# EV-PRAC-01 — Evaluación de la Unidad I

**Tema:** EV-PRAC-01 - SUM - Proceso de requisitos y el framework de IR. Resolver el problema  
**Código de entrega en el SGA:** EV-SUM-01  
**Código de la guía de la prueba escrita:** EV-PRAC-01  
**Cuestionario en línea:** EV-CUE-01  
**Caso de estudio:** Sistema de alerta temprana de crecidas «ALERTARÍO»  
**Estudiante:** Cedeño Avila Winston Damian  
**Universidad:** Universidad Técnica Estatal de Quevedo (UTEQ)  
**Asignatura:** Ingeniería de Requerimientos (ISR-401)  
**Nivel y paralelo:** Cuarto nivel, paralelo B  
**Período académico:** 2026–2027 SPA  
**Fecha de la sesión:** 18 de noviembre de 2026  
**Cierre de la entrega:** 18 de noviembre de 2026, 23:59 (SGA)

## Contenido

La evaluación de la Unidad I aborda los conceptos de requisitos, los documentos StRS/SyRS/SRS, el proceso de Ingeniería de Requisitos y la clasificación y calidad de los requisitos aplicados al caso ALERTARÍO. La documentación digital respeta el contenido de las hojas manuscritas, sin completar respuestas fuera de ellas.

## Estructura de archivos

```text
EV-PRAC-01/
├── README.md             # Documentación de la actividad
├── evidencias/
│   ├── hoja-01.jpg       # Primera hoja manuscrita
│   ├── hoja-02.jpg       # Segunda hoja manuscrita
│   └── hoja-03.jpg       # Tercera hoja manuscrita
├── main.tex              # Archivo principal de la transcripción LaTeX
├── main.pdf              # Resultado compilado del archivo principal
└── logoband.png          # Encabezado gráfico usado por main.tex
```

El archivo `evidencias/.gitkeep` es un marcador técnico de la carpeta y no forma parte de las respuestas. Las fotografías originales permanecen en `evidencias/` y **no se insertan en `main.pdf`**.

## Reproducción del PDF desde LaTeX

- **Compilador:** pdfLaTeX (`pdflatex`).
- **Archivo principal:** `EV-PRAC-01/main.tex`.
- **Archivo generado:** `EV-PRAC-01/main.pdf`.
- **Dependencia de imagen:** `logoband.png` debe estar junto a `main.tex`.
- **Distribución LaTeX:** TeX Live o MiKTeX con los paquetes empleados por el documento.
- **Paquetes utilizados:** `inputenc`, `fontenc`, `helvet`, `geometry`, `graphicx`, `array`, `tabularx`, `longtable`, `pdflscape`, `colortbl`, `xcolor`, `enumitem`, `fancyhdr`, `lastpage`, `tcolorbox` con la biblioteca `most`, `amsmath`, `url`, `needspace`, `caption` e `hyperref`. 

Desde la raíz del repositorio, ejecutar **en este orden**:

```bash
cd EV-PRAC-01
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

La primera ejecución genera el PDF y la segunda actualiza el total de páginas empleado en el pie. Este `main.tex` **no requiere BibTeX ni archivo `referencias.bib`**.

Comprobar que `main.pdf` puede abrirse y que reproduce las respuestas de las tres fotografías. Los contenidos manuscritos, incluidos los errores presentes en los originales, no deben corregirse como parte de la transcripción.

## Registro de evidencias y transcripción

Las fotografías deben conservar sus nombres `hoja-01.jpg`, `hoja-02.jpg`, `hoja-03.jpg`, en ese orden. La guía establece separar el commit de evidencias del commit que incorpora la transcripción LaTeX, de modo que pueda comprobarse el desarrollo escrito antes de su digitalización.

## Entrega al SGA

La entrega en el SGA consiste en un **PDF independiente de una página**, con:

1. Apellidos y nombres completos, asignatura, nivel y paralelo.
2. Código y nombre de la evaluación.
3. Fecha de la sesión y fecha límite: **18/11/2026, 23:59**.
4. URL del repositorio personal, completa y visible en una sola línea.
5. Captura del resumen del cuestionario con identificación del estudiante, datos de la prueba y calificación global.

**Repositorio:** https://github.com/WinstonCD/ISR401-Aportes-Winston-Cedeno

La captura elegida para la carátula procede de la pantalla «Revisión de intento» del cuestionario y muestra la calificación **5,67/10**. `EV-CUE-01` es el código del cuestionario en línea y **no constituye un nombre de archivo obligatorio para la imagen**.

La guía exige también la entrega previa de las actividades formativas vinculadas **GA-TL-01** y **GA-PRAC-01**, así como la digitalización fiel y la entrega dentro del plazo indicado.

# EV-PRAC-01 — Evaluación de la Unidad I

**Actividad:** EV-PRAC-01 - SUM - Proceso de requisitos y el framework de IR. Resolver el problema  
**Código en el SGA:** EV-SUM-01  
**Cuestionario en línea:** EV-CUE-01  
**Caso:** Sistema de alerta temprana de crecidas «ALERTARÍO»  
**Estudiante:** Cedeño Avila Winston Damian  
**Universidad:** Universidad Técnica Estatal de Quevedo (UTEQ)  
**Asignatura:** Ingeniería de Requerimientos (ISR-401)  
**Nivel y paralelo:** Cuarto nivel, paralelo B  
**Período:** 2026–2027 SPA  
**Fecha de evaluación:** 18 de noviembre de 2026  
**Cierre en el SGA:** 18 de noviembre de 2026, 23:59

## Descripción

Evaluación individual sobre fundamentos y proceso de Ingeniería de Requisitos, aplicada al caso ALERTARÍO. La carpeta conserva el desarrollo manuscrito de la prueba y su digitalización.

## Archivos

```text
EV-PRAC-01/
├── README.md
├── evidencias/
│   ├── hoja-01.jpg
│   ├── hoja-02.jpg
│   └── hoja-03.jpg
├── main.tex
├── main.pdf
└── logoband.png
```

Las fotografías de las tres hojas originales se encuentran en `evidencias/`; el documento digital `main.pdf` contiene la transcripción y no incorpora las fotografías.

## Compilación de LaTeX

- **Compilador:** pdfLaTeX, disponible en TeX Live o MiKTeX.
- **Archivo principal:** `EV-PRAC-01/main.tex`.
- **Salida:** `EV-PRAC-01/main.pdf`.
- **Imagen requerida:** `EV-PRAC-01/logoband.png`.
- **Paquetes:** `inputenc`, `fontenc`, `helvet`, `geometry`, `graphicx`, `array`, `tabularx`, `longtable`, `pdflscape`, `colortbl`, `xcolor`, `enumitem`, `fancyhdr`, `lastpage`, `tcolorbox` (biblioteca `most`), `amsmath`, `url`, `needspace`, `caption` e `hyperref`.

Desde la raíz del repositorio, ejecutar en el siguiente orden:

```bash
cd EV-PRAC-01
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

La segunda ejecución resuelve la referencia del número total de páginas. Esta transcripción no requiere BibTeX ni `referencias.bib`.

## Evidencias y entrega

Las hojas manuscritas están identificadas como `hoja-01.jpg`, `hoja-02.jpg` y `hoja-03.jpg`. Su incorporación al repositorio se registró en un commit anterior al de la transcripción.

Para la entrega en el SGA se utiliza un **PDF independiente de una página** que incluye los datos de identificación, código y nombre de la evaluación, fecha de la sesión y fecha límite, URL completa del repositorio en una sola línea y capturas del resumen del cuestionario con su calificación.

**Repositorio:** https://github.com/WinstonCD/ISR401-Aportes-Winston-Cedeno

**Formativas vinculadas:** GA-TL-01 y GA-PRAC-01.

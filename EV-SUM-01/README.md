# EV-SUM-01 — Evaluación sumativa de la Unidad I

**Universidad:** Universidad Técnica Estatal de Quevedo (UTEQ)  
**Asignatura:** Ingeniería de Requisitos (ISR-401)  
**Estudiante:** Winston Damian Cedeño Avila  
**Nivel y paralelo:** 4.º «B»  
**Período:** 2026–2027 SPA  
**Caso de estudio:** ALERTARÍO

## Descripción

Evaluación individual de los fundamentos de Ingeniería de Requisitos de las semanas 1 a 3: identificación, clasificación, calidad y formulación de requisitos, proceso de requisitos, estándares y documentos StRS, SyRS y SRS.

## Estado

**Pendiente de evidencias y transcripción fiel.** La creación de esta carpeta y README no equivale a la entrega de la evaluación.

## Estructura prevista

```text
EV-SUM-01/
├── README.md
├── evidencias/
│   ├── hoja-01.jpg
│   └── hoja-02.jpg
├── main.tex
└── main.pdf
```

Los nombres de fotografías son ilustrativos; se agregarán tantos archivos como hojas originales existan. No se incluyen las fotos dentro de `main.pdf`.

## Procedimiento de digitalización

1. **Después de entregar la prueba escrita**, fotografiar las hojas completas en presencia del docente, según la guía.
2. Subir primero las fotografías a `evidencias/` en un commit independiente.
3. Transcribir en `main.tex` exactamente lo escrito a mano, respetando el orden, la numeración, los errores originales y las tablas. No transcribir los tachones, no añadir ni mejorar respuestas.
4. Incluir al comienzo la declaración de transcripción fiel exigida por la guía, con la fecha real.
5. Compilar `main.pdf` y comparar la versión digital con las fotografías originales.
6. Registrar la transcripción y el PDF en un segundo commit o en varios posteriores.

## Compilación de LaTeX

**Compilador previsto:** pdfLaTeX (`pdflatex`).  
**Archivo principal:** `main.tex`.  
**Archivo de salida:** `main.pdf`.  
**Entorno:** TeX Live o MiKTeX con pdfLaTeX.

Desde la raíz del repositorio:

```bash
cd EV-SUM-01
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

**Pendiente de verificación:** todavía no existe `main.tex` en esta carpeta. Al incorporar la transcripción se confirmarán la compilación, los paquetes LaTeX necesarios y los comandos definitivos, y se actualizará esta sección.

## Entrega en el SGA

Según la guía de evaluación completa, además de la digitalización en el repositorio, se debe subir al SGA un PDF **de una sola página** con:

- Datos del estudiante, asignatura, nivel y paralelo
- Código y nombre de la evaluación
- Fecha de la sesión y fecha límite
- URL completa del repositorio en una sola línea
- Captura del resumen del cuestionario SGA con los datos requeridos

**Repositorio:** https://github.com/WinstonCD/ISR401-Aportes-Winston-Cedeno

## Integridad y referencias

La transcripción será una reproducción fiel del manuscrito, no una corrección posterior. La guía cita ISO/IEC/IEEE 29148:2018, ISO/IEC 25010:2023, SWEBOK v4.0 y Pohl como referencias de la evaluación.

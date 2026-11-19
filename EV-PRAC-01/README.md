# EV-PRAC-01

Transcripción de la evaluación manuscrita EV-PRAC-01, con las evidencias fotográficas originales en el anexo del PDF.

## Estructura

- `main.tex`: archivo principal de LaTeX.
- `main.pdf`: documento compilado.
- `evidencias/hoja-1.jpg` a `hoja-4.jpg`: fotografías de las hojas manuscritas.

## Compilación

**Compilador:** pdfLaTeX  
**Archivo principal:** `main.tex`  
**Dependencias:** distribución LaTeX con los paquetes `babel`, `geometry`, `graphicx`, `float`, `longtable`, `array`, `booktabs`, `enumitem`, `caption` y `hyperref`.

Desde la carpeta `EV-PRAC-01`, ejecutar:

```bash
pdflatex main.tex
pdflatex main.tex
```

El segundo comando actualiza referencias y el PDF final se genera como `main.pdf`.

Las imágenes del anexo deben permanecer en la carpeta `evidencias/` con los nombres indicados.

## Nota sobre las evidencias

Las fotografías originales se conservan como respaldo de la transcripción y se incorporan al PDF en el apartado de anexos.

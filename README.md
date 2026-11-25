# FORM-IC-01-Loor-Mendoza-Byron-Daniel
Investigación individual sobre la arquitectura de microservicios de la plataforma de VALORANT de Riot Games.

Estado: borrador técnico incompleto. No es una entrega terminada ni contiene análisis personal. Codex preparó la estructura LaTeX, la entrada bibliográfica oficial y las instrucciones de compilación; Byron debe realizar la lectura, el análisis y las anotaciones personales. No se ha localizado el encuadre mediante búsqueda por nombre en el espacio de trabajo.

Principal: `informe.tex`. Compilador: pdfLaTeX; bibliografía: Biber con biblatex IEEE. Dependencias: distribución TeX (MiKTeX o TeX Live), paquetes `babel` (español), `fontenc`, `inputenc`, `cabin` (Cabin Condensed, requiere `fontaxes`), `geometry`, `graphicx`, `hyperref`, `biblatex` y `biblatex-ieee`.

```powershell
pdflatex -interaction=nonstopmode -halt-on-error informe.tex
biber informe
pdflatex -interaction=nonstopmode -halt-on-error informe.tex
pdflatex -interaction=nonstopmode -halt-on-error informe.tex
```

Pendientes antes de entregar: contrastar guía, rúbrica, encuadre y restricciones de IA; redactar personalmente una página de análisis excluyendo carátula y referencias; incorporar al menos dos fuentes académicas verificadas de los últimos cinco años; agregar en `capturas/` una captura auténtica anotada por Byron e incluirla en el documento; desarrollar el ejemplo conocido personalmente y la aplicación al PFC real; completar la declaración precisa de IA y volver a verificar visualmente el PDF final. Los comentarios LaTeX orientan el trabajo y no se imprimen. La ubicación de evidencia y declaración debe respetar la guía y su límite de extensión.

Validación del esqueleto: compilación pdfLaTeX + Biber + pdfLaTeX + pdfLaTeX completada. El PDF de borrador tiene tres páginas: carátula, estructura de una página sin análisis y referencias. No contiene capturas ni evidencia personal.

Cierre indicado para la actividad: 28 de noviembre de 2026, 23:59 (America/Guayaquil).

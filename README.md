# FORM-IC-01-Loor-Mendoza-Byron-Daniel
Investigación individual sobre la arquitectura de microservicios de la plataforma de VALORANT de Riot Games.

Estado: borrador técnico incompleto. No es una entrega terminada ni contiene análisis personal. Codex preparó la estructura LaTeX, las entradas bibliográficas y las instrucciones de compilación; Byron debe realizar la lectura, el análisis y las anotaciones personales. No se ha localizado el encuadre mediante búsqueda por nombre en el espacio de trabajo.

Principal: `informe.tex`. Compilador: pdfLaTeX; bibliografía: Biber con biblatex IEEE. Dependencias: distribución TeX (MiKTeX o TeX Live), paquetes `babel` (español), `fontenc`, `inputenc`, `cabin` (Cabin Condensed, requiere `fontaxes`), `geometry`, `graphicx`, `hyperref`, `biblatex` y `biblatex-ieee`.

```powershell
pdflatex -interaction=nonstopmode -halt-on-error informe.tex
biber informe
pdflatex -interaction=nonstopmode -halt-on-error informe.tex
pdflatex -interaction=nonstopmode -halt-on-error informe.tex
```

Verificación bibliográfica por Codex (25 de noviembre de 2026): se cotejaron título, lista completa de autores, revista, año, volumen, número y páginas con Wiley para [Hassan, Bahsoon y Buyya (2022)](https://doi.org/10.1002/spe.3069), sobre escalabilidad y granularidad, y [Aderaldo y colaboradores (2025)](https://doi.org/10.1002/spe.3368), sobre evaluación de patrones de resiliencia. El segundo apareció en línea el 28 de agosto de 2024 y pertenece al volumen 55, número 1, de enero de 2025. Ambos están dentro del intervalo 28 de noviembre de 2021 a 28 de noviembre de 2026. Se conserva la forma de los nombres e iniciales publicada por la editorial. Esta comprobación no acredita lectura personal de Byron ni resultados específicos de Riot. Las tres entradas se muestran en la bibliografía mediante `\nocite`; el alumno deberá citar en su análisis las fuentes que realmente utilice.

Pendientes antes de entregar: contrastar guía, rúbrica, encuadre y restricciones de IA; leer y evaluar personalmente las fuentes seleccionadas; redactar personalmente una página de análisis excluyendo carátula y referencias; agregar en `capturas/` una captura auténtica anotada por Byron e incluirla en el documento; desarrollar el ejemplo conocido personalmente y la aplicación al PFC real; completar la declaración precisa de IA y volver a verificar visualmente el PDF final. Los comentarios LaTeX orientan el trabajo y no se imprimen. La ubicación de evidencia y declaración debe respetar la guía y su límite de extensión.

Validación del esqueleto: compilación pdfLaTeX + Biber + pdfLaTeX + pdfLaTeX completada. El PDF de borrador tiene tres páginas: carátula, estructura de una página sin análisis y referencias. No contiene capturas ni evidencia personal.

Cierre indicado para la actividad: 28 de noviembre de 2026, 23:59 (America/Guayaquil).

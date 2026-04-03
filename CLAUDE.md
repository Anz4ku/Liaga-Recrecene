# Liaga Recrecenie — Project Memory

## Ejemplos con frases en conlang
- Las traducciones siempre van **debajo** de la frase, nunca en la misma línea.
- Usar `<span class="tr">` para la traducción — tiene `display:block` global, color muted y font-size pequeño (.78rem).
- Si los ejemplos van centrados, usar `<p style="text-align:center"><em>frase</em><span class="tr">'traducción'</span></p>`.
- No usar recuadros grises (`.exs` / `.ex-row` / `.ex-word`) para ejemplos nuevos — ese estilo está en desuso.

## Tablas fonológicas
- Las tablas de vocales/consonantes en el panel Fonología llevan **solo las columnas estrictamente necesarias** — nunca añadir columnas extra de "Aproximado", "Equivalentes" u otras aclaraciones no pedidas.
- El **diagrama de vocales** es un SVG trapecio (IPA estándar) con líneas estructurales y labels IPA simples. Sin columnas, sin tablas paralelas al SVG a menos que se pida explícitamente.
- Al recrear un diagrama de referencia, reproducirlo **tal cual** adaptando solo lo que el usuario haya pedido cambiar.

## Commits
- Commitear solo al final de cada sesión, nunca a mitad.

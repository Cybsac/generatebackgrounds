---
name: flyer-backgrounds
description: Generar fondos raster limpios, elegantes y funcionales para flyers comerciales, shows, discotecas, promociones y eventos. Usar para crear o variar backgrounds con degradados, halos, atmósfera y efectos sutiles, interpretando título, público, marca y distribución. Excluir flyers completos, personajes, logos y títulos renderizados salvo solicitud explícita.
---

# Fondos para flyers

## Principio visual
Crear un escenario gráfico que sostenga la publicidad: degradado continuo, profundidad suave, contraste útil y zonas tranquilas para texto y personajes. Interpretar el show mediante color, luz y ritmo; evitar convertir el fondo en una ilustración literal. Priorizar elegancia y funcionalidad frente a acumulación de efectos.

## Leer el contexto
1. Extraer del pedido: título del show, concepto, público, tono, marca, paleta obligatoria, personaje/producto, formato, ubicación de título, sujeto, fecha y pie. Aprovechar información visible de la conversación. No inventar promociones ni datos.
2. Inspeccionar imágenes de referencia antes de usarlas. Separar fondo de personajes, títulos, bebidas, logos y placas. Tomar del fondo su transición tonal, dirección de luz, profundidad, textura y densidad; no copiar la pieza completa.
3. Traducir el título a 2–3 atributos visuales. Tratar asociaciones como hipótesis creativas, no como hechos: “Bajos instintos” → tensión, profundidad, calor; “Noche de chicas” → confianza, energía, glamour. No imponer rosa por género, negro por lujo ni rojo por fiesta.
4. Dar prioridad a instrucciones explícitas y marca, después legibilidad y layout, después asociaciones del show. Si no hay layout, asumir título arriba, sujeto central y pie abajo. Si no hay formato, usar vertical 4:5. Preguntar solo cuando una contradicción impida ejecutar.

## Componer la receta
Leer [combinaciones.md](references/combinaciones.md) para seleccionar parámetros y ejemplos. Definir antes de generar:
- Paleta: 2–4 colores con funciones base, profundidad, luz y acento. Admitir cualquier familia cromática y combinaciones cálidas, frías, neutras o mixtas.
- Campo: lineal, radial, diagonal, elíptico, malla suave o doble foco. Determinar orientación y posición a partir del layout.
- Luz: un foco principal amplio, opcionalmente un contraluz tenue; evitar puntos blancos quemados.
- Profundidad: transición oscura de pie o bordes, viñeta suave opcional, sin marco visible.
- Efectos: elegir cero, uno o dos. Humo difuso, bloom moderado, grano fino, bokeh desenfocado o silueta tonal casi imperceptible. No activar todos.
- Zonas útiles: reservar aproximadamente 30–45% de baja variación visual para textos; pie más tranquilo para información comercial. Mantener foco detrás del sujeto y fuera de letras, salvo que su contraste lo justifique.
- Intensidad: sobria, equilibrada o enérgica. Hacer que alto impacto provenga de relaciones de color y luz, no de ruido.

## Generar
Usar image_gen para creación y edición raster; seguir su skill disponible. Generar un fondo opaco por defecto: transparencia solo si se solicita un overlay. No sustituir una generación solicitada por un prompt escrito.
Construir el prompt con esta plantilla:

“Fondo únicamente para flyer comercial [formato]. Contexto: [show y atributos]. Paleta [colores y roles]. Degradado [tipo, dirección, distribución]. Luz [posición y suavidad]. Profundidad [tratamiento]. Efectos [selección y densidad]. Reservar [zonas y contraste esperado para título/sujeto/pie]. Acabado elegante, limpio, sutil, transiciones continuas. Sin texto, letras, números, logos, personas, personajes, productos, placas, objetos reconocibles, escenarios detallados ni marcas de agua.”

Indicar los títulos únicamente como contexto semántico y exigir que no aparezcan escritos. Pedir formas abstractas, no elementos comerciales de la referencia. Incluir siluetas temáticas solo cuando se hayan solicitado o sean parte explícita de la dirección; mantenerlas periféricas y de bajo contraste.

## Variar sin perder identidad
Conservar restricciones de marca y zonas útiles. Para otra variante cambiar al menos dos ejes estructurales: orientación del degradado, posición del foco, distribución claro/oscuro, relación cromática o efecto. Evitar simples cambios de tono en la misma composición. Para varias opciones formular recetas independientes; generar solo la cantidad pedida. No prometer resultados literalmente ilimitados: usar un sistema abierto de combinaciones coherentes.

## Verificar y entregar
Inspeccionar el resultado: fondo solo, paleta coherente, ausencia de objetos/texto, zonas libres, foco bien situado, efectos discretos, transiciones sin bandas perceptibles y bordes limpios. Evaluar legibilidad según texto claro u oscuro previsto; no afirmar ratios medidos si no se midieron. Si falla, corregir el defecto específico y revisar de nuevo. Para transparencia, verificar canal alfa y limpieza, no confundir fondo negro con transparencia. Entregar la imagen con una frase breve sobre paleta y layout; no afirmar que se generó si solo se preparó un prompt.

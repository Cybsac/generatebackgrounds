---
name: flyer-backgrounds
description: Generar fondos raster limpios, elegantes y funcionales para flyers comerciales, shows, discotecas, promociones y eventos. Usar para crear o variar backgrounds con degradados, halos, atmósfera y efectos sutiles, interpretando título, público, marca y distribución. Excluir flyers completos, personajes, logos y títulos renderizados salvo solicitud explícita.
---

# Fondos para flyers

## Principio visual
Crear un escenario gráfico que sostenga la publicidad: profundidad, contraste útil y zonas tranquilas para texto, personajes e información. Interpretar el show mediante color, luz, encuadre y atmósfera. Evitar fondos genéricos tipo plantilla de Word: ondas doradas, cintas abstractas, filigranas y patrones decorativos sin relación con el evento. La elegancia nace de la dirección de arte y la funcionalidad, no de un acabado de stock. No convertir esa exclusión en prohibición de formas abstractas pertinentes.

## Leer el contexto
1. Extraer del pedido: título del show, concepto, público, tono, marca, paleta obligatoria, personaje/producto, formato, ubicación de título, sujeto, fecha y pie. Aprovechar información visible de la conversación. No inventar promociones ni datos.
2. Inspeccionar imágenes de referencia antes de usarlas. Separar fondo de personajes, títulos, bebidas, logos y placas. Tomar del fondo su transición tonal, dirección de luz, profundidad, textura y densidad; no copiar la pieza completa.
3. Traducir el título a 2–3 atributos visuales. Tratar asociaciones como hipótesis creativas, no como hechos: “Bajos instintos” → tensión, profundidad, calor; “Noche de chicas” → confianza, energía, glamour. No imponer rosa por género, negro por lujo ni rojo por fiesta.
4. Dar prioridad a instrucciones explícitas y marca, después legibilidad y layout, después asociaciones del show. Si no hay layout, asumir título arriba, sujeto central y pie abajo. Si no hay formato, usar vertical 4:5. Preguntar solo cuando una contradicción impida ejecutar.

## Componer la receta
Leer [combinaciones.md](references/combinaciones.md) para seleccionar parámetros y ejemplos. Definir antes de generar:
- Paleta: 2–4 colores con funciones base, profundidad, luz y acento. Ámbar es la identidad principal de esta campaña y el punto de partida cuando no se indique otra dirección. Permitir otras paletas según el show; no teñir todos los eventos de naranja ni imponer ámbar sobre una marca o paleta explícita. Admitir combinaciones cálidas, frías, neutras o mixtas.
- Encuadre: elegir giro, punto de vista, escala/zoom y recorte con intención. Un fragmento ampliado y oblicuo puede aportar más carácter que un escenario completo. No repetir automáticamente esquinas, suelo y foco central en cada encargo; adaptar la perspectiva de cualquier superficie al futuro montaje.
- Campo: lineal, radial, diagonal, elíptico, malla suave o doble foco. Determinar orientación y posición a partir del layout.
- Luz: un foco principal amplio, opcionalmente un contraluz tenue; evitar puntos blancos quemados.
- Profundidad: transición oscura de pie o bordes, viñeta suave opcional, sin marco visible.
- Efectos: elegir cero, uno o dos. Humo difuso, bloom moderado, grano fino, bokeh desenfocado o silueta tonal casi imperceptible. No activar todos.
- Zonas útiles: reservar aproximadamente 30–45% de baja variación visual para textos; pie más tranquilo para información comercial. Mantener foco detrás del sujeto y fuera de letras, salvo que su contraste lo justifique.
- Intensidad: sobria, equilibrada o enérgica. Hacer que alto impacto provenga de relaciones de color y luz, no de ruido.

## Patrones y fotografía subordinada

Usar patrones vinculados a la disco o al evento: malla acústica, retícula de luminarias, reflejos de vidrio, mosaico de espejos o tramas conceptuales pertinentes. Seleccionar por significado y utilidad, no activar todos. Ajustar tamaño, orientación, nitidez y contraste; evitar detalle fino repetido que compita con letras o produzca vibración visual. Un patrón abstracto también es válido si tiene dirección específica y no parece decoración de plantilla.

Admitir fotografía o escenas sutiles en los bordes cuando aporten contexto: fragmentos de cabina, barra, luminarias, percusión o detalles temáticos. Mantenerlos recortados, periféricos y subordinados por escala de área, desenfoque o contraste. No convertir un micrófono, calabaza o consola en protagonista por inercia. No añadir personas, marcas ni el producto que se colocará después. Respetar pedidos de fondo completamente abstracto o sin objetos.

La escena debe acompañar, no formar un marco rígido alrededor del contenido. Evitar reutilizar una fórmula fija de objeto en una esquina + lámparas en la opuesta. Para agendas densas ampliar el campo tranquilo respecto de un flyer de un solo show; para promociones reservar la zona del producto y la de oferta/precio. Las proporciones son orientativas: prevalece el layout real.

## Generar
Usar image_gen para creación y edición raster; seguir su skill disponible. Generar un fondo opaco por defecto: transparencia solo si se solicita un overlay. No sustituir una generación solicitada por un prompt escrito.
Construir el prompt con esta plantilla:

“Fondo únicamente para flyer comercial [formato]. Contexto: [show y atributos]. Paleta [colores y roles]. Campo tonal [tipo, dirección, distribución]. Encuadre [giro, perspectiva, zoom y recorte]. Luz [posición y suavidad]. Profundidad [tratamiento]. [Patrón pertinente o fragmentos fotográficos periféricos, su escala y densidad / fondo abstracto sin objetos]. Efectos [selección]. Reservar [zonas y contraste para título/personas/producto/información]. Acabado limpio de alta calidad, transiciones continuas; fotografía subordinada al montaje. Sin texto, letras, números, logos, personas, personajes, productos protagonistas, placas ni marcas de agua. Sin objetos no especificados, escena detallada o decoración genérica de plantilla.”

Indicar los títulos únicamente como contexto semántico y exigir que no aparezcan escritos. Extraer atmósfera de referencias, sin copiar sus marcas, ofertas o protagonistas. Si se elige fotografía periférica, describir exactamente qué fragmentos se permiten y cómo se subordinan; si se elige abstracción, excluir objetos. No combinar una orden de escena fotográfica con una prohibición contradictoria de todo objeto reconocible.

## Variar sin perder identidad
Conservar restricciones de marca y zonas útiles. Para otra variante cambiar al menos dos ejes estructurales, incluyendo uno espacial: encuadre, giro/perspectiva, escala/recorte, posición del foco, distribución claro/oscuro, patrón o escena periférica. Cambiar solo color y efecto no basta. Para varias opciones formular recetas independientes; no producir la misma habitación recoloreada ni una plantilla de esquinas repetida. Generar solo la cantidad pedida. No prometer resultados literalmente ilimitados: usar combinaciones coherentes.

## Verificar y entregar
Inspeccionar el resultado: fondo solo, paleta coherente, ausencia de texto/protagonistas/objetos no autorizados, zonas libres, foco bien situado, patrones y fotografía realmente secundarios, efectos discretos, transiciones sin bandas perceptibles y bordes limpios. Si la escena capta la atención antes que el futuro contenido, reducir área, contraste o nitidez. Verificar diferencia espacial frente a la variante anterior y ausencia de apariencia de plantilla. Evaluar legibilidad según texto claro u oscuro previsto; no afirmar ratios medidos si no se midieron. Si falla, corregir el defecto específico y revisar de nuevo. Para transparencia, verificar canal alfa y limpieza, no confundir fondo negro con transparencia. Entregar la imagen con una frase breve sobre paleta y layout; no afirmar que se generó si solo se preparó un prompt.

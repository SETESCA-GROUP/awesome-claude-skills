# Tics de IA en castellano: qué vigilar y cómo tratarlo

Lista de patrones que delatan texto generado y que restan credibilidad a un CTO. Adaptada al español a
partir de los léxicos en inglés de dos repos públicos; **los léxicos en inglés no se pueden reutilizar tal
cual**, así que esto es una versión propia.

## Principio

**Marcar y reescribir con criterio, no sustituir con regex.** Cambiar la forma de una frase exige juicio.
Y lo que delata es la **densidad y la repetición**, no la existencia de un recurso: casi todos los autores
humanos usan tríadas o contrastes. El problema es usarlos todos, en cada párrafo, sin contenido detrás.

**Regla de densidad por post:** como máximo **un contraste** ("no es X, es Y") y **una tríada**. Cero puentes
de revelación.

## Vocabulario a evitar (y alternativa)

| Evitar | Mejor |
|---|---|
| "sumergirse en", "profundizar en" (como muletilla) | "analizar", "ver" |
| "en el panorama actual", "en el mundo actual", "en la era de la IA" | empezar directamente por el hecho |
| "potenciar", "impulsar", "aprovechar al máximo" | verbo concreto: "reducir", "automatizar", "acortar" |
| "robusto", "sin fisuras", "holístico", "de extremo a extremo" (sin dato) | el atributo medible: "con trazabilidad por respuesta" |
| "revolucionar", "transformar por completo", "game changer", "disrupción" | el cambio concreto y su cifra |
| "desbloquear", "liberar el potencial" | qué se consigue exactamente |
| "sinergias", "ecosistema" (como relleno), "paradigma" | nombrar las piezas |
| "sin duda", "es fundamental", "cabe destacar", "vale la pena señalar" | borrar; si es importante, se nota |

## Estructuras a marcar

1. **"No es solo X, es Y"** / "No se trata de X, sino de Y" repetido o sin contenido.
2. **Tríadas automáticas** ("rápido, fiable y escalable") sin cifra ni ejemplo detrás.
3. **Puentes de revelación:** "¿El resultado?", "Spoiler:", "Plot twist:", "Y aquí viene lo mejor".
4. **Teasers vacíos:** "lo que nadie te cuenta", "lo que casi nadie ve" sin pagar el gancho en dos líneas.
5. **Fragmentos apilados:** más de dos frases sueltas de una palabra seguidas.
6. **Candor anunciado:** "voy a ser sincero", "confesión:" sin un hecho fechado y desagradable detrás.
7. **Aperturas genéricas:** "Hoy quiero hablaros de…", "En un mundo cada vez más…".
8. **Cierres de relleno:** "¿Qué opináis?", "¿Estáis de acuerdo?", "Etiqueta a alguien que lo necesite".
9. **Uniformidad:** todas las frases con la misma longitud, todos los párrafos de una línea idéntica.
10. **Muro de emojis o de hashtags.**

## Tipografía

- **Raya larga (—):** no está prohibida. Limítala a ~1 por cada 100 palabras y úsala solo donde sustituiría a
  paréntesis o dos puntos con sentido. Tus ejemplos de referencia la usan; no la elimines por sistema.
- **Caracteres invisibles** (espacios de ancho cero, espacios de no separación, guiones suaves): pueden
  colarse al copiar texto. Si el texto viene de otra fuente, conviene pasarlo por un editor que los muestre
  antes de publicar. No hace falta un script.

## Lo que sí sube credibilidad (en vez de "humanizar")

- Al menos **un número, un nombre propio o un detalle en primera persona** por cada ~100 palabras.
- **Ritmo natural:** una frase larga junto a una corta, sin alternar de forma mecánica.
- **Un momento de riesgo real:** un coste, un error, una decisión que podría haber salido mal.

## Qué NO prometer

Ningún ajuste de estilo garantiza evitar un detector de IA, y los detectores discrepan entre sí hasta 50
puntos sobre el mismo texto (también marcan texto escrito por humanos, sobre todo en lengua no nativa).
El objetivo es que **un lector** lo encuentre específico y creíble, no "pasar" un detector. No digas nunca
al usuario que un texto es "indetectable".

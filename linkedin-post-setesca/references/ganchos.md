# Catálogo de ganchos (español, perfil Setesca)

Diez fórmulas adaptadas al registro de un CTO con 30+ años de oficio. Selección y adaptación a partir de
dos catálogos públicos de código abierto (`Jakeschincariol/linkedin-agent-skill` y
`sergebulaev/linkedin-skills`), reescritas para castellano y para los dominios de Setesca.

Cada fórmula lleva plantilla, ejemplo, mejor uso y **trampa** (cómo se estropea).

> **Sobre los datos de rendimiento.** Las cifras que circulan sobre alcance por fórmula (p. ej. "-34 % de
> likes si abres con pregunta") proceden de estudios de proveedores de herramientas (MagicPost, AuthoredUp),
> no verificados de forma independiente. Trátalas como **heurísticas**, no como hechos. No las cites en un
> post ni las presentes al usuario como evidencia sólida.

## Reglas comunes a todos los ganchos

1. **Una idea por gancho.** Si necesita dos frases con coma para explicarse, son dos posts.
2. **Línea 1 sola.** Debe sobrevivir al corte del "…ver más" (~140 caracteres en móvil, ~210 en escritorio).
3. **Línea 2 es el pago de la línea 1**, no el preámbulo de la 3.
4. **Número primero cuando exista y sea real.** "14.200 €" gana a "mucho dinero". Si el número no está en el
   Story Bank ni lo ha dado el usuario, no lo pongas (ver `story-bank.md`).
5. **Pregunta en la primera línea: evítala**, salvo que solo tú pudieras formularla. Mejor al cierre.
6. **Prueba de la firma:** si el gancho funciona igual con el nombre de otra persona, no es tu gancho.
7. **Una estructura retórica fuerte por post** (un contraste o una tríada), no cuatro.

## Fórmulas

### 1. Contrarian fundado
- **Plantilla:** `Todo el mundo dice {consejo común}. Tras {experiencia concreta}, creo que es un error.`
- **Ejemplo:** "Todo el mundo dice que hay que empezar un proyecto de IA por el modelo. Tras 30 años en TI, creo que es el último paso."
- **Mejor para:** posicionamiento y volumen de comentarios.
- **Trampa:** ser contrarian sobre algo que nadie cree. La creencia tiene que ser realmente común.

### 2. Mito desmontado
- **Plantilla:** `{Explicación popular} no es la razón por la que {mal resultado}.`
- **Ejemplo:** "El modelo no es la razón por la que tu RAG alucina en producción."
- **Mejor para:** reencuadrar; permite entregar la causa real en la línea 3.
- **Trampa:** desmontar el mito y no nombrar la causa verdadera. Nómbrala siempre.

### 3. Cifra al frente
- **Plantilla:** `{Cifra concreta}. {Una frase de contexto}.`
- **Ejemplo:** "3 semanas de piloto, 0 usuarios activos al mes. Así fue nuestro primer despliegue de Copilot."
- **Mejor para:** casos reales y resultados medibles.
- **Trampa:** cifra sin historia. La cifra abre la puerta; la historia es la sala.

### 4. Confesión con coste
- **Plantilla:** `{Coste concreto} es lo que me costó {un error concreto}.`
- **Ejemplo:** "6 semanas de retraso es lo que nos costó no versionar los prompts de un agente."
- **Mejor para:** confianza. Se reenvían los posts donde el autor queda mal.
- **Trampa:** humildad impostada ("me importa demasiado") o cualquier encuadre tipo "voy a ser sincero" sin un hecho fechado detrás.

### 5. Antes / después con una sola palanca
- **Plantilla:** `Hace {tiempo} {estado malo}. Hoy {estado bueno}. La diferencia fue {una cosa}.`
- **Ejemplo:** "Hace un año conciliábamos facturas a mano cada cierre. Hoy lo hace un flujo de n8n con revisión humana. Una decisión de diseño lo cambió."
- **Mejor para:** automatización y casos de proceso.
- **Trampa:** transformaciones de tres partes. Una palanca, o el lector deja de creerte.

### 6. Ancla temporal
- **Plantilla:** `{Tarea} me llevaba {tiempo largo}. Ahora, {tiempo corto}.`
- **Ejemplo:** "Preparar un informe de gobierno de datos nos llevaba dos días. Ahora, media tarde."
- **Mejor para:** posts de cómo hacerlo con herramientas o automatización.
- **Trampa:** ratios increíbles. De 5 horas a 20 minutos se cree; de 5 horas a 8 segundos, no.

### 7. Aviso con salida
- **Plantilla:** `{Práctica común} te está costando {cosa concreta que le importa al lector}.`
- **Ejemplo:** "Dar permisos amplios por defecto en SharePoint te está costando la seguridad de Copilot."
- **Mejor para:** audiencias que aún no han conectado causa y coste.
- **Trampa:** miedo sin salida. Da el arreglo en el mismo post.

### 8. Escenario con dilema real
- **Plantilla:** `{Escenario concreto con un coste real}. ¿Qué haces?` (la pregunta puede ir al cierre en lugar del gancho)
- **Ejemplo:** "Dirección quiere un agente de IA en producción en seis semanas y los datos están en tres silos sin gobierno. Aceptas el plazo o lo renegocias."
- **Mejor para:** conversación entre pares.
- **Trampa:** dilema con respuesta obvia. Tiene que haber una bifurcación real.

### 9. Apertura en escena
- **Plantilla:** `«{Frase literal}».\n\n{Quién la dijo, cuándo y por qué importó}.`
- **Ejemplo:** "«Funciona perfecto en la demo».\n\nLa frase que más temo oír antes de un go-live."
- **Mejor para:** posts largos de historia.
- **Trampa:** diálogo que nadie diría. Usa la frase real, incluidas las partes feas.

### 10. Falso binario disuelto
- **Plantilla:** `Ni {opción A obvia} ni {opción B obvia}. El problema es {tercera cosa}.`
- **Ejemplo:** "Ni comprar la plataforma ni construirla a medida. El problema es quién es el dueño del dato."
- **Mejor para:** estrategia y gobierno, cuando ambas respuestas habituales fallan.
- **Trampa:** usarla de forma genérica. Funciona solo como el único contraste del post y con un hecho concreto detrás.

## Mapa objetivo → fórmula

| Si el post debe generar… | Fórmulas |
|---|---|
| Comentarios | 1, 2, 8, 10 |
| Guardados | 3, 6 |
| Confianza / reposts | 4, 5, 9 |
| Alerta a un público problem-aware | 7 |

## Uso en el flujo

El skill propone **tres ganchos de fórmulas distintas** (no tres variaciones de una), indica cuál
publicaría y por qué en una frase, y redacta el post con el elegido.

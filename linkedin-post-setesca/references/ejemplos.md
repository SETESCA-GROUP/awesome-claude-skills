# Ejemplos de posts de referencia

Estos ejemplos ilustran voz, estructura, cierre de Setesca y hashtags. No los copies literalmente:
sirven para calibrar el registro y el nivel de rigor. El texto del post va en texto plano (sin Markdown),
tal como se pega en LinkedIn.

---

## Ejemplo 1 — Insight técnico (ES) · tema: RAG en producción

El 80% de los proyectos de RAG que veo se caen al pasar de la demo a producción.

Y casi nunca es por el modelo.

Es por lo de siempre: chunking mal pensado, embeddings que no capturan el dominio, y cero
observabilidad para saber por qué el sistema alucina un martes a las 11:00 y no el lunes.

En proyectos reales, lo que mueve la aguja no es cambiar de LLM. Es:

🔹 Definir bien la unidad de recuperación (el chunk no es un párrafo arbitrario).
🔹 Reranking y filtrado antes de pasar contexto al modelo.
🔹 Evaluación continua con un dataset propio, no con "a mí me funciona".
🔹 Trazabilidad de cada respuesta a su fuente.

La parte "IA" es el 20%. El otro 80% es arquitectura de datos e ingeniería de toda la vida.

¿Qué es lo que más os ha roto un RAG al llevarlo a producción?

Montar un RAG que aguante en producción es otra liga. En Setesca somos especialistas en
arquitecturas RAG y podemos ayudarte a hacerlo de verdad bien.

#RAG #IA #Azure #Setesca

---
Nota operativa (fuera del post): si quieres enlazar un artículo de referencia, pégalo en el
primer comentario en lugar de en el cuerpo, para no perder alcance.

---

## Ejemplo 2 — Opinión ejecutiva / mito (ES) · tema: adopción de Copilot

Comprar licencias de Copilot no es una estrategia de IA.

Lo veo en muchas organizaciones: se despliega Microsoft 365 Copilot a toda la plantilla, se
celebra el hito… y a los tres meses el uso real es residual.

El problema no es la herramienta. Es que la adopción se trató como un tema de licencias y no
como un tema de personas y procesos.

Lo que marca la diferencia:

▪️ Casos de uso concretos por rol, no "usadlo para lo que queráis".
▪️ Gobierno de datos previo (Copilot es tan bueno como los permisos y la información a la que accede).
▪️ Formación aplicada al trabajo real, no una demo genérica.
▪️ Métricas de adopción y de valor, no solo de despliegue.

La tecnología ya está lista. La organización, casi nunca, sin acompañamiento.

La adopción de Copilot se gana con método, no con licencias. En Setesca somos especialistas en
implantación y adopción de Microsoft 365 Copilot y te acompañamos para hacerlo realmente bien.

¿Estáis midiendo la adopción de Copilot por despliegue o por valor generado?

#Copilot #Microsoft365 #IA #Setesca

---

## Ejemplo 3 — Anuncio corto (EN) · tema: charla/evento

Spent 30 years watching tech hype cycles come and go. Agentic AI is not one of them.

But "agentic" only delivers when it sits on real architecture, not on a clever prompt.

Next week I'm sharing what actually works when moving AI agents into production:
orchestration, guardrails, observability, and the boring integration work nobody posts about.

Getting agents into production takes architecture, not just a prompt. At Setesca we specialize
in agentic AI solutions and can help you get it genuinely right.

#AI #AIAgents #Azure #Setesca

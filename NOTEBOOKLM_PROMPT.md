# Prompt para NotebookLM — Cervecería El Ángel

## Cómo usar este documento

1. Crea un **nuevo notebook** en NotebookLM (https://notebooklm.google.com).
2. Sube como **fuentes** los siguientes documentos:
   - `REQUISITOS.md` de este repositorio.
   - Capturas del Instagram [@cerveceria_angel_almoradi](https://www.instagram.com/cerveceria_angel_almoradi/) (perfil + historias destacadas: Horario, Montaditos, Postres, Tapeo, QR).
   - El artículo del blog Almoradí 1829: https://almoradi1829.blogspot.com/2016/11/cerveceria-bar-angel-en-su-50.html
   - La ficha de ClicAlicante: https://clicalicante.com/cerveceria-el-angel-en-almoradi/
   - Reseñas de Tripadvisor y Gastroranking (copia y pega 20–30 reseñas).
   - El PDF de la carta cuando lo tengas.
3. Pega el prompt maestro de abajo en el chat del notebook.
4. Para cada entregable, usa el prompt específico al final.

---

## Prompt maestro (pegar primero)

> Eres el director creativo de una agencia que se encarga de la presencia digital de un restaurante familiar de tres generaciones llamado **Cervecería El Ángel**, en Almoradí (Alicante, España), fundado en **1966** y con la chef **Marilo Monera** al frente de la cocina actual. El lema es **"Cocinamos la Vida desde 1966"**. La marca combina **tradición huertana** (Vega Baja, productos frescos, marisco, arroces, postres caseros) con un **toque vanguardista** y un trato muy familiar.
>
> Tono de voz: cercano, orgulloso, sin pomposidad, con detalles concretos (nombres de platos, nombres de la familia, lugares de Almoradí). Evita superlativos vacíos ("los mejores", "los más espectaculares"). Prefiere historias y datos comprobables.
>
> Audiencia: vecinos de la Vega Baja, turistas de la costa de Alicante y grupos que celebran ocasiones especiales. Idioma principal: castellano de España (no neutro).
>
> Trabaja **solo con la información de las fuentes** que he cargado. Si no tienes un dato (precio exacto, ingrediente concreto, fecha), dilo explícitamente y propón una pregunta para resolverlo, en vez de inventar.

---

## Entregable 1 — Presentación corporativa (10 diapositivas)

> Genera el guion de una **presentación de 10 diapositivas** para reuniones con potenciales colaboradores (proveedores, ayuntamiento, prensa local). Cada diapositiva debe llevar:
>
> - **Título** (máx. 6 palabras)
> - **Tres bullets** de máx. 10 palabras cada uno
> - **Una frase de cierre** que el orador dirá en voz
> - **Nota de imagen sugerida** (qué foto del restaurante usar)
>
> Estructura:
> 1. Quiénes somos (1966, tres generaciones)
> 2. La cocina de Marilo Monera
> 3. Cuatro pilares: arroces, mariscos, tapas, postres caseros
> 4. Producto fresco y proveedores de la Vega Baja
> 5. Recorrido histórico del local (Cafetería Diego → Los Ángeles → El Ángel → nueva ubicación en C/ Donadores)
> 6. Vida del bar (clientes habituales, fachada en la plaza, momentos de barra)
> 7. Reconocimientos (notas en Google, Gastroranking, prensa)
> 8. Servicios actuales (terraza, comida para llevar, reservas)
> 9. Por qué nos visitas — propuesta de valor en una frase
> 10. Contacto y siguiente paso

---

## Entregable 2 — Infografía "60 años en la plaza"

> Diseña el **contenido textual** de una infografía vertical (formato 1080×1920 px para Instagram Stories y para imprimir en el local). El eje es una **línea de tiempo** desde 1966 hasta hoy. Devuelve:
>
> - 6 hitos con año, titular de 4–6 palabras y descripción de 15–20 palabras
> - Iconografía sugerida para cada hito (objeto reconocible que un ilustrador pueda dibujar)
> - Una cifra "estrella" para el centro: dato impactante (por ejemplo, número aproximado de platos servidos en 60 años, si se puede estimar a partir de los aforos publicados)
> - Un cierre con CTA: "Ven a vivir el próximo capítulo. Reservas: 646 524 157"

---

## Entregable 3 — Cápsulas para Reels (6 ideas)

> Propón **6 guiones cortos para Reels de Instagram**, cada uno de 20–30 segundos. Para cada cápsula entrega:
>
> - **Gancho** (los primeros 3 segundos)
> - **Storyboard** en 3–4 planos
> - **Texto en pantalla** corto
> - **Audio sugerido** (canción típica, audio trending o silencio con voz en off)
> - **CTA final**
>
> Temas obligatorios: (1) plato emblema — calamar a la romana, (2) historia de los tres Ángel, (3) el arroz del día, (4) reacción de un cliente habitual, (5) detrás de la barra a las 13:30, (6) postre casero del fin de semana.

---

## Entregable 4 — Cartel de menú diario reutilizable

> Crea una **plantilla de copy** para el menú diario de cada día de la semana. La salida tiene que poder pegarse tal cual en una historia de Instagram. Devuelve la estructura con marcadores `{ }` para sustituir cada día:
>
> ```
> 🗓️ MENÚ DIARIO — {DÍA, FECHA}
> 2 platos a elegir + bebida + postre · {PRECIO} €
>
> 🍲 Primeros
> · {PRIMERO_1}
> · {PRIMERO_2}
> · {PRIMERO_3}
>
> 🥩 Segundos
> · {SEGUNDO_1}
> · {SEGUNDO_2}
> · {SEGUNDO_3}
>
> 🍰 Postre casero del día
>
> Reservas 📞 646 524 157
> 📍 C/ Donadores 9, Almoradí
> ```
>
> Además, genera **5 ejemplos rellenos** usando platos reales que aparezcan en las fuentes del notebook (arroz con secreto y verduras, consomé con pelota, callos a la madrileña, gazpacho manchego, canelones de carne, etc.).

---

## Entregable 5 — Calendario editorial de 4 semanas

> Diseña un **calendario de 4 semanas** para Instagram. Una publicación al día (lunes a domingo, descansa los martes porque el local cierra). Para cada slot indica:
>
> - Día y semana
> - Formato (foto / carrusel / Reel / historia destacada)
> - Tema
> - Copy listo (máx. 220 caracteres)
> - 4 hashtags locales
>
> Alterna 4 ejes: menú diario, plato icónico, historia familiar, vida del barrio (Mercado de Almoradí, fiestas patronales, eventos del Teatro Cortés).

---

## Entregable 6 — Texto SEO para la web

> Reescribe la sección "Sobre nosotros" y la sección "Nuestra cocina" del documento `REQUISITOS.md` en un copy **listo para publicar** en la web. Cumple estas reglas:
>
> - Densidad natural de las palabras clave "restaurante Almoradí", "arroces Vega Baja", "marisco Almoradí".
> - Estructura H2 + H3 jerárquica.
> - Párrafos de 2–4 líneas máximo.
> - Una llamada a la acción al final de cada bloque.
> - No mientas: si un dato no está en las fuentes, omite el bullet en vez de inventar.

---

## Entregable 7 — Preguntas frecuentes (10)

> A partir de las reseñas cargadas, deduce **las 10 preguntas reales que más se hace la gente** antes de visitar el restaurante y responde cada una en 2–3 frases. Ejemplos esperables: ¿se puede aparcar cerca?, ¿hacen menús para grupos?, ¿tienen opciones sin gluten?, ¿se puede ir con niños?, ¿se puede pagar con tarjeta?, ¿hace falta reservar?, etc.

---

## Entregable 8 — Guion de audio "Notebook"

> NotebookLM ofrece el botón **"Audio Overview"**. Tras cargar las fuentes, pídele que genere un **resumen en formato podcast de 8–10 minutos** con dos voces (presentador y experto), enfocado en contar la historia de Cervecería El Ángel a alguien que viene de fuera de Almoradí. Pide que mencione explícitamente: el cambio de ubicación, los nombres de la familia Roca, la frase "Marisco y Tapas variadas", el lema "Cocinamos la Vida desde 1966" y los servicios actuales.

---

## Consejo de uso

- Genera cada entregable en una conversación separada del notebook para no contaminar contextos.
- Cuando termines un entregable, pega el resultado en un nuevo archivo en el repo: `content/<entregable>.md`.
- Revisa **manualmente** todo lo que toque datos concretos (precios, horarios, nombres) antes de publicarlo. NotebookLM cita fuentes, pero la responsabilidad editorial es del restaurante.

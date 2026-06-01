# Cervecería El Ángel — Análisis de requisitos

## 1. Resumen del negocio

- **Nombre comercial:** Cervecería bar restaurante El Ángel
- **Categoría:** Gastrobar de comida tradicional con producto fresco
- **Lema histórico:** "Marisco y Tapas variadas"
- **Lema actual:** "Cocinamos la Vida desde 1966"
- **Año de fundación:** 1966 (sustituyó a la antigua "Cafetería Diego"; en los 80 se llamó "Los Ángeles")
- **Generaciones al frente:** 3, familia Roca
- **Chef actual:** Marilo Monera
- **Dirección actual:** C/ Donadores 9, 03160 Almoradí (Alicante). NUEVA ubicación. La histórica era Plaza de la Constitución 22.
- **Teléfonos:** 646 524 157 (reservas) · 965 702 598
- **Instagram:** [@cerveceria_angel_almoradi](https://www.instagram.com/cerveceria_angel_almoradi/) — 1.250+ seguidores
- **Valoraciones externas:** Google 4,4 ★ (554 reseñas) · Gastroranking 4,2 / 8,5 (599 reseñas) · TripAdvisor 3,8 (40)
- **Rango de precios:** 10–40 €
- **Servicios:** Terraza, comida en el bar, comida para llevar

### Especialidades
Arroces, mariscos, calamar a la romana, tapas y montaditos, platos caseros, postres caseros, maridaje con vinos. Comida tradicional con toque vanguardista y trato familiar.

### Horario
| Día | Mañana | Noche |
|---|---|---|
| Lunes | 9:00 – 16:00 | — |
| Martes | CERRADO | CERRADO |
| Miércoles | 9:00 – 16:00 | 20:00 – 00:00 |
| Jueves | 9:00 – 16:00 | 20:00 – 00:00 |
| Viernes | 9:00 – 16:00 | 20:00 – 00:30 |
| Sábado | 9:00 – 16:00 | 20:00 – 00:45 |
| Domingo | 9:00 – 17:00 | — |

---

## 2. Objetivos de la web

1. **Convertir búsquedas locales en reservas** ("restaurantes Almoradí", "arroces Vega Baja", "marisco Almoradí").
2. **Dar carta de presentación digital** que esté a la altura de un negocio de 60 años (hoy solo existe Instagram y fichas de directorios).
3. **Centralizar la información clave** que la gente busca: horarios, ubicación nueva, teléfono de reserva, carta y menú diario.
4. **Reforzar la marca** comunicando la mezcla tradición + vanguardia y la historia familiar.
5. **Captar tráfico orgánico** con SEO local bien hecho (Schema.org `Restaurant`, Google Business linking, fotos optimizadas).

## 3. Público objetivo

- **Vecinos de Almoradí y la Vega Baja** que buscan donde comer / cenar entre semana o fines de semana.
- **Turistas y veraneantes** de la costa (Guardamar, Torrevieja, La Marina) que entran tierra adentro un día concreto.
- **Grupos y celebraciones** (comuniones, cumpleaños, comidas de empresa) — punto de dolor: dónde reservar mesa grande con marisco y arroces.
- **Comida para llevar** (público local, días laborables).

## 4. Sitemap propuesto (one-page con secciones ancladas)

1. **Inicio / Hero** — Logo, lema "Cocinamos la Vida desde 1966", CTA reservar.
2. **Sobre nosotros** — Historia de 3 generaciones, foto de la familia, fachada antigua vs. local nuevo.
3. **Nuestra cocina** — Pilares (arroces, mariscos, tapas, postres caseros). Frase sobre producto fresco.
4. **Carta y menú diario** — Bloques destacados + enlace a la carta completa (PDF o `carta.menu`).
5. **Galería** — Cuadrícula de fotos de local, platos y barra.
6. **Reservas** — Botones: llamar, WhatsApp, indicaciones. Aviso de horarios.
7. **Horario y ubicación** — Tabla de horarios + mapa embebido + dirección.
8. **Contacto / Redes** — Teléfonos, IG, email opcional, formulario corto.
9. **Footer** — Datos fiscales, aviso legal, política de cookies.

## 5. Contenidos pendientes (a aportar por el restaurante)

- [ ] Logo en SVG o PNG con fondo transparente y versión monocromática.
- [ ] 10–15 fotos profesionales: 3 de local, 2 de fachada (día y noche), 6 de platos estrella, 2 del equipo.
- [ ] Foto histórica del bar (años 60–70) para la sección de historia — el blog Almoradí 1829 tiene una.
- [ ] Carta completa actualizada (PDF) y carta de vinos.
- [ ] Texto biográfico de la chef Marilo Monera (3–4 líneas).
- [ ] Confirmar si quieren recibir reservas por formulario web o solo por teléfono / WhatsApp.
- [ ] Razón social, CIF y email para el aviso legal.

## 6. Stack y arquitectura

- **HTML + CSS + JS estáticos**, sin framework, sin build step. Una sola página y un par de assets.
- **Despliegue:** GitHub Pages (rama `main`, carpeta raíz). Coste 0 €, HTTPS automático.
- **Fuentes:** Google Fonts (`Playfair Display` para titulares, `Inter` para texto).
- **Iconos:** SVG inline para no añadir librerías.
- **Mapa:** OpenStreetMap embebido (sin necesidad de API key).
- **Imágenes:** WebP optimizado, `loading="lazy"`, dimensiones explícitas.
- **Accesibilidad:** contraste AA, navegación por teclado, `prefers-reduced-motion`.
- **Idioma:** español; preparar `lang="es"` y dejar estructura para añadir valenciano/inglés más adelante.

## 7. SEO local (lo no negociable)

- **Schema.org `Restaurant`** con `openingHoursSpecification`, `address`, `telephone`, `priceRange`, `servesCuisine`, `aggregateRating`.
- **Meta `title` y `description`** con "Almoradí" en la primera mitad.
- **Open Graph + Twitter cards** para que se vea bien al compartir.
- **`sitemap.xml`** y **`robots.txt`**.
- **Enlazar a Google Business Profile** y reclamar la ficha si no está reclamada.
- **NAP consistente** (nombre, dirección, teléfono) idéntico al de la ficha de Google.
- **Vincular dominio propio** (por ejemplo `cerveceriaelangel.es`) y configurar redirección desde GitHub Pages.

## 8. Legal y privacidad (RGPD)

- Aviso legal, política de privacidad y política de cookies enlazados desde el footer.
- Banner de cookies con opción real de rechazar antes que aceptar (si se añade analítica). Si no hay analítica → banner opcional.
- Encriptación HTTPS por defecto (la ofrece GitHub Pages).

## 9. Métricas de éxito (3 meses tras publicar)

- Top 3 en Google para `restaurante almoradí marisco` y `arroces almoradí`.
- 30+ visitas/día medias en orgánico.
- ≥10 clics-a-llamada/semana desde el botón "Reservar".
- Reducir el número de llamadas preguntando "¿a qué hora abrís?".

## 10. Fases

| Fase | Entregable | Estado |
|---|---|---|
| 1 | Análisis de requisitos (este documento) | **Hecho** |
| 2 | Prompt de NotebookLM para generar assets | **Hecho** |
| 3 | Web de prueba (este repo) con copy provisional e imágenes placeholder | **Hecho** |
| 4 | Sesión con el restaurante para recoger fotos, carta y textos | Pendiente |
| 5 | Versión final con assets reales | Pendiente |
| 6 | Despliegue en dominio propio y configuración SEO | Pendiente |

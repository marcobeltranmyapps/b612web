# Conocimiento del proyecto — B612

> Documento vivo. Objetivo: centralizar lo que sabemos de la organización para guiar el diseño, contenido y estructura del sitio web (WebB612). Se debe actualizar a medida que se confirme o corrija información.

## 1. Qué es B612

B612 es un **centro de formación y producción artística** peruano. No es solo una productora audiovisual: forma a sus propios talentos (canto, danza, interpretación) y luego los lleva a escena en montajes de teatro musical, además de ofrecer producción audiovisual.

Disciplinas / frentes de trabajo:

- 🎤 **Canto**
- 💃 **Danza**
- 🎭 **Talleres de interpretación escénica**
- 🎬 **Montajes de teatro musical** (producción propia, temporadas)
- 🎥 **Producción audiovisual**

Marca(s) detectada(s): "B612 Audiovisual" (Instagram, YouTube, Spotify, Linktree) y "B612 Entertainment" (crédito de productor en el micrositio de Frozen). **Por confirmar** si son la misma entidad o una sub-marca específica para las producciones teatrales grandes.

## 2. Líneas de negocio / servicios

| Línea | Descripción | Estado de la info |
|---|---|---|
| Formación — Canto | Talleres/clases de canto | Confirmado que existe; falta detalle (niveles, edades, horarios) |
| Formación — Danza | Talleres/clases de danza | Confirmado que existe; falta detalle (niveles, edades, horarios) |
| Formación — Interpretación escénica | Talleres de actuación | Confirmado que existe; falta detalle |
| Teatro musical | Montajes propios, temporadas, funciones | Confirmado; ver producciones en curso (sección 3) |
| Producción audiovisual | Videoclips, covers, coreografías, contenido para artistas independientes | Confirmado vía YouTube/Spotify/Linktree |

> Hipótesis a validar: los talleres de formación (canto, danza, interpretación) alimentan el elenco de los montajes de teatro musical — ruta "alumno → taller → elenco de producción". Esto es clave para la estructura del sitio (mostrar ese camino, no solo listar servicios sueltos).

## 3. Producciones

### En curso (confirmado por el usuario, 2026-09-18)

- **Frozen, Una Aventura Congelada** — estreno **15 de noviembre**. Tiene micrositio propio con venta de entradas y selección de asientos: `frozen.b612.org.pe` (crédito de producción: "B612 Entertainment"). Incluye un taller asociado a la obra.
- **Aladdin y la lámpara maravillosa** — fecha de estreno **por confirmar**.

### Montajes anteriores (detectados en Instagram — highlights y grid)

- Aladino (versión anterior o el mismo montaje actual, a confirmar)
- Enredados (Tangled) — al menos 4 temporadas/versiones (Enredados I, II, III, IV)
- Mamma Mía II
- "65mts" y "Gnarly" — aparecen como highlights, naturaleza sin confirmar (¿producción, evento o contenido detrás de cámaras?)

### En desarrollo / anunciada (detectado en Linktree, sin fecha)

- **"Mamá mía, ¡mis quince!"** — teaser publicado; sería una obra musical propia (mashup temático de Mamma Mia con quinceañero/a).

> Nota: hay skills ya configurados en este entorno para procesar libretos de estas producciones (`libreto-doc-to-md`, `broadway-libreto-pdf`), incluyendo `Libreto_Aladdin.md` como ejemplo — reutilizar para Aladdin.

## 4. Talento y colaboradores recurrentes (detectado en redes)

B612 promueve activamente a estudiantes/artistas propios con nombre propio, y arma grupos estables de intérpretes jóvenes:

- **Nikybelt** — vocalista, protagonista de varios covers propios (Señal, En Cambio No, Slipping Through My Fingers)
- **Fernanda Samaniego** — vocalista, feat. en covers junto a Nikybelt
- **The Uptown Kids** / **The Uptown Girls** — grupos de intérpretes (niños/adolescentes) para covers y coreografías (Uptown Funk, What Is Love, Los patos y las patas)
- Cuentas que interactúan/colaboran en el feed reciente: `mar_prieto_reynaud`, `geoffreymax.tc`, `kristenbelt__` (posible convención de nombre artístico con sufijo "belt", quizá ligado a técnica vocal de *belting*)

> Esto sugiere que el sitio debería tener un espacio para "talento" o "elenco" — perfiles de alumnos destacados que se convierten en caras visibles de la marca. Vale la pena confirmar con el cliente si esta es una estrategia intencional (mostrar caras de alumnos como parte del atractivo de los talleres).

## 5. Proyectos propios adicionales y portafolio de producción audiovisual para terceros

- **BimBamBum Canal Oficial** — **confirmado por el usuario: es un proyecto propio de B612**, no una alianza externa (corrige la hipótesis anterior). Canal de música/contenido infantil con elenco de niños. YouTube: [@BimBamBumCanalOficial](https://www.youtube.com/@BimBamBumCanalOficial) (64 suscriptores). Publican música original vía DistroKid (ej. "El baile de los animales", con Bastian Cornejo, Geoffrey Tineo). En Instagram (`bimbambumoficial`) también corrieron el "Taller de Contenido Musical BimBamBum" (niños 8–13 años, de la canción al video/TikTok).

En YouTube aparece evidencia clara de que B612 también produce audiovisual **para terceros** (no solo sus propias producciones), lo cual respalda directamente la línea "producción audiovisual para artistas independientes":

- **Tierra de Campeones** — B612 grabó/produjo al menos 2 musicales de este grupo, dirigidos por **Dennis Montejo**: "Matilda - El Musical" y "Annie - El Musical". Por confirmar si es un cliente recurrente, una escuela aliada, o el mismo espacio/teatro.
- **"Secuestrados"** — cortometraje o película con making-of propio en el canal, y entrevista al actor **Sebastian Stimman**. Por confirmar rol exacto de B612 (¿producción completa, solo making-of, distribución?).
- **"La ley del vago"** — otro making-of, mismo patrón que Secuestrados.
- **Panther Fight Academy** — reel profesional; posible cliente de una academia de artes marciales.
- **"A ver si aprendes"** — cortometraje propio.

> Esto sugiere que el sitio necesita una sección de **portafolio de producción audiovisual** separada de "nuestras producciones de teatro musical", para mostrar este trabajo con terceros como servicio ofrecido.

## 6. Público objetivo (hipótesis, por validar)

- Estudiantes/talleristas interesados en teatro musical y audiovisual (rango amplio: niños 8-13 años hasta adolescentes/jóvenes adultos)
- Padres de familia (deciden y pagan talleres de hijos menores)
- Comunidad de teatro musical en Perú (espectadores de las funciones)
- Artistas independientes que buscan producción audiovisual (videoclips, covers)

## 7. Presencia digital

- **Instagram**: [@b612.audiovisual](https://www.instagram.com/b612.audiovisual) — 2,453 seguidores / 2,163 seguidos, cuenta verificada. Bio: "Producción audiovisual para artistas independientes / Eventos y artes escénicas / Talleres y formación". Actividad reciente frecuente (varios posts en septiembre 2026).
- **Linktree**: linktr.ee/b612.audiovisual — centraliza Instagram, YouTube y Spotify, más una lista de "últimas producciones" (videoclips y covers). Miembro de Linktree desde abril 2025.
- **YouTube**: canal [@b612audiovisual](https://www.youtube.com/@b612audiovisual) — 303 suscriptores, 32 videos. Contenido: videoclips/covers, coreografías, funciones completas grabadas, y trabajos de producción audiovisual para terceros (ver sección 5).
- **Spotify**: distribuyen música propia/covers como artista
- **Micrositio de producción**: frozen.b612.org.pe — patrón de landing page dedicada por show grande (entradas, asientos, taller asociado), crédito "B612 Entertainment"
- **aladdin.b612.org.pe** — subdominio ya creado (CNAME a GitHub Pages, registrado el 04-09-2026), mismo patrón que Frozen. Aún no lo hemos revisado a fondo.
- **Correo del dominio**: `b612.org.pe` usa Zoho Mail (MX + SPF + DKIM configurados el 15-09-2026) — ya existe infraestructura de correo propio (ej. algo como contacto@b612.org.pe), no dependen solo de Instagram.

### Observaciones sobre desempeño en redes (con reserva — ver limitación abajo)

- Buena cobertura multiplataforma para una escuela/productora de este tamaño: IG + YouTube + Spotify + micrositio propio por producción, es más sofisticado que la mayoría de academias similares.
- Relación seguidores/seguidos casi 1:1 (2453/2163) — atípico para una marca; sugiere que siguen activamente a alumnos, familias o colaboradores. Vale la pena confirmar si es estrategia deliberada de comunidad.
- Uso consistente de "Historias destacadas" por producción (organización clara por montaje), buena práctica que el sitio web podría espejar (una página/sección por producción).
- Contenido variado: promocional (carteles de funciones), formativo (talleres), behind-the-scenes, covers musicales con producción audiovisual propia — refuerza que "formación" y "producción audiovisual" no son líneas separadas sino que se alimentan entre sí en el contenido.
- **Limitación importante:** Instagram exige iniciar sesión para ver publicaciones individuales completas (captions, comentarios, likes, cuentas etiquetadas). No inicié sesión (no corresponde usar credenciales), así que este análisis se basa en bio, historias destacadas, texto alternativo de imágenes del grid y datos públicos de Linktree — **no es una auditoría exhaustiva de métricas de engagement**. Si quieres ese nivel de detalle (likes/comentarios por post, alcance, etc.), lo ideal es que me compartas acceso de Meta Business Suite / Creator Studio o exportes las estadísticas.

### YouTube — hallazgos y análisis

- Canal pequeño en suscriptores (303) con **32 videos**, pero con un video que es un outlier gigante: **"Dancing Queen - Abba - Video coreografía teatro musical"** tiene **297 mil vistas** (subido hace 1 año) — casi 1000x más que el resto de videos del canal. Esto indica que el contenido *puede* viajar muy lejos del público propio (probablemente compartido/viralizado fuera de Instagram/YouTube, quizá TikTok o reposts), pero ese alcance **no se tradujo en crecimiento de suscriptores** (297K vistas vs. 303 suscriptores es una conversión muy baja).
  - **Oportunidad clara para el sitio/estrategia**: ese video es la prueba de que B612 puede producir contenido con potencial viral; conviene usarlo como pieza destacada en el sitio y reforzar CTAs (suscríbete, síguenos) en los videos.
- El resto de videos se mueve mayormente entre cientos y ~4-5K vistas (covers de "The Uptown Kids/Girls", "Nikybelt", coreografías de Enredados).
- Suben **funciones completas grabadas** (ej. "Una Aventura Enredada" función 4PM y 7:30PM, ~1h20min cada una) — esto es un activo importante: podría ofrecerse como contenido de archivo/nostalgia en el sitio, o incluso como producto (alquiler/venta de la grabación) para quienes no pudieron asistir.
- Confirmado el trabajo de producción para terceros vía making-ofs y musicales dirigidos por Dennis Montejo (Tierra de Campeones) — ver sección 5.
- Último video subido hace ~1 mes: **"Dangerous to Dream (Me atreveré a Soñar)"**, versión en español de una canción del musical *Anastasia* — no hay contexto claro todavía de si es contenido suelto o teaser de una futura producción. Vale la pena preguntar directamente.

## 8. Estilo visual del sitio (aplicado 2026-09-21)

Se rediseñó `public/` con un estilo inspirado en [bladstudios.com/talleres](https://bladstudios.com/talleres) (otra escuela de artes escénicas): tema 100% oscuro (negro + 2 tonos), tipografía nativa del sistema en peso 900 con tracking negativo en títulos, botones pill, tarjetas con tag de categoría (emoji + color), y un sistema de 5 curvas de easing tipo spring. Colores de marca (amarillo `#F5C518`, rosa `#E6197A`, más un teal `#33E0C0` nuevo) se usan como acentos sobre el fondo negro, no como fondo protagonista.

Secciones actuales: Hero (video pendiente, ver abajo) → Talleres (Canto/Danza/Interpretación) → Montajes (Frozen/Aladdin) → Proyectos (portafolio real: Dancing Queen, Matilda para Tierra de Campeones, Secuestrados, Panther Fight Academy) → Contacto.

**Actualizado 2026-09-21:** las 3 tarjetas de Talleres (Canto, Danza, Interpretación) ya usan fotos reales de fondo (`public/img/talleres/`), a partir de fotos que el usuario copió a `fotos/` (raíz, sin publicar): una foto de estudio de canto, una de ensayo de danza, y un frame del video promocional de Frozen para interpretación.

El hero ya tiene video real, ahora usando los 3 clips que el usuario copió a `video/` (raíz del repo, sin publicar — está en `.gitignore`): ensayo/coreografía en un salón (celular), un número musical de ensamble (edificio con vitrales, uniformes tipo colegio), y un teaser promocional de Frozen (actriz en la Plaza de Armas de Lima frente al cartel real "B612 Entertainment presenta Una Aventura Congelada"). Se recortaron los mejores momentos de cada uno y se unieron con crossfades (`ffmpeg`) en un loop de 23s → `public/video/hero.mp4` (~5MB) + `public/video/hero-poster.jpg`. Las tarjetas de Montajes siguen con gradientes de placeholder (pendiente fotos reales).

## 9. Estructura tentativa del sitio (borrador)

- Inicio
- Sobre B612 (historia, misión, equipo)
- Formación (por disciplina: Canto / Danza / Interpretación escénica) — oferta, horarios, inscripción
- Producciones / Teatro musical — página por montaje (actual: Frozen, Aladdin; archivo de anteriores: Enredados, Mamma Mía II, etc.), con entradas cuando aplique
- Talento / Elenco — posible sección para destacar alumnos/artistas propios (Nikybelt, The Uptown Kids, etc.), si el cliente confirma que es parte de la estrategia
- Producción audiovisual (portafolio: videoclips, covers, servicios para artistas independientes)
- Alianzas (si aplica, ej. Bim Bam Bum)
- Galería / Prensa
- Contacto

> Esta estructura es un punto de partida y debe ajustarse según objetivos reales del sitio (¿vender entradas? ¿captar alumnos para talleres? ¿mostrar portafolio audiovisual? ¿todo junto?).

## 10. Información pendiente de confirmar con el cliente

- [ ] Nombre legal / historia de la organización, año de fundación
- [ ] Relación entre "B612 Audiovisual" y "B612 Entertainment" (¿mismo grupo, sub-marca para producciones teatrales?)
- [ ] Ubicación física (¿sede propia, alquilada, teatro de terceros?)
- [ ] Objetivo principal del sitio web (venta de entradas, captación de alumnos, portafolio, todo)
- [ ] Identidad visual existente (logo, colores, tipografías) — ya vimos el isotipo circular amarillo/negro de Instagram, ¿es el definitivo?
- [ ] Contactos oficiales (teléfono, dirección; el email ya sabemos que corre por Zoho Mail sobre b612.org.pe — falta la dirección exacta a usar en el sitio)
- [ ] Revisar qué hay hoy en aladdin.b612.org.pe (micrositio ya creado, sin revisar)
- [ ] Si el sitio nuevo debe **centralizar/reemplazar** los micrositios por producción (como frozen.b612.org.pe) o **coexistir** con ellos
- [ ] Detalle de talleres: modalidades, edades, precios, horarios
- [ ] Fecha de estreno de Aladdin y la lámpara maravillosa
- [ ] Si mostrar "talento/elenco" (alumnos destacados) es una estrategia deliberada a reflejar en el sitio
- [ ] Qué son "65mts" y "Gnarly" (highlights de Instagram sin contexto claro)
- [ ] Relación con "Tierra de Campeones" / Dennis Montejo (¿cliente recurrente, escuela aliada, mismo espacio?)
- [ ] Rol exacto de B612 en "Secuestrados" y "La ley del vago" (¿producción completa o solo registro/making-of?)
- [ ] Si "Dangerous to Dream" (canción de Anastasia) es teaser de una futura producción
- [ ] Si conviene ofrecer las funciones completas grabadas como contenido/producto en el sitio (archivo, alquiler, etc.)
- [ ] Fotos reales de Frozen/Aladdin para reemplazar los gradientes placeholder en las tarjetas de Montajes

## Historial de cambios

- 2026-09-18: Creación del documento a partir de la revisión del perfil de Instagram @b612.audiovisual.
- 2026-09-18: Confirmado por el usuario — B612 es centro de formación y producción artística (canto, danza, interpretación escénica, montajes de teatro musical, producción audiovisual).
- 2026-09-18: Revisión del micrositio frozen.b612.org.pe (crédito "B612 Entertainment", venta de entradas/asientos/taller).
- 2026-09-18: Revisión exhaustiva de Instagram (sin login, por límite de la plataforma) + Linktree: se detectaron YouTube, Spotify, talento recurrente (Nikybelt, Fernanda Samaniego, The Uptown Kids/Girls, colaboradores del feed), alianza con Bim Bam Bum Oficial, y observaciones de desempeño en redes.
- 2026-09-18: Confirmado por el usuario — 2 producciones en curso: Frozen, Una Aventura Congelada (estreno 15 de noviembre) y Aladdin y la lámpara maravillosa (fecha por confirmar).
- 2026-09-18: Revisión del canal de YouTube (@b612audiovisual, 303 suscriptores, 32 videos): video outlier viral (Dancing Queen, 297K vistas), funciones completas grabadas, y portafolio de producción para terceros (Tierra de Campeones/Dennis Montejo, Secuestrados, La ley del vago, Panther Fight Academy).

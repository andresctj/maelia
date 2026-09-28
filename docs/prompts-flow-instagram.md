# Prompts Flow — imágenes Instagram por tipo de post

> **Melia Shop:** prompts ya rellenados → [prompts-flow-melia.md](./prompts-flow-melia.md) · análisis → [analisis-marca-melia.md](./analisis-marca-melia.md)

Copia primero el **Bloque de marca**, rellénalo, y pégalo al inicio de cada prompt.

**Modelo / herramienta:** Flow o Gemini Image (`gemini-3.1-flash-image` / Nano Banana 2)  
**Formato por defecto:** 1080×1080 (1:1) salvo que el prompt diga otra cosa  
**Idioma del texto en imagen:** español, tipografía grande y legible en móvil

---

## Bloque de marca (rellena y reutiliza)

```
MARCA:
- Nombre: [NOMBRE_MARCA]
- Rubro / promesa: [ej. café de especialidad / skincare natural / coaching fitness]
- Público: [ej. mujeres 25–40, emprendedoras en Latam]
- Paleta: primario [#HEX], secundario [#HEX], acento [#HEX], fondo [#HEX], texto [#HEX]
- Estilo visual: [ej. limpio minimal / cálido lifestyle / bold urbano / premium dark]
- Tipografía look: [ej. sans bold moderna / serif elegante + sans clean]
- Logo: [sin logo / espacio superior izquierdo para logo / marca solo como wordmark tipográfico]
- Tono de copy: [cercano / premium / divertido / experto]
- Prohibido: texto borroso, watermark, demasiados elementos, colores fuera de paleta, stock genérico sin alma de marca
```

---

## Reglas fijas (añádelas siempre al final del prompt)

```
REGLAS DE SALIDA:
- Una sola composición clara, no collage caótico
- Texto corto, alto contraste, legible a tamaño móvil (máx. 6–8 palabras en título)
- Márgenes generosos; nada cortado en bordes
- Producto/escena realista y fotográfica (o ilustración plana si el estilo de marca lo pide)
- Sin emojis en la imagen salvo que el prompt lo pida
- Incluir tipografía nítida integrada al diseño (no sticker flojo)
- Aspect ratio: [1:1 | 4:5 | 9:16 según el tipo]
```

---

## 1) Post de feed — anuncio / producto hero

**Ratio:** 1:1 o 4:5

```
[BLOQUE DE MARCA]

Crea un post de Instagram feed (4:5) para [NOMBRE_MARCA].
Tipo: hero de producto.
Escena: [producto / servicio] en contexto aspiracional de [lugar/ambiente].
Composición: producto dominante en el centro-inferior; espacio limpio arriba para texto.
Texto en imagen (exacto):
- Título: "[TÍTULO CORTO]"
- Subtítulo: "[beneficio en 1 línea]"
Colores solo de la paleta de marca. Estilo [estilo visual]. Luz natural suave, calidad campaña publicitaria.
[REGLAS DE SALIDA — aspect 4:5]
```

---

## 2) Promo / oferta (descuento, 2x1, envío)

**Ratio:** 1:1

```
[BLOQUE DE MARCA]

Post Instagram cuadrado de PROMOCIÓN para [NOMBRE_MARCA].
Oferta: [ej. 20% OFF / envío gratis / 2x1].
Vigencia visible: [hasta DD/MM] (texto pequeño pero legible).
Jerarquía: el descuento es el elemento más grande; luego beneficio; luego CTA.
Texto en imagen (exacto):
- Badge: "[OFERTA]"
- Título grande: "[% o beneficio]"
- Línea: "[qué incluye]"
- CTA: "[Compra ahora / Escribe HOY]"
Fondo con textura sutil de marca, no flat aburrido. Urgencia elegante, no gritos de “sale” genérico.
[REGLAS DE SALIDA — aspect 1:1]
```

---

## 3) Tip educativo / carrusel (portada)

**Ratio:** 1:1 — usa como slide 1

```
[BLOQUE DE MARCA]

Portada de carrusel educativo Instagram para [NOMBRE_MARCA].
Tema: [tema del tip].
Look: infografía limpia de marca, número grande "01" o icono simple de [tema].
Texto en imagen (exacto):
- Eyebrow: "TIP"
- Título: "[pregunta o promesa]"
- Pie: "Desliza →"
Mucho espacio negativo; tipografía clara; sin párrafos largos.
[REGLAS DE SALIDA — aspect 1:1]
```

**Slides 2–4 (repetir cambiando número y tip):**

```
[BLOQUE DE MARCA]

Slide [N] de carrusel educativo [NOMBRE_MARCA], mismo estilo visual que una portada tipográfica limpia.
Número grande: "[N]"
Título: "[tip en 4–6 palabras]"
Cuerpo corto (máx 12 palabras): "[explicación]"
Misma paleta y tipografía; diseño consistente de serie.
[REGLAS DE SALIDA — aspect 1:1]
```

---

## 4) Lanzamiento / “nuevo”

**Ratio:** 4:5

```
[BLOQUE DE MARCA]

Anuncio de LANZAMIENTO Instagram para [NOMBRE_MARCA].
Producto/servicio nuevo: [nombre].
Sensación: exclusivo, debut, primer vistazo.
Texto en imagen (exacto):
- Badge: "NUEVO"
- Título: "[nombre del lanzamiento]"
- Sub: "[1 beneficio estrella]"
- CTA: "Disponible ahora"
Hero visual del producto con profundidad; acento de marca en un solo detalle (luz, packaging, ribbon).
[REGLAS DE SALIDA — aspect 4:5]
```

---

## 5) Testimonio / prueba social

**Ratio:** 1:1

```
[BLOQUE DE MARCA]

Post de testimonio Instagram para [NOMBRE_MARCA].
Composición: comillas tipográficas grandes + cita corta + nombre del cliente.
Texto en imagen (exacto):
- Cita: "[frase del cliente, máx 18 palabras]"
- Nombre: "[Nombre] · [rol/ciudad]"
- Sello pequeño: "Cliente real"
Estilo editorial de marca; foto de fondo desenfocada opcional de [contexto]; alto contraste en el texto.
[REGLAS DE SALIDA — aspect 1:1]
```

---

## 6) Quote / frase de marca

**Ratio:** 1:1

```
[BLOQUE DE MARCA]

Post quote Instagram para [NOMBRE_MARCA].
Fondo atmosférico de [textura/escena de marca], texto centrado.
Texto en imagen (exacto):
"[FRASE DE MARCA EN 1–2 LÍNEAS]"
Firmado: — [NOMBRE_MARCA]
Sin foto de stock de persona mirando cámara. Tipografía expresiva pero legible.
[REGLAS DE SALIDA — aspect 1:1]
```

---

## 7) Portada de Reel / Story (vertical)

**Ratio:** 9:16

```
[BLOQUE DE MARCA]

Portada vertical 9:16 para Reel/Story de [NOMBRE_MARCA].
Hook visual fuerte en el tercio superior (zona segura de UI de IG).
Texto en imagen (exacto), grande y centrado:
- Hook: "[pregunta o promesa en ≤6 palabras]"
- Línea chica: "[contexto]"
Espacio inferior limpio para botones de la app. Estilo [estilo visual], alto contraste, sin texto cerca de bordes.
[REGLAS DE SALIDA — aspect 9:16]
```

---

## 8) Behind the scenes / lifestyle

**Ratio:** 4:5

```
[BLOQUE DE MARCA]

Post lifestyle / BTS Instagram para [NOMBRE_MARCA].
Escena: [ej. preparando el producto / día en el taller / rutina del cliente].
Sensación auténtica, fotográfica, luz natural.
Texto mínimo en esquina o barra inferior:
- "[etiqueta corta, ej. Detrás de cámaras]"
- wordmark [NOMBRE_MARCA]
No sobrecargar; la foto vende, el texto solo orienta.
[REGLAS DE SALIDA — aspect 4:5]
```

---

## 9) CTA / “link en bio” / DM

**Ratio:** 1:1

```
[BLOQUE DE MARCA]

Post CTA Instagram para [NOMBRE_MARCA].
Objetivo: que escriban o hagan clic.
Texto en imagen (exacto):
- Título: "[beneficio claro]"
- CTA grande: "[Comenta YO / DM ‘INFO’ / Link en bio]"
- Refuerzo: "[qué reciben]"
Diseño limpio con botón/CTA tipográfico integrado; un solo punto focal.
[REGLAS DE SALIDA — aspect 1:1]
```

---

## 10) Recordatorio / countdown / evento

**Ratio:** 1:1

```
[BLOQUE DE MARCA]

Post countdown/evento para [NOMBRE_MARCA].
Evento: [nombre] · Fecha: [día/hora] · Formato: [online/presencial].
Texto en imagen (exacto):
- "FALTAN [X] DÍAS" (o la fecha grande)
- Título del evento
- CTA: "Reserva tu lugar"
Reloj/calendario como motivo visual sutil de marca, no clipart genérico.
[REGLAS DE SALIDA — aspect 1:1]
```

---

## Cómo usar en Flow (rápido)

1. Pega el **Bloque de marca** relleno.  
2. Elige el prompt del **tipo de post**.  
3. Completa solo los corchetes `[...]`.  
4. Pega las **Reglas de salida** al final.  
5. Si el texto sale mal: regenera pidiendo *“mismo diseño, corrige tipografía nítida, texto exacto: …”*.  
6. Si quieres serie coherente: *“misma paleta, tipografía y márgenes que la imagen anterior”*.

---

## Ejemplo relleno (café)

```
MARCA:
- Nombre: Bruma Café
- Rubro: café de especialidad tostado local
- Público: jóvenes 22–35 que trabajan remoto
- Paleta: primario #2C1810, secundario #C4A484, acento #E85D04, fondo #F7F1E8, texto #1A1A1A
- Estilo: cálido lifestyle editorial
- Tipografía: serif display + sans clean
- Logo: wordmark tipográfico abajo
- Tono: cercano y premium
```

Prompt corto resultante (promo):

```
[bloque Bruma Café]
Post Instagram cuadrado de PROMOCIÓN. Oferta: 2x1 en cold brew los viernes.
Texto exacto: Badge "VIERNES"; Título "2x1 Cold Brew"; CTA "Pide en el local".
Vaso de cold brew con condensación, luz de tarde, paleta de marca.
REGLAS: 1:1, tipografía nítida, alto contraste, sin clutter.
```

---

Cuando me pases **nombre, rubro y 3–4 colores hex**, te devuelvo estos mismos prompts ya rellenados solo para tu marca (sin corchetes).

# 📑 11. Plantillas Personalizadas

---

## 🎯 Objetivo

Al terminar esta sección, vas a saber crear plantillas reutilizables específicas para tu marca de joyería, organizar tu biblioteca de plantillas, y optimizar tu flujo de trabajo para crear contenido más rápido sin perder calidad.

---

## 📁 ¿Qué Es una Plantilla Personalizada?

Una plantilla personalizada es un **diseño base** que ya tiene:

- Colores de tu marca
- Fuentes de tu marca
- Estructura y layout
- Posición del logo
- Estilo visual coherente

**El objetivo:** No empezar de cero cada vez. Solo cambiar el contenido (foto, texto del producto, precio) y publicar.

### Ejemplo práctico:

```
❌ Sin plantilla: 30 minutos por post
   - Elegir tamaño
   - Seleccionar colores
   - Elegir fuentes
   - Crear layout
   - Posicionar elementos
   - Etc...

✅ Con plantilla: 5 minutos por post
   - Abrir plantilla
   - Cambiar foto del producto
   - Cambiar nombre del producto
   - Cambiar precio
   - Exportar
   - Publicar
```

---

## 🏗️ Tipos de Plantillas que Necesitás

### Plantillas de Posts (Feed de Instagram)

| Plantilla                  | Usar para                | Frecuencia |
| -------------------------- | ------------------------ | ---------- |
| **Post producto cuadrado** | Fotos de productos       | Alta       |
| **Post producto vertical** | Fotos de productos (4:5) | Media      |
| **Post quote/inspiración** | Frases, valores de marca | Media      |
| **Post colección**         | Varias piezas            | Baja       |
| **Post antes/después**     | Comparaciones            | Baja       |
| **Post lifestyle**         | Fotos con modelos        | Media      |

### Plantillas de Stories

| Plantilla                   | Usar para              | Frecuencia |
| --------------------------- | ---------------------- | ---------- |
| **Story lanzamiento**       | Nuevo producto         | Alta       |
| **Story detalle**           | Mostrar pieza de cerca | Alta       |
| **Story pregunta/poll**     | Interacción            | Alta       |
| **Story countdown**         | Lanzamientos           | Media      |
| **Story behind the scenes** | Proceso, equipo        | Media      |
| **Story tips**              | Contenido educativo    | Media      |

### Plantillas de Carruseles

| Plantilla                  | Usar para             | Frecuencia |
| -------------------------- | --------------------- | ---------- |
| **Carrusel educativo**     | Tips, guías           | Media      |
| **Carrusel colección**     | Mostrar varias piezas | Media      |
| **Carrusel antes/después** | Comparaciones         | Baja       |
| **Carrusel testimonios**   | Reviews de clientes   | Baja       |

### Plantillas de Covers de Reels

| Plantilla           | Usar para        | Frecuencia |
| ------------------- | ---------------- | ---------- |
| **Cover tutorial**  | "Cómo hacer X"   | Alta       |
| **Cover lista**     | "5 tips sobre Y" | Alta       |
| **Cover resultado** | Antes/después    | Media      |

---

## 🔧 Cómo Crear una Plantilla

### Paso 1: Crear el diseño base

1. Nuevo diseño → elegí el tamaño (1080×1080, 1080×1920, etc.).
2. Configurá los colores:
   - Fondo: color primario de tu marca
   - Elementos: colores de tu paleta
3. Elegí las fuentes:
   - Título: tu fuente de títulos
   - Body: tu fuente de body text
4. Creá el layout:
   - Posición del logo (esquina superior o inferior)
   - Posición del texto principal (centro o tercio superior)
   - Espacios para fotos y textos que van a cambiar

### Paso 2: Definir zonas editables

```
┌─────────────────────────────────────┐
│                                     │
│  [LOGO]              [ZONA FIJA]   │
│                                     │
│  ═══════════════════════════════   │
│                                     │
│  [ZONA PARA FOTO]                   │  ← Esta zona cambia: la foto del producto
│                                     │
│  ────────────────────────────────  │
│                                     │
│  [NOMBRE DEL PRODUCTO]              │  ← Esta zona cambia: el nombre
│                                     │
│  $ [PRECIO]                         │  ← Esta zona cambia: el precio
│                                     │
│  [DESCRIPCIÓN]                      │  ← Esta zona cambia: detalles
│                                     │
│  ═══════════════════════════════   │
│                                     │
│  [@TUMARCA]                         │  ← Esta zona puede cambiar o quedarse fija
│                                     │
└─────────────────────────────────────┘
```

### Paso 3: Dejar elementos "dummy" como guía

1. Poné texto placeholder como "NOMBRE DEL PRODUCTO" para saber dónde va.
2. Poné una foto placeholder para saber dónde irá la imagen del producto.
3. Así cuando dupliques la plantilla, sabés exactamente qué cambiar.

### Paso 4: Guardar como plantilla

1. Tocá el menú **⋮** arriba a la derecha.
2. Seleccioná **"Guardar como plantilla"** o **"Agregar a plantillas"**.
3. Nombra la plantilla descriptivamente: "Post producto - Cuadrado - Negro".
4. Guardá.

> **Pro tip:** Antes de guardar, verificá que la plantilla esté perfecta. No guardés diseños con errores porque los vas a reutilizar mucho y tener que corregir cada uno es perder tiempo.

---

## 🎨 Crear Plantillas Específicas para Joyería

### Plantilla 1: Post Producto Cuadrado

```
Estructura:
┌─────────────────────────────────────┐
│                                     │
│  [LOGO - esquina superior izq]       │
│                                     │
│  ────────────────────────────────  │
│                                     │
│  [FOTO DEL PRODUCTO]                │
│  (Centro, ocupando 60% del canvas)  │
│                                     │
│  ────────────────────────────────  │
│                                     │
│  [NOMBRE DE LA PIEZA]              │
│  (Playfair, centrado, blanco)       │
│                                     │
│  [MATERIAL | TALLA]                 │
│  (Montserrat, pequeño, dorado)      │
│                                     │
│  $ [PRECIO]                         │
│  (Montserrat Bold, grande, blanco)  │
│                                     │
│  ────────────────────────────────  │
│                                     │
│  [@TUMARCA]                         │
│                                     │
└─────────────────────────────────────┘

Colores:
- Fondo: #1A1A1A
- Texto principal: #FFFFFF
- Texto secundario: #D4AF37
- Líneas: #D4AF37

Fuentes:
- Título producto: Playfair Display
- Precio/detalles: Montserrat
```

### Plantilla 2: Story Lanzamiento

```
Estructura:
┌─────────────────────────────────────┐
│ (250px zona segura)                 │
│                                     │
│  [LOGO - esquina superior izq]      │
│                                     │
│  [FOTO DEL PRODUCTO]                │
│  (Ocupando el centro)               │
│                                     │
│  ═══════════════════════════════   │
│                                     │
│  ✨ NUEVO                           │
│  [NOMBRE DEL PRODUCTO]             │
│  [COLECCIÓN / TEMPORADA]           │
│                                     │
│  💬 Comentá "INFO"                │
│                                     │
│ (400px zona segura)                 │
└─────────────────────────────────────┘

Colores:
- Fondo: puede variar (foto o negro)
- Texto: #FFFFFF con sombra
- Acentos: #D4AF37
```

### Plantilla 3: Carrusel Educativo

```
Estructura del Slide 1 (Portada):
┌─────────────────────────────────────┐
│                                     │
│  [FONDO: #1A1A1A]                   │
│                                     │
│  [ÍCONO O FOTO RELACIONADA]        │
│                                     │
│  [TÍTULO DEL CARRUSEL]              │
│  "5 Tips para Cuidar..."            │
│                                     │
│  → Deslizá                          │
│                                     │
└─────────────────────────────────────┘

Estructura de Slides 2-5 (Contenido):
┌─────────────────────────────────────┐
│                                     │
│  [FONDO: #1A1A1A]                   │
│                                     │
│  💎 Tip [N]                         │
│  ────────────────────────────────  │
│                                     │
│  [ILUSTRACIÓN O FOTO]              │
│                                     │
│  [TEXTO DEL TIP]                    │
│  (1-2 líneas máximo)                │
│                                     │
└─────────────────────────────────────┘

Estructura del Slide Final (CTA):
┌─────────────────────────────────────┐
│                                     │
│  [FONDO: #1A1A1A]                   │
│                                     │
│  💎💎💎                             │
│                                     │
│  Guardá este post                   │
│  para no perder estos tips          │
│                                     │
│  @TUMARCA                           │
│  #ETIQUETAS                         │
│                                     │
└─────────────────────────────────────┘
```

---

## 📂 Organizar tus Plantillas

### Método 1: Carpetas de plantillas

1. Perfil → **Plantillas guardadas**.
2. Creá carpetas: "Posts", "Stories", "Carruseles", "Reels".
3. Mové cada plantilla a su carpeta.

### Método 2: Nombrado descriptivo

Nombrá tus plantillas con información clara:

```
✅ Buenos nombres:
- "Post producto - Cuadrado - Negro"
- "Story lanzamiento - Dorado"
- "Carrusel 5 tips - Template"
- "Cover reel - Tutorial - Base"

❌ Malos nombres:
- "Diseño 1"
- "Nuevo diseño (2)"
- "Canva (3)"
- "Prueba"
```

### Método 3: Tags en el nombre

Agregá información útil en el nombre:

```
"PP-CN-B" = Post Producto Cuadrado Negro
"ST-L-D" = Story Lanzamiento Dorado
"C-5T" = Carrusel 5 Tips
"CR-T" = Cover Reel Tutorial
```

---

## 🚀 Usar Plantillas para Crear Posts Rápidos

### Flujo de trabajo rápido:

```
1. ABRIR PLANTILLA
   → Perfil → Plantillas → seleccionar plantilla
   → Se abre una copia de la plantilla

2. CAMBIAR FOTO
   → Tocá la foto placeholder
   → Subí la nueva foto del producto
   → Ajustá el encuadre

3. CAMBIAR TEXTO
   → Tocá dos veces rápido cada texto
   → Escribí el nuevo contenido
   → Verificá que no se corrió el formato

4. REVISAR
   → Verificá que todo se vea bien
   → Revisá los 150px de margen
   → Verificá jerarquía visual

5. EXPORTAR
   → Menú ⋮ → Descargar
   → PNG alta calidad
   → Guardá

6. PUBLICAR
   → Abrí Instagram
   → Subí la imagen
   → Escribí el caption
   → Publicá
```

**Tiempo estimado:** 5-10 minutos por post usando plantillas.

> **Pro tip:** Tené al menos **3 plantillas de posts** y **3 de stories** listas para usar. Así cuando necesites publicar, no perdés tiempo en diseño.

---

## 📋 Plantillas Mínimas que Recomendó

### Mínimo para posts de feed:

| Plantilla                  | Cuándo usarla                   |
| -------------------------- | ------------------------------- |
| **Post producto cuadrado** | Fotos de productos individuales |
| **Post quote/inspiración** | Frases de marca                 |
| **Post colección**         | Varias piezas juntas            |

### Mínimo para stories:

| Plantilla             | Cuándo usarla             |
| --------------------- | ------------------------- |
| **Story lanzamiento** | Nuevo producto            |
| **Story pregunta**    | Interacción con audiencia |
| **Story detalle**     | Mostrar pieza de cerca    |

### Mínimo para carruseles:

| Plantilla                         | Cuándo usarla |
| --------------------------------- | ------------- |
| **Carrusel educativo (5 slides)** | Tips, guías   |
| **Carrusel colección**            | Varias piezas |

---

## 🔄 Actualizar Plantillas

### Cuándo actualizar una plantilla:

- Tu marca cambia de colors o fuentes
- Encontraste un diseño mejor
- Una plantilla ya no se usa y querés reemplazarla
- Tu estilo evolucionó

### Cómo actualizar:

1. Abrí la plantilla existente.
2. Hacé los cambios necesarios.
3. Guardá como nueva plantilla (con el nombre actualizado).
4. Actualizá las referencias donde la usabas.

> **Pro tip:** No borres plantillas antiguas hasta estar segura de que no las necesitás. Pueden servir para campañas específicas.

---

## ❌ Errores Comunes

### Error 1: Plantilla muy rígida

**Problema:** La plantilla solo sirve para un tipo de producto.
**Solución:** Dejá suficiente espacio flexible para diferentes tamaños de fotos y diferentes largos de nombres de productos.

### Error 2: No documentar las plantillas

**Problema:** No sabés para qué sirve cada plantilla.
**Solución:** Nombrá descriptivamente y, si es posible, agregá notas sobre cuándo usar cada plantilla.

### Error 3: Demasiadas plantillas

**Problema:** Tenés 50 plantillas y no sabés cuál usar.
**Solución:** Limitá a **9-12 plantillas básicas**. Si necesitás más, organizalas en subcarpetas.

### Error 4: Plantillas sin probar

**Problema:** Creás plantillas pero nunca las usás.
**Solución:** Cada plantilla nueva, probá usándola para crear un post real. Si funciona, la mantenés. Si no, la ajustás.

### Error 5: Olvidar guardar como plantilla

**Problema:** Hacés un post excelente y no lo guardás como plantilla.
**Solución:** Cuando termines un post que te gustó mucho, usá **"Duplicar"** y guardá la copia como plantilla.

---

## 📌 Resumen

- Las plantillas te ahorran **80% del tiempo** de diseño.
- Creá plantillas para cada formato: posts, stories, carruseles, reels.
- Una plantilla debe tener **colores, fuentes, y estructura de tu marca**.
- Dejá **zonas editables claras** (foto, nombre, precio).
- Guardá con **nombres descriptivos** y organizá en carpetas.
- Mínimo recomendado: **3 plantillas de posts + 3 de stories**.
- Usá la plantilla → cambiar contenido → exportar → publicar.

---

## ✏️ Mini-Acción

1. Creá las siguientes plantillas:

   **Plantilla 1: Post Producto Cuadrado**
   - Tamaño: 1080×1080
   - Fondo: negro
   - Placeholder de foto centrado
   - Texto placeholder: "NOMBRE DEL PRODUCTO"
   - Precio placeholder: "$XXX"
   - Logo en esquina
   - Guardá como "Post producto - Cuadrado"

   **Plantilla 2: Story Lanzamiento**
   - Tamaño: 1080×1920
   - Placeholder de foto
   - Texto: "✨ NUEVO" + placeholders
   - Guardá como "Story lanzamiento"

   **Plantilla 3: Carrusel Educativo (5 slides)**
   - Slide 1: Portada con título y "Deslizá"
   - Slides 2-4: Tip con número y texto
   - Slide 5: CTA final
   - Guardá como "Carrusel 5 tips"

2. Organizá las plantillas en carpetas: "Posts", "Stories", "Carruseles".

3. Probá cada plantilla creando un diseño de ejemplo.

> _Tener plantillas organizadas es como tener un equipo de diseño trabajando para vos. Solo cambiás el contenido y publicás._

---

[Siguiente: 12-exportar-y-compartir.md →](12-exportar-y-compartir.md)

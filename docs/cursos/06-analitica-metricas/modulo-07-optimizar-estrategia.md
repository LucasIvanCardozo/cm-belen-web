# Módulo 7 — Optimizar Estrategia con Datos

## Objetivos de Aprendizaje

Al finalizar este módulo vas a:
- ✅ Usar datos para mejorar tu estrategia de contenido
- ✅ Testear hipótesis con experiments
- ✅ Implementar cambios basado en evidencia
- ✅ Medir el impacto de tus optimizaciones
- ✅ Crear un ciclo de mejora continua

---

## 1. El ciclo de optimización

```
CICLO CONTINUO DE MEJORA:

    ┌──────────────┐
    │   MEDIR     │
    │  Analizar   │
    │   datos     │
    └──────┬───────┘
           ↓
    ┌──────────────┐
    │  HIPÓTESIS  │
    │  Formular   │
    │  teoría    │
    └──────┬───────┘
           ↓
    ┌──────────────┐
    │   TESTEAR   │
    │  Experimento│
    │   pequeño  │
    └──────┬───────┘
           ↓
    ┌──────────────┐
    │  MEDIR      │
    │  Evaluar    │
    │  resultado  │
    └──────┬───────┘
           ↓
    ┌──────────────┐
    │  APLICAR    │
    │  Si funcionó│
    │  Escalar   │
    └──────────────┘

Este ciclo nunca termina. Siempre hay room para mejorar.
```

---

## 2. Crear hipótesis de optimización

```
HIPÓTESIS = Suposición educada que podés probar

ESTRUCTURA DE UNA HIPÓTESIS:

"SI [hago este cambio],
 ENTONCES [espero este resultado],
 PORQUE [esta razón basada en datos]."

EJEMPLOS DE HIPÓTESIS:

✅ BUENA HIPÓTESIS:
"Si publicamos 3 carruseles educativos por semana en vez de 1,
entonces los guardados van a aumentar un 30%,
porque los carruseles educativos tienen 3x más guardados
que los posts de producto."

❌ MALA HIPÓTESIS:
"Si publicamos más seguido, vamos a crecer."
→ No hay dato que soporte por qué
→ No hay métrica específica para medir

✅ BUENA HIPÓTESIS:
"Si añadimos una pregunta al final de cada caption,
entonces los comentarios van a aumentar,
porque los posts con preguntas tienen 2x más comentarios."

❌ MALA HIPÓTESIS:
"Si publicamos a la noche, va a funcionar mejor."
→ ¿Por qué la noche? ¿Qué dato lo soporta?
```

---

## 3. Tipos de experimentos

### Experimento 1: Test A/B de horario

```
TEST A/B DE HORARIO:

HIPÓTESIS:
"Los posts a las 10am van a tener más engagement que los de 8pm."

COMO TESTEARLO:

SEMANA 1:
→ Publicá 3 posts a las 10am
→ Medí engagement de cada uno

SEMANA 2:
→ Publicá 3 posts a las 8pm
→ Medí engagement de cada uno

RESULTADO:
┌─────────────────────────────────────────────────────────────┐
│ HORA      │ Posts │ Engagement Total │ Engagement Promedio │
├─────────────────────────────────────────────────────────────┤
│ 10am      │ 3     │ 450              │ 150                 │
│ 8pm       │ 3     │ 280              │ 93.3               │
└─────────────────────────────────────────────────────────────┘

CONCLUSION:
10am tiene 61% más engagement promedio.
→ CONFIRMA la hipótesis.
→ Establecer 10am como horario principal para posts importantes.

TIEMPO NECESARIO: 2 semanas
```

---

### Experimento 2: Test de tipo de contenido

```
TEST DE TIPO DE CONTENIDO:

HIPÓTESIS:
"Los reels educativos van a tener más guardados que los reels de producto."

COMO TESTEARLO:

DURANTE 2 SEMANAS:
→ Semana 1: Publicá 4 reels de PRODUCTO
→ Semana 2: Publicá 4 reels EDUCATIVOS

MÉTRICAS A COMPARAR:
• Alcance
• Engagement rate
• Guardados
• Comentarios

RESULTADO ESPERADO:
┌─────────────────────────────────────────────────────────────┐
│ TIPO          │ Alcance │ Eng. Rate │ Guardados │ Coment. │
├─────────────────────────────────────────────────────────────┤
│ Reel Producto │ 12,000  │ 3.2%      │ 120       │ 45      │
│ Reel Educativo│ 8,500  │ 5.1%      │ 340       │ 78      │
└─────────────────────────────────────────────────────────────┘

CONCLUSIONES POSIBLES:
• Si educativos tienen más guardados → Más contenido educativo
• Si productos tienen más alcance → Usar para visibilidad
• Si son similares → Balancear ambos tipos
```

---

### Experimento 3: Test de formato de caption

```
TEST DE CAPTION:

HIPÓTESIS:
"Los captions con más de 150 palabras van a generar más guardados
porque la gente lee más y guarda para referencia."

COMO TESTEARLO:

DURANTE 1 SEMANA:
→ 5 posts con captions cortos (<50 palabras)
→ 5 posts con captions largos (150+ palabras)

MÉTRICAS A COMPARAR:
• Guardados
• Tiempo de lectura (si disponible)
• Comentarios

NOTA:
Esto es difícil de testear cleanly porque el contenido también cambia.
Testeá con posts similares para resultados más limpios.
```

---

## 4. Framework de optimización

```
PASO A PASO PARA OPTIMIZAR:

PASO 1: IDENTIFICÁ EL PROBLEMA
   ↓
   "Nuestro engagement rate bajó este mes"

PASO 2: RECOLECTÁ DATOS
   ↓
   Engagement rate: 4.2% → 3.1% (bajó 26%)

PASO 3: FORMULÁ HIPÓTESIS
   ↓
   "Creemos que bajó porque publicamos menos carruseles
   y más fotos simples"

PASO 4: VERIFICÁ LA HIPÓTESIS
   ↓
   • Carruseles el mes pasado: 8 (32% del contenido)
   • Carruseles este mes: 3 (15% del contenido)
   • Engagement rate carruseles: 5.2%
   • Engagement rate fotos simples: 2.1%

PASO 5: CONFIRMÁ O RECHAZÁ
   ↓
   ✓ CONFIRMADO: Los carruseles tienen 2.5x más engagement.
   La reducción en carruseles explica la caída.

PASO 6: PLANIFICÁ ACCIÓN
   ↓
   • Volver a 8+ carruseles por mes
   • Reducir fotos simples a máximo 3/mes

PASO 7: IMPLEMENTÁ Y MEDÍ
   ↓
   Mes siguiente:
   • Carruseles: 9 (38%)
   • Engagement rate: 4.8%
   → MEJORA CONFIRMADA (+54%)
```

---

## 5. Optimizaciones específicas para Joyería

### Optimización 1: Ratio de contenido

```
CONTENIDO PARA JOYERÍA:

DISTRIBUCIÓN RECOMENDADA:

┌─────────────────────────────────────────────────────────────┐
│ 📊 CONTENIDO PARA JOYERÍA                                 │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│ 💰 CONTENIDO DE VENTA (25-30%)                            │
│ • Fotos de producto con precio                             │
│ • Posts de "disponible ahora"                              │
│                                                             │
│ 📚 CONTENIDO DE VALOR (40-50%)                            │
│ • Tutoriales de estilo                                     │
│ • Guía de materiales/cuidados                              │
│ • Tendencias                                               │
│                                                             │
│ 💬 CONTENIDO DE COMUNIDAD (20-25%)                        │
│ • Behind the scenes                                        │
│ • Testimonios                                              │
│ • Preguntas y polls                                        │
│                                                             │
│ ✨ CONTENIDO DE MARCA (10-15%)                           │
│ • Storytelling                                            │
│ • Valores de marca                                         │
│ • Historia del taller/artículo                             │
│                                                             │
└─────────────────────────────────────────────────────────────┘

TEST:
Si tu contenido de venta es más del 50%,
probablemente tu engagement va a bajar.

AJUSTE:
• Si guardados bajos → Más contenido de valor
• Si DMs bajos → Más contenido de venta
• Si engagement general bajo → Más contenido de comunidad
```

---

### Optimización 2: Hashtags por tipo

```
HASHTAGS EFECTIVOS PARA JOYERÍA:

CATEGORÍAS DE HASHTAGS:

1. NICHO (#joyeriaartesanal, #jewelrydesign) - 3-5
2. UBICACIÓN (#joyeriaArgentina, #hechoMexico) - 2-3
3. TENDENCIA (#ootd, #jewelrylover) - 2-3
4. ESTILO (#minimaljewelry, #bohojewelry) - 3-5
5. MATERIAL (#goldjewelry, #silver925) - 2-3
6. EMOCIÓN (#regaloperfecto, #joyascondistintivo) - 2-3

TOTAL RECOMENDADO: 15-20 hashtags

TEST:
→ Semana 1: 20 hashtags de nicho específico
→ Semana 2: 20 hashtags genéricos de moda

RESULTADO ESPERADO:
Los hashtags de nicho específico suelen funcionar mejor
para jewelry porque attracts a la audiencia correcta.
```

---

### Optimización 3: Frecuencia de publicación

```
CUÁNTOS POSTS PUBLICAR:

TEST:
Diferentes frecuencias durante 4 semanas.

┌─────────────────────────────────────────────────────────────┐
│ SEMANA │ Posts │ Engagement │ Engagement Promedio         │
├─────────────────────────────────────────────────────────────┤
│ 1      │ 14    │ 280        │ 20                           │
│ 2      │ 21    │ 350        │ 16.7                         │
│ 3      │ 7     │ 200        │ 28.6 ✓                       │
└─────────────────────────────────────────────────────────────┘

CONCLUSIONES:
• Semana 3 (menos posts, mejor engagement) = Calidad > Cantidad
• Pero... ¿menos posts = menos alcance total?

MÉTRICA COMPUESTA:
• Semana 1: 14 posts × 20 engagement × alcance 5,000 = 7,000 pts
• Semana 3: 7 posts × 28.6 engagement × alcance 5,000 = 10,010 pts

OPTIMIZACIÓN RECOMENDADA:
→ Menos posts, mayor calidad
→ Invertir más tiempo en 1 post excelente que en 3 average
```

---

## 6. Errores de optimización

```
ERRORES COMUNES:

❌ ERROR 1: CAMBIAR TODO A LA VEZ
"Hice 10 cambios y mejoró. ¿Cuál fue el cambio?"
→ Solución: Cambiar solo 1 variable a la vez

❌ ERROR 2: CONCLUSIÓN TEMPRANA
"Pruebo 1 vez y ya saqué conclusiones."
→ Solución: Repetir el test mínimo 3 veces

❌ ERROR 3: IGNORAR EL LARGO PLAZO
"Varias publicacións a las 6am funcionó mejor hoy."
→ Solución: Testear durante semanas, no días

❌ ERROR 4: NO DOCUMENTAR
"¿Por qué cambiamos los hashtags?"
"No me acuerdo."
→ Solución: Documentá todos los cambios y resultados

❌ ERROR 5: OPTIMIZAR LO QUE NO IMPORTA
"Me estoy enfocando en cuál emoji usar."
→ Solución: Enfocá en lo que impacta resultados (tipo de contenido, horarios)
```

---

## 7. Documentar optimizaciones

```
TEMPLATE DE DOCUMENTACIÓN:

┌─────────────────────────────────────────────────────────────┐
│ 📋 OPTIMIZACIÓN #1                                         │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│ FECHA: Mayo 2026                                          │
│                                                             │
│ PROBLEMA: Engagement rate bajo                              │
│                                                             │
│ HIPÓTESIS: Los carruseles tienen mejor engagement          │
│                                                             │
│ TEST:                                                      │
│ • Control: 5 posts fotos simples                           │
│ • Test: 5 posts carruseles                                │
│                                                             │
│ RESULTADO:                                                 │
│ • Fotos simples: 2.1% engagement promedio                 │
│ • Carruseles: 5.4% engagement promedio                    │
│ → Carruseles 2.5x mejor engagement                        │
│                                                             │
│ DECISIÓN: Aumentar carruseles de 3 a 8 por mes            │
│                                                             │
│ IMPLEMENTADO: Junio 2026                                   │
│                                                             │
│ RESULTADO REAL:                                            │
│ • Engagement rate mes de junio: 4.8%                      │
│ • Mejora confirmada: +62%                                 │
│                                                             │
│ STATUS: ✅ ÉXITO                                           │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 8. Ejercicio: Optimizá un aspecto

```
EJERCICIO: Elegí UN aspecto para optimizar

ÁREAS PARA OPTIMIZAR:
1. Horario de publicación
2. Tipo de contenido
3. Formato de caption
4. Cantidad de hashtags
5. Frecuencia de publicación

PASO 1: Elegí qué optimizar
   → Solo 1 cosa. No todo a la vez.

PASO 2: Formulá tu hipótesis
   → "Si hago X, entonces Y va a pasar porque Z."

PASO 3: Diseñá el test
   → ¿Qué vas a medir?
   → ¿Cuánto tiempo vas a testear?
   → ¿Cómo vas a aislar la variable?

PASO 4: Ejecutá el test
   → Durante 1-2 semanas
   → No cambies nada más durante el test

PASO 5: Analizá resultados
   → ¿Se confirmó o rechazó tu hipótesis?

PASO 6: Documentá y aplicá
   → Guardá el aprendizaje
   → Implementá si funcionó

ENTREGA:
• Hipótesis escrita
• Resultados del test
• Conclusión documentada
```

---

## 9. Resumen

```
PUNTOS CLAVE:

✓ El ciclo de optimización es continuo: Medir → Hipótesis → Test → Aplicar

✓ Buena hipótesis: "SI cambio X, ENTONCES resultará Y, PORQUE Z"

✓ Testear una variable a la vez para saber qué funcionó

✓ Testear mínimo 3 veces antes de concluir

✓ Documentar todo: cambios, resultados, decisiones

✓ Framework: Identificar problema → Recolectar → Hipótesis → Testear → Decidir

PARA JOYERÍA:
• Ratio de contenido: 40-50% valor, 25-30% venta
• Menos posts pero de mayor calidad
• Hashtags de nicho > hashtags genéricos

PRÓXIMO MÓDULO:
→ Módulo 8: Herramientas de Análisis
  Explorá las mejores apps y recursos para medir.
```

---

*[← Anterior: Módulo 6 - Crear Reportes](./modulo-06-crear-reportes.md) | [Siguiente: Herramientas →](./modulo-08-herramientas-analisis.md)*

*[Volver al README del curso](./index.md)*

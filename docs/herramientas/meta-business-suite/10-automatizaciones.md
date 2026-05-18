# Módulo 10: Automatizaciones en Meta Business Suite

**Objetivo:** Configurar herramientas que te ahorren tiempo respondiendo consultas repetitivas y mantengan tu cuenta activa automáticamente.

---

## 📋 Contenido

1. ¿Qué son las automatizaciones?
2. Respuestas rápidas (ya visto en Módulo 7)
3. Respuestas automáticas (fuera de horario)
4. Reglas automáticas
5. Mensajes de bienvenida
6. Guardar conversaciones como plantillas
7. Mejores prácticas para automatizaciones

---

## 1. ¿Qué Son las Automatizaciones?

Las automatizaciones son **reglas o respuestas preconfiguradas** que se activan automáticamente según condiciones específicas.

### Ejemplos de Automatizaciones

| Tipo | Qué hace | Cuándo usar |
|------|----------|-------------|
| **Respuesta automática** | Responde automáticamente cuando alguien DM | Fuera de horario |
| **Saludo automático** | Envía mensaje de bienvenida | Cuando alguien te escribe nuevo |
| **Respuesta rápida** | Plantilla con atajo para responder rápido | Cualquier momento |
| **Etiquetado automático** | Etiqueta productos en publicaciones | Al crear posts |
| **Programación automática** | Programa contenido sin intervención | Mantener calendario |

> 💡 **PRO TIP:** Las automatizaciones no reemplazan la atención humana. Son herramientas para ganar tiempo, no para evitar interactuar con clientes.

---

## 2. Respuestas Rápidas (Repaso)

Ya cubrimos las respuestas rápidas en el Módulo 7, pero aquí un resumen rápido:

### Configurar Atajo

**Paso 1:** Ve a **⚙️ Configuración** > **Respuestas rápidas**.

**Paso 2:** Toca **+ Nueva respuesta rápida**.

**Paso 3:** Configura:
- **Atajo:** `/saludo`
- **Mensaje:** "¡Hola! Gracias por escribir a @joyas_belen..."

**Paso 4:** Toca **Guardar**.

### Usar en Conversación

**Paso 1:** Abre una conversación.

**Paso 2:** Escribe `/saludo` en el campo de texto.

**Paso 3:** Toca la respuesta rápida que aparece.

**Paso 4:** Envía.

> 💡 **CONSEJO:** Ten 5-7 respuestas rápidas listas para los mensajes más comunes. Esto reduce drásticamente tu tiempo de respuesta.

---

## 3. Respuestas Automáticas (Fuera de Horario)

### ¿Qué Son?

Las respuestas automáticas son mensajes que **se envían solos** cuando alguien te escribe fuera de tu horario de atención.

### Configurar Respuesta Automática

> ⚠️ **NOTA IMPORTANTE:** Las respuestas automáticas están **más disponibles en Facebook Messenger** que en Instagram. En Instagram, puedes configurar respuestas automáticas solo si tienes Instagram Business con Messenger configurado.

**Paso 1:** Ve a **⚙️ Configuración** > **Automatizaciones** o **Respuestas automáticas**.

**Paso 2:** Toca **Crear respuesta automática** o **Configurar**.

---

### Configuración para Facebook Messenger

```
┌────────────────────────────────────┐
│  Nueva respuesta automática         │
│  ─────────────────────────────────│
│                                    │
│  Nombre:                          │
│  ┌────────────────────────────┐   │
│  │ Fuera de horario           │   │
│  └────────────────────────────┘   │
│                                    │
│  Activar cuando:                   │
│  ○ Siempre                         │
│  ● Fuera de horario                │
│  ○ Ausente (reactivamente)         │
│                                    │
│  Horario:                          │
│  ☑ Lunes: 9:00 AM - 6:00 PM      │
│  ☑ Martes: 9:00 AM - 6:00 PM     │
│  ☑ Miércoles: 9:00 AM - 6:00 PM   │
│  ☑ Jueves: 9:00 AM - 6:00 PM      │
│  ☑ Viernes: 9:00 AM - 6:00 PM     │
│  ☐ Sábado: ________ - ________   │
│  ☐ Domingo: ________ - ________   │
│                                    │
│  [Siguiente]                       │
│                                    │
└────────────────────────────────────┘
```

---

### Mensaje de Respuesta Automática

```
┌────────────────────────────────────┐
│  Mensaje de respuesta              │
│  ─────────────────────────────────│
│                                    │
│  ✏️ Escribe tu mensaje:           │
│  ┌────────────────────────────┐   │
│  │ ¡Hola! 👋                  │   │
│  │                           │   │
│  │Gracias por escribir a     │   │
│  │@joyas_belen.              │   │
│  │                           │   │
│  │Actualmente estamos fuera  │   │
│  │de horario de atención     │   │
│  │(Lunes a Viernes 9am-6pm).  │   │
│  │                           │   │
│  │Te respondemos apenas     │   │
│  │podamos. 💕               │   │
│  │                           │   │
│  │Mientras tanto, puedes     │   │
│  │ver nuestra colección aquí │   │
│  │👉 [LINK]                   │   │
│  └────────────────────────────┘   │
│                                    │
│  ☑ Activar respuestas rápidas     │
│                                    │
│  [Cancelar]        [Guardar]      │
│                                    │
└────────────────────────────────────┘
```

**Paso 3:** Escribe un mensaje amigable y profesional.

**Paso 4:** Toca **Guardar**.

---

### Configuración para Instagram

> ⚠️ **LIMITACIÓN:** En Instagram, las respuestas automáticas son más limitadas. Puedes configurar flujos automatizados usando la integración con Messenger, pero no todas las cuentas lo tienen disponible.

**Si está disponible:**

**Paso 1:** Ve a **Configuración de Instagram** > **Mensajes** > **Respuestas automáticas**.

**Paso 2:** Toca **Agregar respuesta automática**.

**Paso 3:** Configura las mismas opciones (nombre, horario, mensaje).

---

## 4. Mensaje de Bienvenida

### ¿Qué Es?

El mensaje de bienvenida es un **texto automático que se envía UNA SOLA VEZ** cuando alguien nuevo inicia conversación contigo.

**Diferencia con respuesta automática:**
- **Mensaje de bienvenida:** Se envía solo a personas nuevas
- **Respuesta automática:** Se envía cada vez que alguien escribe fuera de horario

### Configurar Mensaje de Bienvenida (Facebook)

**Paso 1:** Ve a **⚙️ Configuración** > **Mensajes** > **Mensaje de bienvenida**.

**Paso 2:** Activa el toggle **"Mensaje de bienvenida"**.

**Paso 3:** Escribe tu mensaje:

```
┌────────────────────────────────────┐
│  💬 Mensaje de bienvenida          │
│  ─────────────────────────────────│
│                                    │
│  Toggle: [Activo ✓]                │
│                                    │
│  ✏️ Mensaje:                      │
│  ┌────────────────────────────┐   │
│  │ ¡Bienvenida a @joyas_belen!│   │
│  │ 💎✨                    │   │
│  │                         │   │
│  │Gracias por escribirnos. │   │
│  │Somos una marca de joyería│   │
│  │artesanal con piezas únicas│   │
│  │                         │   │
│  │¿En qué podemos ayudarte │   │
│  │hoy?                     │   │
│  └────────────────────────────┘   │
│                                    │
│  ☑ Mostrar cuando no estés        │
│  ☑ Mostrar siempre                │
│                                    │
│  [Guardar cambios]                 │
│                                    │
└────────────────────────────────────┘
```

---

## 5. Reglas Automáticas

### ¿Qué Son?

Las reglas automáticas son acciones que Meta ejecuta **según condiciones que tú defines**.

### Tipos de Reglas Disponibles

| Regla | Qué hace | Ejemplo |
|-------|----------|---------|
| **Programar contenido** | Programa posts automáticamente | Publicar todos los días a las 9am |
| **Auto-etiquetar** | Etiqueta productos automáticamente | En posts que contienen cierto producto |
| **Notificar** | Te avisa cuando algo pasa | Cuando alguien menciona tu marca |

### Cómo Crear una Regla de Programación

> ⚠️ **NOTA:** Esta funcionalidad puede variar según la versión de la app y tu región.

**Paso 1:** Ve a **⚙️ Configuración** > **Herramientas** o **Automatizaciones**.

**Paso 2:** Busca **"Reglas"** o **"Programación automática"**.

**Paso 3:** Toca **Crear regla**.

**Paso 4:** Configura la regla:

```
┌────────────────────────────────────┐
│  Nueva regla                       │
│  ─────────────────────────────────│
│                                    │
│  Nombre:                          │
│  ┌────────────────────────────┐   │
│  │ Publicación diaria         │   │
│  └────────────────────────────┘   │
│                                    │
│  Acción:                          │
│  ○ Programar contenido            │
│  ○ Enviar recordatorio            │
│  ● Crear publicación               │
│                                    │
│  Frecuencia:                      │
│  ○ Una vez                         │
│  ● Diaria                          │
│  ○ Semanal                         │
│                                    │
│  Hora: 9:00 AM                    │
│  Días: Lun, Mar, Mié, Jue, Vie    │
│                                    │
│  [Cancelar]        [Crear]        │
│                                    │
└────────────────────────────────────┘
```

> ⚠️ **NOTA IMPORTANTE:** Las reglas automáticas de Meta Business Suite son limitadas en la versión móvil. Para automatización avanzada, necesitarías usar herramientas de terceros como Later, Buffer, o Meta Business Suite en versión web con integraciones.

---

## 6. Plantillas de Conversación

### Crear Plantillas para Casos Comunes

Cuando tienes una conversación que repites mucho (precio, envío, disponibilidad), crea una plantilla dedicada.

**Ejemplo de plantilla: Consulta de Precio**

```
┌────────────────────────────────────┐
│  ✏️ Plantilla: Consulta de Precio  │
│  ─────────────────────────────────│
│                                    │
│  Nombre: Precio de producto       │
│  Atajo: /precio                   │
│                                    │
│  Triggers (cuándo usar):           │
│  "cuánto cuesta"
│  "precio"
│  "cuánto sale"
│  "valor"
│                                    │
│  Respuesta:                        │
│  ┌────────────────────────────┐   │
│  │¡Hola! Gracias por tu      │   │
│  │interés 💕                  │   │
│  │                           │   │
│  │Para darte información     │   │
│  │exacta, ¿podrías decirme  │   │
│  │qué producto te interesa? │   │
│  │                           │   │
│  │Te paso los precios una   │   │
│  │vez que lo sepa 😊        │   │
│  └────────────────────────────┘   │
│                                    │
│  [Guardar plantilla]              │
│                                    │
└────────────────────────────────────┘
```

---

## 7. Mejores Prácticas para Automatizaciones

### Haz:

✅ **Personaliza los saludos**
- Incluye el nombre de tu marca
- Sé amigable pero profesional

✅ **Configura horarios reales**
- Si dices "respondemos de 9am a 6pm", sé consistente
- Actualiza si tu horario cambia

✅ **Mantén respuestas cortas**
- La gente no lee mensajes largos
- Menos de 100 palabras es ideal

✅ **Incluye llamada a la acción**
- "Escríbenos cualquier duda"
- "Mira nuestra colección aquí: [link]"

✅ **Revisa y actualiza regularmente**
- Las respuestas automáticas caducan
- Actualiza precios y disponibilidad

---

### No Hacer:

❌ **No uses automatizaciones para TODO**
- Las respuestas automáticas funcionan para consultas simples
- Para ventas complicadas, responde personalmente

❌ **No pongas mensajes genéricos sin valor**
- "Gracias por escribir" no dice nada
- "¡Hola! Somos [marca], nos especializamos en [X]" es mejor

❌ **No olvides desactivar cuando estás disponible**
- Si programas "fuera de horario" pero revisas mensajes a las 11pm, desactiva la automática

❌ **No uses tono robótico**
- "Estimado cliente, lamentamos informarle..."
- Usa tono conversacional: "¡Hola! 😊"

---

## 8. Herramientas Complementarias (Opcional)

### Meta Business Suite Web

La versión de escritorio (web) tiene más opciones de automatización:

- Reglas más complejas
- Programación masiva
- Integraciones con herramientas externas

### Herramientas de Terceros

| Herramienta | Función | Costo |
|-------------|---------|-------|
| **Later** | Programación avanzada, análisis | Freemium |
| **Buffer** | Programación multi-plataforma | Freemium |
| **Hootsuite** | Gestión completa de redes | Pago |
| **Sprout Social** | Todo-en-uno para social media | Pago |

> 💡 **PRO TIP:** Para empezar, con las herramientas nativas de Meta Business Suite es suficiente. Solo explora herramientas externas cuando sientas que necesitas más funcionalidades.

---

## 🎯 Resumen del Módulo

| Herramienta | Función | Cuándo usarla |
|-------------|---------|---------------|
| **Respuesta rápida** | Texto pre-escrito con atajo | Cualquier momento |
| **Respuesta automática** | Se activa fuera de horario | Cuando no estás disponible |
| **Mensaje de bienvenida** | Primer mensaje a nuevos contactos | Cuando alguien nuevo DM |
| **Reglas automáticas** | Acciones según condiciones | Programación avanzada |

**Concepto clave:** Las automatizaciones te ahorran tiempo, pero no reemplazan la atención humana y personalizada.

---

## 🎓 Mini-Acción: Configura tus Automatizaciones

1. [ ] Ve a Configuración > Respuestas rápidas
2. [ ] Crea 5 respuestas rápidas (saludo, producto, envío, precio, despedida)
3. [ ] Configura mensaje de bienvenida (si está disponible)
4. [ ] Configura respuesta automática de fuera de horario (si está disponible)
5. [ ] Prueba enviando una respuesta rápida a una conversación

**Meta:** Tener un sistema de respuestas que cubra el 80% de tus consultas repetitivas.

---

> 💡 **CONSEJO FINAL:** Las automatizaciones son como un buen asistente: hacen el trabajo rutinario para que tú puedas enfocarte en lo que realmente importa (conectar con clientes, crear contenido, vender).

---

*Avanza al [Módulo 11: Resolución de Problemas](./11-resolucion-problemas.md)*

